#RTdata
##Create Column
1) Make "CrtRT" accurcy=1인 RT만 포함  accurcy=0은 BLANK로 두기   <br />
2) Make "SlowRTremove", "CrtRT" 컬럼에서 RT>3000ms은 BLANK로 두기 <br />
3) Make "CrtRTfinal" , accurcy=1 RT<=3000ms 만 포함 <br />


###Counting
1)Each subject, type column에서 match miss type에 따라 CrtRT 컬럼의 BLANK수  <br />
agegroup에 따라 match miss type에 따라 CrtRT, BLANK수, 그리고 전체에 대한 %로 <br />
2) Each subject, type column에서 match miss type에 따라 SlowRTremove 컬럼의 BLANK수, CrtRT에서 SlowRTremove조건추가로 늘어난 Blank 수를 말함  <br />
agegroup에 따라 match miss type에 따라  CrtRT에서 SlowRTremove조건추가로 늘어난 BLANK수, 그리고 전체에 대한%로 <br />

###Counting 후 추가로 제외할 Subject 결정 후, mean 계산
1) column 구성 <br />
Subject Version List Agegroup matchacc missacc match_med miss_med match_mean miss_mean <br />
Subject Version List Agegroup 까지는 원래 data에 있는 대로 <br />
matchacc missacc matchacc match_med miss_med match_mean miss_mean 컬럼을 새로 계산 <br />

2) matchacc missacc  <br />
matchacc: Each subject, type 컬럼에서 match에 대한  mean % accuracy <br />
missacc: Each subject, type 컬럼에서 miss에 대한  mean % accuracy <br />

3) match_med miss_med <br />
match_med: Each subject, CrtRTfinal 컬럼에서 match에 대한  median RT <br />
miss_med: Each subject, CrtRTfinal 컬럼에서 miss에 대한  median RT <br />

4) match_mean miss_mean
match_mean: Each subject, CrtRTfinal 컬럼에서 match에 대한  mean RT <br />
miss_mean: Each subject, CrtRTfinal 컬럼에서 miss에 대한  mean RT <br />

