# Python-Crime-Data-Analysis   
https://koreait-academy.github.io/Crime-Data-Analysis/
![image](https://user-images.githubusercontent.com/92245622/220792509-6c902638-afd3-4e3c-88df-172e192e6dd2.png)

![image](https://user-images.githubusercontent.com/92245622/220792711-3fdab78c-80d6-4efe-b7c1-2d0ecbbc49cb.png)

<br>

###  <추진배경>

저희가 데이터 분석을 하기 전 많은 데이터를 확인하고 어떤 데이터를 분석할까 이야기 하였습니다.
이야기 중 사람에게 가장 소중한것은 무엇일까 고민 하였습니다.
개인마다 차이는 있을겁니다. 누구는 돈 누구는 연인 또는 가족 아니면 반려견 이라고 대답할것입니다.
모두 소중하고 중요하지만, 저희가 가장 중요하다고 생각하는 것은 생명이였습니다. 
목숨 즉 생명과 밀접하고 실시간으로 업로드 되는 많은 양의 범죄관련 뉴스에 나오는 자연재해와 같은 언제 일어날지 모르는 범죄에 관한 데이터를 분석해보기로 하였습니다.
지역, 장소, 요일, 시간을 통해 언제 가장 많은 범죄가 일어나는지 추가로 범죄가 일어나는 생활의 환경적 요인과 cctv와 범죄율 간의 상관관계를 분석하였습니다. 
이를 통해 조금이라도 범죄 예방에 도움이 될 수 있으면 좋겠습니다. 

<br>

![image](https://user-images.githubusercontent.com/92245622/220792760-31b63f6a-47c5-4b21-a6c0-52e682ad430f.png)

###  <공공데이터포탈>

어떤 데이터를 분석하였는지 더 자세히 설명해 드리겠습니다. 
범죄에 대한 공공 데이터 분석 및 통계입니다. 상황에 따른 범죄 빈도수와 범죄 유형에 대한 빈도수를 파악하기 위해 
1. 대검찰청_범죄지역
2. 대검찰청_범죄발생장소
3. 대검찰청_범죄발생시간
4. 대검찰청_범죄발생요일
5.경찰청_범죄자 생활정도, 혼인관계 및 부모관계 , 5대 범죄 발생건수 
6. 서울시 통계인_자치구 년도별 CCTV 설치 현황
총 6 개의 공공데이터를 이용하여 분석하였습니다.

![image](https://user-images.githubusercontent.com/92245622/220792839-392c09ea-4778-4ee9-ba47-b2678b374b1b.png)

###  <분석결과>

먼저 CCTV 증가와 범죄율의 상관관계를 알아보겠습니다.
CCTV는 매년 증가하고 있으며 이에따라 범죄율도 감소하는 모습을 볼 수 있습니다
 비단 CCTV 증가만으로 범죄율이 감소한다고 볼 수는 없습니다. 또한 범죄율이 감소한다고 나에게 위험이 발생하지
않는다고 말할 수 없습니다. 

![image](https://user-images.githubusercontent.com/92245622/220792942-f6a9501e-192d-4387-94f8-10dee66ebd65.png)

###  <분석결과>

다음은 인구 수 대비 CCTV 설치 대수에 대한 데이터 분석입니다. 강남구 양천구 순으로 인구 수 대비 CCTV 설치수가 많은 것을 알 수 있습니다, 이를 통해 CCTV 설치수가 많은 지역은 범죄율이 낮은지 확인할 필요가 있었고 이는 이 후 유동인구에 및 인구수에 따른 범죄율 상관비에서 더 자세히 알아보겠습니다.

![image](https://user-images.githubusercontent.com/92245622/220793031-aa2e5a87-7858-4c8d-912b-957fd43be628.png)

###  <분석결과>

그럼 어떠  범죄들이 많이 발생하는지 자세히 알아보겠습니다.
우리 나라의 범죄 빈도수는 교통, 폭력, 지능 순으로 높은 폭을 보여주고 있습니다.  그럼 폭력 범죄에서 어떤 폭력 범죄가 많이 일어났는지 보면 
강제추행, 강간, 강도 순으로 많은것을 볼 수 있습니다.  

![image](https://user-images.githubusercontent.com/92245622/220806289-368fe19a-dc44-4253-b4bc-21e1966078d3.png)

###  <분석결과>

다음은 지역과 장소에 관한 범죄율의 상관관계 입니다.
먼저 지역입니다. 인구와 유동인구가 많은 경기도와 서울이 많은 범죄가 발생하는것을 알 수 있습니다.

![image](https://user-images.githubusercontent.com/92245622/220806348-e68cb26f-8f16-424b-a825-bae4fa86ddae.png)


###  <분석결과>
서울의 범죄 발생율입니다. 지도를 보시면 강남이 가장 많은 범죄가 발생함을 알 수 있습니다.
앞서 보았던 CCTV 설치대수와 인구수에 따른 범죄율을  보면 강남구가 인구대비 CCTV 설치수가 가장 많았는데. 이 자료를 보면 CCTV 설치 대수가 많다고 범죄율이 낮아지지는 않았습니다. 
 이는 유동인구 학술자료를 참고하면 유동인구와 밀접한 관련성을 가지고 있는 유흥업소수 1%의 증가는 약 19.8%의 5 대 범죄를 증가시키는 것으로 나타나 유흥업소는 5대 범죄와 같은 강력범죄와 더욱 밀접 한 관련성을 가지고 있는 것으로 판단됩니다. 이는 서울권을 보면 강남은 인구가 많고 유흥업소가 많은 곳으로 범죄율이 가장 높은것을 확인가능합니다. 그럼 이 유흥업소와 관련된 알콜과 시간에 관한 연관성은  장소 이후에 더 알아보겠습니다.


![image](https://user-images.githubusercontent.com/92245622/220806383-9188cbc6-3611-4775-b4c0-322e511dedc4.png)

###  <분석결과>

 장소입니다. 장소별 범죄 빈도수 10개를 뽑아보았습니다. 범죄는 이전에 말씀봐 자연재해 같다고 말씀드렸습니다.
보시면 기타가 1등인데 이는 매우 다양한 곳에서 언제 일어날지 모른다는 것입니다. 
그럼 그나마 분석할 수 있는 장소 노상을 보겠습니다.

<br>

 노상 범죄의 빈도수를 보면 폭행, 절도, 손괴 순으로 높은것을 볼 수 있습니다. 이를통해 지역과 유사하게 인구가 많고 유동인구가 많은 장소에서 범죄율이 증가함을 알 수 있습니다. 이 분석의 결과는 범죄는 사람이 적은곳에서 일어나고 사람이 많은 곳은
범죄가 적게 일어나겠지라는 생각을 전환하게 되었습니다.

![image](https://user-images.githubusercontent.com/92245622/220806414-51e2d296-4894-4081-ae24-acbf38a18bdb.png)

###  <분석결과>

그럼 시간과 요일에 관한 범죄율의 상관관계를 알아보겠습니다.
시간입니다.  보이시는 서울남부지방검찰청의 통계와 같이 21 ~ 23시59분 많은 범죄가 일어날 수 있습니다. 추가 참고자료를 보면
국가의 공식통계자료에 나타난 우리 사회에서 알코올-관련범죄의 경우, 알코올은 손괴 및 방화 등의 파괴성 범죄와 폭행 및 성폭력 등의 폭력범죄와강한 관계를 보이는 것으로 나타났으며. 가정폭력의 경우에도 알코올은 강한 영향을 미치는것을 알 수 있습니다. 이를 통해 분석을 하여 시간데를 보면 야근이나 공부를 했을 수도 있지만 알콜 섭취를 한 사람이 집에 복귀를 많이 하는 시간임을 알 수 있습니다.

![image](https://user-images.githubusercontent.com/92245622/220806530-9927d2b7-2cb5-44e8-9bab-c11c81faa353.png)

###  <분석결과>

다음은 요일입니다. 보시는바와 같이 요일은 범죄율에 큰 폭이 없으며 큰 관계는 없다고 보입니다. 그나마 토요일에 많은 범죄가 
일어난다는 사실을 알 수 있습니다. 범죄가 발생하는 원인은 개인적요인, 심리적 요인, 사회환경적 요인들이 있는데
평소 토요일 주말 약속이 많은것을 알 수 있고 알콜 섭취로 인한 개인의 심리적 요인과 다음날 출근을 
안할 수 있는 안정감에 섭취량이 증가함에 따라 범죄율이 증가한다고 분석할 수 있습니다.

![image](https://user-images.githubusercontent.com/92245622/220806624-a0ee6c93-39fa-413d-a970-9be39e891446.png)

###  <분석결과>

마지막으로 범죄자의 생활정보에 따라 상관관계를 간단히 알아보갰습니다.
먼저 생활정도에 따른 범죄 관계
생활정도가 하류인 쪽에서 많은 범죄가 발생하고, 중류, 상류로 나타나고 있습니다. 하지만 그렇다고 하류 쪽에 있는
 사람들이 더 높은 비율로 범죄를 저지른다고 속단할 수는 없습니다. 일단 하류에 속하는 사람이 인구가 더 많고
이는 강도치사와 같은 생활 폭력범죄이고 경제 탈세 문제 같은 경우에는 상류층에서 많은 범죄가 일어나기 떄문입니다.


![image](https://user-images.githubusercontent.com/92245622/220806881-353ff269-a860-4982-a969-bd99b0981300.png)

###  <분석결과>

혼인관계에 따른 범죄 관계입니다. 이또한
교통범죄와 기타 범죄를 빼고 보면, 폭행, 사기에서는 기혼자들의 범죄가 미혼자보다 높다는 걸 확인할 수 있습니다.
 하지만 절도범죄, 폭력행위, 성풍속범죄, 병역범죄 등에서는 미혼자들의 범죄 건수가 기혼자보다 더 많이 있다는 걸 알 수 있는 도표입니다.
 결혼의 효과가 범죄에 미치는 영향에 대해서는여러 가지 논의가 있으나 학계의 대체적 입장은 결혼이 범죄율을 감소시킨다고 보고있으며
 이는 개인별 추적 조사와 집단에 대한 거시자료 분석 모두에서 동일하게 적용되고 있음을 분석 확인할 수 있습니다.

![image](https://user-images.githubusercontent.com/92245622/220806910-bf568817-55d3-4f67-bf45-00404bf1edae.png)


###  <결론>


전체적인 데이터 분석결과 범죄는 많은 연관 관계를 가지고 있으나 우발성 즉 자연재해와 같이 언제 일어날지 정확히 예측은 불가합니다.
그러나
폭행사건과 같이 우리의 안전을 위협하는 범죄는 갑자기 일어나는 경우가 많고 즉각적인 예방은 어렵지만. 범죄율을 최소화하기 위해, 범죄율이 올라갈 수 있는 시간대 요일대 국가에서 순찰 인력을 강화하고 개인적으로는 CCTV나 사람이 많은 장소라고 안전하다고 판단하기 보단 개인이 추가로 위기의식을 느끼고 조심한다면 개인과 집단의 안전을 조금 더 지킬 수 있다고 분석했습니다.


![image](https://user-images.githubusercontent.com/92245622/220806947-905c0560-f48e-470c-9660-9dbefc925c59.png)
