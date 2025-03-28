# **Heart Disease Prediction using Machine Learning**  

## **Overview**  
Proyek ini bertujuan untuk membangun model Machine Learning guna memprediksi kemungkinan seseorang menderita penyakit jantung berdasarkan berbagai faktor kesehatan. Proses ini mencakup pemilihan model yang relevan, evaluasi performa, serta interpretasi hasil menggunakan teknik validasi dan tuning model.  

## **Workflow**  
1. **Problem Understanding & Model Selection**  
   - Menentukan model Machine Learning yang sesuai berdasarkan karakteristik dataset dan pemahaman masalah.  
   - Menyajikan alasan pemilihan model berdasarkan keunggulan dan kesesuaiannya dengan dataset.  

2. **Model Implementation & Evaluation**  
   - Melakukan eksekusi kode untuk model yang telah dipilih sesuai dengan urutan yang benar.  
   - Menerapkan cross-validation untuk mengevaluasi performa awal model.  
   - Menganalisis hasil cross-validation dan memberikan interpretasi.  

3. **Model Improvement & Tuning**  
   - Menerapkan learning curves untuk memahami bias-variance tradeoff serta membuat visualisasi hasilnya.  
   - Melakukan hyperparameter tuning untuk meningkatkan akurasi model.  

4. **Final Model Evaluation & Interpretation**  
   - Mengukur performa model dengan evaluation metrics yang sesuai (seperti Accuracy, Precision, Recall, F1-score, atau AUC-ROC).  
   - Memberikan interpretasi hasil evaluasi serta alasan pemilihan metrik yang digunakan.  

## **Tools & Libraries**  
- Python (NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn)  
- Jupyter Notebook / Google Colab  
- Dataset: https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset/data

## **Results & Insights**  
Berdasarkan uji coba pemodelan menggunakan model Decision Tree Classifier dan Random Forest Classifier dalam mengolah dataset heart, maka didapatkan bahwa model yang paling baik adalah **Random Forest Classifier dengan nilai akurasi sebesar 82%**, sedangkan Decision Tree adalah 79%. 

## **How to Use**  
1. Clone repository:  
   ```bash
   git clone https://github.com/your-username/heart-disease-ml.git
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Jalankan notebook untuk eksplorasi dan training model.  
