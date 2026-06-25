# 🌊 Sele 30 Saniye 🏃‍♂️💨

**Sele 30 Saniye**, sel ve tsunami gibi su kaynaklı afetlerde doğru hazırlık yapmayı ve kriz anında kaynakları bilinçli kullanmayı öğreten Unity tabanlı bir afet farkındalık oyunudur.

Oyuncu önce afet alarmı sonrası ev içinde sınırlı sürede acil durum çantası hazırlar, ardından çatıya çıkarak topladığı eşyalarla yardım ekipleri gelene kadar hayatta kalmaya çalışır.

## Geliştirici 👨‍💻

- **İsim:** Arif Emre Selvi
- **Akademik Durum:** 2. sınıf YBS (Yönetim Bilişim Sistemleri) Öğrencisi

## Oyunun Öğretmeyi Amaçladığı Hedefler 🧠

- Afet alarmı sonrası hangi eşyaların gerçekten önemli olduğunu öğretmek
- Su, yemek, sağlık ve iletişim araçlarının önemini göstermek
- Panik yerine planlı hareket etmeyi teşvik etmek
- Yardım beklerken kaynak yönetimi yapmayı öğretmek
- 112 Acil Çağrı ve güvenli alana geçiş bilinci kazandırmak

## Oynanış Özeti 🎯

Oyun iki ana bölümden oluşur.

İlk bölümde oyuncu evin içinde 30 saniye boyunca acil durum eşyaları toplar. Çanta kapasitesi sınırlıdır, bu yüzden her eşya doğru seçim olmayabilir.

İkinci bölümde oyuncu çatıya ulaştıktan ilk bölümde topladığı eşyaları verimli kullanarak 7 gün hayatta kalmaya çalışır. Su, yemek, sağlık, korku ve can sıkıntısı gibi değerler oyuncunun kararlarına göre değişir.

## Kontroller ⌨️

| Tuş / Etkileşim | İşlev |
| --- | --- |
| `WASD` / `Yön Tuşları` | Karakteri hareket ettirme |
| `E` | Yakındaki eşyayı alma veya etkileşim kurma |
| `SPACE` | Intro cutscene sahnesini atlama |
| `ESC` | Oyunu duraklatma / pause menüsünü açma |
| `Mouse Sol Tık` | Menü ve karar butonlarını kullanma |

## Oyun Mekanikleri

### 1. Evde Hazırlık Bölümü 🏠

Oyuncu afet alarmından sonra ev içinde dolaşır ve 30 saniye içinde çantasına eşya toplamaya çalışır.

Bu bölümde:

- Top-down 3D kamera kullanılır
- Karakter ev içinde serbestçe hareket eder
- Eşyalar yalnızca yakına gelince isimleriyle görünür
- Eşyalar `E` tuşu ile toplanır
- Envanter kapasitesi 8 slot ile sınırlıdır
- Süre bitince karakter kontrolü kapanır
- Karakter otomatik olarak merdivene / güvenli geçiş noktasına yönelir

### 2. Envanter ve Eşya Seçimi 🎒

Oyunda toplam 15 farklı eşya bulunur.

Doğru acil durum eşyaları:

- El feneri
- Düdük
- Konserve
- İlk yardım kiti
- Su
- Radyo
- Powerbank
- Battaniye
- Yedek kıyafet
- Islak mendil

Daha düşük öncelikli veya riskli eşyalar:

- Oyun konsolu
- Şarj aleti
- Kalın roman
- Oyuncak ayı
- Dambil

Bazı eşyalar ilk bakışta gereksiz gibi görünse de ikinci bölümde moral veya özel olaylar açısından farklı etkiler oluşturabilir. Ancak temel afet hazırlığında su, yemek, sağlık ve iletişim eşyaları çok daha kritiktir.

### 3. Hazırlık Puanı 💯

İlk bölümden sonra oyuncunun topladığı eşyalar değerlendirilir.

Puanlama sistemi:

| Durum | Puan |
| --- | --- |
| Doğru eşya | `+10` |
| Gereksiz / zayıf eşya | `-5` |
| Boş slot | `-3` |
| Su + İlk Yardım + Radyo set bonusu | `+15` |

Hazırlık sonucu üç seviyeden biriyle gösterilir:

