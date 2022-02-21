# Weather Prediction in Australia
## 📌 발표 영상
[![호주날씨예측](https://img.youtube.com/vi/rIwDuQyhjqo/0.jpg)](https://youtu.be/rIwDuQyhjqo)

## 📌 Data Collection
- 호주 날씨 데이터 (145460, 23)
- [데이터 출처: Kaggle](https://www.kaggle.com/jsphyg/weather-dataset-rattle-package)
- Columns
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/dataset.png?raw=true)
  <!-- - 'Date' : 날짜,
  - 'Location' : 장소,
  - 'MinTemp' : 최저 온도 (섭씨),
  - 'MaxTemp' : 최고 온도 (섭씨),
  - 'Rainfall': 강수량 (mm),
  - 'Evaporation' : 증발량 (mm),
  - 'Sunshine' : 일조 시간 (hour),
  - 'WindGustDir' : 가장 강한 바람 방향,
  - 'WindGustSpeed' : 가장 강한 바람 속도 (km/h),
  - 'WindDir9am' : 오전 9시 바람 방향,
  - 'WindDir3pm' : 오후 3시 바람 방향,
  - 'WindSpeed9am': 오전 9시 바람 속도 (km/h),
  - 'WindSpeed3pm': 오후 3시 바람 속도 (km/h),
  - 'Humidity9am' : 오전 9시 습도 (%),
  - 'Humidity3pm' : 오후 3시 습도 (%),
  - 'Pressure9am' : 오전 9시에 평균 해수면으로 감소된 대기압(hpa),
  - 'Pressure3pm' : 오후 3시에 평균 해수면으로 감소된 대기압(hpa),
  - 'Cloud9am' : 오전 9시 구름량 (Many),
  - 'Cloud3pm' : 오후 3시 구름량 (Many),
  - 'Temp9am' : 오전 9시 온도 (섭씨),
  - 'Temp3pm' : 오후 3시 온도 (섭씨),
  - 'RainToday' : 오늘 강우 여부 (Boolean),
  - 'RainTomorrow' : 내일 강우 여부 (Boolean) -->
- 타겟 : RainTomorrow (내일 비가 오는지 여부)

## 📌 Data Preprocessing
- 결측치 제거
  - 50,000 이상의 결측치 갖는 컬럼 제거 : ['Evaporation', 'Sunshine', 'Cloud9am', 'Cloud3pm']
  - 타겟에 결측치 있는 row 삭제
- 컬럼 생성
  - 평균 습도, 평균 기온 컬럼 생성
  - 썸머 타임을 기준으로 여름과 non-여름 계절 구분

## 📌 사용한 머신러닝 모델
- Random Forest
- XGBoost Classifier
- LightGBM Classifier

## 📌 발표 자료
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/01.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/02.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/03.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/04.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/05.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/06.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/07.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/08.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/09.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/10.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/11.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/12.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/13.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/14.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/15.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/16.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/17.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/18.jpg?raw=true)
