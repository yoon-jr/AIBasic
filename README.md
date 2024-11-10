# AIBasic

### 과제 1 : MLP Classification

#### 결과 분석

1.

- learning rate 별 validation accuracy / loss 변화

  ![image](https://github.com/user-attachments/assets/3dd44b77-1cb6-4f8b-be9f-e10e4a9a0d8b)

  learning_rate = 1e-2
  output_size = 10
  epoch_size = 5
  hidden_size1 = 300
  hidden_size2 = 100
  ![image](https://github.com/user-attachments/assets/bf856fda-a308-48fc-93a9-22f69e6c4502)
  learning_rate = 1e-3
  output_size = 10
  epoch_size = 5
  hidden_size1 = 300
  hidden_size2 = 100

**learning_rate를 크게 했을 때 정확도가 올라감.**

- 학습 epoch 변화에 따른 validation accuracy / loss 변화
  ![image](https://github.com/user-attachments/assets/ade5e8c6-69a1-405a-90d2-1a9966c956e8)
  learning_rate = 1e-3
  output_size = 10
  epoch_size = 5
  hidden_size1 = 300
  hidden_size2 = 100
  ![image](https://github.com/user-attachments/assets/2d35f22b-8de1-4070-b90b-5bc8961113a5)
  learning_rate = 1e-3
  output_size = 10
  epoch_size = 10
  hidden_size1 = 300
  hidden_size2 = 100

**epoch_size를 크게 했을 때 정확도가 올라감.**

2.

- Layer 개수 별 validation accuracy / loss 변화
  ![image](https://github.com/user-attachments/assets/7c1aa379-f9d9-4e57-b02a-f25b8eb1cd17)
  4 layer MLP
  learning_rate = 1e-3
  output_size = 10
  epoch_size = 5
  hidden_sizes = [300, 100, 5]
  ![image](https://github.com/user-attachments/assets/691442ff-f193-477a-93f2-22e83cd52d72)
  5 layer MLP
  learning_rate = 1e-3
  output_size = 10
  epoch_size = 5
  hidden_sizes = [700, 300, 100, 5]

**layer가 많을수록 정확도가 높아질 것이라고 예상했지만, 오히려 정확도가 떨어짐.**

- 본인이 낼 수 있는 최대의 validation accuracy
  ![image](https://github.com/user-attachments/assets/d8fa6c3d-5d9a-4940-959b-3c67bd784e48)
  4 layer MLP
  learning_rate = 1e-3
  output_size = 10
  epoch_size = 20
  hidden_size = 1500

**hidden_size를 하나로 하고 크기를 크게 설정했을 때 정확도가 가장 높았음.**

#### 과제 2 : N-layer MLP Classification

#### 과제 3: GAN