- **Çok iyi hazırlık**
- **Orta hazırlık**
- **Riskli hazırlık**

Bu ekranda her eşya için kısa bir geri bildirim verilir. Oyuncu neyi doğru seçtiğini ve hangi seçimin neden zayıf olduğunu öğrenir.

### 4. Çatıda Hayatta Kalma Bölümü ⛺

İkinci bölümde oyuncu artık çatıdadır. Amaç, yardım ekipleri gelene kadar hayatta kalmaktır.

Oyuncu her gün kararlar alır:

- Su iç
- Yemek ye
- Hiçbir şey yapma
- Günü bitir

Takip edilen değerler:

| Değer | Anlamı |
| --- | --- |
| Açlık | Yükselirse risk artar |
| Susuzluk | Çok yükselirse hayatta kalmak zorlaşır |
| Can sıkıntısı | Moral durumunu etkiler |
| Korku | Panik ve kriz riskini artırır |
| Sağlık | Sıfıra düşerse oyun kaybedilir |

### 5. Stok Sistemi 🥣

Toplanan bazı eşyalar ikinci bölümde doğrudan kaynağa dönüşür.

- `Su` eşyası çatı bölümünde su stoğu sağlar
- `Konserve` eşyası yemek stoğu sağlar
- Her su veya konserve, birden fazla kullanım hakkı verir

Oyuncu kaynakları erken tüketirse sonraki günlerde zor durumda kalabilir.

### 6. Rastgele Olaylar ♾️

Çatı bölümünde gün içinde veya gün sonunda rastgele olaylar yaşanabilir.

Bu olaylar oyuncunun topladığı eşyalara göre değişebilir. Örneğin:

- Radyo varsa haber alma şansı artar
- Powerbank bazı elektronik eşyalara anlam kazandırır
- Battaniye soğuk gecelerde işe yarayabilir
- İlk yardım kiti sağlık olaylarında avantaj sağlar
- Düdük yardım ekiplerine yerini belli etme açısından önemlidir

Rastgele olaylar şu değerleri etkileyebilir:

- Açlık
- Susuzluk
- Can sıkıntısı
- Korku
- Sağlık
- Su stoğu
- Yemek stoğu

### 7. Kazanma ve Kaybetme 🏆

Oyuncu seçilen zorluk seviyesine göre belirli gün sayısı boyunca dayanmalıdır.

Kaybetme koşulları:

- Sağlığın `0` veya altına düşmesi
- Açlık veya susuzluğun kritik seviyeye ulaşması
- Korku ve can sıkıntısının birlikte çok yükselmesi

Kazanma koşulları:
- Yedinci güne kadar dayanabilmek
- Değelerlerin 100'den aşağıda olması

Kazanma durumunda oyuncu yardım ekipleri gelene kadar dayanmış olur.

## Teknik Bilgiler 🛠️

| Alan | Bilgi |
| --- | --- |
| Oyun Motoru | Unity |
| Unity Sürümü | `6000.3.10f1` |
| Render Pipeline | Universal Render Pipeline |
| Platform | PC / Desktop |
| Proje Türü | 3D looting + karar tabanlı survival |
| Dil | C# |
| UI | Unity UI + TextMeshPro |

## Kurulum 🚀

Oyunu çalıştırmak için:

1. Sağ taraftaki **Releases** bölümünden ya da direkt **[BURAYA TIKLAYARAK](https://github.com/arifemreselvi/sele-30-saniye/releases/download/v1.0.0/sele30saniye.rar)** oyunun en güncel halini bilgisayarına indir.
2. İndirdiğin rar dosyasını klasöre çıkar ve içindeki `Catiya 30 Saniye.exe` dosyasına çift tıklayarak maceraya başla

## Rehber Video 📺

Oyunun nasıl oynandığını, temel mekaniklerini ve afet hazırlığı sürecini görmek için rehber videoyu izleyebilirsin.

[![Çatıya 30 Saniye Rehber Video](https://img.youtube.com/vi/lbQClqRPzTA/maxresdefault.jpg)](https://youtu.be/lbQClqRPzTA)

Videoyu izlemek için görsele veya [buraya tıkla](https://youtu.be/lbQClqRPzTA).
