# Stratum for YiiMP
with more then 100 algo support

## ▶️ Installation

Requires a YiiMP Server installation.

```
git clone https://github.com/msy2008/stratum-full.git
```

* Compile
```
cd stratum-full/iniparser
make
cd ..
make
```

* Move stratum file (msy2008 Yiimp Installer : https://github.com/msy2008/yiimp_install_scrypt)
```
sudo mv stratum /var/stratum/stratum_full
```

* Run as follows: For example, if you use the scrypt algorithm (copy the scrypt.conf file to the stratum folder)
```
./stratum_full scrypt
```
