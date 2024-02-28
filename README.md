# 『실무로 통하는 인과추론 with 파이썬』 

이 저장소는 한빛출판사에서 출간한 한국어판 "실무로 통하는 인과추론 with 파이썬"에서 참조하는 각종 자료 및 소스 코드와 예제 데이터를 담고 있습니다. 이 책은 다음 서점에서 절찬리에 판매중입니다([교보문고](https://product.kyobobook.co.kr/detail/S000212577153), 예스24[https://www.yes24.com/Product/Goods/125196916], [인터파크](https://book.interpark.com/product/BookDisplay.do?_method=detail&sc.shopNo=0000400000&sc.prdNo=356878902&sc.saNo=003002001&bid1=search&bid2=product&bid3=title&bid4=001), [알라딘](https://www.aladin.co.kr/shop/wproduct.aspx?ItemId=335177841), [한빛미디어](https://www.hanbit.co.kr/store/books/look.php?p_code=B6208936856))

![img](./실무로%20통하는%20인과추론%20with%20파이썬/data/book_cover.jpg)

# 책 소개 #
독자 여러분은 "상관관계는 인과관계가 아니다"라는 말을 많이 들어보셨죠? 이 책은 상관관계가 왜 인과관계와 다른지 그리고 데이터 과학자의 시각에서 인과추론의 기초부터 심화에 이르기까지의 내용을 다양한 실무 사례를 바탕으로 설명합니다. 또한, 인과추론 방법론에 그치지 않고 실무에서의 데이터 분석가 또는 데이터 과학자가 고민하는 수준의 실험 결과의 신뢰성 및 추론 부분까지 다루고 있습니다. 여러분이 인과추론을 처음 접하셨다면, 내용을 바탕으로 파이썬 실습 위주로 진행해볼 수 있고, 데이터 분석가/과학자라면 사례를 중심으로 여러분의 도메인에 접목시켜 학습하는 것을 추천드립니다. 


주요 내용은 다음과 같습니다.
- 인과추론의 기본 개념과 활용법 익히기
- 인과추론과 편향의 관계 이해하기
- 인과추론으로 비즈니스 문제 해결하기
- 인과추론으로 고객을 시간에 따라 관찰하기
- 인과효과가 실험 대상마다 다를 수 있는 이유 학습하기


한국에서는 실무자가 접할 수 있는 인과추론에 대한 자료가 많이 부족하다고 생각합니다. 이 책이 여러분의 인과추론 학습에 있어 좋은 길잡이가 되길 바랍니다.
+ 박지용 교수님의 ["인과추론과 데이터과학"](https://www.youtube.com/@causaldatascience) 강의와 함께 학습하면 더 좋습니다!


# 역자 정보
## [신진수](https://www.linkedin.com/in/jinsoo-shin-436060162/)
네오플을 거쳐 크래프톤의 데이터 분석가로 일하고 있습니다. 게임 업계에서 쌓은 커리어를 기반으로 <던전앤파이터>, <뉴스테이트 모바일>, <배틀그라운드 모바일> 등 다양한 장르의 게임에서 데이터 분석과 실험을 통해 유저 경험을 개선하는 데 기여했습니다. 비영리 데이터 사이언스 커뮤니티인 가짜연구소에서 인과추론팀을 운영 중입니다. 마테우스 파쿠레의 웹북 [「Causal Inference for The Brave and True」](https://github.com/CausalInferenceLab/Causal-Inference-with-Python)를 한국어로 번역하는 작업을 주도했습니다.


## [가짜연구소 인과추론팀](https://pseudo-lab.com/6bbf03d9f11d4af687c0f03c6db39b1b)
가짜연구소 인과추론팀은 2022년부터 데이터를 통한 문제해결력을 높이고자 인과추론을 함께 학습하고 있습니다. 한국어 자료가 많지 않은 인과추론을 많은 분이 쉽게 접하실 수 있도록 기여하고자 하는 마음으로, 가짜연구소에서 인과추론 이야기와 실험 및 조직문화에 대한 이야기를 이어나가고 있습니다. 이 책의 번역 작업에는 인과추론팀 김소희, 김성수, 김상돈, 김준영, 남궁민상, 박시온, 최은희, 정호재, 홍성철이 함께 참여했습니다.


# 챕터별 자료

### 2장-무작위 실험 및 기초 통계 리뷰

| 챕터 | 내용 | 자료 링크 | 
| ------ |------|------|
| 2.6 신뢰구간 | 실제 사례: 코로나19 백신의 효과 | [Efficacy and Safety of the mRNA-1273 SARS-CoV-2 Vaccine](https://www.nejm.org/doi/full/10.1056/nejmoa2035389) |
| 2.8 p 값 | 실제 사례: 실제 사례: 대면 강의 vs. 온라인 강의 | [Is It Live or Is It Internet? Experimental Estimates of the Effects of Online Instruction on Student Learning](https://www.journals.uchicago.edu/doi/10.1086/669930) |
| 2.10 표본 크기 계산 | 더 알아보기 | [A/B Testing Intuition Busters: Common Misunderstandings in Online Controlled Experiments](https://dl.acm.org/doi/abs/10.1145/3534678.3539160) |

### 3장-그래프 인과모델
| 챕터 | 내용 | 자료 링크 | 
| ------ |------|------|
| 3.7.2 랜덤화 재해석 | 민감도 분석과 부분 식별 | [Making Sense of Sensitivity: Extending Omitted Variable Bias](https://academic.oup.com/jrsssb/article/82/1/39/7056023) |
| 3.8.1 충돌부를 조건부 설정 | 더 알아보기 | [DAGitty](https://www.dagitty.net/) |
| 3.8.1 충돌부를 조건부 설정 | 더 알아보기 | [A Crash Course in Good and Bad Controls](https://journals.sagepub.com/doi/epub/10.1177/00491241221099552) |

### 4장-유용한 선형회귀