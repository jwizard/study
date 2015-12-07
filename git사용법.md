# git 사용법

## git에 처음 파일 올리기
 - http://emflant.tistory.com/123

### git config
 - git config 정보는 git commit 시마다 사용하는 주용한 정보로써 초기에 설정해 놓아야 한다.
```
$> git config --global user.name "JWizard"
$> git config --global user.email jwizard@sk.com
```

### git init
 - 로컬저장로소 사용할 폴더를 만든 다음 해당 위치로 이동해서 git init를 입력한다.
```
$> git init
```

### git add
 - 파일 생성하기
```
$> git add a.jsp
$> git add *
```

### git commit
 - 로컬 저장소에 올리기
```
$> git commit -m "test commit"
```

### git remote
 - remote repository 세팅
```
$> git remote add origin https://github.com/jwizard/spring_base.git
```

### git push
 - 마지막 단계로, 원격저장소에 파일을 적용하기
 - username(jwizard@sk.com), userpasswd(thlxxxx)
```
$> git push -u origin master
```

## git 올리기 가이드

### create a new repository on the command line

```
echo # study >> README.md
$> git init
$> git add README.md
$> git commit -m "first commit"
$> git remote add origin https://github.com/jwizard/study.git
$> git push -u origin master
```

### push an existing repository from the command line

```
$> git remote add origin https://github.com/jwizard/study.git
$> git push -u origin master
```
