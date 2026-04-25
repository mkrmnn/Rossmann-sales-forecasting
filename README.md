 Rossmann Mağaza Satış Tahmini (Zaman Serisi Analizi)
Bu proje, Rossmann mağazalar zincirinin geçmiş satış verilerini analiz ederek gelecek dönem satışlarını tahmin etmek amacıyla geliştirilmiştir. XGBoost algoritması kullanılarak, zaman serisi verileri üzerinde feature engineering ve tahminleme yapılmıştır.

 Proje Özeti
Stok yönetimi ve operasyonel verimliliği artırmak için doğru talep tahmini hayati önem taşır. Bu çalışma kapsamında:

Veri Hazırlığı (EDA): Zaman serisindeki trend, mevsimsellik ve gürültü analizleri yapıldı. Eksik veriler iş mantığına uygun şekilde dolduruldu.

Özellik Mühendisliği: Geçmiş satış değerleri (Lags), hareketli ortalamalar (Rolling Windows) ve takvim bazlı değişkenler üretilerek modelin tahmin yeteneği artırıldı.

Modelleme: Regresyon problemlerinde yüksek performans gösteren XGBoost algoritması tercih edildi.

Tahmin: Model, test verisi üzerinde başarıyla doğrulanmış ve gelecekteki 7 günlük satış projeksiyonu oluşturulmuştur.

 Kullanılan Yöntemler:
 
Python (Pandas, NumPy)

Matplotlib & Seaborn (Görselleştirme)

XGBoost (Makine Öğrenmesi)

Scikit-learn (Metrik Analizi)

 Model Performansı:
 
Test seti üzerinde yapılan ölçümlerde aşağıdaki sonuçlar elde edilmiştir:

RMSE: Modelin ortalama hata payı hesaplandı.

MAE: Tahminlerin mutlak hata ortalaması.

MAPE: Satışlar üzerindeki yüzdelik hata oranı.

Not: Model, mağaza kapanış günlerini (Pazar günleri ve tatiller) otomatik olarak saptayabilmekte ve tahminleri bu kısıtlara göre optimize etmektedir.
