# Surface-Scale-Defects
Data Analysis Project
-----------------------------
# Overview
* Organization : POSCO AI BIG DATA ACADEMY  
* Project Title : 압연 공정 scale 불량 유발 영향인자 분석 및 해결 방안 도출  
* Project Description : 압연 공정의 scale 발생 원인 파악 및 결과 해석을 통한 개선 기회 도출  
* Author : 황규희  
* Date : 2021.03.11  
-----------------------------
# Dataset  
* SCALE불량.csv : 후판공정 scale 데이터  
-----------------------------
# Background
## 철의 5대 원소
* C (Carbon) 탄소
  - 강도를 높이는 역할
  - 탄소 증가 : 경도 증가, 항복점 증가, 인장강도 증가
  - 탄소 감소 : 연신율 증가, 연성 증가
* Si (Silicon) 규소
  - 산소를 빼는 탈산제 역할
  - 규소 증가 : 인성 저하
* Mn (Manganese) 망간
  - 점성을 부여하는 역할
  - 내산성을 저해하는 역할
* P (Phosphorus) 인
  - 일반적으로 강에 해로운 원소
  - 인 증가 : 내후성 향상, 피삭성 개선, 충격저항 저하
* S (Sulfur/Thion) 황
  - 철과 결합하여 FeS를 형성
  - 취약하고 용융점이 낮아 열간 및 냉간 가공시 균열을 발생 시킴
### 용어 설명
- 경도 : 딱딱한 정도
- 항복점 : 탄성 한도를 넘어서 최초로 원형을 회복하지 못할 때의 응력이 나타내는 값
- 인장강도 : 재료가 절단되도록 끌어당겼을 때 견뎌내는 최대 하중을 재료의 단면적으로 나눈 값
- 연신률 : 쇠붙이 따위가 끊어지지 않고 늘어나는 비율
- 연성 : 물질이 탄성 한계를 넘는 힘을 받아도 파괴되지 않고 늘어나는 성질
- 인성 : 잡아당기는 힘에 견디는 성질
- 소성가공성 : 재료의 소성을 이용하여 가공하는 것
- 내산성 : 산(酸)에 잘 견디는 성질.
------------------------------
## 공정의 종류
* 제선 공정
  - 고로에 철광성을 넣고 코크스를 태워 철광석 중 산소를 제거하고 용해시켜 선철로 만드는 공정을 의미한다.
* 제강 공정
  - 고로에서 생산된 쇳물인 용선은 탄소의 함유량이 많고 인, 황과 같은 불순물이 포함되어 으스러지기 쉬운 상태다.
  - 탄소 함유량을 줄이고 인, 황등 불순물을 제거하는 공정을 의미한다.
* 연속주조 공정
  - 전로에서 생산된 용강을 일정한 형태의 주형에 부어서 강괴를 만든 후 분괴압연을 거쳐 슬래브를 제조하던 종래의 조괴법을 발전시킨 기술을 의미한다.
  - 중간소재
    + 슬래브(Slab)
    + 블룸(Bloom)
    + 빌릿(Billet) 
* 압연 공정
  - 금속  소성 가공 방법 중 하나인 roll을 이용해 두께를 줄이고 일정하게 만드는 공정을 의미한다.
  - 이때 roll을 압연기 즉 rolling mill이라고 지칭한다.
  - 제강 공정에서 생성된 용강은 연성과 전성이 있기 때문에 형태를 바꿀 수 있다.
  - 열간 압연 : 금속의 재결정 온도 이상에서 작업이 수행되는 경우
  - 냉간 압연 : 금속의 재결정 온도 이하에서 작업이 수행되는 경우

