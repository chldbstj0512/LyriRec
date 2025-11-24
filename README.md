# LyriRec
### 가사 기반 음악 추천 시스템 LyriRec</br>
노래 **가사 정보**를 활용하여 기존 메타데이터 중심 추천 방식보다 더 세밀한 음악 추천을 제공합니다.</br>
[LyriRec_proposal.pdf](https://github.com/user-attachments/files/23700722/LyriRec_proposal.pdf)

---

## 주요 기능
- 곡 메타데이터 기반 추천
- 가사 전처리(키워드·형태소 중심) 기반 추천
- KoBERT 기반 **가사→해시태그 분류 모델**을 통해 가사 임베딩 추출
- 다양한 입력 조합(메타데이터, 해시태그, 가사 벡터) 비교 실험

---

## Dataset
- 멜론/멜론DJ 인기 해시태그 상위 5개 기준으로 약 **10,000곡** 크롤링
- 가사, 아티스트 정보, 메타데이터 수집
- Train/Valid/Test = 8:1:1

---

## Experiments
<img width="743" height="230" alt="image" src="https://github.com/user-attachments/assets/ae1e0d17-8179-4547-a307-6d79bfe912f9" /></br>
1. 메타데이터만 활용  </br>
2. 메타데이터 + 해시태그  </br>
3. 가사 전처리 기반 추천  </br>
4. 가사 임베딩(KoBERT) 기반 추천 </br> 

---

## Goals
- 가사 정보가 실제 추천 성능 향상에 기여하는지 검증  
- 가사를 어떻게 활용하는 것이 가장 효과적인지 비교  
- 향후 가사 임베딩 기반 추천 시스템 설계로 확장 가능  

---

## Team
- 나주영  
- 남규성  
- 최윤서  
