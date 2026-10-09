Aether 2.0 "Orion"

Aether artık **Arch Linux** tabanlı. Arch depolarındaki binlerce uygulama ve Flathub tek tıkla kurulabiliyor.

**Yenilikler**
- **Uygulama Mağazası**: Arch depoları ve Flathub bir arada. Kategoriler, öne çıkanlar, yüklü uygulamalar ve güncellemeler.
- **Aether Dosyalar**: kendi dosya yöneticim. Kopyalama ilerlemesi, çöp kutusu, sürükle bırak, "Birlikte aç".
- **Görev Yöneticisi** (Ctrl+Shift+Esc): uygulamalar ve arka plan işlemleri, CPU / bellek / disk / ağ grafikleri.
- **Oyun Modu**: Steam ve ekran kartı sürücüsünü tek tıkla kurma, performans modu.
- **Masaüstü**: simgeler ve Windows'takine benzer sağ tık menüleri (Yeni klasör, Kes / Kopyala / Yapıştır, Yeniden adlandır...).
- Kurduğun uygulamalar başlat menüsünde kategorilere göre çıkıyor.
- Kurulum programı Aether'i **Windows'un yanına** kurabiliyor (Windows bölümünü küçültür, açılışta seçim menüsü çıkar).
- `sudo` çalışıyor.
- Sanal makinede **3D hızlandırma**: VirtualBox (VMSVGA + 3D), VMware ve QEMU virtio-gpu. Ayarlar → Ekran'da açık olup olmadığı görünüyor.
- Ekran çözünürlüğü değişince görev çubuğu ve pencereler kendini uyduruyor; VirtualBox penceresini büyütüp küçültmek yetiyor.
- VirtualBox, VMware ve QEMU misafir araçları hazır geliyor.

**Bilinen sorunlar**
- Gerçek donanımda test edilmedi. Secure Boot desteklenmiyor, BIOS/UEFI ayarlarından kapatman gerekiyor.
- Windows'un yanına kurmadan önce önemli dosyalarını yedekle. Windows'ta hızlı başlatma ve BitLocker kapalı olmalı.

**Dosyalar**
| dosya | sha256 |
|---|---|
| aether-2.0-orion.iso | `1d5cd5a4cdbb0524d3dde89f4c6d397fb06f65e2c15a6b12d1f4a84f070a17bd` |

Alpine tabanlı daha hafif 1.1 "Nebula" isteyenler için [1.1 sürümü](https://github.com/1260120047-eng/aether/releases/tag/1.1) duruyor.

Kaynak kodu: https://github.com/1260120047-eng/aether-os
