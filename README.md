# My customized wordlists with almost of all Finnish words.

kaikkisanat_muokattu.txt words contain also the suffix 1 - 12345678910 and 666.

sukunimet2022.txt contains almost all Finnish surnames.


## These lists contains Finnish words that can be used, for example, to crack captured wlan handshakes.
Typical scripts for cracking are Aircrack-ng, Wifite and Hashcat.
You can also use lists for online bruteforcing and password spraying.

After you have successfully recorded the WPA handshake you can use the commands:
- sudo wifite --crack --dict /path/kaikkisanat_muokattu.txt
or
- sudo hashcat -m 22000 -a 0 /path/name_of_your_handshake.hc22000 /path/kaikkisanat_muokattu.txt -w 4 --status

Attention! Do not cause harm to anyone's network!






