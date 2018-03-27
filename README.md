
# Flask Skeleton

## settings.py
프로젝트 기본 설정 파일 

## main.py
Flaks app이 존재하는 파일.
실행시킬때는 이것을 사용함 됌.

## manage.py
서버 실행과는 독립된 관리 기능이 있는 명령행 스크립트 파일.
예를 들어, DB 테이블을 초기화 한다거나 우편번호를 파일에서 읽어서 db에 저장한다든가와 같은 기능을 구현

## common
프로젝트 전반적으로 쓰이는 공용 라이브러리

## test
테스트 케이스 파일들 집합. 분산하여 저장하지 않고 이곳에 모아서 관리함.
> 테스트 케이스 파일명은 <orig_filename>_tests.py 


Ref. https://libsora.so/posts/flask-project-structure/
