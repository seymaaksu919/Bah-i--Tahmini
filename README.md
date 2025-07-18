<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
</head>
<body>

  <h1>Bahşiş Tahmin Modeli</h1>

  <p>
    Bu proje, bir restoranda müşterilerin hesap tutarına göre verdikleri bahşiş miktarını tahmin eden doğrusal regresyon modeli içermektedir. Seaborn "tips" veri seti kullanılarak, müşteri hesap tutarları ve verdikleri bahşişler arasında bir ilişki kurulmuştur. Model, Scikit-Learn kütüphanesi kullanılarak eğitilmiş ve test edilmiştir.
  </p>

  <h2>Kullanılan Teknolojiler</h2>
  <ul>
    <li>Python</li>
    <li>NumPy, Pandas</li>
    <li>Scikit-Learn (Linear Regression, Train-Test Split, MSE)</li>
    <li>Seaborn, Matplotlib</li>
  </ul>

  <h2>Proje Açıklaması</h2>
  <ol>
    <li>Veri seti Seaborn üzerinden yüklenir.</li>
    <li>Gerekli öznitelikler seçilir ve kullanılmayacak sütunlar kaldırılır.</li>
    <li>Bağımsız değişken (total_bill) ve bağımlı değişken (tip) vektör haline getirilerek modele uygun hale getirilir.</li>
    <li>Veri eğitim ve test kümelerine bölünerek doğrusal regresyon modeli eğitilir.</li>
    <li>Modelin başarısı Mean Squared Error (MSE) metriği ile değerlendirilir.</li>
    <li>26.5 TL hesap ödeyen bir kadının tahmini bahşiş miktarı ayrıca hesaplanarak analiz edilmiştir.</li>
    <li>Sonuçlar matplotlib ile grafik olarak görselleştirilmiştir.</li>
  </ol>

</body>
</html>
