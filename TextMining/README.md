# Text-Mining

## 🖥️ 프로젝트 소개
- 해외 기사를 크롤링하여 수능 문제를 제작 하였습니다.

  
## 🖥️ 전처리 & 모델링
해외 기사를 영어 수능 문제에 맞춰야 하기 때문에, BBC 기사에서 추상요약을 진행후 핵심문장 4래를 보기로 뽑아서 문제를 만들어 보았습니다.
전처리 : 중심문장을 맞추는 수능 형식에 기출 문제들을 뽑았습니다.
모델링 : 
- BartTokenizer 를 사용하여 추상요약을 진행 하였습니다.
- 임베딩을 통해서 중요 문장을 추출합니다.
- 문장을 전처리를 진행한 이후에 문단에서 중요한 단어들을 추출합니다.
  


## 🕰️ 개발 기간
* 23.04.06일 - 21.06.14일


### ⚙️ 개발 환경
-`Python`

## 실행 화면

<img width="654" alt="image" src="https://github.com/ppdoli123/Text-Mining/assets/93701796/a64d5ffc-8140-42e8-8f1a-45b0036ba784">

<img width="659" alt="image" src="https://github.com/ppdoli123/Text-Mining/assets/93701796/27657af5-ed67-44ef-9fe0-b38574f325fb">
