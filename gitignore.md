# gitignore

> git 저장소에서 관리하고 싶지 않은 파일을 설정할 수 있다.

`. gitignore`파일을 생성하여 아래와 같이 설정할 수 있다.

```bash
*.xlsx # 특정 확장자 모두
secrets/ #특정 폴더 내 모두
a.txt  # 특정 파일
```

일반적으로 개발 환경에서 자주 설정하는 내용은 [gitignore.io](https://gitignore.io/)에서 가져오는 것을 추천한다.

* `python`, `windows`, `jupyternotebook` 