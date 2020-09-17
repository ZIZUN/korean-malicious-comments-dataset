# korean-malicious-comments-dataset
 한국어 악성댓글 데이터셋

 - Korean Haste speech dataset 에서 hate ->0 none ->1 라벨링, offensive는 활용하지 않음 (0:1818  1:3364), 공격적이라고 악성댓글은 아니기 때문.
 - 욕설감지데이터셋 에서 욕설문장만 데이터셋으로 활용 (0:2032), 욕이 안들어갔다고 해서 악성댓글은 아니기 때문.
 - 본인이 직접 라벨링한 데이터셋 (0:2032 1:1636)
  - 라벨링 기준은 욕설이 들어갔거나, 강한 혐오표현, 비난이 들어갔을 경우 0으로 라벨링하였다.


## 성능

|                     | Accuracy (%) |
| ----------------- | ------------ |
| KcBERT            | **90.6**    |
| KoBERT            | 88.2        |
| Attention Bi-LSTM | 85.8      |

## 참조
- [kocohub/Korean-hate-speech-dataset](https://github.com/kocohub/korean-hate-speech)
- [2runo/Curse-detection-data](https://github.com/2runo/Curse-detection-data)