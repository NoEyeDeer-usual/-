#include<stdio.h>
int main() {
	int i;
	printf("输入一个年份：\n");

	scanf_s("%d",&i);
	if (i % 4 == 0&&i% 100 != 0 || i % 400 == 0)
	{
		printf("%d是闰年",i);
	}
	else {
		printf("%d不是闰年",i);
	}
	
}
人生第一段代码
