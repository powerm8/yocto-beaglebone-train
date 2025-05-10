# Day 02: Kurulum ve Ortam Hazırlığı

## 🎯 Hedefler
- Ubuntu ortamında Yocto geliştirme ortamı kurmak
- BeagleBone Black için gerekli katmanları indirmek
- `build/` dizinini başlatmak
- `local.conf` ve `bblayers.conf` dosyalarını gözden geçirmek

---

## 🧰 1. Gerekli Paketlerin Kurulumu (Ubuntu 20.04 / 22.04)

```bash
sudo apt update
sudo apt install -y gawk wget git diffstat unzip texinfo gcc \
  build-essential chrpath socat cpio python3 python3-pip python3-pexpect \
  xz-utils debianutils iputils-ping libsdl1.2-dev xterm
