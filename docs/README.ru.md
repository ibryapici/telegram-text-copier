<div align="center">

# Telegram Text Copier

**Telegram'ın kilidini açın: İstediğiniz metni kolayca kopyalayın.**

[![GitHub License](https://img.shields.io/github/license/ibryapici/telegram-text-copier)](./LICENSE)
[![Greasy Fork Version](https://img.shields.io/greasyfork/v/446342-telegram-text-copier)](https://greasyfork.org/tr/scripts/541182-telegram-text-copier)
[![Greasy Fork Downloads](https://img.shields.io/greasyfork/dt/446342-telegram-text-copier)](https://greasyfork.org/tr/scripts/541182-telegram-text-copier)

</div>

## Genel Bakış

Bu kullanıcı betiği, Telegram web uygulamalarındaki sohbetlerden, hikayelerden ve hatta metin kopyalamanın devre dışı bırakıldığı veya kısıtlandığı özel kanallardan metinleri kolayca seçip kopyalamanızı sağlar.

### Kullanıcı betiği (user script) nedir?

Kullanıcı betikleri, gezinme deneyiminizin kontrolünü size verir. Yüklendikten sonra, özellikler ekleyerek, kullanımı kolaylaştırarak veya can sıkıcı kısımları kaldırarak ziyaret ettiğiniz siteleri otomatik olarak daha iyi hale getirirler. Greasy Fork'taki kullanıcı betikleri diğer kullanıcılar tarafından yazılmış ve dünyayla paylaşmak için yayınlanmıştır. Kurulumları ücretsizdir ve kullanımı kolaydır.

## Kurulum

### Greasy Fork

1.  Bir kullanıcı betiği yöneticisi yükleyin

    Kullanıcı betiklerini kullanmak için önce bir kullanıcı betiği yöneticisi yüklemeniz gerekir. Hangi kullanıcı betiği yöneticisini kullanabileceğiniz, kullandığınız tarayıcıya bağlıdır.

    - Chrome: [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) veya [Violentmonkey](https://chrome.google.com/webstore/detail/violent-monkey/jinjaccalgkegednnccohejagnlnfdag)
    - Firefox: [Greasemonkey](https://addons.mozilla.org/firefox/addon/greasemonkey/), [Tampermonkey](https://addons.mozilla.org/firefox/addon/tampermonkey/), veya [Violentmonkey](https://addons.mozilla.org/firefox/addon/violentmonkey/)
    - Safari: [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) veya [Userscripts](https://apps.apple.com/app/userscripts/id1463298887)
    - Microsoft Edge: [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) veya [Violentmonkey](https://chrome.google.com/webstore/detail/violent-monkey/jinjaccalgkegednnccohejagnlnfdag)
    - Opera: [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) veya [Violentmonkey](https://chrome.google.com/webstore/detail/violent-monkey/jinjaccalgkegednnccohejagnlnfdag)
    - Maxthon: [Violentmonkey](https://chrome.google.com/webstore/detail/violent-monkey/jinjaccalgkegednnccohejagnlnfdag)

    (Not: Chrome tabanlı bir tarayıcıda Tampermonkey uzantısını kullanıyorsanız, Geliştirici Modunu etkinleştirmek için [bu talimatları](https://www.tampermonkey.net/faq.php#Q209) izleyin.)

2.  Greasy Fork'u ziyaret ederek bu betiği yükleyin:
    https://greasyfork.org/tr/scripts/541182-telegram-text-copier

### Manuel Kurulum

1.  Bir kullanıcı betiği yöneticisi yükleyin (yukarıdaki listeye bakın).
2.  Tampermonkey Panosunu açın, `src/telegram-text-copier.js` dosyasını sürükleyip bırakın ve "yükle" düğmesine tıklayın.

## Nasıl Kullanılır

Bu betik yalnızca Telegram Web uygulamasında çalışır.

İçeriğin kopyalanmasına zaten izin verilen kanallar ve sohbetler için bu betiğin bir etkisi olmayacaktır. Lütfen telegram web uygulamasının sağladığı resmi kopyalama işlevini kullanın.

Metin kopyalamanın devre dışı bırakıldığı kanallar ve sohbetler için, bu betik metinleri seçilebilir ve kopyalanabilir hale getirecektir.

## Desteklenen Web Uygulaması Sürümleri

Telegram web uygulamalarının 2 farklı sürümü vardır:

- https://webk.telegram.org / https://web.telegram.org/k/ (**Önerilen**)
- https://webz.telegram.org / https://web.telegram.org/a/

Bu betik, web uygulamasının her iki sürümünde de çalışmalıdır, ancak bazı özellikler yalnızca /k/ sürümünde mevcut olabilir. Belirli özellikler çalışmıyorsa, /k/ sürümüne geçmeniz önerilir.

## Katkıda Bulunma

Topluluktan gelen katkıları memnuniyetle karşılıyoruz! Telegram Text Copier'a katkıda bulunmak isterseniz, şu adımları izleyin:

### Sorunları Bildirme

Bir hata, uyumluluk sorunu bulursanız veya bir özellik talebiniz varsa, lütfen:

1.  Sorunun daha önce Issues (Sorunlar) sekmesinde bildirilip bildirilmediğini kontrol edin.
2.  Değilse, net bir başlık ve açıklama ile yeni bir sorun oluşturun. Varsa ekran görüntüleri veya günlükleri ekleyin.

### Pull Request Gönderme

1.  **Depoyu Fork'layın**: Reponun sağ üst köşesindeki "Fork" düğmesine tıklayın.
2.  **Fork'unuzu klonlayın**:
    ```bash
    git clone https://github.com/ibryapici/Telegram-Text-Copier.git
    cd Telegram-Text-Copier
    ```
3.  Özelliğiniz veya hata düzeltmeniz için **yeni bir dal (branch) oluşturun**:
    ```bash
    git checkout -b ozellik-veya-hata-duzeltme-adi
    ```
4.  **Değişikliklerinizi yapın** ve betiğin desteklenen Telegram web uygulamalarında hala doğru çalıştığından emin olun.
5.  **Değişikliklerinizi** açıklayıcı bir mesajla **commit'leyin**:
    ```bash
    git commit -m "Özellik ekle/sorunu düzelt: Kısa açıklama"
    ```
6.  **Fork'unuza push'layın:**
    ```bash
    git push origin ozellik-veya-hata-duzeltme-adi
    ```
7.  **Bir Pull Request (PR) Gönderin:**
    - Orijinal depoya gidin: [ORİJİNAL_REPO_LİNKİ](https://github.com/ibryapici/Telegram-Text-Copier).
    - "New Pull Request"e tıklayın ve dalınızı seçin.
    - Değişikliklerinizin bir açıklamasını ekleyin ve gönderin.

### Geliştirme Yönergeleri

- Kodunuzu temiz ve iyi belgelenmiş tutun.
- Mevcut kodlama stilini takip edin.
- Değişikliklerinizi hem Telegram WebK hem de WebZ sürümlerinde test edin.
- Tampermonkey ve Violentmonkey gibi başlıca kullanıcı betiği yöneticileriyle uyumluluğu sağlayın.

## 📝 Lisans

Bu proje MIT Lisansı ile lisanslanmıştır. Detaylar için `LICENSE` dosyasına bakınız.
