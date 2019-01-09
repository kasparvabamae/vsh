Project name: veebiserverite haldus

Installatin: 
Algelt otsisin iso debian 8.10 netish kui selle leitsin tegin virtuaalmasina: 
Virtuaalmasina nimi – vsh_kaspar_vabamae (kõik tähed on väikesed)
virtuaalketta maht – 8 GB 
operatiivmälu suurus – 1 GB
operatsioonisüsteem – Linux Debian – versioon 8.10

järgmiselt panin interneti valmis: Settings > Network > Attact to Bridge Adapter > Advance 
seal panin MAC Addressi oma arvuti numbri järgi
Minu arvuti number on 6 ja MAC Addressi sain 0800278CABB5.


Nüüd installisin debiani. 
panin hostname: vsh-kasparv
username: it
Partitioning method: Guided - use entire disk
Debian archive mirror: ftp.ee.debian.org
Software to install: SSH Server, Standard system untilities
Installisin GRUB boot loaderi
Device for boot loader: /dev/sda ata-VBOX HARDISK 

siis tegin ip a ja sain IP-ks: 172.23.13.42
