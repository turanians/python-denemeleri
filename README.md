🌌 3D Young's Double Slit Experiment Simulation
Bu proje, kuantum mekaniği ve dalga optiğinin en temel taşlarından biri olan Young Çift Yarık Deneyi'ni (Double Slit Experiment) üç boyutlu (3D) ortamda simüle eden bir yazılımdır. Geleneksel 2D gösterimlerin aksine, eğik perde fiziğini, dalga girişimlerini ve faz farklarını dinamik bir 3D uzayda görselleştirir.

🚀 Özellikler
Üç Boyutlu Görselleştirme: Dalga kaynakları, yarıklar ve gözlem perdesi arasındaki ilişkiyi 3D olarak inceleyin.

Eğik Perde Analizi: Perdenin açısına göre kırınım ve girişim desenlerindeki (interference patterns) bozulmaları ve değişimleri gözlemleyin.

Dinamik Parametreler: Dalga boyu, yarıklar arası mesafe, perde uzaklığı gibi kritik fiziksel değişkenleri gerçek zamanlı olarak manipüle edin.

Çoklu Platform Desteği:

Masaüstü analizi için Python (VPython / PyQt5) altyapısı.

Web tabanlı erişim için Three.js entegrasyonu.

🛠️ Kullanılan Teknolojiler
Proje, hem masaüstü hem de web platformlarında yüksek performanslı 3D render alabilmek için aşağıdaki teknolojilerle geliştirilmiştir:

Python 3.x

VPython / PyQt5 (Masaüstü 3D Grafik ve Arayüz)

Three.js / JavaScript (Web Tabanlı 3D Modelleme)

Web Sürümü (Three.js)
Herhangi bir kurulum yapmadan web sürümünü çalıştırmak için index.html dosyasını tarayıcınızda açmanız veya projeyi yerel bir sunucuda (örn: Live Server) başlatmanız yeterlidir.

🔬 Matematiksel Altyapı
Simülasyondaki girişim deseni hesaplamaları, ışığın dalga karakteristiğine ve yol farkına dayanan klasik dalga mekaniği formüllerine dayanır:

Yol Farkı: Yarıklar ile perde üzerindeki bir nokta arasındaki mesafe farkı.

Girişim Şartı:

Aydınlık Çizgiler (Maksimum): d * sin(teta) = m * lambda

Karanlık Çizgiler (Minimum): d * sin(teta) = (m + 1/2) * lambda

Eğik perde durumunda, perdenin dönme matrisi kullanılarak her bir pikselin dalga kaynaklarına olan gerçek 3D mesafesi dinamik olarak hesaplanır.



🤝 Katkıda Bulunma
Bu projeyi Fork edin

📄 Lisans
Bu proje MIT lisansı altında korunmaktadır.
