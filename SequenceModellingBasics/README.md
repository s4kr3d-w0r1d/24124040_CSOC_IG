# SequenceModellingBasics 🚀

This project implements a complete **Binary Sentiment Classification** pipeline using sequence-based models (RNN / BiLSTM) on the Amazon Reviews dataset.

### Tasks Covered:

✅ Data Loading & Preprocessing  
✅ Text Cleaning & Tokenization  
✅ Padding & Sequence Preparation  
✅ GloVe Embeddings Integration  
✅ Model Building: Bidirectional LSTM  
✅ Evaluation: Accuracy, F1-score, Confusion Matrix  
✅ Analysis of False Positives & Negatives  
✅ Stretch Goal: Impact of Review Length  
✅ Bonus: Minimal Clue Challenge  

### Why BiLSTM?

BiLSTM captures both **past** and **future** context, which helps in understanding subtle tone, sarcasm, and ambiguous cues in reviews.

### Repository Structure:

- `01_Data_Preprocessing.ipynb` → Data cleaning, tokenization  
- `02_BiLSTM_Glove.ipynb` → Model building & training  
- `03_Minimal_Clue_Challenge_04_Stretch_Goals.ipynb` → Error analysis  
- `report/` → Final LaTeX report  

---

### Result Highlights:

- F1-Score: **~0.95**  
- Insights: Model performs well but struggles on highly sarcastic or very short ambiguous reviews.

---

**Note:** Large files (csv, GloVe, model weights) are gitignored.  
Glove embeddings used: `glove.6B.100d.txt`.

---

