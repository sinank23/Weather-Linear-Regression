# WW2 Weather Data - Linear Regression Model

Bu proje, Kaggle üzerinde yer alan İkinci Dünya Savaşı dönemine ait hava durumu veri seti kullanılarak geliştirilmiş bir Makine Öğrenmesi (Basit Doğrusal Regresyon) çalışmasıdır.

## Proje Adımları
1. **Veri Temizliği:** Eksik ve bozuk (NaN, 'T', '#VALUE!') veriler tespit edilip temizlendi.
2. **Keşifsel Veri Analizi (EDA):** Korelasyon ısı haritası ve dağılım grafikleri ile değişkenler arası doğrusal ilişkiler incelendi.
3. **Modelleme:** `MinTemp` (Minimum Sıcaklık) bağımsız değişkeni kullanılarak `MaxTemp` (Maksimum Sıcaklık) tahmini için Scikit-Learn ile Linear Regression modeli eğitildi.
4. **Sonuç:** Model, eğitimde hiç görmediği %20'lik test verisi üzerinde **R² = 0.7543** ve **MSE = 17.20** başarı skoru elde etmiştir.

## Kullanılan Kütüphaneler
* Python (Pandas, NumPy)
* Scikit-Learn
* Matplotlib & Seaborn
