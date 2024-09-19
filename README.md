💳 Kredi Kartı Dolandırıcılığı Tespiti
Bu proje, kredi kartı dolandırıcılığını tespit etmek amacıyla oluşturulmuş bir makine öğrenimi modeli içerir. Proje, denetimli öğrenme ve denetimsiz öğrenme yöntemlerini bir araya getirerek, dolandırıcılık olup olmadığını tespit etmeyi hedefler. Veriler, Kaggle üzerinden alınmıştır ve model çıktı olarak 0 (dolandırıcılık değil) veya 1 (dolandırıcılık) değerlerini üretir.

📊 Veri Seti
Bu projede kullanılan veri seti, Kaggle platformundan alınmıştır. Veri seti, kredi kartı işlemlerine ait anonimleştirilmiş özellikler ve bu işlemlerin dolandırıcılık olup olmadığına dair etiketlerden oluşmaktadır.

🔗 Kaggle'daki proje sayfası: https://www.kaggle.com/code/zeynepoozer/credit-card-fraud-detection

🎯 Hedef
Bu projenin temel amacı, dolandırıcılığı tespit etmek için çeşitli makine öğrenimi algoritmalarını karşılaştırmak ve en iyi performansı sağlayan modeli bulmaktır.

Denetimli Öğrenme (Supervised Learning) 👨‍🏫:

Kredi kartı işlemlerinin dolandırıcılık olup olmadığını gösteren etiketlerle eğitilmiş modeller kullanıldı.
Kullanılan algoritmalar: Logistic Regression, Decision Tree Classifier

Denetimsiz Öğrenme (Unsupervised Learning) 🤖:

Veriler üzerinde dolandırıcılık etiketleri olmadan, yalnızca işlemlerin normal mi yoksa anormal mi olduğunu tespit etmek için kullanıldı.
Kullanılan algoritma: MiniBatchKMeans

🛠️ Kullanılan Teknolojiler
Bu projede aşağıdaki Python kütüphaneleri kullanılmıştır:

Python 🐍              
Pandas 🐼 – Veri manipülasyonu ve analizi için.                                                                                                                                                                     NumPy 📊 – Sayısal işlemler ve dizi işlemleri için.         
Matplotlib 📉 – Veri görselleştirme için.          
Seaborn 📈 – İleri düzey veri görselleştirme için.          
Scikit-Learn 📘:                
sklearn.preprocessing – Veri ön işleme (normalizasyon, standardizasyon vb.)                      
sklearn.model_selection – Eğitim ve test veri setlerinin ayrılması, k-katlı çapraz doğrulama.                         
sklearn.metrics – Model performansını değerlendirmek için çeşitli metrikler.                    
sklearn.tree – Karar ağaçları oluşturmak için.               
sklearn.cluster – KMeans gibi denetimsiz öğrenme algoritmaları.            
sklearn.decomposition – PCA gibi boyut indirgeme yöntemleri.               

📈 Model Performans Karşılaştırmaları
Denetimli ve denetimsiz öğrenme yöntemlerinin performansını karşılaştırarak dolandırıcılık tespiti üzerine önemli bulgular elde edildi. Farklı modelleri şu metriklerle değerlendirildi:     

Accuracy: Doğru tespit edilen işlemlerin oranı.     
Precision: Dolandırıcılık olarak işaretlenen işlemlerin ne kadarının doğru olduğu.        
Recall: Tespit edilen dolandırıcılık vakalarının tüm dolandırıcılık vakalarına oranı.          
F1-Score: Precision ve Recall'un harmonik ortalaması.          

  

