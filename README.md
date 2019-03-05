# Centos

CentOS7.x 설치 이후 필요한 스크립트를 작성하는 리포지터리입니다.

- bin : 실행파일이 모여있습니다.
- env : 환경변수 파일이 모여있습니다.
- scripts : bash script가 모여있는 경로입니다. 

## CentOS Bash 설정

~/.bashrc 파일 내부에 아래 코드가 설정되어있어야 합니다.

```bash 
source ~/centos/env/init.env
source ~/centos/env/help.env
```
