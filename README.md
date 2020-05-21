# 골든타임 (Golden Time)

## [주제] 
공공 데이터분석을 통한 응급 의료 취약 지역 선정

## [연구 배경]
"응급실과 119 안전센터의 접근성을 고려한 응급의료 취약지 분석" 연구의 한계와 이를 보완하기 위한 추가적인 요인을 고안.
해당 연구에서 사용한 접근성 변수 외에도 각 지역의 인구 특성, 각 병원의 의료 시설 인프라는 해당 지역을 응급의료 취약지로
선정에 영향을 미치는 요인이 될 수 있으며, 이를 활용해 기존 연구보다 의미있는 응급의료 취약지를 분석한다.

<br>

## [팀원]
조병준: 코드 및 기획, 총 기획 및 진행
박경재: 코드 및 기획, 코딩 총괄
이시우: 코드 및 기획, 통계 총괄
정윤호: 코드 및 기획, 시각화 구현, 기록
손지현 (청강생): 코드 및 기획
서아론 (청강생): 코드 및 기획 


* 역할분배에 관하여: 모든 팀원들이 아이디어 제시하고 통계 방법론들을 논의하며 데이터분석과 코딩에 참여했으나, 통계적인 부분의 진행 관리 및 팀원 지시는 응용통계학 전공자이신 이시우님께서 담당하셨으며, 데이터분석의 프로그래밍 부분의 진행 관리 및 팀원 지시는 박경재님께서 담당하셨습니다. 팀이 다양한 배경과 전공으로 이루어진만큼, 팀원 모두 서로를 보완하고 이끌어가는 방법으로 프로젝트를 진행하고 있습니다. 

<br>

## 1. 사용할 데이터
- 의료 취약 지역을 선정하는 변수는 다음과 같다.
  1. 접근성 - 특정 지역의 중심을 기점으로 도로망을 통해 특정 시간(30분) 내에 이동할 수 있는 응급 의료 시설 점수
  2. 의료 시설 인프라 - 수용 가능한 질환, 시술명 / 가용 병상 수 / 병원 등급에 따른 점수
  3. 인구 - 취약 계층, 인구 밀도

### 1-1. 데이터 출처
- 접근성, 의료 시설 인프라에 대한 데이터는 국립 중앙의료원에서 제공하는 응급의료조회서비스를 사용.
- 취약 계층 - ?
- 인구 밀도 - ?

### 1-2. 데이터 분석 기법
- 응급 의료 취약 지역 scoring 통계 모델
  1. Prescriptive Analysis - Factor analysis : 접근성, 인프라, 인구 변수에 대한 scoring 작업 진행.
  2. Path Analysis - 변수들 간의 관계를 규정. 위 3가지 변수에 대한 관계를 규정?

- 미래 응급 의료 취약 지역 예측(미정)
  1. Time Series Analysis(시계열 분석) - 해당 지역의 인구 밀도 변화에 따른 응급 의료 취약 지역 변화 가능성 예측.

<br>

## 2. 응급의료조회 API 활용 구체 방안
### 2-1. 접근성 데이터 호출 API
  1.

### 2-2. 
### 2-3. 데이터별 가중치

<br>

## 3. 인구 정보(취약 계층, 인구 밀도) 활용 방안
### 3-1. 


## 토의 내역:
https://hackmd.io/pzLZVST9Q_iLrxQ09N16cw?view
