# flask101_deploy_test
아래의 source를 가지고 "깔끔한 파이썬 탄탄한 백엔드" 서적의 Chapter09 "AWS에 배포하기"를 따라서 진행함. 개략적인 진행은 아래와 같이 하였음.

- AWS RDS (Relational Database Service) 세팅
    - source의 `config.py` 수정
- AWS EC2 (Elastic Compute Cloud) 세팅
    - source의 `setup.py` 작성
    - PEM 발급
    - instance에 코드 배포
- ALB (Application Load Balancer) 세팅

source: https://github.com/rampart81/python-backend-book/tree/master/chapter7