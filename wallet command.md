To create a wallet run in linux cmd
./dero-wallet-cli-linux-amd64 --rpc-server --rpc-bind 0.0.0.0:10103 --daemon-address=148.163.68.4:9999

after wallet is created
./dero-wallet-cli-linux-amd64 --rpc-server --rpc-bind 0.0.0.0:10103 --rpc-login ourwalletname:yourpassword --wallet-file wallet.db --daemon-address=148.163.68.4:9999

to mine once wallet is created
./hansen33s-dero-miner-linux-amd64 -wallet-address="add your dero address" -daemon-rpc-address="stratum.crimsonfusion.org:10300"

