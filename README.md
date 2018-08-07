
# WBB smart contract

* _Standart_        : ERC20
* _Name_            : WBBС
* _Ticket_          : WBBС
* _Decimals_        : 18
* _Emission_        : Mintable
* _Crowdsales_      : 2
* _Fiat dependency_ : Yes
* _Tokens locked_   : Yes

## Smart-contracts description

Contract mint bounty and founders tokens after main sale stage finished. 
Crowdsale contracts have special function to retrieve transferred in errors tokens.
Also crowdsale contracts have special function to direct mint tokens in wei value (featue implemneted to support external pay gateway).

### Contracts contains
1. _WBBToken_ - Token contract
2. _Presale_ - Presale contract
3. _Mainsale_ - ICO contract
4. _Configurator_ - contract with main configuration for production
### How to invest
To purchase tokens investor should send ETH (more than minimum 0.1 ETH) to corresponding crowdsale contract.
Recommended GAS: 250000, GAS PRICE - 21 Gwei.

### Wallets with ERC20 support
1. MyEtherWallet - https://www.myetherwallet.com/
2. Parity 
3. Mist/Ethereum wallet

EXODUS not support ERC20, but have way to export key into MyEtherWallet - http://support.exodus.io/article/128-how-do-i-receive-unsupported-erc20-tokens

Investor must not use other wallets, coinmarkets or stocks. Can lose money.

## Main network configuration

* _Minimal insvested limit_     : 0.1 ETH
* _Price_                       : 1 ETH =  WBBС- pre sale
* _Bounty tokens percent_       : 5% 
* _Founders tokens percent_     : 15% 
* _Marketing tokens percent_    : 10% 
* _For sale tokens percent_     :  
* _Founders tokens wallet_      : 0x9C93e79E17Fb9B187E5Edf264c571081289E4814
* _Marketing tokens wallet_     : 0x47497893408D3a0f6F3cDb70EdfbdaB18b8e9EC7
* _Bounty tokens wallet_        : 0x535cc5A392D805e707086da7EAfF5C1bD2Ec3Ed9

### Links
1. Configurator -
2. _Deploi_ -
3. Transaction send 1 eth
### Referal system
* _Referer percent_ - 5%
* _Minimal investor value limit to activate referer bonus_ - 10 ETH
* _Limitations_ - Investor сan't accrue bonus to himself


### Value bonus system

* from 800000000000000000 wei,10;
  * from   4000000000000000000 wei, 15;
   * from  8000000000000000000 wei, 20;
    * from 40000000000000000000 wei,25;

### Crowdsale stages

#### Presale
* _Base price_                 : WBBС per ETH
* _Hardcap_                    : 42000000000000000000000 Wei
* _Period_                     : 65 days 
* _Start_                      : 28.01 2018 00:00:00 GMT
* _Wallet_                     :0x619B63f9b9aC6570AB86bc4fB232Ac04Bc47618E
* _Contract owner_             :0x41FEa3861abCd7c769feAe7E84c03E3C84A68174

#### ICO
* _Base price_                 :  WBBС per ETH
* _Hardcap_                    : 830000000000000000000000 Wei
* _Start_                      : 
* _Wallet_                     : 
* _Contract owner_             :

_Milestones_
1. 7 days                      : bonus +20% 
2. 7 days                      : bonus +15% 
3. 7 days                      : bonus +10% 
4.  days                       : bonus +0%


