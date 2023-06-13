# ETG
# Güncellemeler
sudo apt-get update -y && sudo apt-get upgrade -y

sudo apt install -y build-essential libssl-dev cmake screen git htop

# Opside'ı yükleyelim
wget -c https://pre-alpha-download.opside.network/testnet-auto-install-v2.tar.gz 
tar -C ./ -xzf testnet-auto-install-v2.tar.gz
chmod +x -R ./testnet-auto-install-v2
cd ./testnet-auto-install-v2

# Genesisi yükleyelim:
wget -c https://pre-alpha-download.opside.network/testnet-auto-install.tar.gz 
tar -C ./ -xzf testnet-auto-install.tar.gz
chmod +x -R ./testnet-auto-install
cd ./testnet-auto-install
./install-ubuntu-en-1.0.sh
# Bu komutu girdikten sonra sırasıyla:
Cüzdan adresi

Şifre

Tekrar Cüzdan adresi

Tekrar şifre

Vereceği 12 kelimeyi alın, daha sonra sadece ilk 4 hafrlerini girin.
Node'umuz sync olduktan sonra (6-8 saat) buraya gidelim.

Upload deposit data'ya kadar okey diyin.

Daha sonra WinSCP ile /root/testnet-auto-install-v2/validator_keys/deposit_data klasörünü masa üstüne atın.

Upload edin.

Tüm tikleri işaretledikten sonra 25000 IDE'yı stake edin.

Kontrol:
