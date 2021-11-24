1.세가지 진법의 정수 상수(2-5)
~~~
#include <stdio.h>

int main(void)
{
	printf("%d\n", 12);   // 10진수 정수 상수 출력 
	printf("%d\n", 014);  // 8진수 정수 상수 출력
	printf("%d\n", 0xc);  // 16진수 정수 상수 출력
  printf("%o\n", 12);  
	printf("x\n", 12);    10진수를 8진수나 16진수로 출력
	printf("X\n", 12);
  

	return 0;
}
~~~

2. 지수 형태의 실수 상수(2-6)
~~~
#include <stdio.h>

int main(void)
{
	printf("%.1lf\n", 1e6);         // 지수 형태의 실수를 소수점 형태로 출력
	printf("%.7lf\n", 3.14e-5);     // 소수점 이하 7자리까지 출력
	printf("%le\n", 0.0000314);     // 소수점 형태의 실수를 지수 형태로 출력 
	printf("%.2le\n", 0.0000314);   // 지수 형태로 소수점 이하 둘째 자리까지 출력

	
	return 0;
}
~~~

3. 문자와 문자열 데이터의 출력(2-7)
~~~
#include <stdio.h>

int main(void)
{
	printf("%c\n", 'A');                          // 문자 상수의 출력
	printf("%s\n", "A");                          // 문자열 상수 출력
	printf("% c은 % s입니다.\n", '1', "frist");   // 문자(%c) 문자열(%s) 을 함께 출력 
	
	return 0;
}
~~~

4. 변수의 선언과 사용(3-1)
~~~
#include<stdio.h>

int main(void)
{
int a;
int b, c;
double da;
char ch;

a = 10;
b = a;
c = a + 20;
da = 3.5;
ch = 'A';

printf("변수 a의 값 : %d\n", a);
printf("변수 b의 값 : %d\n", b);
printf("변수 c의 값 : %d\n", c);
printf("변수 da의 값 : %.1lf\n", da);
printf("변수 ch의 값 : %c\n", ch);

return 0;
}
~~~

5. char형 변수의 사용
~~~
#include<stdio.h>

int main(void)
{
	char ch1 = 'A';    // 문자로 초기화, 저장된 값은 문자의 아스키 코드 값
	char ch2 = 65;     // 문자 'A'의 아스키 코드 값에 해당하느 정수로 초기화
	printf("문자 %c의 아스키 코드 값 : %d\n", ch1, ch2);
	printf("아스키 코드 값이 %d인 문자 : %c\n", ch1, ch2);

	return 0;
}
~~~

