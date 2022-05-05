# SQL Query Tokenizer
기존의 BERT Tokenizer를 SQL Corpus 데이터 셋을 활용해 학습시켜, SQL Query를 Tokenization을 할 수 있도록 Custom 하였습니다.

코드 실행 시 파일 경로와 디렉토리 구조를 확인하여 실행해주시면 됩니다.


## 파일 설명
|파일명|설명|
|------|---|
|220503_Tokenizer.ipynb|Colab 소스 코드, 코드 내 설명 -> https://colab.research.google.com/drive/1ie5ymettTTA3yod9eW7BZNJz1LU7u1Yi#scrollTo=KRiU_83Q6zj8 확인|
|resultVocabJson.json|Tokenizer가 학습하여 얻은 Vocabulary - json 형식 (Numbering 확인 가능)|
|resultVocabTxt.txt|Tokenizer가 학습하여 얻은 Vocabulary - txt 형식|
|sqlCorpus.txt|Tokenizer 학습에 활용한 SQL Corpus Data set|


## 버전 관리
+ 22/05/02 초기 버전 - 임의의 SELECT문들 긁어서 SQL Corpus 생성하여 Tokenizer 학습시킴, Query 구성 다양화 & 테이블명, 컬럼명 전처리 필요
