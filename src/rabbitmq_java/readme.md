GuideLine
==========
앞서 말했다시피 리눅스 데비안10 에서 테스트 중입니다.

테스트 방법
-------------

1. 가장 먼저 maridb, java, rabbitmq가 debian10에 설치완료 되어야 합니다.
2. 파일들을 clone합니다.
3. db에 데이터베이스와 테이블을 생성합니다.
4. 라이브러리 jar파일들을 환경변수 설정해줍니다.
5. 컴파일 후 실행파일 destRun을 실행시킵니다.

*로컬 통신은 문제가 없으나 rpc 원격통신을 할 경우 조금 주의 해야 할 사항이 있습니다. 가상머신에서 사용할 경우 원격통신 할 PC들의 아이피 주소를 맞춰
 주어야 하므로 와이파이 사용시 가상머신 네트워크 세팅을 브릿지로 바꾸어 줍니다. 유선 네트워크를 사용 할 경우 가상 머신 네트워크 세팅을 NAT로 잡아주고
 서버 쪽에서 포트 포워딩을 해주어야 합니다. 