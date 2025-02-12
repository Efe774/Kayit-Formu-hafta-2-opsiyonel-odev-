# Kayıt Formu

Bu proje, HTML ve CSS kullanarak basit bir kayıt formu oluşturur. Formda kullanıcıdan ad, e-posta, yaş, cinsiyet, aktiviteler, iletişim tercihleri ve yorumlar alınır. 

## Özellikler

- **Sayfa Başlığı**: Formun başlığı `<h1>` etiketi içinde yer alır ve `id="title"` ile tanımlanır.
- **Açıklama**: Formun kısa bir açıklaması `<p>` etiketi içinde yer alır ve `id="description"` ile tanımlanır.
- **Kullanıcı Girişi Alanları**:
  - **İsim**: Kullanıcıdan adını alır.
  - **E-posta**: Kullanıcıdan e-posta adresini alır ve HTML5 doğrulama ile geçerli e-posta formatı kontrol edilir.
  - **Yaş**: Kullanıcıdan yaş bilgisini alır ve belirli bir aralıkta (18-100 yaş) sınırlandırılır.
  - **Cinsiyet Seçimi**: Kullanıcıya cinsiyet seçeneği sunan bir dropdown menü vardır.
  - **Aktivite Seçimi**: Kullanıcıya ilgilendiği aktivitelerle ilgili seçenekler sunulur (spor, müzik).
  - **İletişim Tercihleri**: Kullanıcıya e-posta ve SMS ile iletişim seçenekleri sunulur.
  - **Yorumlar**: Kullanıcıdan yorum almak için bir metin alanı (textarea) bulunur.
- **Form Gönderimi**: Form verilerini göndermek için bir submit butonu vardır.

## Teknolojiler

- **HTML**: Formun yapısal öğeleri için kullanıldı.
- **CSS**: Formun stilini ve sayfanın arka planını tasarlamak için kullanıldı. Arka plan mavi tonlarında bir gradient ile oluşturuldu.

## Kullanım

### 1. HTML ve CSS Dosyalarını İndirme

Bu projeyi yerel olarak çalıştırmak için HTML ve CSS dosyalarını aşağıdaki adımları takip ederek indirmeniz gerekir.

1. **HTML Dosyasını İndirin**: [index.html](./index.html)
2. **CSS Dosyasını İndirin**: [styles.css](./styles.css)

### 2. Dosyaların Yerleştirilmesi

- HTML dosyasını tarayıcınızda açarak formu görüntüleyebilirsiniz.
- CSS dosyasını `styles.css` olarak kaydedin ve HTML dosyasının `<head>` kısmında aşağıdaki gibi ilişkilendirin:

```html
<link rel="stylesheet" href="styles.css">

```

## Geliştirici

- **Ad**: [Saim Efe Omağ](https://github.com/Efe774)
