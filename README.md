<h1 align="center">📐 Delik Dizilimi Hesaplama</h1>
<p align="center">
Manuel Freze & CNC için Dairesel (PCD) Delik Hesaplama Aracı
</p>

<p align="center">
  <a href="https://kyrstr1.github.io/DelikDizilimiHesaplama/">
    🔗 Canlı Demo
  </a>
</p>

---

## 🚀 Proje Hakkında

**Delik Dizilimi Hesaplama**, dairesel parçalar üzerindeki eşit aralıklı deliklerin konumlarını hesaplamak için geliştirilmiş basit ve hızlı bir web aracıdır.

Manuel freze kullanırken ya da CNC programı yazarken delik açılarını tek tek hesaplamak yerine, değerleri girerek anında sonucu alabilirsin.

---

## 🎯 Özellikler

- ✔️ PCD (Pitch Circle Diameter) hesaplama mantığı
- ✔️ Girilen delik sayısına göre eşit açı dağılımı
- ✔️ Anlık hesaplama
- ✔️ Basit ve sanayi odaklı arayüz
- ✔️ Tamamen statik (sunucu gerektirmez)

---

## 🛠️ Nasıl Kullanılır?

1. Parça çapını gir
2. PCD (Delik merkezleri çapı) değerini gir
3. Delik sayısını gir
4. **HESAPLA** butonuna bas
5. Açısal dağılım ve sonuçları görüntüle

---

## 🧮 Hesaplama Mantığı

Delikler eşit aralıklı olacak şekilde şu formül kullanılır:

```text
360° / Delik Sayısı
```

Örneğin:

- 6 delik → 360 / 6 = 60°
- 8 delik → 360 / 8 = 45°
- 12 delik → 360 / 12 = 30°

Bu açı değerleri referans alınarak işleme yapılır.

---

## 💻 Kullanılan Teknolojiler

- HTML5
- CSS3
- Vanilla JavaScript

Tamamen front-end tabanlıdır.  
Herhangi bir backend veya veritabanı kullanılmamıştır.

---

## 🌐 Canlı Kullanım

Projeyi buradan deneyebilirsin:

👉 https://kyrstr1.github.io/DelikDizilimiHesaplama/

---

## 📦 Kurulum

Projeyi lokal çalıştırmak için:

```bash
git clone https://github.com/kyrstr1/DelikDizilimiHesaplama.git
cd DelikDizilimiHesaplama
```

Ardından `index.html` dosyasını tarayıcıda açman yeterlidir.

---

## 📌 Hedef

Sanayi ortamında:
- Manuel hesap hatalarını azaltmak
- Zamandan tasarruf sağlamak

---

## 📜 Lisans

Bu proje açık kaynaklıdır.

---

<p align="center">
Geliştiren: Kayra
</p>
