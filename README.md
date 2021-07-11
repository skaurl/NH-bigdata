# AI야, 진짜 뉴스를 찾아줘!

<div>
  <img src="https://user-images.githubusercontent.com/55614265/100062745-73920c00-2e73-11eb-9f3d-9da9b5892b7b.png">
</div>

# Result
<div>
  <img src="https://user-images.githubusercontent.com/55614265/104973768-24aec000-5a39-11eb-93a6-30afa263b3b9.png">
  <img src="https://user-images.githubusercontent.com/55614265/104973764-21b3cf80-5a39-11eb-80b5-3c1e1dff7ea6.png">
</div>

# Setting
<div>
  <li>구글 드라이브 연결</li>
  <li>라이브러리 다운로드</li>
  <li>라이브러리 불러오기</li>
  <li>GPU 설정</li>
  <li>kobert 불러오기</li>
</div>

# Preprocessing
<div>
  <li>카테고리 오류 데이터 제거</li>
  <li>title + content로 데이터 구축</li>
  <li>중복 데이터 제거</li>
  <li>Train : Test = 9 : 1</li>
  <li>max_len = 128로 데이터 통일</li>
  <li>tokenizer와 kobert로 데이터 변화</li>
</div>

# Classification
<div>
  <li>BERTClassifier 사용</li>
  <li>batch_size = 64</li>
  <li>warmup_ratio = 0.01</li>
  <li>num_epochs = 5</li>
  <li>max_grad_norm = 1</li>
  <li>log_interval = 200</li>
  <li>learning_rate =  5e-5</li>
</div>

# Scoring
<div>
  <li>데이터 불러오기</li>
  <li>시간 측정 시작</li>
  <li>라이브러리 불러오기</li>
  <li>Model 불러오기</li>
  <li>형태소 분석 + 전처리</li>
  <li>예측</li>
  <li>시간 측정 종료</li>
  <li>제출</li>
</div>

# PPT
<div>
  <img src="https://user-images.githubusercontent.com/55614265/125189127-93930600-e271-11eb-9a31-4d033b51773a.jpg">
  <img src="https://user-images.githubusercontent.com/55614265/125189131-968df680-e271-11eb-8cf4-c3a5aa5fc332.jpg">
  <img src="https://user-images.githubusercontent.com/55614265/125189133-97bf2380-e271-11eb-93a4-728f27741fe1.jpg">
  <img src="https://user-images.githubusercontent.com/55614265/125189134-9857ba00-e271-11eb-8b81-f2913efc9199.jpg">
  <img src="https://user-images.githubusercontent.com/55614265/125189135-98f05080-e271-11eb-8169-fe8ea1e0cca0.jpg">
  <img src="https://user-images.githubusercontent.com/55614265/125189136-9988e700-e271-11eb-9644-07e8b2fb4811.jpg">
  <img src="https://user-images.githubusercontent.com/55614265/125189138-9a217d80-e271-11eb-8a97-d76292ec3ffe.jpg">
  <img src="https://user-images.githubusercontent.com/55614265/125189139-9aba1400-e271-11eb-9328-c46ed91829a2.jpg">
  <img src="https://user-images.githubusercontent.com/55614265/125189140-9aba1400-e271-11eb-819e-bd2101f97745.jpg">
  <img src="https://user-images.githubusercontent.com/55614265/125189142-9b52aa80-e271-11eb-9e09-ce70a86c88d6.jpg">
  <img src="https://user-images.githubusercontent.com/55614265/125189143-9b52aa80-e271-11eb-8c9a-cd2bab613adb.jpg">
  <img src="https://user-images.githubusercontent.com/55614265/125189144-9beb4100-e271-11eb-8a68-fc45686a7ab5.jpg">
  <img src="https://user-images.githubusercontent.com/55614265/125189145-9c83d780-e271-11eb-969a-38d78689541f.jpg">
  <img src="https://user-images.githubusercontent.com/55614265/125189146-9c83d780-e271-11eb-8513-a9da7d802cf0.jpg">
  <img src="https://user-images.githubusercontent.com/55614265/125189147-9d1c6e00-e271-11eb-9990-7d151ffb8ea7.jpg">
  <img src="https://user-images.githubusercontent.com/55614265/125189148-9d1c6e00-e271-11eb-9289-b067d972ea73.jpg">
  <img src="https://user-images.githubusercontent.com/55614265/125189150-9db50480-e271-11eb-8e14-281b8fa65db2.jpg">
  <img src="https://user-images.githubusercontent.com/55614265/125189151-9db50480-e271-11eb-9297-fa7cb29ef9a2.jpg">
  <img src="https://user-images.githubusercontent.com/55614265/125189152-9e4d9b00-e271-11eb-881b-46a9e2390543.jpg">
  <img src="https://user-images.githubusercontent.com/55614265/125189153-9e4d9b00-e271-11eb-8711-df502cb18b2d.jpg">
  <img src="https://user-images.githubusercontent.com/55614265/125189154-9ee63180-e271-11eb-8b66-dd4508021755.jpg">
  <img src="https://user-images.githubusercontent.com/55614265/125189155-9ee63180-e271-11eb-8b4a-08860b908fcb.jpg">
  <img src="https://user-images.githubusercontent.com/55614265/125189159-9f7ec800-e271-11eb-93a1-419a5d46af49.jpg">
  <img src="https://user-images.githubusercontent.com/55614265/125189160-a0175e80-e271-11eb-85e3-1a63fe782095.jpg">
  <img src="https://user-images.githubusercontent.com/55614265/125189161-a0175e80-e271-11eb-8f43-6da834ecb8e1.jpg">
  <img src="https://user-images.githubusercontent.com/55614265/125189162-a0aff500-e271-11eb-930f-b9ad5ccd5847.jpg">
  <img src="https://user-images.githubusercontent.com/55614265/125189163-a0aff500-e271-11eb-815e-d9e72f71dde6.jpg">
</div>
