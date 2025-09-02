# 🏥 Pusula_Erdem_Baran

**İsim Soyisim:** ERDEM BARAN  
**Email:** erdembaran908@gmail.com

---

## 📄 Proje Hakkında

Bu proje, **fiziksel tıp ve rehabilitasyon** alanında toplanmış bir veri seti üzerinde çalışmaktadır.  
Amaç, veri setini **EDA (Exploratory Data Analysis)** ile analiz etmek ve **modellemeye hazır** hale getirmektir.  

- Gözlem Sayısı: 2235  
- Özellik Sayısı: 13  
- Hedef Değişken: `TedaviSuresi`  

> ⚠️ Bu projede model geliştirme yapılmamıştır; odak veri analizi ve ön işleme üzerindedir.

---

## 📊 Veri Seti Özellikleri

| Sütun Adı           | Açıklama                                    |
|--------------------|--------------------------------------------|
| HastaNo            | Anonim hasta ID                             |
| Yas                | Yaş                                         |
| Cinsiyet           | Cinsiyet                                    |
| KanGrubu           | Kan grubu                                   |
| Uyruk              | Uyruk                                       |
| KronikHastalik     | Kronik hastalıklar (virgülle ayrılmış)     |
| Bolum              | Bölüm/Klinik                                |
| Alerji             | Alerjiler (tekli veya virgülle ayrılmış)   |
| Tanilar            | Tanılar                                     |
| TedaviAdi          | Tedavi adı                                  |
| TedaviSuresi       | Tedavi süresi (seans sayısı)               |
| UygulamaYerleri    | Uygulama alanları                           |
| UygulamaSuresi     | Uygulama süresi                             |

---

## 🔎 Yapılan Çalışmalar

### 1️⃣ Exploratory Data Analysis (EDA)
- Veri yapısı ve değişken tipleri incelendi
- Eksik değerler tespit edildi ve özetlendi
- Sayısal ve kategorik değişkenlerin dağılımları görselleştirildi
- Korelasyon ve ilişkiler analiz edildi
- `TedaviSuresi` dağılım grafiği oluşturuldu

### 2️⃣ Veri Ön İşleme
- Eksik değerler uygun yöntemlerle dolduruldu (`median`, `most_frequent` vb.)
- Kategorik değişkenler **OneHotEncoder** ile dönüştürüldü
- Sayısal değişkenler için ölçeklendirme yapıldı
- Veri, modellemeye hazır hale getirildi:
  - `X_ready` → Özellikler (ön işlenmiş)
  - `y` → Hedef değişken (`TedaviSuresi`)

---

## 🛠️ Kullanılan Kütüphaneler

- `pandas`  
- `numpy`  
- `matplotlib`  
- `seaborn`  
- `scikit-learn`  

---

## 💻 Çalıştırma Talimatları

1. GitHub reposunu klonlayın:  
```bash
git clone https://github.com/erdembrn34/Pusula_Erdem_Baran.git
