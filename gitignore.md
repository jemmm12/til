# gitignore

> git으로 관리하지 않을 파일/폴더를 관리

* `.gitignore` 파일을 생성하여 아래와 같이 작성
  * 메모장에서 편집 금지

```bash
data.csv # 특정 파일
*.png # 특정 확장자
secret/ # 특정 폴더
!profile.png # 이 파일은 넣고 png파일 무시
```

* OS (windows/mac), 개발환경(IDE, text editor), 특정 언어에서 발생하는 파일/폴더들
  * https://gitignore.io
    * 예) 자바로 eclipse로 윈도우에서 개발하고 있다.
      * java, eclipse, windows 검색
    * 예) 맥에서 파이썬 주피터노트북으로 머신러닝



# 원격 저장소 충돌 재현

1. Github 직접 파일 수정

   > Github 수정/삭제 등 편집은 커밋이라는 사실

2. 로컬

   ```bash
   $ touch test.txt
   $ git add .
   $ git commit -m 'Add test'
   $ git push origin master
   
   ```

   