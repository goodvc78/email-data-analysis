## E-Mail 데이터 곱씹어보기  

### 개요
나의 E-Mail Data를 탐색하고 분석하는 과정을 기술하였다. 
<br>주요 내용은 https://brunch.co.kr/@goodvc78/13 참조 

### 구성 
#### Export 받은 E-Mail에서 데이터를 로드하고 탐색하는 전과정의 소스   
./01. email-data-analysis.ipynb 

### Export 받은 E-Mail Data 위치  
* 받은 메일 파일 
 ./resource/email-data-20161116/receive-mail.csv
* 보낸 메일 파일 
 ./resource/email-data-20161116/send-mail.csv
* 데이터 샘플(CSV파일) 
 <pre>
"2013-02-01 오후 2:47:46","최 규민","곽 정웅","봉 승태","RE: 시체광풍 EchoSystem 수정본 "
"2016-04-14 오후 7:00:32","파이_최규민","라크슈미_봉승태;사이고노아이_최동근;라바_주정만;지기_최재국","'남기환(KiHwan Nam)';'#최승우 연구원(KAIST)'","RE: 아프리카TV 분석데이터에 대한 내용에 관현 문의"
"2016-04-25 오후 1:33:07","파이_최규민","라크슈미_봉승태;사이고노아이_최동근;라크슈미_봉승태;지기_최재국","'남기환(KiHwan Nam)'","RE: 아프리카TV 분석데이터에 대한 내용에 관현 문의"
</pre> 


### 데이터 탐색 결과 주요 화면
* 주고 받은 메일 산점도 
<img src='https://t1.daumcdn.net/thumb/R1280x0/?fname=http://t1.daumcdn.net/brunch/service/user/Kvs/image/Trh3ZAzAC5M6-Eqoxzlcs0R4OUs.png' />

* E-Mail 토픽 추출 
<img src='https://t1.daumcdn.net/thumb/R1280x0/?fname=http://t1.daumcdn.net/brunch/service/user/Kvs/image/b0uiwTHjm9j5Mqcz0ANsTV4cgXY.png' />

* E-Mail Netwokr 분석 
<img src='https://t1.daumcdn.net/thumb/R1280x0/?fname=http://t1.daumcdn.net/brunch/service/user/Kvs/image/bDCjHjbGYoa_JeGv3NP6oBIazc8.png' />

