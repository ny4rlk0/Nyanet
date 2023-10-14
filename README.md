# Nyanet
<br><a href="https://github.com/ny4rlk0/Nyanet/releases/download/GelistiriciSurumu/GelistiriciSurumu.zip">Nyanet İndir Yeni Sürüm / Download Nyanet New Version</a>
<br><a href="https://www.virustotal.com/gui/file/8e910b396e1a56a08bf8fd0050c4d42b2e3e3f6f5150b5b208aeda55fa70dd70/detection">Virustotal</a>
<br>
<br>Microsoft Edge yeni eklenen güvenlik ağı adlı vpn servisi yazılımın çalışmasını bozuyor. Edge kullanırken Gizlilik Arama ve Hizmetlerden kapatın.
<br>Türkiye'den, dünyadaki tüm sitelere sansürsüz girmenizi sağlayan yazılım.
<br>C# ve C++ ile yazılmıştır.
<br>DNS işinizi kendiniz halledemiyorsanız ilk çalıştırmanızda iki kutucuğuda işaretlemenizi ve Başlat'a basmanızı tavsiye ederim.
<br>~ny4rlk0
<br>Yenilikler: Yazılım kurcalanmaya karşı güvenceye alındı. Eksik dosyaları bu repodan yeniden indirme özelliği eklendi. Kendini koruma özelliği eklendi. Hata ayıklamaya karşı basit önlemler alındı. DoH eklerken ayarların çalışmamasına ve şifreli DNS hizmetinin açılmamasına sebep olan bir hata düzeltildi! (Bu hatayı düzeltmek için regedit ayarlamaları yapmak gerekti.) Bir terslik olmazsa daha fazla güncelleme almayacak.
<br>Yazılım beklentilerimde istediğim fonksiyonalite ve amaca ulaştı. Bir şeyler yolunda gitmediği sürece daha fazla güncelleme almayacaktır!
<br><a href="https://github.com/ny4rlk0/Nyanet/releases/download/GelistiriciSurumu/GelistiriciSurumu.zip">Nyanet İndir Yeni Sürüm / Download Nyanet New Version</a>
<br><br><img src="1.png">
## Gereksinimler (Bunlar yüklü olmadan bilgisayarınızda çalışmaz!)
<br>windowsdesktop-runtime-6.0.20-win-x64
<br>windowsdesktop-runtime-6.0.20-win-x86
<br><a href="https://github.com/ny4rlk0/Nyanet/releases/tag/Gereksinimler">Gereksinimleri indirmek için tıkla!</a>
<br><br><img src="2.png">
<br><img src="SS.png">
<br><a href="https://github.com/ny4rlk0/Nyanet/files/12543047/Nyanet.zip">Nyanet Eski Sürüm</a>
<br>DNS Sunucusu Ekle (+ butonu) kısmındaki alanların hepsinin dolu olması gerekmektedir. İlk açıldığında ne yazmanız gerektiğine dair örnek görünüyor zaten.
<br>Ekle'ye bastıktan sonra listeden eklediğiniz sunucunun adını seçin ve sırasıyla DNS ekle ve DNS aktifleştiri işaretleyin. 
<br>Artık sisteminize DNS eklemiş ve aktifleştirmiş bulunuyorsunuz. İsterseniz hazır Google ve Cloudflare DNS sunucularını da kullanabilirsiniz.
<br>Yine herhangi bir DNS sunucusunu seçtikten sonra sırasıyla DNS ekle ve DNS aktifleştiri işaretleyin.
<br>Yazılım içinde farklı modlar var ancak varsayılan yazanlarla sabit kalmanızı tavsiye ederim.
<br>İlk kullanımınızda DNS altındaki tüm tik işareti olanları bir kere işaretleyin. En alttaki Gereksinim olan Windows Desktop Runtime'ın belirli sürümlerini
<br>indirmesi internetinize bağlı biraz uzun sürebilir. Yaklaşık 104.4MB indirme yapacaktır ve otomatik yükleyecektir. Yükleme bitince ekranda gözükecektir.
<br>
<br>Bilinen Buglar: (+) butonu ile dns ekledikten sonra eklenen DNS sunucusu dışında başka bir sunucu seçip uygularsanız eklediğiniz sunucu listede görünmesine rağmen programı
<br>yeniden başlatana kadar o ayarları kullanamıyorsunuz. Kodlama kısmında Ekle kısmından aldığım değişkenleri yedek değişkenlerde tutmamam bu hataya sebep oldu.
<br>Bu hata programın akışını etkilemiyor. Şimdilik düzeltmeyle uğraşmayacağım. .d (Yeni sürümde bu sorun çözüldü!)
<br>
<br>Neler Yapıyor Merak Ediyorsanız Detayına İnelim Biraz:
<br>Program Açılıyor ve Eksik dosyam var mı? diye kontrol ediyor. (Bir kere)
<br>Herhangi bir hata ayıklama uygulaması var mı? diye kontrol ediyor varsa Nyanet'i bilgisayarınızdan siliyor. Çalışıyorsa kurcalamayın işte asdalkşdjawld.
<br>Yoksa içerdiği tüm dosyaların MD5 değerlerini kontrol ediyor. Bir dosya değiştirilmişse tüm programı githubdan yeniden indiriyor. (30 saniyede bir defa)
<br>Programın çalıştığı klasörde kendi dosyalarından başka bir dosya ya da klasör varmı diye kontrol ediyor. Varsa kurcalanmayı önlemek için kendisini SoftwareProtectionService adlı klasör oluşturup ona kopyalıyor ve not bırakıyor.
<br>Programı githubdan yeniden indirirken bu sayfadaki linkteki sürümü software.zip olarak indirip aynı klasörde Release adlı bir kasöre çıkartıyor.
<br>Yazılım indirme sırasında oluşan: nyaInternalCodes.bat=> Program kendisini yeniden indirdiğinde mevcut programı sonlandırıp siliyor. Güvenliği bilinen sürümünü olan indirilmiş programı açıyor. Zip dosyası ve release klasörünü silip kendinide siliyor.(Bana göre güvenliği bilinen. Kaynak kodu açık olmadığı için. lol)
<br>Başlat tuşu: Bu programa özel C++'da yazılmış DPI Sansürünü Aşan bir servisi seçili modda başlatıyor.
<br>Seçili DNS ayarlarını uygula: Yukarıda seçtiğiniz DNS ayarlarını regedit üzerinden bilgisayarınıza uyguluyor. (DNS Over Https'yi aktif değilse regedite müdehale edip group policy ayarlarını değiştirerek aktive ediyor.)
<br>Yenile: Regediti ağ adaptörleri için sorguluyor.
<br>0.03 Saniyede bir eğer başka işlem yapmıyorsa DNS sunucularını kontrol ediyor, eğer değişmişse ekrana yazıyor.
<br>Buradaki bilgilere bakarak Virustotalde hangi uyarının neden geldiğini anlayabilirsiniz.
