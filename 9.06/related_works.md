# AI 학습을 이용한 합의 알고리즘에 관한 연구들

## [Coin.AI: A Proof-of-Useful-Work Scheme for Blockchain-Based Distributed Deep Learning](https://arxiv.org/pdf/1903.09800.pdf)

## [Energy-recycling Blockchain with Proof-of-Deep-Learning](https://arxiv.org/pdf/1902.03912.pdf)

## [Proof-of-Learning: a Blockchain Consensus Mechanism based on Machine Learning Competitions](https://researchcommons.waikato.ac.nz/bitstream/handle/10289/12900/short_paper.pdf?sequence=9)

## [A Proof of Useful Work for Artificial Intelligence on the Blockchain](https://arxiv.org/pdf/2001.09244v1.pdf)

## [Proof of Learning (PoLe): Empowering Machine Learning with Consensus Building on Blockchains](https://arxiv.org/pdf/2007.15145.pdf?ref=machinelearningatscale.com)

## [Improving the Speed and Quality of GAN by Adversarial Training](https://arxiv.org/abs/2008.03364)

## [인공지능 작업증명 합의알고리즘을 사용하는 블록체인 구현](https://www-dbpia-co-kr.libproxy.sungkyul.ac.kr/journal/detail?nodeId=T16059533)

## 연구들의 공통점
일단 모두 GAN은 아님. 공통적으로 채굴자가 모델을 생성한 후, 그 모델을 검증하는 방식.

## 위 연구들과의 차별점
위 선행 연구 모두 모델을 생성해야 블록 생성 권한을 부여하기 때문에 블록 생성 주기가 길어짐. 따라서 디지털 화폐 전송 시간 증가.
GAN은 판별자의 판별여부로 블록 생성 권한을 부여하기 때문에 블록 생성 주기가 상대적으로 짧음.

## GAN의 단점
블록체인을 유지하기 위해서 학습을 계속해야하기 때문에 오버피팅의 가능성이 존재.
새로운 데이터셋을 투입하는게 가능하도록 개발해야함.
