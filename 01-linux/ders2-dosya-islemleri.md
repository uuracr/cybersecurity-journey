# Ders 2: Dosya işlemleri

- `touch dosya`: boş dosya oluşturur
- `echo "yazı" > dosya`: üstüne yazar
- `echo "yazı" >> dosya`: sonuna ekler
- `cat dosya`: içini gösterir
- `cp kaynak hedef`: kopyalar
- `mv kaynak hedef`: taşır ya da adını değiştirir
- `rm dosya`: siler (geri dönüşü yok)

# Hata notları

- `touch` tek başına yanlış, dosya adı lazım
- `cp not.txt` yanlış, `cp not.txt yedek.txt` doğru (kaynak + hedef)
- `rm not.txt ls` yanlış: `rm` arkasındaki her şeyi dosya sanır, komutları ayrı satırda yaz
