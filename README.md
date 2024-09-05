
# Kapalı Çarşı Altın Fiyatları API

## Türkçe

**Kapalı Çarşı Altın Fiyatları API**, güncel altın fiyatları, döviz kurları ve çeşitli metallerin alış/satış fiyatlarını JSON formatında sunan bir API'dir.

##### 🔗 Canlı Demo (https://kapali-carsi-altin-api.vercel.app)

### API Kullanımı

- **Base URL**: `https://kapalicarsi.apiluna.org`
- API'yi kullanarak canlı altın fiyatları, döviz kurları ve diğer piyasa verilerini çekebilirsiniz.

#### Örnek GET İsteği:

```bash
GET https://kapalicarsi.apiluna.org/
```

#### Örnek API Yanıtı:

```json
[
  {
    "code": "ALTIN",
    "alis": "2794.380",
    "satis": "2813.320",
    "dusuk": 2805.07,
    "yuksek": 2810.75,
    "kapanis": 2787.7,
    "tarih": "06-09-2024 01:41:31"
  },
  {
    "code": "CEYREK_YENI",
    "alis": 4527,
    "satis": 4602,
    "dusuk": 4588,
    "yuksek": 4598,
    "kapanis": 4516,
    "tarih": "06-09-2024 01:41:31"
  }
]
```

### API Yanıt Açıklaması:

- **code**: Altın türü veya döviz kodu (örn: "ALTIN", "CEYREK_YENI").
- **alis**: Alış fiyatı.
- **satis**: Satış fiyatı.
- **dusuk**: Gün içi en düşük fiyat.
- **yuksek**: Gün içi en yüksek fiyat.
- **kapanis**: Kapanış fiyatı.
- **tarih**: Fiyat verisinin güncellenme tarihi ve saati.

### API Özellikleri

- **JSON Formatı**: Tüm yanıtlar JSON formatındadır.
- **Gerçek Zamanlı Güncellemeler**: Veriler her dakika güncellenir.
- **Çeşitli Varlıklar**: Altın, döviz, değerli metaller ve diğer piyasa verileri yer alır.

### API Sınırları ve Kısıtlamalar

- **Saniye Başına İstek (RPS)**: API'ye her saniye en fazla 1 istek yapılmalıdır.
- **Kapsam**: Bu API yalnızca bilgi amaçlıdır ve yatırım tavsiyesi değildir. Yatırım kararlarınızı verirken profesyonel destek almanız önerilir.

---

## English

**Kapalı Çarşı Gold Prices API** provides real-time gold prices, exchange rates, and metal buy/sell rates in JSON format.

##### 🔗 Live Demo (https://kapali-carsi-altin-api.vercel.app)

### API Usage

- **Base URL**: `https://kapalicarsi.apiluna.org`
- You can use this API to retrieve live gold prices, exchange rates, and other market data.

#### Example GET Request:

```bash
GET https://kapalicarsi.apiluna.org/
```

#### Example API Response:

```json
[
  {
    "code": "ALTIN",
    "alis": "2794.380",
    "satis": "2813.320",
    "dusuk": 2805.07,
    "yuksek": 2810.75,
    "kapanis": 2787.7,
    "tarih": "06-09-2024 01:41:31"
  },
  {
    "code": "CEYREK_YENI",
    "alis": 4527,
    "satis": 4602,
    "dusuk": 4588,
    "yuksek": 4598,
    "kapanis": 4516,
    "tarih": "06-09-2024 01:41:31"
  }
]
```

### API Response Explanation:

- **code**: Type of gold or exchange code (e.g., "ALTIN", "CEYREK_YENI").
- **alis**: Buy price.
- **satis**: Sell price.
- **dusuk**: Lowest price of the day.
- **yuksek**: Highest price of the day.
- **kapanis**: Closing price.
- **tarih**: Date and time of the price update.

### API Features

- **JSON Format**: All responses are in JSON format.
- **Real-Time Updates**: Data is updated every minute.
- **Various Assets**: Provides prices for gold, exchange rates, precious metals, and more.

### API Limits and Restrictions

- **Requests per Second (RPS)**: Limit requests to 1 request per second.
- **Scope**: This API is for informational purposes only and does not provide investment advice. It is recommended to consult with professionals when making investment decisions.
