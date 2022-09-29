# Build and Deploy 5 JavaScript & React API Projects in 10 Hours - Full Course | RapidAPI

## Introduction

Google 지도를 사용하여 고급 여행 동반자 응용 프로그램을 구축하고 배포합니다. \
Geolocation, Google Maps API, 장소 검색, 전문 Rapid API의 위치에 기반한 레스토랑, 호텔 및 명소 가져오기, \
데이터 필터링 등을 통해, 이 여행 어드바이저 앱은 현재 YouTube 및 전체 인터넷에서 찾을 수 있는 최고의 지도 애플리케이션입니다.

## Setup

폴더 생성 : travel_advisor \
터미널에서 travel_advisor 폴더 안에 React 설치 : npx create-react-app . \
src 폴더 삭제 후 : index.js 와 App.js 파일만 생성. \
public 폴더에서 index.html 파일만 남기고 모두 삭제. 

터미널에서 필요한 파일 설치 : \
npm install @material-ui/core @material-ui/icons @material-ui/lab @react-google-maps/api axios google-map-react \
=> @material-ui/core 들의 버전 문제로 설치가 안됨. (React 버전 17 이상 지원 안됨)

아래 코드로 설치 ( package.json 에서 확인 ) \
npm install @material-ui/core --legacy-peer-deps \
npm install @material-ui/icons --legacy-peer-deps \
npm install @material-ui/lab --legacy-peer-deps \
npm install @react-google-maps/api --legacy-peer-deps \
npm install axios \
npm install google-map-react --legacy-peer-deps 

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

**Note: this is a one-way operation. Once you `eject`, you can't go back!**
