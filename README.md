# 🌟 **GitHub - 🔑 MyProject - Git Kullanımı Rehberi**

Bu rehber, Git ile proje yönetiminde temel ve ileri düzey adımları takip edebilmeniz için hazırlanmıştır. 👨‍💻  
Adım adım kılavuzlar ve açıklamalarla her seviyeden kullanıcı için uygundur.

---

## 🎯 **1. Git Kurulumu ve Başlangıç**

> **Git'i Sisteminizde Kontrol Edin**  
🌈 Başlangıç için Git'in sisteminize yüklü olup olmadığını kontrol edin:

```bash
git --version
```

📥 **Eğer Git yüklü değilse**: [Resmi Git Web Sitesi](https://git-scm.com/) üzerinden indirin.

---

## 🌐 **2. Yeni Bir Git Deposu Oluşturma**

> **Git Deposu Başlatma**  
✨ Projenizi bir Git deposuna dönüştürmek için:
```bash
git init
```
Bu komut, projenizin kök dizininde bir `.git` klasörü oluşturur.

---

## 🔗 **3. Uzak Depo Bağlantısı**

> **Uzak Depo Ekleme**  
🌟 Uzak bir depoya bağlanmak için:
```bash
git remote add origin https://github.com/kullanıcı_adı/MyProject.git
```

> **Bağlantıyı Kontrol Etme**  
✅ Bağlantılarınızı doğrulamak için:
```bash
git remote -v
```

---

## 📂 **4. Değişikliklerin Takibi**

### 📝 **Dosyaları Takibe Alma**
```bash
git add dosya_adi
```
✨ **Örnek**:
```bash
git add index.html
```

📦 **Tüm dosyalar için**:
```bash
git add .
```

---

### 🔒 **Değişiklikleri Kaydetme (Commit)**
```bash
git commit -m "İlk commit"
```
🖋 **İpucu**: Açıklama kısmını kısa ve net tutun.

---

## 🚀 **5. Uzak Depoya Gönderme**

> **İlk Push**  
Depodaki değişiklikleri uzak depoya gönderin:
```bash
git push -u origin main
```
📌 Ana dal (`main` veya `master`) adını kontrol edin.

---

## 🔄 **6. Güncellemeleri Çekme ve Birleştirme**

> **Güncellemeleri Çekme**  
Uzak depodaki son değişiklikleri alın:
```bash
git pull origin main
```

---

## 🌳 **7. Dal (Branch) Yönetimi**

### 🌱 **Yeni Bir Dal Oluşturma**
```bash
git branch yeni_dal
```

### 🌍 **Dala Geçiş Yapma**
```bash
git checkout yeni_dal
```

### 📤 **Yeni Dalı Yükleme**
```bash
git push -u origin yeni_dal
```

### 🔗 **Bir Dalı Birleştirme**
```bash
git checkout main
git merge yeni_dal
```

---

## 🔍 **8. Geçmişi İnceleme**

### 📜 **Commit Geçmişini Görüntüleme**
```bash
git log
```

### 🧾 **Daha Kısa Görünüm**
```bash
git log --oneline
```

---

## 🛠 **9. Hataları Geri Alma**

### 🔄 **Son Commit'i Geri Almak**
```bash
git revert HEAD
```

### ✂️ **Takipten Çıkarmak**
```bash
git reset dosya_adi
```

---

## 🔥 **10. Sık Kullanılan Diğer Komutlar**

### 🛡 **Değişiklikleri Kontrol Etme**
```bash
git status
```

### 🔎 **Farklılıkları Görüntüleme**
```bash
git diff
```

### 📥 **Depoyu Klonlama**
```bash
git clone https://github.com/kullanıcı_adı/MyProject.git
```

---

## 🎩 **11. İleri Seviye: Stash Kullanımı**

### 💾 **Değişiklikleri Geçici Olarak Saklama**
```bash
git stash
```

### ♻️ **Stash'i Geri Yükleme**
```bash
git stash apply
```

---

### 🎉 **Mutlu Kodlamalar!**
Bu rehber sayesinde Git'i kolayca öğrenebilir ve projelerinizi verimli bir şekilde yönetebilirsiniz! 🖤✨
