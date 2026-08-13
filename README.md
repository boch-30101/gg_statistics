# gg_statistics
통계 기본 실습

# git 레피지토리 만들기
- 레포지 토리 클론하기
```
git clone git_url statistics_ex
```

# 가상환경 구성하기
- 디렉토리 이동
```
cd statistics_ex
```
- uv 가상환경 만들기
```
uv init --bare
```

# 주피터 노트북 사용환경 구성하기
- ipkernel 설치
```
uv add ipykernel
```
- 가상환경 .venv를 eda_env 이름으로 등록하기
```
python -m ipykernel install --user --name .venv --display-name "eda_env"
```

# 설치 라이브러리
```
uv add numpy
```