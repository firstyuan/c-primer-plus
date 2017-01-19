# c-primer-plus
programming exercise
/*
    3．编写一个程序，发出警报声，并打印下列文字：
    Startled by the sudden sound, Sally shouted, "By the Great Pumpkin,  what was that!"
*/
#include<stdio.h>
int main(void)
{
 printf("\aStartled by the sudden sound,Sally shouted,\"By the Great pumpkin,what was that!\"\n");  //  \a警报  \"双引号
 return(0);
}

/*4．编写一个程序，读入一个浮点数，并分别以小数形式和指数形式打印。输出应如同下面格式（实际显示的指数位数也许因系统而不同）：
    The input is 21.290000 or 2.129000e+001.
*/
#include<stdio.h>

int main(void)
{
	double a;
	scanf("%lf",&a);
	printf("the input is %f or %e\n",a,a);   //以指数形式输出用%e
return 0;
}
