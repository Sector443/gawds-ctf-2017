# The All Mighty Blockchain [200pts]

Pristine wanted to meet her love MacBox so she sent him a message. NSA was able to get hold of that message on the Ropsten network at address - 0x53deb18d4ad930705980af05c2543bf92085b47c Can you decrypt it?


### Let's look at that address on ropsten.etherscan.io blockchain crawler

![alt screenshot1](https://github.com/Sector443/gawds-ctf-2018/blob/master/Ethereum/gawds_ropsten_eth.png "Screenshot 1")

We can see list of transactions on that address. First one seems failed. If we check second transaction which does not send any ether to destination but it has data in hex format. By clicking Convert to ASCII button we can see the flag.

flag{This_w@s_an_e@$y_one}

![alt screenshot2](https://github.com/Sector443/gawds-ctf-2018/blob/master/Ethereum/gawds_ropsten_eth_flag.png "Screenshot 2")

