# Uzlaştırmacı Evrak Asistanı

Windows için evrak hazırlama ve dosya süreç takibi uygulaması.

**[En son sürümü indir](https://github.com/onurmuratlekesiz/uzlastirici-surumler/releases/latest)**

Sürüm sayfasındaki **Uzlastirmaci.zip** dosyasını indirin. `update.json`, uygulamanın sürüm kontrolü için kullandığı dosyadır; kullanıcıların ayrıca indirmesi gerekmez.

## İlk kullanım

ZIP'i kalıcı ve yazılabilir bir klasöre çıkarıp içindeki EXE'yi açın. Windows 10/11 (64 bit), Microsoft Edge WebView2 ve resmi PDF üretimi için Microsoft Word gerekir. Program verileri bulunduğu kurulum klasöründe saklanır.

## Eski sürümden geçiş

1. Uygulama içinden yedeğinizi alın.
2. Uygulamayı sistem tepsisinden de tamamen kapatın.
3. ZIP'i ayrı bir klasöre çıkarın. Yeni EXE ve `_internal` klasörünü birlikte eski kurulumunuza kopyalayın.
4. Mevcut `settings.json`, `cases.json`, `history.json`, `profiles.json`, `profiles`, `output`, `custom_templates`, yedekler ve diğer kişisel dosyalarınızı koruyun. Kurulum klasörünün tamamını silmeyin.
5. Uygulamayı yeniden açın. Sonraki sürümleri **Ayarlar > Uygulama Güncellemeleri** alanından yükleyebilirsiniz.

## Uygulama içi güncelleme

1.1.0 ve sonrası sürümler yeni sürümleri açılışta ve günlük olarak kontrol eder. Uygulama temalı bildirim ve güncelleme bandı gösterilir. **Şimdi Güncelle** seçilince paket indirilip doğrulanır; uygulama kapatılıp yeniden açılır. Profil, dosya kayıtları, evraklar ve özel şablonlar korunur. Yeni program açılışı doğrulanamazsa önceki sürüm geri alınır.

Kaydedilmemiş dosya formu veya devam eden evrak üretimi varsa güncelleme başlatılmaz. Otomatik kontrol ayarlardan kapatılabilir. İnternet yokken mevcut sürümü kullanmaya devam edebilirsiniz. Güncelleme kontrolünde dosya veya taraf bilgileri gönderilmez.

Bu depoda yalnızca dağıtım paketleri ve sürüm açıklamaları bulunur. Kaynak kodu deposu özeldir; kullanıcı kayıtları, profil bilgileri ve dosya evrakları yayımlanmaz.
