1. 10과 20을 더하는 프로그램
~~~
#include<stdio.h>

int main(void){
 
 10 + 20;
 
 return 0;
 
 }
~~~

2. 문자열을 화면에 출력하는 프로그램
~~~
#include <stdio.h>   //stdio : standard input output(표준입출력)의 줄임말 

int main(void)
{
	printf("be happy");   //문자열 "be happy" 출력
	printf("my friend");  //문자열 "my friend" 출력

	return 0;
}
~~~

3.제어 문자를 사용한 출력
~~~
#include <stdio.h>

int	main(void)
{
	printf("be happy\n");                  // "be happy"를 출력하고 줄을 바꿈(\n)
	printf("12345678901234567890\n");      // 화면에 열 번호를 출력하고 줄을 바꿈(\n)
	printf("my\tfriend\n");
	// "my"를 출력하고 탭 위치로 이동(\t) 후에 "friend"를 출력하고 줄을 바꿈(\n)
	printf("goot\b\tchance\n");           //"goot"를 출력하고 한 칸 왼쪽으로 이동(\b)해
	// t를 d로 바꾸고 탭 위치로 이동 후에(\t) "chance"를 출력하고 줄을 바꿈(\n)
	printf("cow\rw\a\n");
	// 맨 앞으로 이동(\r) 해 c를 w로 바꾸고 벨소리(\a)를 내고 줄을 바꿈(\n)

	return 0;
}
~~~

4. 정수와 실수의 출력
~~~
#include<stdio.h>
int main()
{
    printf("%d\n", 10);
    printf("%lf\n", 3.4);
    printf("%.1lf\n", 3.45);
    printf("%.10lf\n", 3.4);
    printf("%d과 %d의 합은 %d입니다.\n", 10, 20, 10+20);
    printf("%.1lf-%.1lf = %.1lf\n", 3.4, 1.2, 3.4 - 1.2);

    return 0;
}
~~~

