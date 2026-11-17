# Ders 3: Yardım ve arama

- `komut --help`: kısa yardım
- `man komut`: el kitabı (çıkış q)
- `grep kelime dosya`: arar (-i fark etmez, -n satır no, -c sayar)
- `find yer -name "*.txt"`: dosya arar

# Hata notları

- Tırnak kapatmazsam `dquote>` çıkar, Ctrl + S 
- `head -n 10` tek başına bekler, `komut | head -n 10` yaz
- `find ~ -name "*.txt"` doğru. `-name` sabit bir seçenek, yerine kendi kelimemi yazamam. Arkasına aranacak adı yazarım.
- `find ~ -isim "*.txt"` yanlış, `find ~ -name "*.txt"` doğru (seçenek adı sabit, `-name`)
