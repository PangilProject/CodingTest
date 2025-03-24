# CodingTest

## 구성원 정보

| 이름   | 사용 언어 |
| ------ | --------- |
| 김광일 | python    |
| 김민섭 | python    |
| 김채린 | C++       |
| 김하람 | python    |

## 방식

1. **Repository 설정**

   - `coding-test` 같은 이름으로 GitHub Repository 생성
   - `main` 브랜치는 항상 안정적인 상태 유지

2. **Branch 전략**

   - 각자 **자신의 이름 또는 닉네임**으로 브랜치를 만든다.

3. **폴더 구조**

   ```
   /
   ├── README.md
   ├── problems/  # 문제 풀이 코드 모음
   │   ├── pangil/
   │   │   ├── boj-1234.py
   │   │   ├── programmers-5678.js
   │   ├── rlacofls/
   │   │   ├── boj-9999.cpp
   │   │   ├── leetcode-2222.py
   ```

   - `problems/` 아래에 각자 폴더를 만들고 코드 저장

4. **작업 흐름**

   1. `feature/{이름}` 브랜치에서 문제별 브랜치(`feature/{이름}/boj-1234`) 생성
   2. 문제 풀이 후 **PR 생성** (베이스 브랜치는 `feature/{이름}`)
   3. 생성한 **PR**을 merge 진행.
   4. 다른 사람이 리뷰 진행 (댓글 기능 사용)

5. **PR 리뷰 방식**
   - GitHub의 **PR Review 기능**을 사용해서 코드에 직접 코멘트 작성
