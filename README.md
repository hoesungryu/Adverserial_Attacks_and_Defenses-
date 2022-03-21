# Adverserial_Attacks_and_Defenses-

Based on this [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8294186)
 
## Type of Adverserial Attacks
 
 
1. Poisoning Attack: 잘못된 학습 데이터를 주입하여 오동작 발생하게 하는 공격
2. Evasion Attack: 학습 단계가 아닌 분류 단계에서 데이터를 변조하여 오동작 발생하게 하는 공격
3. Model Extraction Attack: 인공지능의 동작을 모사하여 정보를 추출하는 등의 공격
4. Inversion Attack: 반복적으로 질의하여 학습에 사용된 데이터를 추출하여 정보의 프라이버시를 침해하는 공격
   
 
## The way of making adverserial example
1. L-BFGS(BOX-CONSTRAINED L-BFGS)
2. FGSM(Fast Gradient Sign Method) [1]
3. BIM(BASIC & LEAST-LIKELY-CLASS ITERATIVE METHODS)
4. PGD(Projected Gradient Descent) [2] : Baseline 
5. ONE PIXEL ATTACK
6. C&W( CARLINI AND WAGNER ATTACKS )
7. JSMA( JACOBIAN-BASED SALIENCY MAP ATTACK)
8. Deepfool
 
## Code
https://github.com/Jeffkang-94/pytorch-adversarial-attack
 
## Reference
[1] Explaining and Harnessing Adversarial Examples, Ian J. Goodfellow, et. al.,  ICLR 2015 <p>
[2] Towards Deep Learning Models Resistant to Adversarial Attacks, Aleksander M ˛adry, et. al. 2019 https://arxiv.org/abs/1706.06083
