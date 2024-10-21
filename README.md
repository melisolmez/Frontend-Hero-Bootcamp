# Frontend-Hero-Bootcamp

# HMTL
- HTML web sayfalarının yapısını ve içeriğini tanımlamak için kullanılan bir dildir. HTML, tarayıcıların web sayfalarını nasıl görüntüleyeceğini belirlemek için kullanılan temel bir teknoloji ve web sitelerinin oluşturulmasında kullanılan en önemli bileşendir.
Aşağıda basit bir HTML sayfası örneği bulunmaktadır:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Sayfa Başlığı</title>
</head>
<body>
    <h1>Merhaba Dünya!</h1>
    <p>Bu, bir paragraf örneğidir.</p>
    <a href="https://www.example.com">Örnek bir bağlantı</a>
</body>
</html> 
```


 - HMTL de iskelet genellikle üç gruptan oluşur. Bunlardan biri header kısmı biri body yani main kısım biri de footer kısmı
 - Body içinde tanımlanan şeyler kullanıcının göreceği kısımdır
 - Header içinde sayfa başlığı harici bilgiler görünmezler
 - Html etiketleri:
 - `<p>`: Paragraf oluşturmak için kullanılan bir etikettir.
- `<h1>`: Bir başlık oluşturmak için kullanılır (en yüksek seviye).(1-6 ya kadar değer alır)
- `<a>`: Bağlantı oluşturmak için kullanılır.
- `<ul>`: Sırasız liste oluşturmak için kullanılır.
- `<ol>`: Sıralı liste oluşturmak için kullanılır.
- `<li>`: Liste öğelerini tanımlamak için kullanılır.
- `<div>`: Sayfa içinde bölüm oluşturmak için kullanılır.
- `<span>`: İnline elemanlar için bir konteyner görevi görür.
- `<img>`: Resim eklemek için kullanılır. 
- `<hr>`: Alt çizgi eklemek için kullanılır. 
- `<br>`: Alt satır eklemek için kullanılır. 
- `<dl>`: Tanım listeleri oluşturmak için kullanılır. 
- `<table>`: Tablo yapısı oluşturmak için kullanılır. `<tr>` satır eklemek için,`<th>` sutün eklemek için kullanılır

### HTML'de Formlar
- Formlar, kullanıcılar ile etkileşim kurmak ve veri toplamak için kullanılan önemli HTML bileşenleridir. Web sayfalarında kullanıcıların bilgi girmesine veya seçim yapmasına olanak tanır. Aşağıda form etiketleri ve kullanım alanları hakkında bazı bilgiler verilmiştir:

- `<form>`: Formun başlangıcını ve sonunu belirten etiket. İçinde kullanıcıdan alınacak veriler bulunur.
- `<input>`: Kullanıcının veri girmesine olanak tanır. Çeşitli türleri vardır, örneğin:
  - `type="text"`: Metin girişi.
  - `type="email"`: E-posta girişi.
  - `type="password"`: Şifre girişi.
  - `type="checkbox"`: Onay kutusu.
  - `type="radio"`: Radyo düğmesi.
  - `type="submit"`: Formu göndermek için buton.
- `<label>`: Form elemanlarının tanımlanmasında kullanılır ve kullanıcı dostu hale getirir.
- `<textarea>`: Çok satırlı metin girişi sağlar.
- `<select>`: Açılır menü oluşturur ve kullanıcının birden fazla seçenek arasından seçim yapmasına olanak tanır.
- `<option>`: Açılır menüdeki seçenekleri tanımlar.

### HTML'de Attribute
- HTML'de attribute'lar, HTML etiketlerine ek bilgi eklemek için kullanılır. Her attribute, bir etiketin işlevselliğini artırmak ve daha fazla bilgi sağlamak için tasarlanmıştır. Attribute'lar genellikle "anahtar-değer" çiftleri şeklinde tanımlanır.
- `class`, `id`, `style` ve `title` gibi attribute'lar global attribute'dir.

### HTML'de Semantik Etiketler
- Semantik etiketler, HTML'de içeriklerin anlamını belirlemek ve yapılandırmak için kullanılan etiketlerdir. Bu etiketler, sayfanın içeriğinin ne anlama geldiğini tanımlayarak, hem geliştiricilerin hem de arama motorlarının içeriği daha iyi anlamasına yardımcı olur. Semantik etiketlerin kullanımı, erişilebilirlik ve SEO (arama motoru optimizasyonu) açısından da önemlidir.
- Bazı semantik etiketler :
  - `<header>`: Sayfanın veya bölümün başlık bölümünü tanımlar.
  - `<nav>` : Sayfa üzerindeki navigasyon bağlantılarını içeren bölüm. Genellikle menüler için kullanılır.
  - `<main>`: Sayfanın ana içeriğini tanımlar. Genellikle bir sayfanın en önemli bölümüdür.
  - `<article>`: Bağımsız, kendi başına anlam taşıyan bir içerik parçasını tanımlar. Blog yazıları veya haber makaleleri için idealdir.
  - `<section>`: Sayfanın belirli bir konusunu veya bölümünü tanımlar. Genellikle başlık ve içeriğe sahiptir.
  - `<figure>` : Bir görselin veya görsel ile ilişkili içeriğin (örneğin, bir resim, grafik veya diyagram) belirtildiği semantik bir etikettir.
  - `<img>`: Görseli sayfaya eklemek için kullanılır. src (kaynak) ve alt (alternatif metin) attribute'ları ile birlikte gelir.
  - `<figcaption>`: Görselin altına eklenen açıklayıcı metni belirtir. Görselin içeriğini tanımlar ve açıklama sağlar.

- `<aside>`: Sayfanın ana içeriğinden bağımsız olarak ek bilgi veya yan içerik sunar. Genellikle içerikle ilgili daha fazla bilgi veya destekleyici içerik barındırır.
- `<footer>`: Sayfanın veya bölümün alt kısmında yer alan bilgileri temsil eder. Sayfanın genel bilgilerini ve bağlantılarını içerir.