# :dizzy: plot_fits_image

위키에서 공개되어있는 별자리와 성운 등의 적경과 적위 정보를 입력하여, 허블 아카이브에서 별을 촬영한 천문 기록 데이터른 fits 확장자 파일을 다운받아 파이썬 코드를 활용해 시각화했다.
fits파일은 그래픽 파일만 구현이 가능할 뿐아니라, 촬영 날짜 정보 찍고 있는 위치, 사용 기기 등의 정보를 제공하고있다. 코드는 생성형 AI를 통해 작성했으며, 데이터에 대한 분석은 코드로 계속 데이터를 돌려보며 익힐 수 있었다. 즉, 과학 정보도 아무런 사전 지식 없는 나 같은 사람이 접근 및 분석을 시도할 수 있는 것이 공공데이터의 의의다.

### :dizzy:원숭이 머리 성운 정보

#### - 원숭이 머리 성운 위키정보 사용
[원숭이 머리 성운 위키 정보](https://ko.wikipedia.org/wiki/%EC%9B%90%EC%88%AD%EC%9D%B4_%EB%A8%B8%EB%A6%AC_%EC%84%B1%EC%9A%B4 )

#### -원숭이 머리 성운 Hubble Legacy Archive
[원숭이 머리 성운 fits 파일 출처](https://hla.stsci.edu/hlaview.html#Inventory|filterText%3D%24filterTypes%3D|query_string=06%2009.7%2020%2030&posfilename=&poslocalname=&posfilecount=&listdelimiter=whitespace&listformat=degrees&RA=92.425000&Dec=20.500000&Radius=0.200000&inst-control=all&inst=ACS&inst=ACSGrism&inst=WFC3&inst=WFPC2&inst=NICMOS&inst=NICGRISM&inst=COS&inst=WFPC2-PC&inst=STIS&inst=FOS&inst=GHRS&imagetype=best&prop_id=&spectral_elt=&proprietary=both&preview=1&output_size=256&cutout_size=12.8|ra=&dec=&sr=&level=&image=&inst=ACS%2CACSGrism%2CWFC3%2CWFPC2%2CNICMOS%2CNICGRISM%2CCOS%2CWFPC2-PC%2CSTIS%2CFOS%2CGHRS&ds=)

- 흑백 촬영본 그리기
  
![원숭이 머리 성운](https://github.com/user-attachments/assets/add3f5e6-059e-42df-af65-556d4c455749)!

- 컬러 촬영본 그리기
  
![원숭이 머리 성운](https://github.com/user-attachments/assets/8fca320f-c7e3-4738-ba0b-bd3d87b3a20f)

| 항목         | 값                        |
|-------------|---------------------------|
| 형태        | 행성상 성운               |
| 적경        | 06h 09.7m                 |
| 적위        | +20° 30′                   |
| 거리        | 6,400 광년 (2,000 파섹)   |
| 겉보기 등급 | +6.8                      |
| 별자리      | 오리온자리                |

| 항목                 | 값                                     |
|----------------------|--------------------------------------|
| 파일 유형            | SCI (과학 이미지 데이터)             |
| 이미지 크기          | 1924 × 2085 × 3 (3개의 채널 포함)  |
| 비트 심도 (BITPIX)   | -32 (부동소수점 데이터)              |
| 촬영 날짜           | 2025-03-15T16:32:04 UTC             |
| 망원경              | HST (허블 우주망원경)                |
| 사용된 기기         | WFC3 (광역 카메라 3, 적외선 모드)   |
| 관측 대상           | NGC 2174                            |
| 적경 (RA)           | 92.29428416667°                     |
| 적위 (Dec)          | 20.45989166667°                     |
| 제안된 관측 프로젝트 | 프로젝트 ID 13623                    |

### :dizzy:수리 성운 (창조의 기둥) 정보



#### - 수리 성운 위키정보 사용
[수리 성운 위키 정보](https://ko.wikipedia.org/wiki/%EC%88%98%EB%A6%AC_%EC%84%B1%EC%9A%B4)

#### - 수리 성운 Hubble Legacy Archive
[수리 성운 fits 파일 출처](https://hla.stsci.edu/hlaview.html#Inventory|filterText%3D%24filterTypes%3D|query_string=18%2018%2048%20-13%2049&posfilename=&poslocalname=&posfilecount=&listdelimiter=whitespace&listformat=degrees&RA=274.700000&Dec=-13.816667&Radius=0.200000&inst-control=all&inst=ACS&inst=ACSGrism&inst=WFC3&inst=WFPC2&inst=NICMOS&inst=NICGRISM&inst=COS&inst=WFPC2-PC&inst=STIS&inst=FOS&inst=GHRS&imagetype=best&prop_id=&spectral_elt=&proprietary=both&preview=1&output_size=256&cutout_size=12.8|ra=&dec=&sr=&level=&image=&inst=ACS%2CACSGrism%2CWFC3%2CWFPC2%2CNICMOS%2CNICGRISM%2CCOS%2CWFPC2-PC%2CSTIS%2CFOS%2CGHRS&ds=)<br/>

- 컬러 촬영본 그리기
  
![수리 성운(창조의 기둥)](https://github.com/user-attachments/assets/40894abd-412d-4521-b281-9f02c83371ab)

| 항목   | 값                 |
|--------|-------------------|
| 형태   | H II 영역         |
| 적경   | 18h 18m 48s       |
| 적위   | -13° 49′         |
| 거리   | 7,000 광년        |
| 겉보기 등급 | 6.0          |
| 별자리 | 뱀자리           |

| 항목                 | 값                                     |
|----------------------|--------------------------------------|
| 파일 유형            | SCI (과학 이미지 데이터)             |
| 이미지 크기          | 4000 × 4200 × 3 (3개의 채널 포함)  |
| 비트 심도 (BITPIX)   | -32 (부동소수점 데이터)              |
| 촬영 날짜           | 2025-03-16T12:00:46 UTC             |
| 망원경              | HST (허블 우주망원경)                |
| 사용된 기기         | WFC3 (광역 카메라 3, 적외선 모드)   |
| 관측 대상           | LBN67-IR (독수리 성운의 적외선 영역) |
| 적경 (RA)           | 274.7172066667°                     |
| 적위 (Dec)          | -13.8360555556°                     |
| 제안된 관측 프로젝트 | 프로젝트 ID 13926                    |

