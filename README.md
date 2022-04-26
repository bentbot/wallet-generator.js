# wallet-generator.js
Generate a number of different crypto coin Blockchain wallet private and public keys in pure Javascipt.
Forked from WalletGenerator.net JS Wallet Generator: https://github.com/walletgeneratornet/WalletGenerator.net

### Setup:
In raw HTML
````
    <script src="/assets/js/wallet-generator.js></script>
````
Or in Angular in your angular.json
````
    ...
    {
        "projects": {
            "app": {
                    "architect": {
                        "build": {
                            "scripts": ["src/assets/js/wallet-generator.js"]
                        
    ...
````
### Usage
JS / HTML:
````
      var address = get_address('bitcoin');
      console.log(address);
````
TS / Angular:
````
	declare function get_address(name): any;
	...
	
	generate(symbol,cb?) {
		var wallet = get_address(symbol.toLowerCase());
		if(cb) cb(wallet);
    		return wallet;
  	}
````
### Output:

````
	{
		"coin": 'BitCoin',
		"public": '17vGnniEqqezaKpdnRE2sUDF1Fr1aAzZD1',
		"private": '5KDxUKNFi3p5CXcHee588VV5b7F9QxCyN9PoaUUM95CF5pj9tMk'
	};
````
### Supported Coins:
Valid coin names you can use with the generator are:
- 2give
- 42coin
- acoin
- agacoin
- alphacoin
- alqo
- animecoin
- anoncoin
- apexcoin
- auroracoin
- aquariuscoin
- axe
- bbqcoin
- biblepay
- bitcoin
- bitcoin cash
- bitcoindark
- bitcore
- bitcoingold
- bitconnect
- birdcoin
- bitsynq
- bitzeny
- blackcoin
- blackjack
- blocknet
- bolivarcoin
- boxycoin
- bunnycoin
- cagecoin
- campuscoin
- canadaecoin
- cannabiscoin
- capricoin
- cassubiandetk
- cashcoin
- catcoin
- chaincoin
- colossuscoinxt
- condensate
- copico
- coppercoin
- corgicoin
- cryptobullion
- cryptoclub
- cryptoescudo
- cryptonite
- cryptowisdomcoin
- c2coin
- dash
- deafdollars
- deeponion
- deutsche emark
- devcoin
- digibyte
- digitalcoin
- dimecoin
- dnotes
- dogecoin
- dogecoindark
- egulden
- ekrona
- electra
- ember
- emerald
- emercoin
- energycoin
- espers
- fastcoin
- feathercoin
- fedoracoin
- fibre
- florincoin
- flurbo
- fluttercoin
- frazcoin
- freicoin
- fudcoin
- fuelcoin
- fujicoin
- gabencoin
- garlicoin
- globalboost
- goodcoin
- gridcoinresearch
- gulden
- guncoin
- hamradiocoin
- hfrcoin
- hodlcoin
- htmlcoin
- hyperstake
- imperiumcoin
- incakoin
- incognitocoin
- influxcoin
- innox
- iridiumcoin
- icash
- ixcoin
- judgecoin
- jumbucks
- khcoin
- kittehcoin
- lanacoin
- latium
- lbry credits
- litecoin
- litedoge
- lomocoin
- madbytecoin
- magicinternetmoney
- magicoin
- marscoin
- martexcoin
- masterdoge
- mazacoin
- megacoin
- mintcoin
- mobiuscoin
- monetaryunit
- monocle
- mooncoin
- myriadcoin
- namecoin
- navcoin
- needlecoin
- neetcoin
- nyc
- neoscoin
- nevacoin
- novacoin
- nubits
- nyancoin
- ocupy
- omnicoin
- onyxcoin
- paccoin
- particl
- paycoin
- pandacoin
- parkbyte
- peercoin
- pesetacoin
- phcoin
- phoenixcoin
- piggycoin
- pinkcoin
- pivx
- peercoin
- potcoin
- primecoin
- prospercoinclassic
- quark
- qubitcoin
- reddcoin
- riecoin
- rimbit
- roicoin
- rubycoin
- rupaya
- sambacoin
- seckcoin
- sibcoin
- sixeleven
- smileycoin
- songcoin
- spreadcoin
- stealthcoin
- stratis
- swagbucks
- syscoin
- tajcoin
- terracoin
- titcoin
- tittiecoin
- topcoin
- transfercoin
- treasurehuntcoin
- trezarcoin
- unobtanium
- usde
- vcash
- versioncoin
- vergecoin
- vertcoin
- viacoin
- vikingcoin
- w2coin
- wacoins
- wankcoin
- wearesatoshicoin
- worldcoin
- xp
- yenten
- zcash
- zetacoin
- testnet bitcoin
- testnet dogecoin
- testnet monetaryunit
- testnet pivx
- testnet wacoins
 
Warning: This software is provided as-is without warranty.
