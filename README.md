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

   - 각자 **자신의 이름 또는 닉네임**으로 브랜치를 만든다. (예: `feature/kim`, `feature/lee`)
   - 문제를 풀 때는 해당 브랜치에서 **문제별 브랜치**를 생성한다. (예: `feature/kim/boj-1234`)

3. **폴더 구조**

   ```
   /
   ├── README.md
   ├── problems/  # 문제 풀이 코드 모음
   │   ├── kim/
   │   │   ├── boj-1234.py
   │   │   ├── programmers-5678.js
   │   ├── lee/
   │   │   ├── boj-9999.cpp
   │   │   ├── leetcode-2222.py
   ├── reviews/  # 코드 리뷰 작성
   │   ├── kim/
   │   │   ├── boj-1234.md  # 리뷰 내용 작성
   │   │   ├── programmers-5678.md
   │   ├── lee/
   │   │   ├── boj-9999.md
   │   │   ├── leetcode-2222.md
   ```

   - `problems/` 아래에 각자 폴더를 만들고 코드 저장
   - `reviews/` 폴더에 리뷰를 남김

4. **작업 흐름**

   1. `feature/{이름}` 브랜치에서 문제별 브랜치(`feature/{이름}/boj-1234`) 생성
   2. 문제 풀이 후 **PR 생성** (베이스 브랜치는 `feature/{이름}`)
   3. 다른 사람이 리뷰 진행 (코멘트 또는 `reviews/`에 기록)
   4. 수정 후 다시 푸시 & 머지
   5. 여러 문제를 모아 `feature/{이름}` → `main`으로 PR 보내고 머지

5. **PR 리뷰 방식**
   - GitHub의 **PR Review 기능**을 사용해서 코드에 직접 코멘트 작성
   - `reviews/` 폴더에 정리해서 상세한 피드백 남기기
