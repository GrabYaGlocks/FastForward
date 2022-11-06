# FastForward Gizlilik Politikası

## Otomatik güncelleme

FastForward, güncel baypaslar sağlamak için her saat Github'a bir istek gönderir ve yeni bir taahhüt bulunursa en son "enjeksiyon komut dosyasını" indirir.

Bunun için [Github'ın gizlilik politikası](https://help.github.com/en/github/site-policy/github-privacy-statement) geçerlidir.

## Kalabalık Baypas

Crowd Bypass (Seçenekler > "Bypass edilemeyen kısaltıcıların hedeflerini ver ve al.") etkinleştirildiğinde, uzantı bazen sunucumuza istek gönderir:

- Bilinen bir atlanamayan kısaltıcı web sitesini ziyaret ettiğinizde, başka birinin hedefini önceden bildirmiş olup olmadığını veritabanına göre kontrol edebilmesi için URL gönderilir.
- Böyle bir web sitesindeki ziyaretinizi tamamladığınızda, gelecekteki ziyaretçiler için kaydedilebilmesi için URL ve hedef URL gönderilir.

Kötüye kullanımı önlemek için, bir bağlantı gönderdiğinizde IP adresinizin karma bir sürümünü veritabanımıza kaydederiz. Veritabanına yalnızca geliştiriciler erişebilir.
