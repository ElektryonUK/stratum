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

* Move stratum file
```
sudo mv stratum /home/yiimp-data/yiimp/site/stratum/stratum_full
or 
sudo mv stratum /var/stratum/stratum_full
```

After run addport modify run.sh with stratum_full
```
sudo vim /home/yiimp-data/yiimp/site/stratum/config/run.sh
or
sudo vim /var/stratum/config/run.sh
