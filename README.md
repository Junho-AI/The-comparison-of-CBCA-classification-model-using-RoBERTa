# The comparison of CBCA classification model using RoBERTa (RoBERTa를 활용한 CBCA 준거 분류 모델 성능 비교 )
## (KSC2021 언어공학 우수논문 선정)
[Link](https://www.kiise.or.kr/academy/board/academyNewsView.fa?MENU_ID=080100&sch_add_bd=%ED%95%99%ED%9A%8C%EC%86%8C%EC%8B%9D&NUM=2242)

 
## Abstract
- 아동 성범죄의 경우 피해자의 진술은 사건의 유, 무죄를 판별함에 있어서 매우 중요하게 작용하며, 대검찰청에서는 피해자 진술분석 기법인 CBCA(Criteria-Based Content Analysis)에 따라, 총 19개의 준거로 분류하여 실제 판결에 사용된다. CBCA는 피해자의 진술을 기반으로 신빙성을 판단할 수 있는 기준이며, 진술 문장에서 CBCA 준거가 많이 나타날수록 신빙성이 높다고 판단한다. 그러나 이는 진술분석관의 주관적 의견에 따라 준거 분류가 상이할 수 있다. 따라서 본 논문에서는 자연어 처리 모 델인 RoBERTa(Robustly Optimized BERT approach)를 사용하여 주관성의 개입을 배제하고 진술의 객관적 분류를 위하여 2가 지의 분류 방식을 적용하였다. 실험은 진술 문장을 CBCA의 16개 준거로 분류하는 두 가지 방법으로 진행하였다. 두 가지 방 법은 전체 모든 준거들을 동시에 분류하는 방법과 4개의 Group으로 나누어 1차 분류 후 해당 Group 내에서 어떠한 준거인지 2차 분류하는 방법으로 구성하였다. 분류 결과, 전자의 방식이 후자의 방식보다 높은 F1-score를 달성하였다.
## Code
- 대검찰청으로부터 제공받은 102개의 성범죄 대면조사 녹취록을 사용
- 
