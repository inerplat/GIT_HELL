# GIT-HELL

## 디렉토리 생성
```
mkdir "폴더명"
```

## 버전관리 시작
```
git init
```

## 상태보기
```
git status
```

## 로그
```
git log
```

## 수정내용 확인
```
git diff
```
## commit을 진행할 파일 추가
```
git add
```

## 내용 제출
```
git commit
```
>commit를 진행하기 전 git add를 반드시 진행해야 함
>(수정하고싶은 파일을 선택하기 위해서)
>
>### git add + git commit
>```
>git commit -a
>```

## log에서 수정내역 보기
```
git log -p
```

## gistory 설치
파이썬 3.x기준
```
pip3 install gistory
```

## gistory 실행
```
gistory -p"포트번호"
```
>ex) 분석을 원하는 디렉토리로 이동 후 gistory -p8805

## branch 상태보기
```
git branch
```

## branch 이동하기
```
git checkout "branch_name"
```

## branch 삭제
```
git branch "branch_name" --d
```
