# Peregrin rota paketleri

Peregrin: Walk & Ride the World uygulamasının sonradan indirilen rota paketleri burada durur.
Uygulama ilk kurulumda İlk Maratonun ve Likya Yolu ile gelir; diğer rotalar kullanıcı seçince bir kez iner ve sonra internetsiz çalışır.

- İçerik: yalnızca rota fotoğrafları ve metinleri (8 dil). Kullanıcı verisi yok.
- Güvenlik: uygulama her paketin SHA-256 parmak izini bilir; değiştirilmiş bir paket açılmaz.
- Paketler `peregrin` deposundaki araçlarla üretilir; bu depoya elle dosya konmaz.

Yapı (paketler eklendikçe):
```
rotalar.json            # rota listesi, sürüm ve parmak izleri
paketler/<rota>-<sürüm>.zip
```
