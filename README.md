# piksel-terminal

Banner'larımızdaki piksel yazı tipini terminale getiren küçük bir Rust aracı. Yazdığın metni bloklarla büyük harflerle basıyor, istersen 256 renkli terminal rengiyle.

```
cargo run --release -- --renk 141 DEOKWAVE
```

Terminalin dar ise `--dar` ile her piksel tek karakter genişliğinde basılıyor.

Metni başka bir komuttan da verebilirsin: `echo SELAM | piksel-terminal --renk 81`.

Kullanımı unutursan `--yardim` yazman yeterli.

© 2026 Deokwave. Tüm hakları saklıdır.
