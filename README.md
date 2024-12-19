# fake_news_validation
데이터는 AI HUB의 낚시성 기사 탐지 데이터 중 part1의 데이터를 사용하였으며 newsTitle, newsContent, useType를 사용했습니다. 

https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=&topMenu=&aihubDataSe=data&dataSetSn=71338
<hr>

● Make_AI_Model
AI 모델을 만들 때 사용했던 파이썬 파일이 있는 폴더입니다.
데이터 위치에 맞게 데이터 파일 위치를 수정해주시길 바랍니다.
<hr>

● client/exten
사용자가 설치해서 사용할 확장 프로그램입니다.
extension파일을 크롬 확장자 관리(chrome://extensions) 페이지에서 확장 프로그램을 추가하세요.
서버를 실행하고 원하는 뉴스 페이지에서 확장 프로그램을 실행하세요.
Analyze버튼을 누르면 잠시 후 해당 뉴스의 정확도가 나옵니다.
<hr>

● server
서버에 올려서 돌리는 코드입니다.
서버 환경에 맞게 코드를 수정해서 실행해야합니다

(1). DB이름과 사용자, 비번, 포트주소를 맞춰줘야합니다.

(2). 각각의 파일 위치에서 데이터를 가져오거나 파일을 실행하는 코드일 경우 
실제 해당 위치에 해당 파일이 있는지 확인하셔야 합니다.

