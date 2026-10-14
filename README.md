# Daily AI/NLP Quiz

> 매일 AI · NLP 분야의 주제 하나를 잡고, 3개의 연속 질문으로 깊게 파고드는 면접 대비 기록

---

## 진행 현황

| 항목 | 값 |
|---|---|
| 시작일 | 2026-05-06 |
| 총 진행일 | 37일 |
| 총 질문 수 | 111+ 문항 |
| 커버 주제 | ML 기초 · NLP 기초 · Transformer · Post-training · PEFT · RAG · 추론 최적화 · Context Engineering |

---

## 주제별 인덱스

### ML 기초 · 최적화

| 날짜 | 주제 | Q1 | Q2 | Q3 |
|---|---|---|---|---|
| [05-06](quizzes/2026-05-06.md) | 정규화 · Adam | L1 vs L2 정규화 | L1 미분불가능 처리 | Adam Optimizer |
| [05-07](quizzes/2026-05-07.md) | Optimizer 심화 | SGD vs Adam | Adam Bias Correction | Adam vs AdamW |
| [05-08](quizzes/2026-05-08.md) | 활성화 함수 · 정규화 | ReLU vs GELU | SiLU(Swish)와 SwiGLU | BatchNorm vs LayerNorm |
| [05-09](quizzes/2026-05-09.md) | Dropout | Dropout 동작 방식 | Inverted Dropout 기댓값 | Dropout + BN 충돌 |
| [05-10](quizzes/2026-05-10.md) | Batch Normalization | BN 수식과 ICS | 학습 vs 추론 시 BN | BN vs LN 비교 |
| [05-11](quizzes/2026-05-11.md) | 손실 함수 | Cross-Entropy vs MSE | CE가 MSE보다 좋은 이유 | CE와 KL-Divergence |
| [05-12](quizzes/2026-05-12.md) | 역전파 | Backprop & Chain Rule | 오차 신호 δ 전파 | Vanishing Gradient |
| [06-25](quizzes/2026-06-25.md) | 학습률 스케줄링 | Warmup 필요성 | Cosine Annealing | Warmup+Cosine 조합 |
| [06-26](quizzes/2026-06-26.md) | Bias-Variance | Tradeoff & 과적합/과소적합 | Bias/Variance 진단 | 복잡도와 Bias·Variance |
| [07-02](quizzes/2026-07-02.md) | 가중치 초기화 | Zero init 대칭성 | Xavier vs He | Xavier·He의 2 차이 |

### NLP 기초

| 날짜 | 주제 | Q1 | Q2 | Q3 |
|---|---|---|---|---|
| [05-13](quizzes/2026-05-13.md) | Word2Vec | CBOW vs Skip-gram | Softmax 비용 절감 | 임베딩 벡터 연산 |
| [05-14](quizzes/2026-05-14.md) | 토크나이저 | BPE 알고리즘 | Byte-level BPE vs BPE | 한국어 BPE 토큰 수 |
| [05-15](quizzes/2026-05-15.md) | 언어 모델 평가 | Perplexity & n-gram | Zero Probability 스무딩 | n-gram vs 신경망 LM |

### Transformer 아키텍처

| 날짜 | 주제 | Q1 | Q2 | Q3 |
|---|---|---|---|---|
| [05-18](quizzes/2026-05-18.md) | Attention | Scaled Dot-Product Attention | Multi-Head Attention | Self-Attention 복잡도 |
| [05-19](quizzes/2026-05-19.md) | Positional Encoding | Sinusoidal PE | 상대 위치 선형 변환 증명 | Sinusoidal vs Learned vs RoPE |
| [05-20](quizzes/2026-05-20.md) | FFN · Normalization | Transformer FFN | SwiGLU 수식 | Pre-Norm vs Post-Norm |
| [06-16](quizzes/2026-06-16.md) | RoPE | 회전으로 위치 인코딩 | 상대 위치 의존성 | vs Sinusoidal/Learned |
| [06-30](quizzes/2026-06-30.md) | Pre/Post-Norm | LN 위치 차이 | Pre-norm 안정성 | 현대 LLM의 선택 |

### Post-training · RLHF

| 날짜 | 주제 | Q1 | Q2 | Q3 |
|---|---|---|---|---|
| [05-21](quizzes/2026-05-21.md) | SFT | SFT 손실함수 | Prompt Masking | SFT 한계와 RLHF 필요성 |
| [05-22](quizzes/2026-05-22.md) | RLHF · DPO · GRPO 개요 | Reward Model & PPO KL | DPO의 이점 | GRPO vs PPO |
| [05-25](quizzes/2026-05-25.md) | DPO 심화 | RLHF-PPO 한계 & DPO 유도 | DPO의 β와 π_ref 역할 | DPO 한계와 보완 |
| [05-26](quizzes/2026-05-26.md) | GRPO 심화 | Group Relative Advantage | 그룹 크기 G의 영향 | Rule-based Reward |

