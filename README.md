# Buzdoku

Klasik sudoku ve eriyen buz sudoku. Tek dosya, telefonda tarayıcıdan oynanır.

**[Oyna](https://r00twr3nch.github.io/buzdoku/)**

## İki oyun

Ana sayfada üç kapı var.

**Sudoku** bildiğin tahta. Doğru rakam yerinde kalır. Yanlış rakam bir can götürür.

**Buzdoku** aynı tahta, farklı kural. Doğru rakam buz olur. Süre dolmadan satırı, sütunu ya da 3×3 bloğu kapatamazsan erir. Kapanan çizgi donar; o rakamlar bir daha gitmez.

**Spiral** kare tahta değildir. Dokuz köşeli dokuz halka vardır ve her halkada dokuz kutu bulunur. Dıştan merkeze inen her kol da dokuz kutudur. Halkalar üçerli, kollar da üçerli gruplanır; her 3×3 parça klasik sudokudaki blok gibidir. Her halka, her kol ve her 3×3 blok 1’den 9’a kadar birer kez dolar. Aynı bloktaki kutular aynı renktedir.

Üç yanlışta oyun biter.

## Zorluk

| | Boş kutu |
|---|---|
| Kolay | 35 |
| Orta | 45 |
| Zor | 53 |

Spiralde boş kutu sayısı 28, 40 ve 50’dir.

Her yeni oyunda tahta yeniden karılır. Çözüm tektir.

## Kontroller

- Kutuya dokun, rakamı alttaki tuşlardan ya da klavyeden yaz.
- **Geri al** son doğru hamleyi siler.
- **İpucu** rastgele bir boş kutuya doğru rakamı koyar. Buzdoku’da o rakam da eriyebilir.
- **Yeni** aynı zorlukta başka bir tahta açar.
- Sol üstteki çıkış ana sayfaya döner.

Buzdoku’da erime süresi ayarlardan değişir. 5 ile 20 saniye arası. Seçim tarayıcıda kalır.

## Yerelde

`index.html` dosyasını aç. Başka bir şey kurmana gerek yok.
