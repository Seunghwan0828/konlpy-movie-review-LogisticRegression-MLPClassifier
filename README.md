# konlpy_movie_review_LogisticRegression_MLPClassifier
 
LogisticRegression과 MLPClassifier 이용하여 한국영화리뷰 분석을 하였습니다.

1.Konlpy를 설치해주고 데이터를 읽어와줍니다

2.Konlpy의 0kt 형태서 분석기를 이용하여 파일의 id를 제거하고 TEXT와 LABEL을 train_docs와 test_docs에 넣어주었습니다

3.namedtuple를 사용하여 doc2vec이 요구하는 형태로 데이터를 바꿔줘줍니다

4.doc2vec를 이용하여 토큰을 벡터화 시킨다

5.학습과 테스트 데이터를 만들어준다

6.LogisticRegression과 MLPClassifier을 이용하여 분석을 해보았습니다.

7.최종결과= LogisticRegression은 67%의 결과가 나왔고 MLPClassifier은 70%의 결과가 나왔다.

8.분석= LogisticRegression보다 MLPClassifier의 결과가 3%정도 높게 나왔다.
