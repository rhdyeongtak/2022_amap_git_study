# (h1) 공영탁의 일기장
### (h2) 목차

   * _나는 누구인가_
   * _어린이날에 한 일_
   * _오늘 한 일_
   * _코드_
* ## (h3) 나는 누구인가
   * 저는 22학번 소프트웨어공학과 공영탁입니다.
* ## (h4) 어린이날에 한 일
   * 친구들과 치맥 후 새벽 피시방을 달림
* ## (h5) 오늟 한 일 
   *  1시에 축구 예선전을 함
   * 노래방에 감
* ## (h6) __코드__
   * c언어 과제 마지막 문제

'''c
#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>
int main() {
	int i=1 , sum=0;
	for (;;) {
		sum += i;
			if(sum > 10000) {
				sum -= i;
				i -= 1;
				break;
			}
		i += 1;
	}
	printf("1부터 %d까지의 합이 %d입니다.", i, sum);
	return 0;
'''
