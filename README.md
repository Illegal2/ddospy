# JOKER.PY - JTH (Just Testing HTTP)

**JTH**, HTTP üzerinden yük testi yapmak için geliştirilmiş, tamamen **eğitim ve araştırma** amaçlı bir Python scriptidir. Gerçek saldırılar için kullanılması yasaktır!

---

## Özellikler

- Rastgele User-Agent ve Referer üretimi
- Saldırı süresi seçimi (1–7 gün)
- Gerçek zamanlı istek sayacı
- Renkli ve menülü terminal arayüzü
- Termux & Linux destekli

---

## Termux Kurulumu (Android)

1. **Termux İndir**: [F-Droid](https://f-droid.org/packages/com.termux/)
2. Uygulamayı aç ve şu komutları sırayla gir:

```bash
pkg update -y && pkg upgrade -y
pkg install git python -y
pip install colorama
git clone https://github.com/Illegal2/joker.py.git
cd joker.py
python ddos.py
