# LikeLion-Mini-Project


### 프로젝트 소개
---
1️⃣ **네이버 웹툰 제목 스크래핑**
- `pandas`, `requests`, `BeautifulSoup`
- 01_naver-webtoon_by-popularity-of-the-day.ipynb
- **활용 데이터**
  - [네이버 웹툰](https://comic.naver.com/webtoon)

![image](https://github.com/Son-jinseon/LikeLion-Mini-Project/assets/105479949/003e813d-3187-4a69-b507-2fde6fcffa20)
---|

---
2️⃣ **직업/성별별 이혼 데이터 분석**
- `pandas`, `matplotlib`, `seaborn`
- **활용 데이터**
  - [[KOSIS] 시도/직업별(2007) 이혼](https://kosis.kr/statHtml/statHtml.do?orgId=101&tblId=DT_1B85033&conn_path=I2)
  - [[KOSIS] 시도/직업별(2008~) 이혼 (2008~2017)](https://kosis.kr/statHtml/statHtml.do?orgId=101&tblId=DT_1B85012&conn_path=I2)
  - [[KOSIS] 시도/시군구/월별 이혼 (시도 2007~2017)](https://kosis.kr/statHtml/statHtml.do?orgId=101&tblId=DT_1B85029&conn_path=I2)
  - [[KOSIS] 시도/평균 이혼 연령 (2007~2017)](https://kosis.kr/statHtml/statHtml.do?orgId=101&tblId=DT_1B85011&conn_path=I2)
- 02_divorce_by_occupation_gender.ipynb

<table>
  <tr>
    <td>
      <img src="https://github.com/Son-jinseon/LikeLion-Mini-Project/assets/105479949/06d2f761-710f-467e-beb9-0474e19298e2"/><br>
      <img src="https://github.com/Son-jinseon/LikeLion-Mini-Project/assets/105479949/f87c72f5-b253-4916-ac31-4671bb99a810"/>
    </td>
    <td>
       <img src="https://github.com/Son-jinseon/LikeLion-Mini-Project/assets/105479949/da913e67-7525-4374-8791-9dfa2bf378f2" />
    </td>
  <tr>
</table>

---
3️⃣ **신용카드 사용자 연체 예측**
- `pandas`, `numpy`, `matplotlib`, `seaborn`, `OrdinalEncoder`, `MinMaxScaler`, `CatBoostClassifier`
- **활용 데이터**
  - [[Dacon] 월간 데이콘 신용카드 사용자 연체 예측 AI 경진대회](https://dacon.io/competitions/official/235713/overview/description)
- **심사 기준** : Logloss
- **점수** : 0.83576
- 03_credit-card_user_delinquency_forecast.ipynb

![image](https://github.com/Son-jinseon/LikeLion-Mini-Project/assets/105479949/a008d94b-6801-4a3e-9b71-a3c9544be9b6) | ![image](https://github.com/Son-jinseon/LikeLion-Mini-Project/assets/105479949/2137eb19-c67e-44b8-916b-4ff11fe86799)
---|---|

---
4️⃣ **TMDB Box Office_영화 흥행 수익 예측**
- `pandas`, `ast`, `Ordinal Encoder`, `MinMaxScaler`, `CatBoostRegressor`
- **활용 데이터**
  - [[Kaggle] TMDB Box Office Prediction](https://www.kaggle.com/competitions/tmdb-box-office-prediction)
- **심사 기준** : RMSLE
- **점수** : 2.10605
- 04_TMDB_Box_Office_Prediction.ipynb

![image](https://github.com/Son-jinseon/LikeLion-Mini-Project/assets/105479949/6b22c069-0d9b-4fa9-9e2c-05992b361b2d) | ![image](https://github.com/Son-jinseon/LikeLion-Mini-Project/assets/105479949/00ba4652-0773-416e-8337-ebc6534f436d)
---|---|

---
5️⃣ **Spaceship Titanic_다른 차원 이동 승객 예측**
- `pandas`, `seaborn`, `KNNImputer`, `tensorflow`
- **활용 데이터**
  - [[Kaggle] Spaceship Titanic](https://www.kaggle.com/competitions/spaceship-titanic/data)
- **심사 기준** : classification accuracy
- **점수** : 0.77881
- 05_Spaceship_Titanic.ipynb

![image](https://github.com/Son-jinseon/LikeLion-Mini-Project/assets/105479949/e00800f9-f664-4ea6-8174-fac2f40f4301) | ![image](https://github.com/Son-jinseon/LikeLion-Mini-Project/assets/105479949/f23bdee0-6860-4b02-ad66-e42d58955ffc) | ![image](https://github.com/Son-jinseon/LikeLion-Mini-Project/assets/105479949/d3cfd44d-8188-4afc-924f-ee7929a46a55)
---|---|---|

---
6️⃣ **MNIST 이미지 속 알파벳 찾기**
- `pandas`, `numpy`, `matplotlib`, `glob`, `cv2`, `train_test_split`, tensorflow`, `ImageDataGenerator`
- **활용 데이터**
  - [[Dacon] 월간 데이콘 제 2회 컴퓨터 비전 학습 경진대회](https://dacon.io/competitions/official/235697/overview/description)
- **심사 기준** : Accuracy
- **점수** : The kernel appears to have died ... 😱
- 06_dirty_mnist_multi_label_classification.ipynb

![image](https://github.com/Son-jinseon/LikeLion-Mini-Project/assets/105479949/2bb09124-fa73-4a67-97b0-212ad513e45e) | ![image](https://github.com/Son-jinseon/LikeLion-Mini-Project/assets/105479949/e1f8610d-cde7-41ae-8648-79b828c1f6a0)
---|---|

![image](https://github.com/Son-jinseon/LikeLion-Mini-Project/assets/105479949/9fb05e70-87ab-4578-8b8f-dc5fd2cf930e) | ![image](https://github.com/Son-jinseon/LikeLion-Mini-Project/assets/105479949/868eb31c-9aa8-4901-8ed0-3a9dff498523)
---|---|

---
7️⃣ **문장 유형 분류**
- `pandas`, `tensorflow`, `Tokenizer`, `pad_sequences`, `train_test_split`
- **활용 데이터**
  - [[Dacon] 문장 유형 분류 AI 경진대회](https://dacon.io/competitions/official/236037/overview/description)
- **심사 기준** : Weighted F1 Score
- **점수** : 0.43941
- 07_Classify_sentence_types.ipynb

유형![image](https://github.com/Son-jinseon/LikeLion-Mini-Project/assets/105479949/cd0d7202-7c37-45ae-89cf-63a2dffed924) | 유형![image](https://github.com/Son-jinseon/LikeLion-Mini-Project/assets/105479949/9287dade-4bb1-4b7e-bdb7-16ce3c98aed0) | 극성![image](https://github.com/Son-jinseon/LikeLion-Mini-Project/assets/105479949/dee7028c-4873-4ea1-8823-c6a6e8c29a33) | 극성![image](https://github.com/Son-jinseon/LikeLion-Mini-Project/assets/105479949/55b70c73-283b-46ed-8309-dabb74e69ca4)
---|---|---|---|

시제![image](https://github.com/Son-jinseon/LikeLion-Mini-Project/assets/105479949/9161fc9e-0e80-49bb-8d98-cfb6b6266eb5) | 시제![image](https://github.com/Son-jinseon/LikeLion-Mini-Project/assets/105479949/b6d1aa59-90ca-4a71-8ca3-c4c291d49037) | 확실성![image](https://github.com/Son-jinseon/LikeLion-Mini-Project/assets/105479949/26dd65ef-0175-4e92-b94a-79141afc0d00) | 확실성![image](https://github.com/Son-jinseon/LikeLion-Mini-Project/assets/105479949/521aa669-9296-4a46-a3d0-3681b92f1b67)
---|---|---|---|


![image](https://github.com/Son-jinseon/LikeLion-Mini-Project/assets/105479949/b9e57354-4ea9-4f40-884c-44ba220e835b)
