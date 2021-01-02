# AI야, 진짜 뉴스를 찾아줘!

<div>
  <img src="https://user-images.githubusercontent.com/55614265/100062745-73920c00-2e73-11eb-9f3d-9da9b5892b7b.png">
</div>

# Result
<div>
  <img src="https://user-images.githubusercontent.com/55614265/103460234-0158f500-4d58-11eb-8583-93dec1cee94c.png">
  <img src="https://user-images.githubusercontent.com/55614265/103460232-fe5e0480-4d57-11eb-86a8-3f9c42158186.png">
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
