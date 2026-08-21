# certificate_coding
정보처리기사/PCCE/PCCP 등 코딩 관련 자격증 시험 준비를 위한 코드 공부 기록용 레파지토리
---
4단위 커리큘럼이 종료되는 시점 이후로 코딩테스트도 다시 재개할 것!

[명심할 것]
- 완벽하게 풀라는 게 아니다.
- 하루에 너무 많은 문제를 풀지 말 것.
- 푸는 것에 집착하지 말고, 한 문제를 풀더라도 나만의 로직을 만들자. 



## 입출력





## 조건문 1
▶️'_'는 "이 변수는 사용하지 않음"을 의미하는 관례적인 변수명
 반복은 필요하지만 반복변수 값은 사용하지 않을 때 사용
for _ in range(반복횟수):
    실행할 코드

▶️else 뒤에 조건문 if 쓸 수 있음 
ex)
else:
    if b >= 19:
        print('WOMAN')
    else:
        print('GIRL')




## 조건문 2








## 단순 반복문






## 다중 반복문 





### 문자열
▶️a,b = map(int, input().split())







## 1차원 배열






## 2차원 배열 



[파이썬 코테 풀면서 핵심 문법 정리하기]

## 대소문자 변환
"Hello World"

.lower()      → "hello world"   # 전부 소문자
.upper()      → "HELLO WORLD"   # 전부 대문자
.swapcase()   → "hELLO wORLD"   # 대↔소 뒤집기
.capitalize() → "Hello world"   # 첫 글자만 대문자
.title()      → "Hello World"   # 단어마다 첫 글자 대문자
```


```python
## 백슬래시 출력

# 방법1. 백슬래시 두 개
print("\\")     # → \
print("\\'")    # → \'

# 방법2. r 붙이기 (raw string)
print(r"\n")    # → \n
print(r"\'")    # → \'

# 비교
print("\n")     # → 줄바꿈 실행됨
print(r"\n")    # → \n 그대로 출력
```

**핵심**
- `\` 는 원래 특수기능 문자 (`\n` 줄바꿈, `\t` 탭 등)
- 문자 그대로 출력 → `\\` 또는 앞에 `r` 붙이기





