# TIL (Today I Learned)
## git & github 특강 1일차 정리
### CLI 기초
* CLI (Command Line Interface)
  * 다양한 명령어
    1. mkdir
    2. ls
    3. mv
    4. touch

* Markdown
  * Markdown 실습
  * 제목 `# 제목`
  * 목록
    1. 순서 없는 목록 `* 목록`
    2. 순서 있는 목록 `1. 목록`
  * 강조
    1. _기울임_
    2. __굵게__
    3. ___기울임&굵게___
    4. ~~취소~~
  * 코드 
    ```python
    for i in range(10)
        print("Hi")
    ```
  * 링크 `[표시할 글자](주소)`
  * 이미지 `![대체 텍스트](이미지 주소)`
  * 인용 `> 인용문`
    > 인용문
  * 표

    | col1 | col2 |
    | :---: | :---: |
    | 1 | 2 |

  * 수평선 `---`
---
  

### Git 기초
* git init
  * git으로 관리 시작 -> 디렉토리당 한번만 (주의! 홈폴더나 바탕화면 X)
* git status
  * 파일 상태 확인
* git add 파일명
  * Staging area에 파일 올리기
* git commit -m "커밋 사유"
  * 변경사항을 기록 (vim 빠져 나오는 것 esc + :q)
* git log
  * 커밋의 내역 확인
  * --oneline 으로 간단하게 표시
* 커밋 비교하기
  * git diff 해쉬값 해쉬값

### Github
* github와 연결
  * git remote add URL
  * git remote -v
  * git remote rm origin
* github에 local commits 올리기
  * git push origin master