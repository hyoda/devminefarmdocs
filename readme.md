
# 신규생성
```
명령어: mkdocs new .

C:\Users\seohy\devminefarms>docker run --rm -it -v "%cd%":/docs squidfunk/mkdocs-material new .
```



# 프리뷰모드 개발환경 실행
```
명령어: mkdocs serve 

docker run --rm -it -p 8000:8000 -v "%cd%":/docs squidfunk/mkdocs-material
```

# 빌딩작업
```
명령어: mkdocs build


```
docker run --rm -it -v "%cd%":/docs squidfunk/mkdocs-material build

# 빌드
```

```