### RAG · 검색

| 날짜 | 주제 | Q1 | Q2 | Q3 |
|---|---|---|---|---|
| [05-27](quizzes/2026-05-27.md) | 검색 전략 | BM25 · Dense · Hybrid Search | 코사인 유사도 vs 내적 · ANN | Cross-Encoder Reranker |
| [05-28](quizzes/2026-05-28.md) | Chunking | Fixed-size vs Semantic Chunking | Overlap Chunking 문제점 | Parent Document Retriever |
| [05-29](quizzes/2026-05-29.md) | 벡터 인덱스 | HNSW 계층구조 & greedy 탐색 | M과 ef_construction Trade-off | HNSW vs IVF-PQ |
| [06-01](quizzes/2026-06-01.md) | Retrieval 모델 | Bi-encoder vs Cross-encoder | Cross-encoder 학습 & Hard Negative | Hard Negative Mining |
| [06-12](quizzes/2026-06-12.md) | Dense Retriever 학습 | 대조학습 목표 | In-batch Negatives | Hard Negative (ANCE) |

### 추론 최적화

| 날짜 | 주제 | Q1 | Q2 | Q3 |
|---|---|---|---|---|
| [06-02](quizzes/2026-06-02.md) | KV Cache · 디코딩 | KV Cache와 반복 계산 제거 | KV Cache 메모리 수식 & MQA/GQA | Speculative Decoding |
| [06-03](quizzes/2026-06-03.md) | 양자화 | PTQ vs QAT · INT8 | LLM.int8() · SmoothQuant | GPTQ |
| [06-08](quizzes/2026-06-08.md) | Speculative Decoding | 동작 원리 | Draft·Target 수락 조건 | 속도 향상·한계 |
| [06-09](quizzes/2026-06-09.md) | Flash Attention | 메모리 병목(HBM/SRAM) | Tiling · online softmax | Recomputation |
| [06-11](quizzes/2026-06-11.md) | 디코딩 전략 | Temperature | Top-k vs Top-p | 적응적 샘플링·조합 |
| [06-18](quizzes/2026-06-18.md) | PagedAttention | KV cache 단편화 | 페이징 비유 | 이점·메모리 공유 |
| [06-23](quizzes/2026-06-23.md) | GQA/MQA/MHA | KV cache & MQA | MQA 저하·GQA 절충 | 현대 LLM 표준 |
| [06-24](quizzes/2026-06-24.md) | Beam Search | Greedy vs Beam | 빔 너비 B 한계 | Length norm·최적성 |

### PEFT

| 날짜 | 주제 | Q1 | Q2 | Q3 |
|---|---|---|---|---|
| [06-04](quizzes/2026-06-04.md) | LoRA | 저랭크 분해 원리 | ΔW low-rank & rank r | Merge · QLoRA |

### Context Engineering

| 날짜 | 주제 | Q1 | Q2 | Q3 |
|---|---|---|---|---|
| [07-16](quizzes/2026-07-16.md) | Chain-of-Thought | CoT 효과 원리 | Zero-shot vs Few-shot | Self-Consistency |

---

## 날짜별 로그

