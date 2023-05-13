# -Python---Snake-Game-Y-lan-Oyunu-

   Python dilinde yılan oyunu programı yazıldı.
   
Yılan oyunu Python dilinin turtle modülü, time ve random kütüphaneleri ile yazıldı. Time 
kütüphanesi oyunun hızını ayarlamak için, random kütüphanesi ile elmanın konumu oyun sırasında 
rastgele değişmesi için kullanıldı. Turtle; Python’ da çizim yapılmasını sağlayan modüldür. Bu 
modüldeki çizim komutları ile ilk olarak 600x600 boyutunda yeşil renginde oyun alanı olan bir 
pencere oluşturuldu ve yılanın çizimine geçildi. Yılanın kafası siyah renk ve kare şeklinde, kuyruğu da
beyaz renk olarak tasarlandı. Kafa her oyun başladığında (0,100) noktasında bulunacak şekilde 
ayarlandı. Program çalıştırıldığında çok hızlı çalıştığı için yalnızca yeşil renkli oyun ekranı görünüyor,
yılan kafası görünmüyordu. Oyunun çalışmasını yavaşlatmak için time kütüphanesi kullanıldı ve 
programın çalışma hızı yılan hızına eşitlenerek problem çözüldü. Tekrar çalıştırıldığında yılan kafası
göz ile takip edilebildi. Yiyecek, elma baz alınarak kırmızı bir yuvarlak cisim olarak tasarlandı.
Yılanın hareketleri yukarı, aşağı, sağa ve sola olacak ve her harekette yılanın konumu 20 piksel 
değişecek şekilde komutta belirlendi. Yeme işlemi bir döngü ile kontrol edildi. Kafanın her 
hareketinde konum 20 piksel değişecek şekilde ayarlandı. Elma ile kafanın arasındaki mesafe 20 
pikselden az ise bir çarpışma var yani yeme işlemi olmakta, bu durumda elmanın konumu random 
kütüphanesi ile oyun penceresi içerisinde rastgele bir şekilde değişecek şekilde ayarlandı. Oyun için 
skor değeri her elma yendiğinde 10 artacak şekilde belirlendi. Yılan her elma yediğinde hızı artırıldı ve 
kuyruğu kafa boyutu kadar uzatıldı. Yılan kenarlara çarptığında oyun bitip tekrar başlayacak ve skor 
değeri sıfırlanacak şekilde yazılarak program tamamlandı ve başarıyla çalıştı.
