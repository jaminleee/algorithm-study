# 🍯 코드를 줄여줄 꿀 라이브러리 모음

- 순열/조합 [itertools.permutations() .combinations()]()
- 재귀 [sys.setrecursionlimit()]()

### itertools .permutations() .combinations()

- `itertools` 는 반복되는 데이터를 처리하는 기능을 포함하고 있는 라이브러리이다.

  ```python
  itertools.permutations(iterable, r=None) # 순열 튜플들 반환
  itertools.combinations(iterable, r) # 조합 튜플들 반환
  ```

### sys.setrecursionlimit()

- 파이썬의 기본 재귀 깊이 제한은 `1000`밖에 되지 않고, 이를 초과하면 `런타임에러` 가 발생한다.
- 따라서 파이썬 재귀 문제 풀이시 아래와 같이 재귀 깊이 제한을 풀어주어야한다.
  ```python
  sys.setrecursionlimit(10**6)
  ```