| 날짜 | 주제 카테고리 | 핵심 키워드 |
|---|---|---|
| [2026-05-06](quizzes/2026-05-06.md) | ML 기초 · 최적화 | L1/L2, Adam |
| [2026-05-07](quizzes/2026-05-07.md) | ML 기초 · 최적화 | Adam, AdamW, Bias Correction |
| [2026-05-08](quizzes/2026-05-08.md) | ML 기초 · 최적화 | GELU, SwiGLU, LayerNorm |
| [2026-05-09](quizzes/2026-05-09.md) | ML 기초 · 최적화 | Dropout, Inverted Dropout |
| [2026-05-10](quizzes/2026-05-10.md) | ML 기초 · 최적화 | Batch Normalization, ICS |
| [2026-05-11](quizzes/2026-05-11.md) | ML 기초 · 최적화 | Cross-Entropy, KL-Divergence |
| [2026-05-12](quizzes/2026-05-12.md) | ML 기초 · 최적화 | Backpropagation, Vanishing Gradient |
| [2026-05-13](quizzes/2026-05-13.md) | NLP 기초 | Word2Vec, CBOW, Skip-gram |
| [2026-05-14](quizzes/2026-05-14.md) | NLP 기초 | BPE, Byte-level BPE |
| [2026-05-15](quizzes/2026-05-15.md) | NLP 기초 | Perplexity, n-gram, Smoothing |
| [2026-05-18](quizzes/2026-05-18.md) | Transformer | Attention, MHA, 복잡도 |
| [2026-05-19](quizzes/2026-05-19.md) | Transformer | Positional Encoding, RoPE |
| [2026-05-20](quizzes/2026-05-20.md) | Transformer | FFN, SwiGLU, Pre/Post-Norm |
| [2026-05-21](quizzes/2026-05-21.md) | Post-training | SFT, Prompt Masking |
| [2026-05-22](quizzes/2026-05-22.md) | Post-training | RLHF, DPO, GRPO, PPO |
| [2026-05-25](quizzes/2026-05-25.md) | Post-training | DPO 심화, β, π_ref |
| [2026-05-26](quizzes/2026-05-26.md) | Post-training | GRPO, Group Advantage, Rule-based Reward |
| [2026-05-27](quizzes/2026-05-27.md) | RAG · 검색 | BM25, Dense Retrieval, Reranker |
| [2026-05-28](quizzes/2026-05-28.md) | RAG · 검색 | Chunking, Parent Document |
| [2026-05-29](quizzes/2026-05-29.md) | RAG · 검색 | HNSW, IVF-PQ, ANN |
| [2026-06-01](quizzes/2026-06-01.md) | RAG · 검색 | Bi-encoder, Cross-encoder, Hard Negative |
| [2026-06-02](quizzes/2026-06-02.md) | 추론 최적화 | KV Cache, GQA, Speculative Decoding |
| [2026-06-03](quizzes/2026-06-03.md) | 추론 최적화 | 양자화, PTQ/QAT, GPTQ, SmoothQuant |
| [2026-06-04](quizzes/2026-06-04.md) | PEFT | LoRA, 저랭크 분해, QLoRA |
| [2026-06-08](quizzes/2026-06-08.md) | 추론 최적화 | Speculative Decoding, Draft/Target |
| [2026-06-09](quizzes/2026-06-09.md) | 추론 최적화 | Flash Attention, Tiling, Recomputation |
| [2026-06-11](quizzes/2026-06-11.md) | 추론 최적화 | Temperature, Top-k, Top-p |
| [2026-06-12](quizzes/2026-06-12.md) | RAG · 검색 | Dense Retriever, InfoNCE, ANCE |
| [2026-06-16](quizzes/2026-06-16.md) | Transformer | RoPE, 회전 행렬, 상대 위치 |
| [2026-06-18](quizzes/2026-06-18.md) | 추론 최적화 | PagedAttention, KV cache, vLLM |
| [2026-06-23](quizzes/2026-06-23.md) | 추론 최적화 | GQA, MQA, MHA, KV cache |
| [2026-06-24](quizzes/2026-06-24.md) | 추론 최적화 | Beam Search, Length Norm |
| [2026-06-25](quizzes/2026-06-25.md) | ML 기초 · 최적화 | Warmup, Cosine Annealing |
| [2026-06-26](quizzes/2026-06-26.md) | ML 기초 · 최적화 | Bias-Variance, 과적합/과소적합 |
| [2026-06-30](quizzes/2026-06-30.md) | Transformer | Pre-norm vs Post-norm |
| [2026-07-02](quizzes/2026-07-02.md) | ML 기초 · 최적화 | 가중치 초기화, Xavier, He |
| [2026-07-16](quizzes/2026-07-16.md) | Context Engineering | Chain-of-Thought, Self-Consistency |

---

## 기여 환영

답변에 오류가 있거나 더 나은 설명이 있다면 언제든지 기여를 환영합니다!

**기여 방법**

1. 이 저장소를 Fork합니다.
2. 수정할 날짜의 파일(`quizzes/YYYY-MM-DD.md`)을 편집합니다.
3. Pull Request를 생성합니다. PR 제목은 `fix: YYYY-MM-DD Q{N} - 수정 내용 한 줄 요약` 형식을 따라주세요.

**기여 유형 예시**

- 오답 또는 불완전한 풀이 수정
- 수식 오류 정정
- 더 직관적인 설명이나 예시 추가
- 오타 수정

---

## 구조

```
daily_quiz/
├── README.md
└── quizzes/
    ├── img/            # 퀴즈에 사용된 이미지
    └── YYYY-MM-DD.md   # 날짜별 퀴즈 파일 (Q1~Q3 + 풀이)
```
