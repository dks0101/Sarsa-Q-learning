# Q-learning & Sarsa Reinforcement Learning Project

이 프로젝트는 강화 학습 알고리즘인 Q-learning과 Sarsa를 다양한 `MiniGrid` 환경에서 학습시키고, 그 결과를 시각화한 내용입니다.

## 프로젝트 파일 구조

### 학습에 필요한 파일들

- **requirements.txt**: Q-learning 및 Sarsa 학습을 위해 필요한 라이브러리와 그 버전 정보를 담고 있습니다. 다음 명령어로 필요한 라이브러리들을 설치할 수 있습니다.
  ```bash
  pip install -r requirements.txt

- **utils.py**: `gym` 환경을 wrapping하여 Q-learning 및 Sarsa 학습 시 관측을 평평한 배열 형태로 변환해주고, 학습 도중 녹화된 비디오를 재생할 수 있도록 해주는 파일입니다. 게임 플레이를 비디오로 저장하고 시각적으로 확인하는 데 사용됩니다.

- **__init__.py**: 모듈을 초기화하는 역할을 하며, `utils.py`에 있는 함수와 클래스를 가져옵니다.

## 학습 코드

- **Q-learning.ipynb**:  
  Q-learning을 `MiniGrid-Empty` 환경에서 학습시킨 코드입니다.
  
- **Sarsa.ipynb**:  
  Sarsa 알고리즘을 `MiniGrid-Empty` 환경에서 학습시킨 코드입니다.

- **Q-learning_lavagap.ipynb**:  
  Q-learning을 `MiniGrid-LavaGap` 환경에서 학습시킨 코드입니다.
  
- **Sarsa_lavagap.ipynb**:  
  Sarsa 알고리즘을 `MiniGrid-LavaGap` 환경에서 학습시킨 코드입니다.

## 결과 비디오 폴더

- **Q-learning_4000**:  
  Q-learning을 `MiniGrid-Empty` 환경에서 4000 에피소드 동안 학습한 결과 비디오입니다.
  
- **Q-learning_lavagap_4000**:  
  Q-learning을 `MiniGrid-LavaGap` 환경에서 4000 에피소드 동안 학습한 결과 비디오입니다.

- **Sarsa_20000**:  
  Sarsa를 `MiniGrid-Empty` 환경에서 20000 에피소드 동안 학습한 결과 비디오입니다.

- **Sarsa_lavagap_30000**:  
  Sarsa를 `MiniGrid-LavaGap` 환경에서 30000 에피소드 동안 학습한 결과 비디오입니다.

## 로그 폴더

- **rewards_qlearning.csv**:  
  Q-learning을 `MiniGrid-Empty` 환경에서 학습시킨 후, 에피소드별 보상을 기록한 파일입니다.
  
- **rewards_qlearning_lavagap.csv**:  
  Q-learning을 `MiniGrid-LavaGap` 환경에서 학습시킨 후, 에피소드별 보상을 기록한 파일입니다.

- **rewards_sarsa.csv**:  
  Sarsa를 `MiniGrid-Empty` 환경에서 학습시킨 후, 에피소드별 보상을 기록한 파일입니다.

- **rewards_sarsa_lavagap.csv**:  
  Sarsa를 `MiniGrid-LavaGap` 환경에서 학습시킨 후, 에피소드별 보상을 기록한 파일입니다.
