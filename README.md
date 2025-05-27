# DDoS Saldırılarının Tespitinde Makine Öğrenmesi ve Derin Öğrenme Algoritmalarının Karşılaştırılması

Bu çalışmada Canadian Institute for Cybersecurity (CIC) tarafından sunulan CIC-IDS2017 veri seti kullanılmıştır. Bu veri seti, ağ trafiği analizi ve siber güvenlik araştırmaları için yaygın olarak kullanılmaktadır. Kayıtlar saldırı türü, kaynak ve hedef IP adresleri, paket boyutu ve zaman damgası gibi çeşitli özelliklere sahiptir. Veri seti, gerçek ağ trafiğinden türetilmiştir ve Brute Force FTP, Brute Force SSH, DoS, Heartbleed, Web Attack, Infiltrasyon, Botnet ve DDoS saldırı türlerini içerir. Bu veri seti, toplamda 225745 satır ve 79 sütundan oluşmaktadır ve hem BENIGN (zararsız) hem de DDoS (saldırı) olmak üzere iki farklı etiketi içermektedir. 

Çalışma kapsamında makine öğrenmesi algoritmaları olan Destek Vektör Makinesi (SVM), K-En Yakın Komşu (KNN), DT (DT), Çok Katmanlı Algılayıcılar (MLP) ve XGBoost’un yanı sıra derin öğrenme teknikleri olan Evrişimsel Sinir Ağı (CNN) ve Yinelemeli Sinir Ağı (RNN) gibi modeller kullanılarak DDoS saldırılarının tespiti yapılmıştır.

Aşağıda .ipynb dosyalarının içerikleri verilmiştir.
- PCA_ile_ML_modelleri.ipynb: Veri setinin boyutunu azaltmak amacıyla Başlıca Bileşenler Analizi (PCA) tekniği uygulanmıştır. Daha sonra makine öğrenmesi modelleri kullanılarak tespit yapılmıştır.
- ML_modelleri.ipynb: PCA tekniği kullanılmadan makine öğrenmesi modelleri ile tespit yapılmıştır.
- DL_modelleri.ipynb: Derin öğrenme modelleri kullanılarak tespit yapılmıştır.

