# Yocto Eğitim Projesi – BeagleBone Black

Bu depo, BeagleBone Black üzerinde Yocto Project kullanarak gömülü Linux sistemleri geliştirmeyi öğrenmek amacıyla hazırlanmıştır. Eğitim 10 günlük bir plana göre yapılandırılmıştır ve her gün bir modül içermektedir.

## 🧠 Eğitim Amacı
- Yocto Project ekosistemine giriş yapmak
- BeagleBone Black için özel Linux imajı oluşturmak
- Kendi katmanımızı (meta-custom) oluşturarak özelleştirmeleri uygulamak
- Uygulama, servis ve kernel düzeyinde geliştirme yapmak

## 🧰 Kullanılan Donanım
- BeagleBone Black Rev. C
- microSD Kart (en az 8 GB önerilir)
- USB-UART kablosu veya mini USB
- Linux (Ubuntu 22.04 tavsiye edilir) yüklü bilgisayar

## ⚙️ Kullanılan Yazılım ve Sürüm
- Yocto Project: Kirkstone (LTS)
- BitBake
- OpenEmbedded-core
- meta-ti, meta-yocto, meta-openembedded

## 📅 Eğitim Planı

| Gün | Konu Başlığı |
|-----|----------------|
| 1   | Yocto'ya Giriş ve Ekosistem Tanıtımı |
| 2   | Kurulum ve Ortam Hazırlığı |
| 3   | İlk Derleme: core-image-minimal |
| 4   | Layer (Katman) Yapısı ve Yönetimi |
| 5   | Recipe (Tarif) Yazımı – Temeller |
| 6   | Paket Yönetimi ve Özelleştirme |
| 7   | Uygulama ve systemd servisi eklemek |
| 8   | Kernel Derleme ve Özelleştirme |
| 9   | Rootfs, Bootloader ve Donanım Özelleştirmeleri |
| 10  | Temizlik, Hata Ayıklama ve Devam Senaryoları |

## 📂 Günlük klasör yapısı
Her gün için ayrı bir klasör yer alacaktır:
