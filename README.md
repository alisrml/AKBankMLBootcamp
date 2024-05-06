# AKBankMLBootcamp

## Özet
Bu projede qualitywğne-red veri seti kullanılarak sınıflandırma yöntemiyle makine öğrenmesi modeli oluşturulmuştur. Bu işlemin gerçekleştirilmesi sırasında bir dizi işlem gerekleştirilmiştir. Gerçekleştirilen işlemler sırasıyla şu şekildedir.

### Exploratory Data Analysis (EDA)
bu adımda veri seti import edildikten sonra, veri setinde bulunan 12 farklı özellik gözlenmiştir. Bu veriler toplamda 1599 farklı örneğe aittir ve tamamı non-null değerlerden oluşmaktadır. Ayrıca veriler arasındaki korelasyon ilişkisine ait tablo oluşturulmuş ve hangi özelliklerin kaliteye etki ettiği konusunda fikir edinilmiştir.

### Veri Ön İşleme
bu adımda kalite özelliği ile korelasyon değeri 0.1 den fazla olan özellikler, relevant_features olarak ayrıştırılmış ve eğitimde kullanılacak olan özellikler seçilmiştir. Ayrıca quality özelliğinin 6 farklı değerden 3 farklı değere gruplandırılmıştır.

### Model Seçimi
Decision tree modelinde farklı derinlik ve kriter ile elde edilen sonucların dogruluk degerleri kıyaslanarak en iyi sonuc veren model belirlenmiştir.

### Model Değerlendirme
Eğitim sonucunda elde edilen modelin precision recall f1score gibi değerleri hesaplatılıp yazıdırılmıştır.
