# open-api-crawlering

## 국토교통부_한국건설기술연구원 상시/수시 교통량 정보조회서비스
### DATA 제공 URL https://www.data.go.kr/iim/api/selectAPIAcountView.do

1) 수시 도로유형별 교통량 조회 ✔
2) 상시 차종별 교통량 조회 ✔
3) 상시 시간대별 교통량 조회
4) 교통량 측정 지점 조회 ✔
5) 측정 장치 목록 조회 ✔
6) 측정 장치 상세 상태 조회

💃🕺
### 사용방법 (요청메세지 입력)
```
http://apis.data.go.kr/1613000/KICTOpenAPI/spothcv + 인증키 + 그 외 요청 변수입력 
```

### 추가설명
요청변수는 번호마다 다름. <br/>
예를 들어 2번의 `요청변수`에는 'dtype', 'output', 'pageNo', 'month', 'numOfRows' 등이 있음 <br/>
`응답항목`에는 'resultCode', 'resultMsg', 'numOfRows', 'year', 'dtype', 'pageNo', <br/>
'count', 'traffic', < 'spot_id', 'month', 'day', 'direction', 'vehicle_type1' 부터 'vechicle_type12', 'totalcount' >

자세한 데이터 설명은 위 주소에 들어가서 기술문서 참고 😉

![open api 활용가이드](https://user-images.githubusercontent.com/99319638/167350628-f21ed972-efec-4072-8ed1-3a6cd4f24fa0.PNG)


##### 정리해두면 언젠가 다시 사용하는 날이 있지 않을까 :)
##### 기억보다는 기록에 !
