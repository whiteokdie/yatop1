#include <stdio.h>
#define SIZE 5
int main(void)
{
    int m[SIZE] = {0};
      for(int i = 0; i < SIZE; ++i)
      {
        scanf("%d", &m[i]);
      }
      for(int i = 0; i < SIZE; ++i)
      {
        printf("*[%d]", m[i]);
      }
      printf("\n");
      for( int i = 4; i >= 0; --i)
      {
        printf("[%d]", m[i])
      }
      printf("\n");
      for(int i = 0; i < SIZE; ++i)
      {
        if(i % 2 == 0){
            printf("[%i]", m[i]):
        }
      }
      printf('\n');
      for(int i = 0; i < SIZE; ++i)
      {
        if(i % 2 > 0){
            printf("[%i]", m[i]);
        }
      }
}
