## 📊 Table 1: Model Performance Metrics
| Model       | Accuracy | Precision (Macro) | Precision (Weighted) | Recall (Macro) | Recall (Weighted) | F1-Score (Weighted) |
|-------------|----------|-------------------|-----------------------|----------------|--------------------|----------------------|
| ModernBERT  | 0.8702   | 0.8271            | 0.8687                | 0.8242         | 0.8702             | 0.8693               |
| RoBERTa     | 0.8671   | 0.8191            | 0.8657                | 0.8217         | 0.8671             | 0.8659               |
| DeBERTa     | 0.8576   | 0.8145            | 0.8572                | 0.8077         | 0.8576             | 0.8573               |
| BERT        | 0.8548   | 0.8036            | 0.8530                | 0.8038         | 0.8548             | 0.8535               |
| DistilBERT  | 0.8490   | 0.7978            | 0.8465                | 0.7952         | 0.8490             | 0.8473               |
| GPT-2       | 0.8460   | 0.7970            | 0.8426                | 0.7917         | 0.8460             | 0.8433               |
| CNN         | 0.7398   | 0.6992            | 0.7245                | 0.5602         | 0.7398             | 0.7101               |
| LSTM        | 0.6452   | 0.2151            | 0.4162                | 0.3333         | 0.6452             | 0.5060               |

## 📈 Table 2: Comparison of Model Performance on Previous Balanced Datasets
| Model      | Accuracy | Recall  | F1-Score | Improvement (Accuracy / Recall / F1) |
|------------|----------|---------|----------|--------------------------------------|
| BERT       | 0.7784   | 0.7822  | 0.7776   | +9.81% ↑ / +9.28% ↑ / +9.76% ↑        |
| RoBERTa    | 0.8237   | 0.8252  | 0.8240   | +5.27% ↑ / +5.08% ↑ / +5.09% ↑        |
| DistilBERT | 0.7955   | 0.7983  | 0.7950   | +6.73% ↑ / +6.35% ↑ / +6.58% ↑        |

## ⏱ Table 3: Training and Inference Efficiency of Different Models
| Model       | # Params (M) | Train Time per Epoch (s) | Best Epoch | Inference Time per Sample (s) |
|-------------|--------------|---------------------------|------------|-------------------------------|
| CNN         | 4.06         | 5.52                      | 6          | 0.0001                        |
| LSTM        | 4.83         | 9.25                      | 1          | 0.0002                        |
| DistilBERT  | 66.96        | 37.49                     | 1          | 0.0007                        |
| BERT        | 109.48       | 67.20                     | 1          | 0.0012                        |
| GPT-2       | 124.44       | 74.19                     | 1          | 0.0014                        |
| RoBERTa     | 124.65       | 106.76                    | 1          | 0.0019                        |
| DeBERTa     | 139.19       | 303.40                    | 2          | 0.0036                        |
| ModernBERT  | 149.61       | 264.94                    | 1          | 0.0049                        |

## Figure 1. Confusion Matrices for ModernBERT, RoBERTa, and DeBERTa.
![image](https://github.com/user-attachments/assets/88f51c58-626b-47a5-951b-4fa6ba156199)

## Figure 2. NLP Model Performance Radar Chart.
![image](https://github.com/user-attachments/assets/e8261a34-cfb5-4dc7-9064-b66d453fd76a)

