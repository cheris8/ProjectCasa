
# Project Casa

### 프로젝트 개요

서울에 위치한 아파트 가격을 예측해주는 시스템을 구축하는 프로젝트이다.

### 사용자 가이드

1.  [Project Casa](https://github.com/whoareyouwhoami/ProjectCasa.git)
    레포를 클론 한다.

2.  가상환경을 활성화 시킨 후 `pip -r requirements.txt`를 실행시켜 필요한 패키지들을 설치한다.

3.  아래와 같이 실행 시키면 된다.

<!-- end list -->

    $ sh casa.sh --apt_name 아파트이름 --apt_area 아파트 면적

**예시:**

    ==== 실행 ====
    $ sh casa.sh --apt_name 당산반도유보라팰리스 --apt_area 108 --predict_num 4
    
    ==== 결과 ====
                       Q1        Q2         Q3
    period                                                                     
    2020-01-01  118.50000  118.5000  118.50000
    2020-02-01   33.37900   35.7580   37.61550
    2020-03-01   38.46725   40.1345   41.80175
    2020-04-01   40.42275   40.8455   41.26825

**이미 패키지들을 설치 했으면 가상환경만 활성화 시키면 된다.**
