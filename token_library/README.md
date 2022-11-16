# Token Library
This repositorty will add custom token in metamask 

# How to configure and use 
copy or iclude this js library url in your code.
set following variables for your token:
tokenAddress,tokenSymbol,tokenDecimals and tokenImage in your code then call _addToken() function of library

# Example
1) First include js library
     ```<script src="token_library.js"></script>```
2) Use function
  ```function _addToken(){

        const tokenAddress = '0xc1A016C2c1aCa2F381dD14d3F0a5cDbe4c986F45';
        const tokenSymbol = 'ETH';
        const tokenDecimals = 18;
        const tokenImage = 'https://s2.coinmarketcap.com/static/img/coins/64x64/1027.png';
        
        addToken(tokenAddress,tokenSymbol,tokenDecimals,tokenImage);
  
    }```
