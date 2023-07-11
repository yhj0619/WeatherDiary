# WeatherDiary
3-2 모바일응용 최종 프로젝트

## 🖥️ 프로젝트 소개
날씨와 위치를 기반으로 일기를 작성하는 다이어리 안드로이드 앱입니다.
<br>

## 🕰️ 개발 기간
* 22.12.5일 - 22.12.28일
  <br>

### ⚙️ 개발 환경
- `Java 8`
- `JDK 1.8.0`
- **IDE** : STS 3.9
- **Framework** : Springboot(2.x)
- **Database** : Oracle DB(11xe)
- **ORM** : Mybatis

## 📌 주요 기능
#### 1. 날씨 정보 제공 & 옷차림 추천
- 현재 위치의 날씨 정보 제공(OpenWeatherMap API 이용)
- 기온에 따른 옷 추천 및 현재 기온에 따른 옷 추천 기능
#### 2. 일기 작성
- 일기 작성 시, 자동으로 해당 위치의 상세 날씨 정보가 작성
- 이는 사용자가 임의로 수정 가능
- 어떠한 위치에서 있었던 일기를 기록하고 싶을 때 현 위치가 보이는 Google Map 제공
- Google Map 위치 변경 가능
- Google Place API를 이용하여 해당 위치 주변 장소의 상세 정보 제공
- SQLiteDatabase를 이용하여 일기 영구 저장

#### 3. 일기 수정
- 저장된 일기 모두 수정 가능
  
#### 4. 이메일, 메세지 공유
- 날씨 정보를 이메일과 메세지로 공유 가능

## ✔️📍📸 앱 시연 영상
<a href = "https://drive.google.com/file/d/15omEHbSg-wutco8GdQizTJKo82bSw0Ff/view?usp=share_link">
