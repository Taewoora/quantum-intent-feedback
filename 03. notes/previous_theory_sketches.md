# Previous Theory Sketches  
> 과거 이론 메모 및 초기 구상 정리

---

## 📄 Distance-Based Feedback Model for Adaptive Quantum State Preparation  
### 파일:
- [Existence_as_Function.pdf](./Existence_as_Function.pdf) (영어)
- [Existence_as_Function(kor).pdf](./Existence_as_Function(kor).pdf) (한국어)

### 개요:
이 문서에서는 간단하면서도 효과적인 거리 기반 피드백 모델을 제안합니다.  
주요 내용은 다음과 같습니다:

- **핵심 아이디어:**  
  출력 분포에서 지배적인 상태와 목표 상태 사이의 해밍 거리를 기반으로, 회전 게이트를 조정하여 회로를 점진적으로 목표 상태로 유도합니다.

- **회로 구성:**  
  얕은 회로 구조(Hadamard, CX, Z)를 기반으로 하며, Ry 게이트를 통해 각 큐비트의 회전 각도를 조정합니다.

- **실험 결과:**  
  Qiskit을 이용한 반복 시뮬레이션을 통해, 타겟 상태에 수렴하는 경향을 보였으며 통계적으로도 유의미함(ANOVA, t-test)을 확인했습니다.

- **의의:**  
  이 모델은 그래디언트 계산 없이도 피드백만으로 상태 정렬이 가능하다는 점에서, 변분 접근법에 대한 현실적인 대안을 제시합니다. 특히 NISQ 시대의 제약 하에서 높은 실용성을 지닙니다.

---

향후 자가조절 회로, 강화학습형 제어 구조, 동적 상태 추적 등으로의 확장이 기대됩니다.
