# Deven.
Exam No.4
#include<stdio.h>
int main()
{
    int n,m;
    scanf("%d %d",&n,&m);
    int arr[n][m];
    int i,j;
    for(i=0;i<n;i++){
        for(j=0;j<m;j++){
            scanf("%d",&arr[i][j]);
        }
    }
   for(i=0;i<n;i++){
        for(j=0;j<m;j++){
            printf("%d\n",&arr[i][j]);
        }
    }
    for(i=0;i<n;i++){
        for(j=0;j<m;j++){
            printf("%d\n",&arr[j][i]);
        }

    }
    return 0;
}
