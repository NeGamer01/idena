1. download dan insatal aplikasi client idena

https://www.idena.io/download

2. Download file connect.bat (file untuk membuka putty dan idena secara otomatis)

https://bit.ly/3KUowhP
https://www.mediafire.com/file/rhhlcca4rigbka8/connect.bat/file

3. Edit file connect.bat

4. Install idena manager di vps :

nano a.sh

source <(curl -sL https://bit.ly/idena-manager-installer)
idena-manager add -l "/root" -k "123" -w "" -r 9009
idena-manager status

bash a.sh

5. Restore akun idena

Decrypt Private key menjadi node key

https://devkodev.github.io/IdenaDevTools/

idena-manager change-node-key 1

0x28d30c8ba34181eb081f07cae465c58f5a022c0c

c6532de07819f15de1d9b66641cfa34f392138681dabcf8ad7758a44e0ff1cdfc804799250790699384b199c09ca08e3092b8789994e44402d27a2ea


7b9002897c3235e3a6a04387fc06cf7de99970b93278d6c212c66c1c89b5b017


https://www.mediafire.com/file/65dw7qpwolfv7fq/Republic_Community.zip/file

https://forumsa-mp.blogspot.com/2021/08/install-gammodes-samp-in-vps-ubuntu.html?m=1
