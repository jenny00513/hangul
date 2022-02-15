# Hangul
```
정수 프로세스(없음) // int main(void)
{
    정수 가, 나; // int a, b;
    
    입력(가); 입력(나); // cin >> a >> b;
    출력(가 + 나); // cout << a + b;
    
    종료; // return 0;
}
```

# 사용법
**반드시 템플릿의 상단 주석을 유지해주세요!**<br>
세미콜론(;)으로 끝나지 않는 코드는 아름답지 않기 때문에, 세미콜론은 치환하지 않습니다.<br>
(참고: 이 템플릿은 c++용이며, 다른 언어의 버전은 존재하지 않습니다.)

## 입출력
cin, cout과 동일한 문법이 적용됩니다.
```
입력(x); → cin >> x;
출력(x); → cout << x;
```

## 입출력 세팅

```
빠른입출력; → ios_base::sync_with_stdio(false); cin.tie(NULL); cout.tie(NULL);
입출력세팅; → 빠른입출력; cout << fixed; cout.precision(20);
```

## 기본 구문

```
만약 → if
아니라면 만약 → else if
아니라면 → else

반복 → for
조건을만족하는동안 → while
중단; → break;
하위중단; → continue;

그리고 → and 혹은 &&
또는 → or 혹은 ||
```

## 비트 연산
```
아니다 → ! (not)
택 → ^ (xor)
교집합 → & (and)
합집합 → | (or)
왼쪽밀기 → << (left shift)
오른쪽밀기 → >> (right shift)
```

## 자료형

```
정수 → int
전구 → bool
문자 → char
실수 → double
긴실수 → long double
문자열 → string
긴정수 → long long
몰루 → auto
없음 → void
쌍 → pair

상수로 → const

첫번째값 → (pair).first
두번째값 → (pair).second
```

## STL(standard template library)

```
동적배열 → vector
집합 → set
다중집합 → multiset
해싱집합 → unordered_set
사전 → map
다중사전 → multimap
해싱사전 → unordered_map
우선순위큐 → priority_queue
더미 → stack
대기열 → queue
양방향대기열 → deque

추가 → push
제거 → pop

앞에추가 → push_front
뒤에추가 → push_back
앞에제거 → pop_front
뒤에제거 → pop_back

삽입 → insert
삭제 → erase
찾기 → find
개수 → count

시작 → begin
끝 → end
시작의반대 → rbegin
끝의반대 → rend

최대 → max
최소 → min
정렬 → sort
하계 → lower_bound
상계 → upper_bound

더크다 → greater
```

## 상수

```
참 → true
거짓 → false
아무것도아님 → NULL
공백 → " "
개행 → "\n"
```

## 기타

```
반환 → return
종료; → return 0;
프로세스 → main

구구팔 → 998244353
십억 → 1e9
십억칠 → 1e9+7
십억구 → 1e9+9
십팔억 → 1e18
```
