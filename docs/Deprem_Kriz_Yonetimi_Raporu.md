
# Deprem Sonrası Kriz Yönetimi: IoT Tabanlı Kara Kutu Sistemi

## 1. Proje Özeti (sektördeki çözümlerden ayıran özellikler, problemi çözen hangi yöntemler var, bizim projemin farkı nedir)

### Amaç
Afet sonrası hasar gören yapıların hızlı tespiti ve kurtarma ekiplerinin etkin şekilde yönlendirilmesi için IoT tabanlı bir kara kutu sistemi geliştirmek. 
Bu sistem, aynı zamanda sel ve ısı algılama gibi afet senaryolarında da kullanılabilir.

### Sorun ve Çözüm Önerisi
Deprem sonrası kurtarma ekiplerinin yıkılan binaları tespit etme süreci uzun sürebilmektedir. IoT tabanlı kara kutu sistemi sayesinde, bu süreç minimuma indirilerek ekiplerin yoğunluğa göre bölgelere öncelik sırası vermesi sağlanacaktır.

### Nihai Faydalanıcılar
- **AFAD** ve yerel yönetimler.
- **Vatandaşlar**, mobil uygulama aracılığıyla afetle ilgili bilgilere erişebilecektir.
- **Kolluk kuvvetleri** ve **Meteoroloji Genel Müdürlüğü**, gelecekteki potansiyel verilerden faydalanabilir.

---

## 2. Proje Fikrinin Açıklanması

### 2.1. Çözüm Ürettiği Sorun / İhtiyaç

#### Problem
Deprem sonrası yıkılan binaların hızlı bir şekilde tespit edilememesi, kurtarma çalışmalarını geciktirmekte ve can kaybını artırmaktadır.

#### Çözüm
Binaların çatısına yerleştirilecek IoT kara kutu cihazları ile:
- **Deprem, ısı ve sel algılama** sensörleri sayesinde afet sonrası veriler toplanır.
- Gerçek zamanlı olarak AFAD ekiplerine iletilir.
- Bölgesel yoğunluk analizi yapılabilir.
(diğer projeyle kıyasla)

### 2.2. Yerlilik ve Özgünlük Tarafı
- **Özgünlük**: Birbirine bağlanabilen kutular sayesinde bölgeler arası bilgi aktarımı. Sensör entegrasyonu ile çoklu afet yönetimi.
- **Yerlilik**: Kutuların üretiminde mümkün olduğunca milli kaynaklar kullanılacaktır. Maliyet yüksek olursa alternatif çözümler değerlendirilecektir.

### 2.3. Hedef Kitle
- **AFAD ve Yerel Yönetimler**: Ana faydalanıcılar.
- **Vatandaşlar**: Mobil uygulama üzerinden bilgi ve uyarı alabilirler.
- **Kolluk Kuvvetleri ve Meteoroloji Genel Müdürlüğü**: Gelecekteki geliştirme aşamalarında potansiyel kullanıcılar.

---

## 3. Kullanılacak Yöntem

### IoT Sensör ve Cihaz Teknolojileri
- **Deprem Sensörleri**: Akselerometreler ile sarsıntı ölçümü.
- **Isı ve Sel Sensörleri**: Çoklu afet tespiti.
- **Bağlantı Teknolojileri**: Bluetooth, LoRaWAN, Wi-Fi, LTE gibi düşük maliyetli ve dayanıklı seçenekler.

### Enerji Kaynakları
- Güneş ve rüzgar enerjisi desteği.
- Acil durumlar için dahili şarj edilebilir bataryalar.

### Yazılım Altyapısı
- **Backend**: Django Rest Framework (Python).
- **Mobil Uygulama**: Flutter.
- **Veri Görselleştirme**: Grafana entegrasyonu.

### Pilot Uygulama
Prototip kutular, belirlenen bölgelerde test edilecek ve AFAD’dan geri bildirim alınacaktır.

---

## 4. Proje Takvimi

| **Aşama**               | **Başlangıç Tarihi** | **Bitiş Tarihi**  | **Açıklama**                           |
|-------------------------|---------------------|------------------|---------------------------------------|
| Planlama ve Araştırma   | Ocak 2025          | Şubat 2025       | Teknik gereksinimlerin belirlenmesi. |
| Prototip Üretimi        | Mart 2025          | Nisan 2025       | IoT kutularının üretilmesi.          |
| Yazılım Geliştirme      | Nisan 2025         | Haziran 2025     | Backend ve mobil uygulama.           |
| Pilot Uygulama          | Temmuz 2025        | Ağustos 2025     | Sahada testler ve iyileştirmeler.    |
| Nihai Sunum ve Teslim   | Eylül 2025         | Eylül 2025       | Hackathon’a uygun final sunumu.      |

---

## 5. Gelecekteki Gelişmiş Özellikler

- **Vatandaş Bildirimleri**: Mobil uygulama üzerinden afet bilgileri.
- **Sağlık Durumu Paylaşımı**: Kullanıcıların izinlerine göre sağlık verilerinin AFAD’a iletilmesi.(engelli bireylere ayrıcalık, kimlik kartları)
- **Veri Paylaşımı**: Çatı kutularının topladığı ısı ve rüzgar verilerinin Meteoroloji’ye aktarılması.

---

## 6. Kaynakça

1. **IoT Teknolojilerini Kullanan Afet Sonrası Yönetim Sistemi** - dergipark.org.tr
2. **Depremde Hasar Gören Binaların Uzaktan Algılama Yöntemleriyle Tespiti** - tufuab.org.tr
3. **Acil Durum ve Afet Yönetiminde Süreç Yaklaşımı ve Teknoloji** - dergipark.org.tr
4. **3B Nokta Bulutlarından Deprem Sonrası Hasarlı Binaların Tespiti** - tdmd.org.tr
5. **Deprem Sonrası Hasar Tespitinde Yeni Teknolojiler** - makinetamir.com
6. **Digital Twin Based Disaster Management System Proposal: DT-DMS** - arxiv.org
7. **A Survey on the Role of Wireless Sensor Networks and IoT in Disaster Management** - arxiv.org
8. **Depremler ile Sigortacılık Sektörünün Dijital Dönüşümü** - tsb.org.tr
9. **Afet Yönetimi için Coğrafi Tabanlı Deprem Ontolojisi** - dergipark.org.tr
