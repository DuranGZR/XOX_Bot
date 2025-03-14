# 🤖 XOX Bot - Yapay Zekâ Destekli Tic-Tac-Toe (XOX) Oyunu

Bu proje, Python programlama dili kullanılarak geliştirilen **yapay zekâ destekli bir XOX (Tic-Tac-Toe) botudur**. Bot, **Takviye Öğrenmesi (Reinforcement Learning) ve Q-Öğrenme** algoritması kullanılarak eğitilmiş ve stratejik hamleler yapabilecek şekilde tasarlanmıştır.

---

## 🎯 Proje Amacı

Bu proje aşağıdaki amaçlarla geliştirilmiştir:

- **Takviye Öğrenmesi (Reinforcement Learning)** algoritmalarını kullanarak öğrenebilen bir oyun botu oluşturmak.
- **Q-Öğrenme (Q-Learning) algoritmasını uygulayarak** optimal hamleleri öğrenmesini sağlamak.
- **Yapay zekâ ile oyun geliştirme alanında pratik bir örnek sunmak.**
- **Eğitim verisini analiz ederek, stratejik kararlar alabilen bir model oluşturmak.**

---

## 🗂️ Proje Yapısı

Bu projede aşağıdaki ana bileşenler yer almaktadır:

- **`main.py`** – Oyunun ana çalıştırma dosyasıdır. Kullanıcı, bu dosya aracılığıyla bot ile oyun oynayabilir.
- **`qlearning.py`** – Q-Öğrenme algoritmasının implementasyonunu içerir. Botun öğrenme sürecini yönetir.
- **`train_bot.py`** – Botun belirli sayıda oyun oynayarak kendisini eğitmesini sağlayan eğitim modülüdür.

---

## 🔍 Q-Öğrenme Algoritması

Q-Öğrenme, **model tabanlı olmayan (model-free) bir takviye öğrenmesi algoritmasıdır**. Bu projede, botun her oyun durumuna karşılık optimal hamleyi öğrenmesini sağlamak amacıyla uygulanmıştır. Bot, oynadığı her oyunda ödüller ve cezalar alarak kararlarını geliştirir.

### Algoritma Adımları:
1. **Durum (State) Tanımlama** – Oyun tahtasındaki mevcut durumu değerlendirir.
2. **Eylem (Action) Seçimi** – Keşif (Exploration) veya kullanılmış deneyimlere dayalı olarak en iyi hamleyi belirler.
3. **Ödüllendirme (Rewarding)** – Yapılan hamlenin sonucuna göre ödül veya ceza alır.
4. **Q-Değeri Güncelleme** – Öğrenme süreci boyunca Q-tablosu güncellenir ve botun hamle stratejisi geliştirilir.

---

## 🚀 Kullanım Kılavuzu

Projeyi çalıştırmak için aşağıdaki adımları takip edebilirsiniz:

### 1️⃣ Gerekli Bağımlılıkları Kurun

Öncelikle, Python'un ihtiyacı olan bağımlılıkları yükleyin:
```bash
pip install numpy
```

### 2️⃣ Botu Eğitin

Botun daha iyi hamleler yapabilmesi için öncelikle **eğitim sürecini çalıştırmanız gerekmektedir**:
```bash
python train_bot.py
```

### 3️⃣ Oyunu Başlatın

Botun öğrendiği stratejileri test etmek için oyunu başlatabilirsiniz:
```bash
python main.py
```

---

## 🔧 Kullanılan Teknolojiler ve Kütüphaneler

Projede aşağıdaki Python kütüphaneleri kullanılmıştır:

- **`numpy`** – Sayısal hesaplamalar ve matris işlemleri için kullanılır.

---

## 📚 Kaynaklar ve Referanslar

- **Q-Öğrenme Algoritması Üzerine Bir Kaynak**: [Q-Learning ve Takviye Öğrenmesi](https://www.youtube.com/watch?v=Qy2B4Xvpf-U)
- **Tic-Tac-Toe AI Kullanımı**: [Ayrıntılı Makale](https://towardsdatascience.com/reinforcement-learning-and-tic-tac-toe-cd0da481a1e5)

---

## 🤝 Katkıda Bulunma

Eğer projeye katkıda bulunmak isterseniz:
1. **Fork** yapın (projeyi kopyalayın).
2. Geliştirmelerinizi ekleyin.
3. **Pull Request (PR)** oluşturarak projeye katkıda bulunun.

Geri bildirimleriniz ve önerileriniz için **issue açabilirsiniz**. 🌟

