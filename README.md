# Elastic Beanstalk :heart_eyes:
Elastic Beanstalk은 크게 보아 어플리케이션(Application)과 환경(Environment)으로 구성된다. <br />
어플리케이션은 버저닝된 형태로 관리되며, LB와 SG와 같은 환경들이 생성 배포 유지 관리가능한 Tier의 형태를 이루고 있다. <br />
다시말해 Devops의 모든 요소를 가지고 있다고 볼 수 있다.
<br /><br />

## Elastic Beanstalk Terminology(용어)
- Application: elastic beanstalk 논리적인 컴포넌트 집합을 말한다. 다시 말해 환경, 버전, 설정들을 포함함.
- Version: 특정 버전닝된 artifact를 의미하며 s3특정 폴더에 저장됨.
- Environment: AWS 리소스에 배포되어 돌아가는 버전을 의미하며, 같은 버전의 다수의 환경위에서 동작가능함.
- Environment Tier: elastic beanstalk을 선택할때 webserver 또는 worker 와 같은 tier를 선택하게됨.
- Configuration: elastic bean의 설정들.
<br />

## Table List
- [사전 준비 작업](./docs/pre-requisite.md)
- [EB CLI와 Git 사용](./docs/ebcli-git.md)
- [Elastic Beanstalk 사용법](./docs/ebcli-deploy.md)
- [환경 변수 관리법](./docs/ebcli-environment-variable.md)
- [Docker로 배포하기](./docs/ebcli-docker.md)
- [RBS 연결 Nodejs예제](./docs/ebcli-rds-connection-test-example.md)

## Link
- [Elastic Beanstalk 사용경험](http://yonguri.tistory.com/entry/AWS-AWS-Elastic-beanstalk-%EC%9D%84-%EC%9D%B4%EC%9A%A9%ED%95%9C-%EC%9B%B9%EC%96%B4%ED%94%8C%EB%A6%AC%EC%BC%80%EC%9D%B4%EC%85%98-%EA%B5%AC%EC%B6%95-1)
- [MacOS에서 aws-cli 설치가이드](https://docs.aws.amazon.com/ko_kr/cli/latest/userguide/cli-install-macos.html)
- [MacOS에서 eb-cli 설치가이드](https://docs.aws.amazon.com/ko_kr/elasticbeanstalk/latest/dg/eb-cli3-install-osx.html)

