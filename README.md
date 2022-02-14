# Hangul
참고: 이 템플릿은 c++용이며, 다른 언어의 버전은 존재하지 않습니다.

# 문법
없는 것 빼고 모두 한글로 이루어져 있습니다.<br>
세미콜론(;)으로 끝나지 않는 코드는 아름답지 않기 때문에, 세미콜론은 치환하지 않습니다.

## 입출력
cin, cout과 동일한 문법이 적용됩니다.
```
입력(x); → cin >> x;
출력(x); → cout << x;
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
정수쌍 → pair<int, int>
긴정수쌍 → pair<ll, ll>
몰루 → auto
없음 → void

첫번째값 → (pair).first
두번째값 → (pair).second
```

## STL(standard template library)

```
동적배열 → vector
집합 → set
다중집합 → multiset
사전 → map
다중사전 → multimap
해싱집합 → unordered_set
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
