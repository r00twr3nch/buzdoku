# Buzdoku

Klasik sudoku ve eriyen buz sudoku. Tek dosya, telefonda tarayıcıdan oynanır.

**[Oyna](https://r00twr3nch.github.io/buzdoku/)**

## İki oyun

Ana sayfada iki kapı var.

**Sudoku** bildiğin tahta. Doğru rakam yerinde kalır. Yanlış rakam bir can götürür.

**Buzdoku** aynı tahta, farklı kural. Doğru rakam buz olur. Süre dolmadan satırı, sütunu ya da 3×3 bloğu kapatamazsan erir. Kapanan çizgi donar; o rakamlar bir daha gitmez.

Üç yanlışta oyun biter.

## Zorluk

| | Boş kutu |
|---|---|
| Kolay | 35 |
| Orta | 45 |
| Zor | 53 |

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
