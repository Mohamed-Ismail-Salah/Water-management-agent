# Water-management-agent
# 🔬 Water Quality Models Benchmark

Below is a unified comparison table for all models, with placeholders for  
**ROC curves** and **Confusion Matrices** (upload your images inside the `images/` folder).

---

## 📊 Benchmark Summary Table

| Model | Accuracy | Macro Precision | Macro Recall | Macro F1 | Support | ROC Curve | Confusion Matrix |
|-------|----------|------------------|--------------|----------|----------|-----------|------------------|
| **CNN–CRNN–M5T** | 0.8446 | 0.6670 | 0.7922 | 0.7119 | 18,164 | ![ROC](<img width="613" height="547" alt="14166b77-f66b-49dc-8be3-0f724e55d189" src="https://github.com/user-attachments/assets/b75c3953-827b-4f48-888e-5ef0575df2fc" />
) | ![CM](<img width="1175" height="490" alt="5be63de1-eda5-417b-adf7-925670e1cc7f" src="https://github.com/user-attachments/assets/11e6a803-f033-4544-9478-7f3be761fcb8" />
) |
| **DNN Model** | 0.95 | 0.93 | 0.95 | 0.93 | 544,935 | ![ROC](images/dnn_roc.png) | ![CM](images/dnn_cm.png) |
| **DPSGT** | 0.9962 | 0.99 | 0.97 | 0.98 | 408,688 | ![ROC](images/dpsgt_roc.png) | ![CM](images/dpsgt_cm.png) |
| **LWQformer** | 0.98397 | 0.94 | 0.94 | 0.94 | 544,935 | ![ROC](images/lwqformer_roc.png) | ![CM](images/lwqformer_cm.png) |
| **SA_LSTM_WITH_LOADEST** | 0.98 | 0.97 | 0.98 | 0.98 | 326,961 | ![ROC](images/sa_lstm_roc.png) | ![CM](images/sa_lstm_cm.png) |
| **SBiLSTM** | 0.99517 | 0.98 | 0.97 | 0.98 | 408,688 | ![ROC](images/sbilstm_roc.png) | ![CM](images/sbilstm_cm.png) |
| **VBAED** | ~1.00 | 0.98 | 0.98 | 0.98 | 544,935 | ![ROC](images/vbaed_roc.png) | ![CM](images/vbaed_cm.png) |

---

 

