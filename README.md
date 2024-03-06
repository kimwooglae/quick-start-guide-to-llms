<h1 align="center">대규모 언어 모델에 대한 빠른 시작 가이드</h1>

<p align="center">
  <a href="https://amazon.com/quick-start-guide-language-models/dp/0138199191">오늘 사본을 받으시고 평가/리뷰를 남겨주셔서 소감을 알려주세요! ⭐⭐⭐⭐⭐
</p>

<p align="center">
  <img src="images/qsllm.jpeg" alt="대형 언어 모델에 대한 빠른 시작 가이드">
</p>

<p align="center">
  '대규모 언어 모델에 대한 빠른 시작 가이드' 책의 GitHub 리포지토리에 오신 것을 환영합니다. 이 리포지토리에는 이 책에서 사용된 코드 스니펫과 노트북이 포함되어 있으며, Transformer 모델의 다양한 애플리케이션을 보여줍니다.
</p>


## 리포지토리 구조

### 디렉터리

* `노트북`: 이 디렉터리에는 책의 각 챕터에 대한 Jupyter 노트북이 들어 있습니다.
* `데이터`: 노트북에 사용된 데이터 세트가 들어 있습니다.
* `이미지`: 노트북에 사용된 이미지와 그래프가 들어 있습니다.

### 노트북

다음은 `notebooks` 디렉토리에 포함된 노트북 중 일부입니다:

#### 파트 1 - 대규모 언어 모델 소개

