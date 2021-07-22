# NYM-update-to-Milhon
1- wget -O nym_upgrade.sh https://api.nodes.guru/nym_upgrade.sh && chmod +x nym_upgrade.sh && ./nym_upgrade.sh

2- go to wallet https://testnet-milhon-wallet.nymtech.net/ create new wallet or use old one

3- nym-mixnode sign --id nodei --text "@telegramid Punkaddsess"   (İf you don't know your id use this code systemctl status nym-mixnode | grep id )


4- after that code you will see transfer address copy and paste this bot https://t.me/nympunkbot

5- https://testnet-milhon-wallet.nymtech.net/ back your wallet and in console past this code: journalctl -u nym-mixnode -o cat | grep Version: -B 6  you will see your bond codes paste it in your wallet to bond section and bond it 

6- journalctl -u nym-mixnode -o cat | grep "Since startup mixed" | tail -1

 After 2 minutes check if it start to mix
