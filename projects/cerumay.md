# Cerumay City & Social: Yeni Nesil Dijital Topluluk Platformu

**Cerumay City**, kullanıcıların dijital bir şehir metaforu içinde sosyalleştiği, içerik ürettiği ve topluluklar kurduğu bir sosyal ağ projesidir. Habbo Hotel gibi oyun tabanlı görseller yerine; Instagram, Telegram ve Discord'un modern arayüz dinamiklerini birleştiren, **arayüz odaklı** bir yaşam simülasyonudur.

---

## 1. Temel Konsept ve Vizyon
Platform, "Herkesin bir evi olduğu dijital bir şehir" mottosuyla yola çıkar. Kullanıcılar kendilerini piksel karakterlerle değil, özelleştirilebilir modern **Profiller** ile tanıtır. Amaç, sosyal statü, içerik paylaşımı ve gerçek zamanlı iletişimi şehir hayatı kurgusuyla birleştirmektir.

---

## 2. Kullanıcı Yolculuğu (User Journey)

### 2.1. Başlangıç: Evsizlik (The Nomad State)
Şehre yeni katılan her kullanıcı "Evsiz" statüsündedir. Platformda kalıcı bir yer edinmek ve sosyal statü kazanmak için ilk hedefi bir daire sahibi olmaktır.

### 2.2. Yerleşim Süreci
* **Talep:** Kullanıcı, beğendiği bir binadan "Daire Talep Formu" oluşturur. Daireler başlangıçta **ücretsizdir**.
* **Onay:** Bina sahibi (Yönetici), kullanıcının profilini inceler ve talebi onaylarsa kullanıcı daireye yerleşir.
* **Sahiplik:** Kullanıcı artık o dairenin sahibidir ve şehrin resmi bir vatandaşı olur.

---

## 3. Yapısal Hiyerarşi

Sistem üç ana katmandan oluşur: **Şehir > Bina > Daire**.

### 3.1. Binalar (The Buildings)
Binalar, sosyal kümeleri temsil eder.
* **Kapasite:** Her bina sabit **20 Daireden** oluşur.
* **İnşaat Kuralı:** İlk bina herhangi bir şart aranmaksızın ücretsiz oluşturulabilir.
* **Büyüme Kuralı:** İkinci bir bina inşa etmek isteyen kullanıcının, ilk binasındaki doluluk oranının **%75 (15 daire)** seviyesine ulaşmış olması gerekir.
* **Bina Duvarı (Panosu):** Bina sakinlerinin görebildiği, akış (feed) mantığında çalışan ortak bir iletişim panosudur. Bina içi etkinlikler (toplantı, parti vb.) buradan duyurulur.

### 3.2. Daireler (Apartments)
Daire, kullanıcının özel alanıdır. İki tür kapasite ayrımı vardır:
1.  **Yerleşik Kapasite (Residents):** Bir dairede (aile veya ev arkadaşı konseptiyle) **en fazla 5 kullanıcı** yaşayabilir. Bu kişiler arasında hiyerarşik roller (Anne, Baba, Çocuk, Yönetici vb.) atanabilir.
2.  **Misafir Kapasitesi (Guests):** Dairenin seviyesine ve genişliğine göre, anlık olarak sohbete katılabilecek dış kullanıcı sayısıdır. (Örn: Başlangıç seviyesi 10 kişi, Lüks daire 100 kişi).

**Daire İçi Özellikler:**
* **Akış Duvarı (Main Feed):** Instagram tarzı, daire sakinlerinin içerik paylaştığı alan.
* **Hediye Duvarı (Asset Wall):** Ziyaretçilerin bıraktığı hediyelerin sergilendiği alan. Her hediyenin bir **Cerium Puan** karşılığı vardır ve dairenin piyasa değerini artırır.
* **Ekonomi:** Geliştirilen ve değeri artan daireler, **Cerium** para birimi karşılığında başka kullanıcılara satılabilir.

---

## 4. İletişim ve Sosyalleşme (Chatting & Social)

İletişim altyapısı "Mekan Bazlı" ve "Koltuk (Seat)" sistemiyle çalışır.

### 4.1. Chatting Mantığı
* **Koltuk Sistemi:** Bulunulan ortamın (Daire, Bina Toplantı Odası, Topluluk Alanı) kapasitesi kadar "Koltuk" vardır.
* **Hibrit İletişim:** Kullanıcılar **Yazılı (Text)** veya **Sesli (Voice)** koltuklara oturabilir.
* **Zaman Aşımı (Timeout):** Odada aktif bir akış (ses veya yazı) yoksa, sistem kaynaklarını korumak ve sunucu yükünü azaltmak için "Chatting" modu otomatik olarak kapanır.

### 4.2. Topluluklar (Communities)
Şehir yapısından bağımsız olarak; ilgi alanlarına (Müzik, Teknoloji, Sanat) göre **Topluluklar** kurulabilir. Bu alanlar, binalardan bağımsız sosyalleşme merkezleridir.

---

## 5. Ekonomi ve Oyunlaştırma (Gamification)

Kullanıcının şehirdeki her eylemi bir puana dönüşür ve statüsünü belirler.

* **Cerium Değeri:** Sistemin ana para birimi/puanıdır.
* **Hediye Sistemi:** Misafirler, gittikleri dairelere dijital hediyeler bırakabilir. Bu hediyeler dairenin değerini yükseltir.
* **Aktivite Puanları:**
    * Toplantılara katılmak.
    * Diğer daireleri ziyaret etmek.
    * Topluluk kurmak veya yönetmek.
* **Ticaret:** Yüksek puana ve popülariteye sahip daireler, kullanıcılar arasında el değiştirebilir (Satış).
