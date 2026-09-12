# Poipu Menü

Poipu Coffee'nin ekran menüsü. İki statik HTML sayfası; dijital tabela yazılımı
sayfayı doğrudan açar.

| Sayfa | İçerik |
|---|---|
| `sicak.html` | Coffees — kahveler, sütlü kahveler, matcha & ube, kahvesiz içecekler |
| `soguk.html` | Poipu — imza içecekler ve soğuklar |
| `index.html` | ikisine de bağlantı veren basit kapak |

## Ekrana bağlama

Tabela yazılımında "website" kaynağı olarak sayfanın adresi verilir; her ekran
kendi sayfasını gösterir. Sayfa 3840×2160 için tasarlandı, 1920×1080'de de
bozulmadan çalışır. Ölçüler ekran yüksekliğine göre hesaplanır, sabit piksel yok.

Notlar:
- Tabelanın tarayıcısı sayfayı her gösterimde yeniden yükler; font dosyaları depo
  içinde durduğu için internet kesilse bile menü bozulmaz.
- Mevsimlik satır cihazın **tarihine** göre görünür/gizlenir. Ekranın saati ve saat
  dilimi yanlışsa satır yanlış zamanda görünür — kurulumda kontrol edin.
- Hareket azaltma ayarı açık bir cihazda alttaki kayan şerit durur, yazılar okunur
  hâlde kalır.

## Güncelleme

Sayfalar elle yazılmaz, üretilir. Fiyat ya da ürün değişince yeni sayfalar üretilip
bu depoya konur; buradaki dosyaları doğrudan düzenlemeyin, ilk üretimde geri gelir.
