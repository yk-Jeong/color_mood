# color_mood
🎨 사용자가 제시한 이미지의 무드를 추측하는 딥러닝 모델 구축 프로젝트 


### 프로젝트 개요
(기획의 배경 및 의도 들어갈 자리) 

- 가설: 
- 프로젝트의 목표: 색조(color tone)이 인간에게 불러일으키는 공통된 심상을 딥러닝을 통해 모델화하고자 함 

### 파일 설명
- **code.ipynb** 분석을 위해 작성한 전체 코드(`google colab`에서 작업)
- **presentation.pdf** 프레젠테이션을 위해 제작한 ppt의 pdf 버전

>💭 **작업환경** `google colab` 
>
>📅 **진행기간** 1차 21.07.15 ~ 21.12.13 수정 22.08.00~
### 문제해결 과정
이미지에서 주 색조를 추출하는 모델을 구축 → 추출한 주 색조를 자연어 색상명으로 변환 → 자연어 색상명과 각 무드를 매칭 → 입력받은 이미지의 주 색조를 추출해 무드를 도출 → 사용자의 피드백 수집
- 사용 모델: 


### 데이터 세트의 특징

- 출처: 인터넷 서점 예스24(yes24.com)에서 국내 문학부문 최신간 표지 1천여건을 직접 수집(selenium 활용)
※데이터 세트 전처리 과정: (400, 280)px로 이미지 크기 축소 통일
그 외 결측치 제거, 대소문자 통일 등 기본적인 전처리 완료 

### 결과 요약

- 가설: 검증되었는지?
- 목표: 달성되었는지?
- 그 밖에 기대하지 않았던 인사이트가 있었다면?

### 한계점과 보완 방안
- 해결하지 못한 문제: 

#### 한계
- 데이터상의 한계: 
- 모델 구축상의 한계: 

#### 보완방안
- 데이터 측면: 
- 



### Update
- (2022.07.28~) 프로젝트 소개문 재작성

