Penguin PCA: Boyut İndirgeme ve Görselleştirme
Bu proje, ünlü Palmer Penguins veri setini kullanarak, karmaşık verileri nasıl daha basit ve anlaşılır hale getirebileceğimizi gösteren bir Temel Bileşen Analizi (PCA) uygulamasıdır.

Projenin Amacı
Veri setindeki penguenlere ait 4 farklı fiziksel özelliği (gaga uzunluğu, gaga derinliği, yüzgeç uzunluğu ve vücut kütlesi) alıp,
bu 4 boyutlu veriyi anlamlı bir şekilde 2 boyuta (2 ana bileşen) indirgemek ve penguenlerin cinsiyetlerine göre nasıl kümelendiğini görselleştirmektir.

Adım Adım Yapılanlar
Veri Temizliği: Analizi bozabilecek eksik değerler (NaN) temizlendi.

Standartlaştırma: Farklı birimlerdeki (gram, mm) veriler, PCA'in doğru çalışması için standart bir ölçeğe getirildi.

PCA Uygulaması: 4 adet özellik, verideki varyansı (bilgiyi) en iyi temsil eden 2 temel bileşene dönüştürüldü.

Görselleştirme: Elde edilen bileşenler kullanılarak erkek ve dişi penguenler arasındaki farklar bir dağılım grafiği (scatter plot) üzerinde gösterildi.

Sonuç
Bu çalışma sayesinde, çok boyutlu verilerin grafik üzerinde nasıl temsil edilebileceğini ve PCA'in veri setindeki "bilgiyi" ne kadar oranda koruyabildiğini (explained_variance_ratio_) gözlemlemiş olduk.

![penguen_grafiği]("gender_graph.png")
