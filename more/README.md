# 補充內容
#whileNotLoop.c
`
#include<stdio.h>

int sum(int n){
    int s = 0;
    int i = 1;

WHILE:
    if(i>n) goto EXIT;
    s = s + i;
    i = i + 1;

goto WHILE;
EXIT:
    return s;
}

int main(){
    int s10 = sum(10);
    printf("s10 = %d\n", s10);
}
`

/*int sum(int n){
    int s = 0;
    int i = 1;

LOOP:
    s = s + i;
    i = i + 1;
    if(i<=n) goto EXIT;
    return s;
}

int main(){
    int s10 = sum(10);
    printf("s10 = %d\n", s10);
}
*/
