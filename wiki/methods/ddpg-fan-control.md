# DDPG 智慧風扇控制方法
- 採用 Deep Deterministic Policy Gradient（Actor-Critic 四網路 + 經驗回放）輸出連續風扇 PWM 工作週期（見 [[Chiou2022]]）。
- 精簡冗餘統計特徵、加入最高溫移動平均與上限溫差（Case 6），並依過熱、過熱升溫、非過熱與特定目標溫度區間（90～95°C）設計分段獎勵函數。
