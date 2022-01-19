# Today I Learned

- 복습 철저히 하기 !!!!!!
- 오늘 하루도 화이팅 하기 !!!!!!

### 작성규칙

- 폴더와 파일명은 영문으로 작성하기

- 항상 그날 공부한내용 이나 추가한 내용 있으면 github에 올려서 기록 남기기

  

## git init

```
git init은 하위폴더 포함 git으로 관리한다는 의미이므로 github에 올리고 싶은 경우에는 꼭 git init해주기

*홈디렉토리를 git init은 절대 금지 (하면 쓸데없는 것까지 관리하므로 낭비입니다.)
```



1. __git add__
   - git add 파일 이름  <<< github에 올리기 위한 첫단계
2. __git commit -m "부가설명"__
   - `"부가설명"`에는 파일에 관한 간략한 설명 쓰면 좋을듯 합니다.
3. __git push__
   - 처음에는 git push -u origin master  << 맨처음 github에 push할때는 해야합니다.
   - 안해도 상관없으나 추후 다시 push할 경우 git push만 입력하면 되므로 꼭 하세요!
4. __git status__
   - 현재 상태를 확인해주는 창입니다. 
   - 수시로 해서 지금 상태가 어떤지 확인하면 좋을듯??



## 참고사항

### 제일 먼저 해야할 일

1. 로컬과 원격 연동하는법
   - __git remote add origin `github HTTPS 복사에서 붙여넣기`__
   - 확인하는 법은 __git remote -v__
   - 연결 끊을 경우 __git remote rm origin__