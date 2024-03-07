# GIS-Data
 공간 정보 데이터 및 베이스 맵

## 사용한 환경
PostgreSQL 16 <br>
PostGIS 3.4.1 <br>
QGIS 3.34.4 <br>
Jupyter Notebook <br>


## Base Map
![image](https://github.com/yoohwanihn/GIS-Data/assets/73772238/f3077cbb-8559-4cb5-9334-b8a5fd6279c3)

## Extension Function
![image](https://github.com/yoohwanihn/GIS-Data/assets/73772238/7392f2e0-f2e3-42d0-957f-5423d3960a37)


## 유의 사항

Shape 파일은 그냥 사용해도 상관 없지만 비공간 데이터를 벡터 레이아웃으로 추가할 경우 <br>쿼리문 연산을 위해 칼럼 데이터를 변경해주어야 합니다.

![image](https://github.com/yoohwanihn/GIS-Data/assets/73772238/3f2848ab-9ad7-4032-8643-52eedd4a4c21)<br><br>
<b>인구수 = INTEGER</b><br><br><br>
![image](https://github.com/yoohwanihn/GIS-Data/assets/73772238/4d39b0f4-b87e-44c9-a9b8-6b3ac0bc26fa)<br>
![image](https://github.com/yoohwanihn/GIS-Data/assets/73772238/6c2fbc3e-c30c-4d66-be6c-9530b7047161)<br><br>
부동소수점을 사용하는 <b>위도, 경도 =FLOAT</b>
