##자율주행 컴퓨팅 과제 #1
학습을 시키기 위해 필요한 파일들
● requirements.txt : Q-learning & Sarsa를 학습시키기 위해 필요한 라이브러리와 버전 정보를 담고 있는 파일
● utils.py :  gym 환경을 wrapping하여 Q-learning & Sarsa를 학습할 시 관측을 평평한 배열 형태로 변환하고, 게임의 비디오를 녹화하고 재생하는 기능을 제공해주는 파이썬 파일
● __init__.py : 모듈을 초기화하는 역할을 하는 파이썬 파일, utils 파일 안의 모듈을 가지고 오고 있다.

학습시키고 mingrid 돌려본 파일:
● Q-learning.ipynb : Q-learning을 학습시켜 Empty에서 q-learning돌려본 코드
● Sarsa.ipynb : Sarsa를 학습시켜 Empty에서 sarsa 돌려본 코드

● Q-learning_lavagap.ipynb : Q-learning을 학습시켜 Lavagap에서 q-learning 돌려본 코드
● Sarsa_lavagap.ipynb : Sarsa를 학습시켜 Lavagap에서 sarsa 돌려본 코드

result video 폴더:
Q-learning_4000 : Q-learning을 empty 환경에서 돌려본 영상
Q-learning_lavagap_4000 : Q-learning을 lavagap 환경에서 돌려본 영상
Sarsa_20000 : Sarsa를 empty 환경에서 돌려본 영상
Sarsa_lavagap_30000 : Sarsa를 lavagap에서 돌려본 영상

logs 폴더: 
rewards_qlearning.csv : Q-learning 학습 시 reward 저장한 파일 (empty)
rewards_qlearning_lavagap.csv : Q-learning 학습 시 reward 저장한 파일 (lavagap)
rewards_srasa.csv : Sarsa 학습 시 reward 저장한 파일 (empty)
rewrads_sarsa_lavagap.csv : Sarsa 학습 시 reward 저장한 파일 (lavagap)
