# Kapsamlı Markdown Dosyası Örneği

Markdown, metinlerinizi basit bir biçimde düzenlemenize ve biçimlendirmenize olanak tanır. Aşağıda Markdown'ın çeşitli özelliklerini detaylı bir şekilde bulabilirsiniz.

## İçindekiler

1. [Giriş](#giriş)
2. [Başlıklar](#başlıklar)
3. [Listeler](#listeler)
   - [Sırasız Liste](#sırasız-liste)
   - [Sıralı Liste](#sıralı-liste)
   - [İç İçe Liste](#iç-içe-liste)
4. [Kod Blokları](#kod-blokları)
   - [JavaScript](#javascript)
   - [Python](#python)
5. [Resimler](#resimler)
6. [Bağlantılar](#bağlantılar)
7. [Alıntılar](#alıntılar)
8. [Kalın ve İtalik Metin](#kalın-ve-italik-metin)
   - [Hem Kalın Hem İtalik](#hem-kalın-hem-italik)
9. [Tablo](#tablo)
10. [Satırlar](#satırlar)
11. [Yatay Çizgi](#yatay-çizgi)
12. [HTML Etiketleri](#html-etiketleri)
13. [Matematik Düşünceleri](#matematik-düşünceleri)
14. [Sonuç](#sonuç)

## Giriş

Markdown, metinleri biçimlendirmenin ve düzenlemenin etkili bir yoludur. Özellikle yazılı içerikleri hızlı ve kolay bir şekilde düzenlemek isteyenler için idealdir. Bu dosya, Markdown dilinin çeşitli özelliklerini kapsamlı bir şekilde sunar.

## Başlıklar

Başlıklar, içeriğinizi düzenlemenin ve hiyerarşiyi göstermenizin yollarıdır. Başlık seviyeleri aşağıdaki gibidir:

- `# Birinci Seviye Başlık` (en büyük başlık)
- `## İkinci Seviye Başlık`
- `### Üçüncü Seviye Başlık`
- `#### Dördüncü Seviye Başlık`
- `##### Beşinci Seviye Başlık`
- `###### Altıncı Seviye Başlık` (en küçük başlık)

## Listeler

### Sırasız Liste

Sırasız liste oluşturmak için `-`, `*`, veya `+` işaretlerini kullanabilirsiniz:

- Birinci madde
- İkinci madde
- Üçüncü madde

### Sıralı Liste

Sıralı liste oluşturmak için numaralandırma kullanabilirsiniz:

1. İlk adım
2. İkinci adım
3. Üçüncü adım

### İç İçe Liste

İç içe listeler oluşturmak da mümkündür:

- Ana madde
  - İç madde 1
  - İç madde 2
    - Alt madde 1
    - Alt madde 2

## Kod Blokları

Kod blokları, programlama kodlarını veya komutları biçimlendirmenin ve vurgulamanın etkili bir yoludur. Üçlü backtick (```) kullanarak kod blokları oluşturabilirsiniz. Kod dilini belirterek sentaks renklendirmesi yapılabilir.

### JavaScript

```javascript
function greet(name) {
    return `Merhaba, ${name}!`;
}
