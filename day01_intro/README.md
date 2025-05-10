# Day 01: Yocto'ya Giriş ve Ekosistem Tanıtımı

## 🎯 Hedefler
- Yocto nedir, ne işe yarar?
- OpenEmbedded, BitBake, Poky gibi bileşenlerin rolleri
- Yocto'nun diğer gömülü Linux sistemlerine (Buildroot vs.) göre avantajları
- Yocto ile BeagleBone Black gibi cihazlara neden özel imaj üretilir?

---

## 📌 1. Yocto Nedir?

Yocto Project, gömülü sistemler için özelleştirilmiş Linux dağıtımları oluşturmanı sağlayan açık kaynaklı bir projedir. Bir işletim sistemini sıfırdan, modüler ve sürdürülebilir bir şekilde inşa etmeye olanak tanır.

---

## 🔧 2. Yocto Ekosistemi Bileşenleri

| Bileşen       | Açıklama |
|---------------|----------|
| **BitBake**   | Yapı motorudur. `make` benzeri bir görev yürütücüdür. |
| **OpenEmbedded Core** | Temel tarif ve sınıf sistemini içerir. |
| **Poky**      | BitBake + OpenEmbedded Core + örnek katmanlar içeren referans dağıtımdır. |
| **Katman (Layer)** | Her bileşenin bir modül gibi ayrıldığı yapı. Uygulama, kernel, BSP katmanları olabilir. |
| **Tarif (Recipe)** | Paketlerin nasıl indirileceği, derleneceği, kurulacağı bilgisini içerir. |

---

## ⚖️ 3. Neden Yocto?

| Buildroot | Yocto |
|-----------|-------|
| Hızlıdır, basittir | Daha esnek ve ölçeklenebilirdir |
| Paket yönetimi zayıftır | RPM, DEB, IPK desteklidir |
| Daha az modülerdir | Katman mimarisi ile özelleştirilebilir |
| Genellikle daha az kontrol sunar | Yocto her bileşen üzerinde detaylı kontrol verir |

---

## 📦 4. BeagleBone Black İçin Yocto

BeagleBone Black (BBB), TI Sitara (AM335x) işlemcisi kullanan, yaygın bir ARM tabanlı geliştirici kartıdır. Yocto ile BBB için özel:
- Kernel derleyebilir,
- I/O sürücüleri ekleyebilir,
- Kendi servislerini çalıştırabilirsin.

---

## 📝 Bugünkü Görevler

1. GitHub deposuna bu `day01_intro/README.md` dosyasını yükle.
2. “Yocto Ekosistemi Diyagramı” gibi bir görsel (elle veya dijital çizim) eklemek istersen bu klasöre koyabilirsin.
3. [Yocto Project Resmi Sitesi](https://www.yoctoproject.org/) üzerinden dokümantasyon incele.

---

## 📚 Kaynaklar
- https://www.yoctoproject.org
- https://docs.yoctoproject.org
- https://wiki.yoctoproject.org/wiki/Newcomers

