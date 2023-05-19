./aves-geth --datadir=/home/panda/.aves

./aves-geth --datadir /home/panda/.aves account new

0xB36D6cC2C8935eCeBcF9F64e45A6Ba11d634858A

./aves-geth --datadir /home/panda/.aves --networkid 33333 --port 30310 --http --http.port 9720 --authrpc.port 8780 --http.api personal,eth,net,web3,admin,txpool,debug --cache=8000 --maxpeers 100 --syncmode full --password /home/panda/.elh/.elh-pw --nat any --allow-insecure-unlock --snapshot=false --mine --miner.etherbase 0xB36D6cC2C8935eCeBcF9F64e45A6Ba11d634858A --unlock 0xB36D6cC2C8935eCeBcF9F64e45A6Ba11d634858A

./aves-geth attach /home/panda/.aves/geth.ipc

admin.addPeer("enode://...")



admin.peers <<< to show peers list

