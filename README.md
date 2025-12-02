# PISTACHIO GUSTO Web Projesi

Bu proje, lüks Antep fıstığı bazlı ürünler (Dubai Çikolatası, fıstık kreması ve ezmesi) üreten "PISTACHIO GUSTO" markası için kurgusal bir kurumsal web sitesidir. Ödevin amacı, CSS veya JavaScript kullanmadan, **sadece saf HTML** ile yapısal ve anlamsal öğelerin kullanımını göstermektir.

##  Dosya Organizasyonu
Proje, tümü birbirine göreceli yollarla bağlı dört ana HTML dosyasından ve bir medya klasöründen oluşmaktadır:

* **index.html**: Ana Sayfa. `<header>`, `<main>`, `<article>`, `<img>` ve `<footer>` içerir.
* **about.html**: Marka Hikayesi. `<section>`, `<figure>`, `<figcaption>` ve zorunlu **5 anlamsal etiket** (`<time>`, `<mark>`, `<blockquote>`, `<details>`, `<summary>`) içerir.
* **services.html**: Ürün Çeşitleri. `<table>`, `<thead>`, `<tbody>`, `<tfoot>` yapısı ve en az 4 sütun / 5 satır içerir.
* **contact.html**: İletişim Formu. Tam donanımlı form öğelerini (`<form>`, `<fieldset>`, `<legend>`, `<label>` + farklı `<input>` tipleri, `<textarea>`, `<select>`) içerir.
* **assets/**: Resim, ses ve video dosyalarının (img src="" ile referans verilen) saklandığı klasördür.

##  Karştığım Zorluklar
Projenin en büyük zorluğu, site genelinde tutarlı bir gezinme (`<nav>`) ve sayfa yapısını korurken, modern bir görünüm ihtiyacını hiç CSS kullanmadan sadece HTML'in yapısal gücüyle çözmeye çalışmaktı.