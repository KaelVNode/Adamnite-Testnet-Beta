# Adamnite-Testnet-Beta

System Requirements - 5 core CPU | 8GB of RAM | 10GB of free HDD or SSD Space

### Instalation 
```
sudo apt update && sudo apt upgrade -y
```
```
sudo apt install make clang pkg-config libssl-dev libclang-dev build-essential git curl ntp jq llvm tmux htop screen unzip cmake -y
```

Karena repo bersifat pribadi, kami memerlukan token akses, untuk ini;

pengaturan -> pengaturan pengembang -> token akses pribadi -> token klasik -> buat token baru

```
git clone https://"access-token"@github.com/Adamnite/goAdamnite.git
```
```
cd goAdamnite/Ubuntu
```

```
chmod +x gnite
```
```
chmod +x gnite-test
```
```
./gnite account new
```
```
screen -S adamnite
```
```
./gnite
```


### Sending Transactions

Pastikan Anda berada di direktori goAdamnite/Ubuntu dan telah mendapatkan test token $NITE.

Periksa saldo Anda dengan

```
./gnite-test --balance "your public address"
```

```
./gnite-test --sendaddr "your address" --recaddr "the address you want to send coins to" --amount "the amount you want to send --password "your password"
```

### Staking

```
./gnite-test --sendaddr "your address" --recaddr "the account you want to stake your coins to (can be one of the public accounts listed in the beta testing channel)" --amount "the amount you want to send" --txtype true --password "your password"
```

Run ``./gnite-test -h`` for help and additional commands.

