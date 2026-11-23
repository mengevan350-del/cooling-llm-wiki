# LLM Wiki 內容索引（Index）

## Overview & Reviews
- [[cooling-layers-comparison]] — 四層散熱鏈結（介面熱阻 → 伺服器機內風扇控制 → 機櫃旁通 → 機房氣流組織）比較與文獻回顧初稿。

## Sources (5 篇來源)
- [[Chiou2022]] — 邱致翰（2022），1U 氣冷伺服器暫態熱傳與旁通模型及 DDPG 智慧風扇控制碩士論文。
- [[Honeywell2024]] — Honeywell（2024），電子元件熱介面材料（TIM 1/1.5/2）與相變化材料（PCM）應用說明。
- [[Energies2020]] — Energies（2020），高密度機房熱通道封閉（HAC）下高架地板與硬地板送風 CFD 比較。
- [[AppliedEnergy2016]] — Applied Energy（2016），冷熱通道封閉下機櫃氣流旁通實驗量測與能耗影響模型。
- [[NYCU_SmallDC_CFD]] — 陽明交大碩士論文，《中小型資料中心流場熱管理之數值模擬》（冷熱通道、上下吹與擋板 CFD 分析）。

## Concepts
- [[thermal-impedance-and-tim]] — 接觸介面氣隙、熱流收縮與熱介面材料（TIM）熱阻抗概念。
- [[airflow-bypass]] — 伺服器散熱器流道旁通與機櫃通道旁通氣流機制。
- [[fan-oscillation-and-overcooling]] — 風扇轉速震盪對壽命的影響，以及過度吹冷造成的能耗浪費。

## Methods
- [[ddpg-fan-control]] — 深度確定性策略梯度（DDPG）狀態特徵選取與分段獎勵函數設計。
- [[cfd-and-1d-thermal-modeling]] — 1U 串並聯流道暫態熱傳迭代模型與機房三維 CFD 氣流組織模擬方法。

## Experiments
- [[1u-server-and-containment-results]] — 1U 伺服器 Config 1～3 實驗數據與機房通道封閉旁通/壓差實測結果彙整。
