Week1-2 학습정리
==
## 강의 복습 내용

#### 1. Variables
>스킵

#### 2. Function and Console I/O

텍스트 포매팅

> 방법 1: 
>* print(“%3.2f %5.2f” % (1.2423, 1.2345))  
>* => 1.24   1.23  
>* 3.2 : 세칸 할당해서 소수점 두자리 까지  
>
> 방법 2:
>* “ ~~{0}~~{1:.5f}~~ “.format(“apple”,5.243) “
>* {index:type}

패딩
> {0 : >10s } : 10칸할당, 오른쪽 정렬

f-string
>* 기존변수 선언후
>* print(f”~~{기존변수명:*^20}~~})	:	가운대 정렬, 공백 *로 채움, 20칸 할당 

#### 3. Conditionals and Loops

- is 연산( a is b )
    - 메모리의 주소를 비교
    - ex)
        - a = [1,2,3,4,5]
        - b = a[:]
        - 결과는 False
        - 파이썬은 -5~256까지 미리 메모리를 잡아둬서 a=100,b=100일때 is 결과 참임
- if 문
    - 불린외에는 존재하면 트루임
- all(리스트), any()
    - 이거도 조건문
- 삼항연산자
        - a=True if 조건문 else FALSE

- if __name__ == “__main__” :
	main()
	- 메인인지 체크


#### 4. String and advanced function concept

- 텍스트 슬라이싱
    - a[시작값: 끝나는 값: 스텝]
        - a[::2] : 두칸 단위로 슬라이싱
        - a[::-1] : 문자열 반전
- raw string
    - r”~~\~~”
        - 역슬래쉬를 인식안함

## 피어세션 정리
- 조에 늦게합류하여 자기소개
- 과제 궁금한 점 질답
- 아이스브레이킹

## 과제
  - 모두 제출 완료
  - baseball 과제에서 빠트린 조건을 조원분이 지적해주심
