
# Load Package

이 레포지토리는 5Zigo Gri jo의 Load의 역할을 담당하고 있습니다.

## 설치방법
이 레포지토리의 설치 방법은 아래와 같습니다.
```
# main
$ pip install git+https://github.com/5Zigo-Gri-jo/load.git
```
※ 다만 본 레포지토리는 https://github.com/5Zigo-Gri-jo/airflow_dags.git 레포지토리의 하위 패키지입니다.

## 동작내용
Transform_Package를 통해 데이터 프레임 형태로 저장한 데이터를 최종적으로 Load_Package를 이용해 parquet 파일형태로 저장하는 모듈입니다. 
