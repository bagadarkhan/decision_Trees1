# Iris Veri Seti ile Karar Ağacı Sınıflandırması

Bu proje, **Iris veri seti** kullanılarak `DecisionTreeClassifier` ile bir sınıflandırma modeli oluşturmayı, 
modeli değerlendirmeyi ve karar ağacını görselleştirmeyi amaçlamaktadır.

## İçerik
- Iris veri setini yükleme (`sklearn.datasets.load_iris`)
- Eğitim ve test veri setlerine ayırma (`train_test_split`)
- Karar ağacı modeli oluşturma ve eğitme (`DecisionTreeClassifier`)
- Model doğruluğunu ölçme (`accuracy_score`)
- Karışıklık matrisi (`confusion_matrix`)
- Karar ağacını görselleştirme (`plot_tree`)
- Özellik önem derecelerini hesaplama (`feature_importances_`)

## Kullanılan Kütüphaneler
- scikit-learn
- matplotlib

## Notlar
- `criterion` parametresi `"gini"` veya `"entropy"` olarak değiştirilebilir.
- `max_depth` parametresi ile ağacın derinliği kontrol edilebilir.
- Iris veri seti, makine öğrenmesinde giriş seviyesinde çok kullanılan klasik bir veri setidir.