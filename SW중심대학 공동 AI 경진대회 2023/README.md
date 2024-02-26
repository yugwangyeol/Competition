# SW중심대학 공동 AI 경진대회 2023

<br/>

## 1. 배경 & 목적
 
- 주제 : 위성 이미지 건물 영역 분할 (Satellite Image Building Area Segmentation)
- 목적 : 위성 이미지의 건물 영역 분할(Image Segmentation)을 수행하는 AI모델을 개발
![스크린샷 2024-02-26 155600](https://github.com/yugwangyeol/Competition/assets/72298825/76ce5839-dc17-4c90-90f1-a688cb09d0d5)

<br/>

## 2. 주최/주관 & 성과

- 주최/주관: DACON
- 참가인원 : 1,032명
- 성과 : 103등

<br/>

## 3. 프로젝트 기간

![스크린샷 2023-04-03 144109](https://github.com/yugwangyeol/Competition/assets/72298825/3ebfbfaa-04b9-4b22-ac60-db3021aa74d1)

<br/>

## 4. 프로젝트 소개

**[본선]**  
<br/>
&nbsp;&nbsp;&nbsp;&nbsp; 위성 이미지에서 건물을 segmentation 하는 프로젝트를 진행하였다. 기본 Segment 모델과 항공/위성 segment에 특화된 모델을 사용하였다. Segmentation 모델은 **SAM, YOLOV8**과 같은 모델을 사용하였다. 항공.위성 특화 모델로는 **building-foot-print model**을 기본으로 사용하였다.
&nbsp;&nbsp;&nbsp;&nbsp; 대회 진행을 위해 다양한 전처리 기법과 데이터 augmentation 기법을 시도하였다. 그러나 대회 특성상 방대한 데이터와 제한된 자원으로 인해 많은 실험을 진행하지 못하였다.

<br/>

## 5. Process

### ch.1 EDA  

- 데이터 라벨 특성 파악
- Miss match Data search

---

### ch.2 Data cleansing & augmentation  

- Data cleansing
- Data patch transform
- Data split

---

### ch.3 Modeling

- SAM
- YOLOV8
- building-foot-print
- 후처리

<br/>

## 6. 프로젝트 팀원 및 담당 역할

**[팀원]**

- 학부생 5명

**[담당 역할]**

- 데이터 전처리 및 EDA
- 모델링&알고리즘 개발

<br/>

## 6. 발표 자료&참고 자료

[SW중심대학 공동 AI 경진대회 2023](https://dacon.io/competitions/official/236092/overview/description)  
