#include <stdio.h>

int main() 
{  
  int a, b, c;
  printf("ENTER ANGLES OF TRAINGLE.\n" );
  printf("ENTER 1ST ANGLE:" );
  scanf("%d",&a);
  printf("\nENTER 2ND ANGLE:" );
  scanf("%d",&b);
  printf("\nENTER 3RD ANGLE:" );
  scanf("%d",&c);

  if ( a + b + c != 180)
    printf("\nINVALID VALUES.\n");
  else if (a==b && b==c)
    printf("ITS EQUILATERAL TRIANGLE.\n");
  else if (a==b || b==c || a==c)
    printf("ITS ISOSELES TRIANGLE.\n");
  else if (a==90 || b==90 || a==90)
    printf("ITS RIGHT ANGLED TRIANGLE.\n");
  else
    printf("ITS SCALENE TRIANGLE.\n");


return 0;
}
