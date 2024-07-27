<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kapsamlı Markdown Dosyası Örneği</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Kapsamlı Markdown Dosyası Örneği</h1>
    </header>

    <nav>
        <ul>
            <li><a href="#giriş">Giriş</a></li>
            <li><a href="#başlıklar">Başlıklar</a></li>
            <li><a href="#listeler">Listeler</a></li>
            <li><a href="#kod-blokları">Kod Blokları</a></li>
            <li><a href="#resimler">Resimler</a></li>
            <li><a href="#bağlantılar">Bağlantılar</a></li>
            <li><a href="#alıntılar">Alıntılar</a></li>
            <li><a href="#kalın-ve-italik-metin">Kalın ve İtalik Metin</a></li>
            <li><a href="#tablo">Tablo</a></li>
            <li><a href="#satırlar">Satırlar</a></li>
            <li><a href="#yatay-çizgi">Yatay Çizgi</a></li>
            <li><a href="#html-etiketleri">HTML Etiketleri</a></li>
            <li><a href="#matematik-düşünceleri">Matematik Düşünceleri</a></li>
            <li><a href="#sonuç">Sonuç</a></li>
        </ul>
    </nav>

    <main>
        <section id="giriş">
            <h2>Giriş</h2>
            <p>Markdown, metinleri biçimlendirmenin ve düzenlemenin etkili bir yoludur. Özellikle yazılı içerikleri hızlı ve kolay bir şekilde düzenlemek isteyenler için idealdir. Bu dosya, Markdown dilinin çeşitli özelliklerini kapsamlı bir şekilde sunar.</p>
        </section>

        <section id="başlıklar">
            <h2>Başlıklar</h2>
            <p>Başlıklar, içeriğinizi düzenlemenin ve hiyerarşiyi göstermenizin yollarıdır. Başlık seviyeleri aşağıdaki gibidir:</p>
            <ul>
                <li><code># Birinci Seviye Başlık</code> (en büyük başlık)</li>
                <li><code>## İkinci Seviye Başlık</code></li>
                <li><code>### Üçüncü Seviye Başlık</code></li>
                <li><code>#### Dördüncü Seviye Başlık</code></li>
                <li><code>##### Beşinci Seviye Başlık</code></li>
                <li><code>###### Altıncı Seviye Başlık</code> (en küçük başlık)</li>
            </ul>
        </section>

        <section id="listeler">
            <h2>Listeler</h2>
            <h3>Sırasız Liste</h3>
            <ul>
                <li>Birinci madde</li>
                <li>İkinci madde</li>
                <li>Üçüncü madde</li>
            </ul>

            <h3>Sıralı Liste</h3>
            <ol>
                <li>İlk adım</li>
                <li>İkinci adım</li>
                <li>Üçüncü adım</li>
            </ol>

            <h3>İç İçe Liste</h3>
            <ul>
                <li>Ana madde
                    <ul>
                        <li>İç madde 1</li>
                        <li>İç madde 2
                            <ul>
                                <li>Alt madde 1</li>
                                <li>Alt madde 2</li>
                            </ul>
                        </li>
                    </ul>
                </li>
            </ul>
        </section>

        <section id="kod-blokları">
            <h2>Kod Blokları</h2>
            <p>Kod blokları, programlama kodlarını veya komutları biçimlendirmenin ve vurgulamanın etkili bir yoludur. Üçlü backtick (<code>```</code>) kullanarak kod blokları oluşturabilirsiniz. Kod dilini belirterek sentaks renklendirmesi yapılabilir.</p>

            <h3>JavaScript</h3>
            <pre><code class="language-javascript">
function greet(name) {
    return `Merhaba, ${name}!`;
}
            </code></pre>

            <h3>Python</h3>
            <pre><code class="language-python">
def greet(name):
    return f"Merhaba, {name}!"
            </code></pre>
        </section>

        <section id="resimler">
            <h2>Resimler</h2>
            <p>Resimleri Markdown'da şu şekilde ekleyebilirsiniz:</p>
            <pre><code>![Açıklama](resim-url)</code></pre>
        </section>

        <section id="bağlantılar">
            <h2>Bağlantılar</h2>
            <p>Bağlantıları Markdown'da şu şekilde oluşturabilirsiniz:</p>
            <pre><code>[Link Metni](http://example.com)</code></pre>
        </section>

        <section id="alıntılar">
            <h2>Alıntılar</h2>
            <p>Alıntıları Markdown'da şu şekilde oluşturabilirsiniz:</p>
            <pre><code>&gt; Bu bir alıntıdır.</code></pre>
        </section>

        <section id="kalın-ve-italik-metin">
            <h2>Kalın ve İtalik Metin</h2>
            <p>Metni kalın ve italik yapmak için:</p>
            <pre><code>**Kalın Metin**</code></pre>
            <pre><code>*İtalik Metin*</code></pre>
            <pre><code>***Hem Kalın Hem İtalik***</code></pre>
        </section>

        <section id="tablo">
            <h2>Tablo</h2>
            <p>Tabloları Markdown'da şu şekilde oluşturabilirsiniz:</p>
            <pre><code>| Başlık 1 | Başlık 2 |
|----------|----------|
| Hücre 1  | Hücre 2  |
| Hücre 3  | Hücre 4  |</code></pre>
        </section>

        <section id="satırlar">
            <h2>Satırlar</h2>
            <p>Satırları Markdown'da şu şekilde oluşturabilirsiniz:</p>
            <pre><code>Metin
---
Metin</code></pre>
        </section>

        <section id="yatay-çizgi">
            <h2>Yatay Çizgi</h2>
            <p>Yatay çizgi oluşturmak için:</p>
            <pre><code>---</code></pre>
        </section>

        <section id="html-etiketleri">
            <h2>HTML Etiketleri</h2>
            <p>Markdown içinde HTML etiketlerini de kullanabilirsiniz:</p>
            <pre><code>&lt;div&gt;Bu bir div elemanıdır.&lt;/div&gt;</code></pre>
        </section>

        <section id="matematik-düşünceleri">
            <h2>Matematik Düşünceleri</h2>
            <p>Matematiksel ifadeleri Markdown'da şu şekilde yazabilirsiniz:</p>
            <pre><code>$$
E = mc^2
$$</code></pre>
        </section>

        <section id="sonuç">
            <h2>Sonuç</h2>
            <p>Markdown, basit bir biçimlendirme dili olarak metinlerinizi düzenlemenin ve biçimlendirmenin hızlı bir yolunu sunar. HTML ve CSS ile bu biçimlendirmeyi web sayfalarına dönüştürmek mümkündür.</p>
        </section>
    </main>
</body>
</html>
