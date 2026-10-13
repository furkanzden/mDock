<div align="center">

# 🏝️ mDock
### Windows İçin Dinamik Ada (Dynamic Island)

*Apple'ın ikonik Dynamic Island deneyimini, Windows masaüstünüze taşıyan ultra hafif ve akıllı widget.*

[![Platform](https://img.shields.io/badge/Platform-Windows%2010/11-0078D6?style=flat-square&logo=windows)]()
[![Size](https://img.shields.io/badge/Boyut-Sadece%2097%20KB-2ea44f?style=flat-square)]()
[![CPU](https://img.shields.io/badge/Boşta%20CPU-%250.1-brightgreen?style=flat-square)]()

</div>

---

## 🌟 Neden mDock?
mDock, masaüstünüzü şık bir Apple estetiğiyle buluştururken sistem kaynaklarınızı yormaz. Electron veya web tabanlı ağır widget'ların aksine, **yalnızca ~97 KB** boyutunda tek bir `.exe` dosyasından ibarettir. Kurulum gerektirmez, arka planda **%0.1 CPU** ile çalışır ve siz farkına bile varmadan masaüstü deneyiminizi iyileştirir.

---

## 🎬 Önizleme

<div align="center">
  <i>✨ Varsayılan görünüm, Hover (Üzerine Gelme) animasyonu ve Medya Kontrolleri</i>
  <br><br>
  <img width="390" height="154" alt="image" src="https://github.com/user-attachments/assets/f8f71544-16b8-4ca2-bba3-a54cac6fb9d1" />
  <br>
<img width="660" height="207" alt="image" src="https://github.com/user-attachments/assets/9c72d761-6de3-4e6a-82c6-4ab43c59f0c5" />

</div>

---

## 🎮 Nasıl Kullanılır? (Kontroller ve Etkileşimler)

mDock, klavye ve fare kombinasyonlarıyla zenginleştirilmiş, sezgisel bir kullanım sunar. İşte adayı kontrol etmenin yolları:

### 🖱️ Temel Etkileşimler
| Eylem | Sonuç |
| :--- | :--- |
| **Fare ile Üzerine Gel (Hover)** | Ada pürüzsüz bir fizik animasyonuyla genişler. Medya kontrolleri ve çalan uygulamanın logosu görünür. |
| **Fare Tekerleği (Scroll)** | Üzerindeyken kaydırarak **Sistem Sesini** ayarlayın (🔊 HUD menüsü açılır). |
| **SHIFT + Fare Tekerleği** | Kaydırarak **Monitör Parlaklığını** donanımsal olarak ayarlayın (☀️ HUD menüsü açılır). |
| **ALT + Sol Tık (Sürükle)** | Ada'yı ekranda istediğiniz yere serbestçe taşıyın. |

### ⌨️ Gelişmiş Kısayollar
| Kısayol | Sonuç |
| :--- | :--- |
| **CTRL + Hover** | **Hızlı Erişim (Quick Launch)** modunu açar. Favori uygulamalarınız adada sıralanır. |
| ↳ *Sol Tık* | Seçili uygulamayı başlatır. |
| ↳ *Sağ Tık* | Uygulamayı hızlı erişim listesinden kaldırır. |
| ↳ *+ Butonu* | Listeye yeni bir `.exe` veya kısayol (`.lnk`) ekler. |

  <br>
<img width="539" height="106" alt="image" src="https://github.com/user-attachments/assets/5d3e4759-9337-406e-bc68-4a7c7784bc87" />

---

## 🎵 Akıllı Medya Entegrasyonu
Ada'nın üzerine geldiğinizde, arka planda müzik veya video oynatan uygulamayı (Spotify, YouTube/Chrome, Apple Music, VLC vb.) anında algılar.
*   🎨 **Dinamik Logolar:** Şarkı hangi uygulamadan çalıyorsa o uygulamanın gerçek simgesi gösterilir.
*   🔄 **Akıllı Butonlar:** Şarkı çalıyorsa *Duraklat (||)*, durduysa *Oynat (▶)* butonu belirir.
*   🎛️ **Tam Kontrol:** Önceki, Oynat/Durdur ve Sonraki butonlarıyla medya kontrolü.

---

## ⚙️ Ayarlar ve Özelleştirme

Sistem tepsisindeki (sağ alt köşe) mDock simgesine **Sağ Tıklayarak** veya menüden **⚙️ Ayarlar...** seçeneği ile iOS tarzı şık, koyu temalı ayarlar paneline ulaşın.

İstemediğiniz özellikleri kapatarak widget'ı tamamen kendinize göre şekillendirebilirsiniz:
*   🔊 Ses ve Parlaklık HUD Göstergeleri
*   🎵 Şarkı Değişim Bildirimi & İlerleme Çubuğu
*   ⚡ Mini Donanım Monitörü (CPU & RAM kullanımı)
*   🌤️ Hava Durumu Göstergesi (Saatin yanında anlık sıcaklık)
*   🎮 Tam Ekran Oyun/Uygulama Algılama (Oyun oynarken otomatik gizleme)
*   🚀 Windows ile Otomatik Başlatma

*Not: Ayarlardan kapattığınız her özellik, arka planda kesinlikle sıfır yük oluşturur.*

---

## 📥 İndirme ve Kurulum

mDock kolay kurulum ile sadece bir exe dosyası üzerinden kurulabilir. 
İsterseniz mDocuk Porable sürümünüde kullanailirsiniz.

1.  [Releases](https://github.com/furkanzden/mDock/releases/tag/v1.0.0) sayfasından en güncel `mDock.exe` dosyasını indirin. 
2.  Zip dosyasını istediğiniz bir klasöre çıkartın (Örn: `C:\Programlar\mDock`).
3.  `mDock.exe` dosyasını çift tıklayarak çalıştırın.
4.  İlk açılışta ayarlarınızın kaydedileceği `config.json` dosyası otomatik olarak oluşur.

> ⚠️ **Windows Defender Uyarısı:** Uygulama imzalı (code-signed) olmadığı için nadiren Windows Defender uyarı verebilir. "Yine de Çalıştır" (Run anyway) seçeneğine tıklayarak güvenle devam edebilirsiniz.

---

## 🔄 Konumu Sıfırlama

Eğer ada'yı ALT tuşu ile sürükleyerek yanlış bir yere taşıdıysanız ve bulamıyorsanız endişelenmeyin:
1. Sağ alttaki sistem tepsisindeki mDock simgesine sağ tıklayın.
2. **"📍 Konumu Ortala"** seçeneğine tıklayın. Ada ekranın üst ortasındaki varsayılan yerine geri dönecektir.

---

<div align="center">
  <br>
  <sub>mDock, Windows kullanıcıları için Apple estetiğini en hafif haliyle sunar.</sub>
  <br><br>
  <b>Projeyi beğendiyseniz bir ⭐ Yıldız vermeyi unutmayın!</b>
  <br><br>
  <i>🛠️ Geliştirici: <a href="https://github.com/furkanzden">[furkanzden]</a></i>
</div>
