DataSet: https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients
30.000 Kişinin Verisi ile Yapılmıştır.

1.	📌 Veri Temizleme ve Ön İşleme (Data Preprocessing)
✅ Eksik veri doldurma (missing value imputation) işlemleri yapıldı.
✅ Kategorik değişkenleri one-hot encoding veya label encoding ile dönüştürdük.
✅ Bazı değişkenlerin ölçeklendirilmesi (standardization, min-max scaling) yapıldı.

2.	📊 Keşifsel Veri Analizi (EDA) ve Görselleştirme
✅ Korelasyon analizi yapıldı.
✅ Veri görselleştirmeleri için bazı kodlar yazıldı.

3.	⚙️ Özellik Mühendisliği (Feature Engineering & Feature Selection)
✅ Model için değişken seçimi yapıldı.

4.	🤖 Model Seçimi ve Eğitimi (Model Selection & Training)
✅ Lojistik Regresyon (Logistic Regression) modeli eğitildi.
✅ Modelin bağımsız değişkenlerle nasıl ilişkilendiğini inceledik.
5.	📉 Model Değerlendirme (Evaluation Metrics)
✅ Confusion Matrix, Accuracy, Precision, Recall hesaplandı.

6.	🔬 Model Doğrulama (Cross-Validation & Generalization)
✅ K-fold Cross Validation (k=10) uygulandı.
✅ Modelin genel doğruluğunu test ettik.
7.	🛠️ ShinyApp Entegrasyonu
✅ ShinyApp kodları yazıldı ve yayınlandı.

8.	🚀 ShinyApp Dashboard
9.	📢 Elde ettiğim bulguları daha anlaşılır hale getirmek için bir ShinyApp dashboard’u geliştirdim.
🔗 ShinyApp Uygulamasını Buradan İnceleyebilirsiniz:

👉 https://berman954.shinyapps.io/CreditRisk/
################
Modelin Başarısı: Modelinizin doğruluğunu ve nasıl test ettiğinizi açıklayın. Örneğin: "Bu model, doğruluk oranı %81.18 olan ve doğruluğu test edilmiş bir lojistik regresyon modelidir. Ödeyemeyen müşterileri doğru bir şekilde tahmin etmiştir.
  
Korelasyon ve Önemli Özellikler: Hangi özelliklerin model için daha önemli olduğunu ve bu özelliklerin kredi riskini nasıl etkilediğini açıklayın. Örneğin: "Modelde 'LIMIT_BAL' (kredi limit) ve 'PAY_0' (ödenmeyen önceki ödeme) gibi özellikler en önemli faktörlerdir.

Model Performans Göstergeleri: Precision, recall, specificity gibi metriklerin nasıl çalıştığını ve modelin doğru tahmin yapma oranlarını açıklayın. Örneğin: "Model, ödeyemeyen müşterileri %97.37 doğrulukla tespit etti ancak düşük bir 'specificity'ye sahipti, bu da 'negative class' tahminlerinde sınırlı başarıya işaret etmektedir.

📊 Model Performansı:
Modelin doğruluğu %81.18 olarak hesaplandı. Bu model, kredi borcu ödemeyenleri doğru bir şekilde tahmin etmiştir. Grafiklerde, modelin doğruluğu ve öngörüleri gösterilmektedir. (Buraya ROC curve veya Confusion Matrix ekleyebilirsiniz.)

🔎 Korelasyon Matrisinin Görselleştirilmesi:
Verideki anahtar özelliklerin korelasyonlarına odaklandım. 'LIMIT_BAL' (kredi limiti) ve 'PAY_0' (önceki ödeme durumu) gibi faktörler, ödememe riskini belirlemede kritik rol oynamaktadır.
📈 Özellik Önemliliği:
Modelin tahmininde en önemli faktörler 'LIMIT_BAL' ve 'PAY_0' olarak belirlendi. Bu özelliklerin yüksek etkisi, müşterilerin ödeme davranışlarını tahmin etmede ne kadar önemli olduğunu gösteriyor.

💼 Sonuçlar ve Yararlar:
Bu model, finansal kuruluşların kredi verme kararlarını daha doğru bir şekilde alabilmelerine yardımcı olabilir ve riski minimize eder. 

##############ENG########################


1. 📌 Data Cleaning and Preprocessing
✅ Missing value imputation was performed.  
✅ Categorical variables were transformed using one-hot encoding or label encoding.  
✅ Some variables were scaled (standardization, min-max scaling).  

2. 📊 Exploratory Data Analysis (EDA) and Visualization
✅ Correlation analysis was conducted.  
✅ Some visualization scripts were written.  

3. ⚙️Feature Engineering & Feature Selection 
✅ Feature selection for the model was completed.  

4. 🤖Model Selection and Training 
✅ A Logistic Regression model was trained.  
✅ The relationship between the model and independent variables was examined.  

5. 📉 Model Evaluation (Evaluation Metrics)
✅ Confusion Matrix, Accuracy, Precision, and Recall were calculated.  

6. 🔬Model Validation (Cross-Validation & Generalization)  
✅ K-fold Cross Validation (k=10) was applied.  
✅ The model’s overall accuracy was tested.  

7. 🛠️ShinyApp Integration 
✅ ShinyApp scripts were written and published.  

8. 🚀ShinyApp Dashboard: Analyze Credit Risk Interactively!

9. 📢 To make my findings more understandable, I developed a ShinyApp dashboard.  
🔗 Check out the ShinyApp here:  

👉 (https://berman954.shinyapps.io/CreditRisk/)  

