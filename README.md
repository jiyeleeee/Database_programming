# 🚽전국 공중화장실 현황

## 🧻홈페이지 링크
http://dbpt10.dothome.co.kr/final/intro.html

### Development tool
- DateBase: mysql
- Languages" Php + html + css + javascript
- Server: Bitnami

### Contents : 
화장실 - 좌식 여부, 남여공용여부 및 구분여부, 장애인화장실, 어린이,영업시간, 등등…
이 웹사이트는 본인이 위치한 지역을 포함한 국내 다양한 지역의 공중화장실의 여부를 확인할 수 있습니다.
공중화장실은 공공 시민들이 이용하도록 제공하기 위해 국가, 지방자치단체, 법인 또는 개인이 설치하는 화장실입니다. 공중화장실은 시민의 편의를 위해 설치된 공공시설 이기 때문에 어린이, 장애인을 위한 공간도 필수적으로 마련되어 있어야 합니다.
공중화장실은 성별에 의해서 여성용과 남성용으로 나누어지지만 어떤 곳은 남녀공용인 경우와 여성과 남성 두 구간이 붙어있는 경우도 있습니다.  따라서 사전에 검색하여 남녀공용을 원치 않는 사람은 미리 피할 수 있고,  남녀가 분리된 화장실을 이용할 수 있습니다.
또한, 장애인 분들이 장애인 전용 화장실을 이용하기 위해 많은 화장실을 찾으러 다닐 필요 없이 사이트를 통해 빠르게 찾을 수 있습니다. 이 외에도 어린이 좌변기, 소변기의 여부를 확인할 수 있도록 테이블에 보여줌으로써 사이트를 이용하는 사람들에게 편의를 줄 수 있도록 구현하였습니다.

## 💩홈페이지 소개

### ❣️ ENTER버튼을 누르면 본 페이지로 입장합니다. 지역을 선택하기 위해 전국지도를 띄우고 상세 정보 출력을 위한 테이블을 하단에 보여줍니다. 
<img width="960" alt="index" src="https://user-images.githubusercontent.com/70576313/102040997-a3e51e80-3e11-11eb-9e09-c9118b6c5e4e.png">

### ❣️ 경기도를 선택했을 때 해당 지역이 초록색으로 표시되고, 경기도에 있는 모든 공중화장실을 지도 오른쪽 테이블에 나타냅니다.
<img width="960" alt="select" src="https://user-images.githubusercontent.com/70576313/102041117-e73f8d00-3e11-11eb-93d7-2ab0cb819c3a.png"> 

### ❣️ 서울특별시의 공중화장실의 상세 정보를 검색합니다.
<img width="960" alt="search_city" src="https://user-images.githubusercontent.com/70576313/102041132-f1fa2200-3e11-11eb-9b64-9a30dfe278b3.png">

### ❣️ 서울특별시 강남구의 공중화장실의 상세 정보를 검색합니다.
<img width="960" alt="search_gu" src="https://user-images.githubusercontent.com/70576313/102041140-f8889980-3e11-11eb-92c7-ef7785c8f184.png">

### ❣️ 서울특별시 강남구의 공중화장실의 상세 정보를 출력하고, 장애인용 화장실을 체크하면 장애인용 화장실이 설치된 화장실만 출력합니다. 
<img width="960" alt="res" src="https://user-images.githubusercontent.com/70576313/102041151-fde5e400-3e11-11eb-85df-f28f44aeb80f.png">