* [`2_semantic_search.ipynb`](notebooks/2_semantic_search.ipynb): OpenAI와 오픈 소스 모델을 사용한 시맨틱 검색에 대한 소개입니다.
  * 여기](https://colab.research.google.com/drive/1h8dmDclOnYsXKlMDYp1uRuW55xbzypUY?usp=sharing)에 업데이트된 OpenAI 클라이언트 사용법과 **최신 V3 OpenAI 임베딩**이 포함된 업데이트된 버전이 있습니다. 스포일러 경고, 오픈 소스 임베더 + 미세 조정된 크로스 인코더가 가장 큰 OpenAI 임베더를 이겼습니다 :)
* [`3_prompt_engineering.ipynb`](notebooks/3_prompt_engineering.ipynb): 인스트럭션 정렬형 LLM을 위한 효과적인 프롬프트 엔지니어링에 대한 가이드입니다.

#### 파트 II - LLM 최대한 활용하기

* [`4_fine_tuned_classification.ipynb`](notebooks/4_fine_tuned_classification.ipynb): OpenAI 모델 미세 조정을 통해 텍스트 분류를 수행하는 방법을 알아보세요.
  * OpenAI가 새로운 미세 조정 API를 만들었고 Amazon이 제가 사용한 데이터 세트에 대한 액세스 권한을 취소했기 때문에 이전 노트북의 업데이트된 버전은 [`UPDATED 4_fine_tuned_classification_sentiment.ipynb`](notebooks/UPDATED%204_fine_tuned_classification_sentiment.ipynb)를 확인하세요(항상 긴장을 유지하게 해줍니다, 여러분께 감사드립니다).
* [`5_adv_prompt_engineering.ipynb`](notebooks/5_adv_prompt_engineering.ipynb): k-shot, 시맨틱 k-shot, 생각의 사슬 프롬프트, 연쇄, 검색 증강 생성(RAG) 지원 챗봇 구축 등 프롬프트 엔지니어링을 위한 고급 기술을 GPT-4로 구현합니다.
* [`5_VQA.ipynb`](notebooks/5_VQA.ipynb): 오픈 소스 LLM을 사용한 프롬프트 체이닝 및 시각적 질문 답변(VQA) 소개
* [`6_recommendation_engine.ipynb`](notebooks/6_recommendation_engine.ipynb): 사용자 정의 미세 조정 LLM을 사용해 추천 엔진 구축하기
  * 더 많은 그래프와 더 많은 계산이 포함된 이 사례 연구의 최신 업데이트는 여기에서 이 콜랩 노트북을 확인하세요! [https://colab.research.google.com/drive/1JfxyxdGCDjYeO52Bk1JzW4Af94xndTws?usp=sharing](https://colab.research.google.com/drive/1JfxyxdGCDjYeO52Bk1JzW4Af94xndTws?usp=sharing)

#### 파트 III - 고급 LLM 사용법

* [`7_constructing_a_vqa_system.ipynb`](notebooks/7_constructing_a_vqa_system.ipynb): 오픈 소스 GPT2와 비전 트랜스포머를 사용해 시각적 질의응답 시스템을 구축하는 단계별 가이드입니다.
* [`7_using_our_vqa.ipynb`](notebooks/7_using_our_vqa.ipynb): 이전 노트북에서 구축한 VQA 시스템을 사용할 노트북입니다.
* [`7_rl_flan_t5_summaries.ipynb`](notebooks/7_rl_flan_t5_summaries.ipynb): 강화 학습(RL)을 사용하여 FLAN-T5 모델로 보다 중립적이고 문법적으로 정확한 요약을 생성합니다.
* [`8_latex_gpt2.ipynb`](notebooks/8_latex_gpt2.ipynb): 라텍스 공식을 생성하도록 GPT-2를 미세 조정합니다.
* [`8_anime_category_classification_model_freezing.ipynb`](notebooks/8_anime_category_classification_model_freezing.ipynb): 모델 레이어를 고정하는 것과 고정하지 않은 상태를 유지하는 것을 비교하여 애니메이션 카테고리를 분류하도록 BERT 모델을 미세 조정합니다.
* [`8_optimizing_fine_tuning.ipynb`](notebooks/8_optimizing_fine_tuning.ipynb): 동적 패딩, 그라데이션 누적, 혼합 정밀도 등 트랜스포머 모델의 미세 조정을 최적화하기 위한 모범 사례입니다.
* [`8_sawyer_1_instruction_ft.ipynb`](notebooks/8_sawyer_1_instruction_ft.ipynb): SAWYER 봇의 명령어 모델을 미세 조정합니다.
* [`8_sawyer_2_train_reward_model.ipynb`](notebooks/8_sawyer_2_train_reward_model.ipynb): 사람의 선호도를 통해 SAWYER 봇의 보상 모델을 훈련합니다.
* [`8_sawyer_3_rl.ipynb`](notebooks/8_sawyer_3_rl.ipynb): 인간 피드백으로부터의 강화 학습(RLHF)을 사용하여 SAWYER 봇을 더욱 조정합니다.
* [`8_sawyer_4_use_sawyer.ipynb`](notebooks/8_sawyer_4_use_sawyer.ipynb): SAWYER 봇 사용
* [`9_distillation.ipynb`](notebooks/9_distillation.ipynb): 변압기 모델에 대한 지식 증류 기법에 대한 탐구.

앞으로도 미세 조정, 고급 프롬프트 엔지니어링, 변압기 결합 및 다양한 사용 사례와 같은 주제를 탐구하는 노트북을 계속 추가할 예정입니다. 기대해 주세요!


## 사용 방법

이 리포지토리를 사용하려면 로컬 컴퓨터에 복제하고 노트북 디렉토리로 이동한 다음 원하는 Jupyter 노트북을 엽니다. 일부 노트북에는 특정 데이터 세트가 필요할 수 있으며, 이는 `data` 디렉터리에서 찾을 수 있습니다.

필요한 라이브러리가 설치되어 있고 최신 상태인지 확인하세요. 일반적으로 터미널에서 `pip install -r requirements.txt`를 실행해 이 작업을 수행할 수 있습니다.

## 기여하기

기여를 환영합니다! 추가, 수정 또는 개선할 사항이 있으면 언제든지 풀 리퀘스트를 제출하세요.

## 면책 조항

이 리포지토리는 교육용이며 "대규모 언어 모델에 대한 빠른 시작 가이드" 책과 함께 제공됩니다. 노트북에서 다루는 주제에 대한 심층적인 설명과 토론은 책을 참조하세요.

## Sinan에서 더 보기

1. Sinan의 뉴스레터 [AI 오피스 아워](https://ai-office-hours.beehiiv.com/)에서 더 많은 AI/LLM 콘텐츠를 확인하세요!
2. Sinan은 팟캐스트 [실용적으로 지능적으로](https://podcasts.apple.com/us/podcast/practically-intelligent/id1678774315)를 통해 최신 AI에 대한 이야기를 나누고 있습니다!
3. 오라일리의 [데이터, LLM 및 ChatGPT 시작하기](https://www.oreilly.com/playlists/2953f6c7-0e13-49ac-88e2-b951e11388de) 플레이리스트에서 Sinan의 엄선된 작업 목록을 확인하세요!