# EOSAPI
EOS Mainnet API URLs

# Mainnet chain_id

## aca376f206b8fc25a6ed44dbdc66547c36c6c33e3a119ffbeaef943642f0e906

# HowTo get available EOS api_endpoint & ssl_endpoint?

## 1. get BPs info
cleos -u https://api.eosnewyork.io system listproducers  
```
Producer      Producer key                                           Url                                                         Scaled votes
zbeosbp11111  EOS7rhgVPWWyfMqjSbNdndtCK8Gkza3xnDbUupsPLMZ6gjfQ4nX81  http://www.zbeos.com                                        0.0275//api.eosnewyork.io  system  listproducers -l 
eoscannonchn  EOS73cTi9V7PNg4ujW5QzoTfRSdhH44MPiUJkUV6m3oGwj7RX7kML  https://eoscannon.io/                                       0.0271
eoshuobipool  EOS5XKswW26cR5VQeDGwgNb5aixv1AMcKkdDNrC59KzNSBfnH6TR7  http://eoshuobipool.com                                     0.0270
eosnewyorkio  EOS6GVX8eUqC1gN1293B3ivCNbifbr1BT6gzTFaQBXzWH9QNKVM4X  https://bp.eosnewyork.io                                    0.0269
eosauthority  EOS4va3CTmAcAAXsT26T3EBWqYHgQLshyxsozYRgxWm9tjmy17pVV  https://eosauthority.com                                    0.0255
eosisgravity  EOS55HTTjoxVX1zVpW8pabxygBb1J3SEnG5D8D3y3KgrnSbLpELfE  http://eosgravity.com                                       0.0251
cypherglasss  EOS5rTrUiqvgu7YCVyKCeQ1QXA7Uo94FZhq7zKcNPqbrCP5u5fQXo  http://cypherglass.com                                      0.0247
eosliquideos  EOS4v1n2j5kXbCum8LLEc8zQLpeLK9rKVFmsUgLCWgMDN38P6PcrW  http://vote.liquideos.com/                                  0.0234
eoscanadacom  EOS5HYV7rWeRxpZMCooe8YHRFQHKK7ncdmmUMTe3wCMaY2EvyVzUx  https://www.eoscanada.com                                   0.0234
eosstorebest  EOS8FrjiXUDAFc8pSQkFejk1zRxyALnqPbYdJsqhAwKMya3tY7TaU  http://www.eos.store                                        0.0233
eosiomeetone  EOS5gS4ZtanRS2Jx4vpjAQaVNci3v65iZiGCgMr9DNwu67x2pt8Qd  https://meet.one                                            0.0232
cryptolions1  EOS5yHaUBwhpwFftNjADdVwBpCVybLPg5P3z7HpTbDGjUfpqwWSSf  http://CryptoLions.io                                       0.0230
eosswedenorg  EOS7SGSBsWhSob6TEric6u3TGodcc1uXFcqSrquJ3Etuqcbb3VnNY  https://eossweden.se                                        0.0230
eos42freedom  EOS4tw7vH62TcVtMgm2tjXzn9hTuHEBbGPUK2eos42ssY7ip4LTzu  https://www.eos42.io                                        0.0225
bitfinexeos1  EOS6sgKjHUFtY1XxxQaMDwfxBac6nDBibVzZHb8LFMVmvSjcCdDhE  https://www.bitfinex.com                                    0.0221
eosbeijingbp  EOS5dGpcEhwB4VEhhXEcqtZs9EQj5HeetuXDnsAGVHMXHAFdMjbdj  https://www.eosbeijing.one                                  0.0220
eosdacserver  EOS6VkageCqyz1X97n7E1JyjPoZu8HEX6CVujY5ABzk3fPyV3vzZK  https://eosdac.io                                           0.0214
helloeoscnbp  EOS79cHpaEittzgJWgj79tdRhgzLEWy8wXmmQ3fL7kkDjmYYiGNet  https://www.helloeos.com.cn                                 0.0211
eosasia11111  EOS76gG6ATpqfVf5KrVjh3f4JAa4EKzAwWabTucNQ4Xv2TmVAj9bN  https://www.eosasia.one                                     0.0209
teamgreymass  EOS4xurP5oZk4WvMUp9neKkw94DJ2iq48GtMD5Dff3GKe6krh2ctR  https://greymass.com                                        0.0209
argentinaeos  EOS7n4UUEDQRWeJ5UmCf9yqWXY5fsTtbo78HyYa5uBbM1xwa5DwRj  https://www.eosargentina.io                                 0.0205
libertyblock  EOS5jDCYph3hctKED9tHbe9L77q8JZToeuMnefMDdyfPkrb89FzSt  http://monitor.libertyblock.io                              0.0201
starteosiobp  EOS5mB5dYCpQTHUPBS8SJ52sidTY9t7QNsZ2wg1Nzo5a1jKQM3Qx4  https://www.starteos.io                                     0.0200
eosriobrazil  EOS7RioGoHQnhv2fJEiciP9Q7J8JgfJYFcyofVkmCqMop8Q1PzgqP  https://eosrio.io                                           0.0185
eoscafeblock  EOS7MAPWVuYcxNtc2n9e6WaEedEZd9thGVHn2Wpu2PoMhNiteTTqL  https://eoscafecalgary.com                                  0.0155
eosantpoolbp  EOS6F9hDeGD3unoq67N9pmLVXKvsLTqi7wx3Ly9kxq4fZB3qLTjcs  https://www.eosantpool.com                                  0.0155
eostribeprod  EOS6J5d6rwHJYPZnuv7KRrf5cekTf3atRTjMgbU1YMKuNnrgGvEdE  https://eostribe.io                                         0.0153
jedaaaaaaaaa  EOS5XP49jx9eJNQZjqvP7pfKNaAe5JmyAbPZMdsiqD61QQEExqUYe  http://www.eosjapan.org                                     0.0138
eosafricaone  EOS5HG6pV9FXK64uJSr2GPXfiBEk8GRRedZDcRVXw8mZNuQ51QdMW  http://bp.eosio.africa                                      0.0136
eosnationftw  EOS8PkNNBYU1xnbcjBUNm1mT6N68QiGvCDgPT97rqurLBEjDanSXK  https://bp.eosnation.io                                     0.0133
jrrcryptoeos  EOS7JR4vL3P2qgPwfMagZDqAtRLjB38qQCe6xw87gefVV73x85bsw  http://www.eosjrr.io/                                       0.0130
eosamsterdam  EOS8HDwgQnKMHAxzva9eyHsPeETv23JSQ6RRzQjJLvCsZ6b1ySgQo  https://eosamsterdam.net                                    0.0123
eosflytomars  EOS6Agpfp38bTyRjJDmB4Qb1EpQSq7wnEAsALXgXE7KFSzKjokkFD  http://www.bitmars.one                                      0.0121
eosyskoreabp  EOS7TjKVBkBcSmjsXF4jJfZ1QU9RqVHuBkkcHNJoEcHGR79CoLf2f  http://eosys.io                                             0.0120
eosbixinboot  EOS7QC1XfAtkYeLjbHQjcDWVqUsxuSJ3YRhNyG93VAv2u3uHopGVp  http://en.eosbixin.com                                      0.0115
eoseouldotio  EOS6SSA4gYCSZ3q9NWpxGsYDv5MWjSwKseyq25RRZexwj8EM6YHDa  https://bp.eoseoul.io                                       0.0113
sheos21sheos  EOS5nUybopuNRPp4Lgpt3BCxT3j2Zw3BftJha8gLbJFvMQBMC3ToL  https://sheos.org                                           0.0108
eosunion1111  EOS5YrPTWCKNHHLuntq13Q9X6M2CFCNGb21GqrcjUexqBBjxpCG7H  http://eosunion.io/                                         0.0105
eosgenblockp  EOS65tu7JUi74KL1JAffKYtMw6HRKnxD1LAxLBFoCvcdfBB9AMU8n  https://www.genesis-mining.com/eos                          0.0101
aus1genereos  EOS57ZyzVjoEG2bvzmYmmeiH8YnYtRudxNKxppx17q7Hg29F8tW4t  http://www.genereos.io                                      0.0094
eoslaomaocom  EOS8QgURqo875qu3a8vgZ58qBeu2cTehe9zAWRfpdCXAQipicu1Fi  https://eoslaomao.com                                       0.0093
blocksmithio  EOS6XVaKPQNJeyCdKXG3VbLD7VZZbah8jNQBafCySPgzEtnNiM7L8  https://eosblocksmith.io                                    0.0092
blockmatrix1  EOS6oNSm6QKnMBzJDHiA32KsEjSgKKt1nGdPYfc2wZU34HA9GjP9q  https://blockmatrix.network                                 0.0088
eosdublinwow  EOS5bjub7pm8H9WLMYW5ETSwfFKrEJpVWwiwK5knvGAqLVUjEpLxx  https://www.eosdublin.com                                   0.0086
eosnodeonebp  EOS6xcmB3LnUwcjFu55hKFQwX8EHWWerwbHyAs3VpaJmbBFp4bmDs  http://www.eosnodeone.io                                    0.0084
eosnairobike  EOS54UAELQVaMrc1y98W7KsfLbBchvsQg7FCEYpoiQLi5y1Gvyqcy  http://www.eosnairobi.io                                    0.0083
eosfishrocks  EOS4xAhqjLs5fsCzw7QsGYJtRDVo3t2xRFCHd7amGEWwhjSb5DPZT  https://eos.fish                                            0.0077
tokenika4eos  EOS8Src8Nd3EoJpewmPzSDjZP8A3iLuHky4itLqWwuCjPNdCztrVL  https://tokenika.io/                                        0.0075
oraclegogogo  EOS67BuVBFqC9wWw8NaDg7JZ3FseSg55Rvwh6NJQUehBhmEsHfmLh  https://oraclechain.io                                      0.0067
eossv12eossv  EOS7fv6nadePJBdCiWyR2Ldz5YWyzJGMBkEo47zUSWFttduQhHHaa  https://eossiliconvalley.io                                 0.0062
```
## 2. get bp.json
curl https://bp.eosnewyork.io/bp.json  
```
{
  "producer_account_name": "eosnewyorkio",
  "producer_public_key": "EOS6GVX8eUqC1gN1293B3ivCNbifbr1BT6gzTFaQBXzWH9QNKVM4X",
  "org": {
    "candidate_name": "EOS New York",
    "website": "https://www.eosnewyork.io",
    "code_of_conduct": "https://steemit.com/eos/@eosnewyork/eos-new-york-code-of-conduct",
    "ownership_disclosure": "https://steemit.com/eos/@eosnewyork/eos-new-york-ownership-disclosure-and-corporate-structure",
    "email": "community@eosnewyork.io",
    "branding": {
      "logo_256": "https://bp.eosnewyork.io/Logo_256.jpg",
      "logo_1024": "https://bp.eosnewyork.io/Logo_1024.jpg",
      "logo_svg": "https://bp.eosnewyork.io/eosnewyorkio.svg"
    },
    "location": {
      "name": "Cook Islands",
      "country": "CK",
      "latitude": -18.857952,
      "longitude": -159.785278
    },
    "social": {
      "steemit": "eosnewyork",
      "twitter": "eosnewyork",
      "youtube": "UCg7aeCSXUTP49w_elxgYIXA",
      "facebook": "eosnewyorkBP",
      "github": "eosnewyork",
      "reddit": "eosnewyork",
      "keybase": "d3ck",
      "telegram": "eosnewyorkchat",
      "wechat": "kevineosnewyork"
    }
  },
  "nodes": [
    {
      "location": {
        "name": "primary",
        "country": "BR",
        "latitude": -23.5505,
        "longitude": -46.6333
      },
      "is_producer": true,
      "p2p_endpoint": "node1.eosnewyork.io:6987",
      "api_endpoint": "http://api.eosnewyork.io",
      "ssl_endpoint": "https://api.eosnewyork.io"
    }
  ]
}
```
## 3. get p2p_endpoint and ssl_endpoint URL
http://api.eosnewyork.io  
https://api.eosnewyork.io

---
http://node1.zbeos.com:8888  
http://node2.zbeos.com:8888  
https://mainnet.eoscannon.io  
https://mainnet.eoscannon.io  
http://119.254.15.39:8888  
http://119.254.15.40:8888  
http://api.eosnewyork.io  
https://api.eosnewyork.io  
http://publicapi-mainnet.eosauthority.com  
https://publicapi-mainnet.eosauthority.com  
http://api-mainnet.eosgravity.com/  
http://api.cypherglass.com:8888  
https://api.cypherglass.com  
http://node2.liquideos.com:80  
https://node2.liquideos.com:443  
http://node2.liquideos.com:80  
https://node2.liquideos.com:443  
http://mainnet.eoscanada.com  
https://mainnet.eoscanada.com  
http://api.eos.store  
https://api.eos.store  
http://api.eos.store  
https://api.eos.store  
https://mainnet-us.meet.one  
https://mainnet-jp.meet.one  
https://mainnet-sg.meet.one  
http://bp.cryptolions.io:8888  
https://bp.cryptolions.io  
http://fn.eossweden.se  
https://fn.eossweden.se  
http://api.eosbeijing.one  
https://api.eosbeijing.one  
http://eu1.eosdac.io  
https://eu1.eosdac.io  
http://eu2.eosdac.io  
https://eu2.eosdac.io  
http://api.helloeos.com.cn  
https://api.helloeos.com.cn  
https://api.helloeos.com.cn  
https://api.helloeos.com.cn  
https://api1.eosasia.one/  
https://api1.eosasia.one/  
http://eos.greymass.com  
https://eos.greymass.com  
https://api.eosargentina.io:8888  
http://api-mainnet.starteos.io  
http://api-mainnet1.starteos.io  
http://br.eosrio.io:8080  
http://api.eosrio.io:8080  
http://mainnet.eoscalgary.io  
http://209.41.67.115:9115  
http://api.jeda.one:8888  
http://jhb.eosio.africa:8088  
http://cpt.eosio.africa:8088  
http://api.eosn.io  
https://api.eosn.io  
http://eu-west-nl.eosamsterdam.net:80  
https://eu-west-nl.eosamsterdam.net:443  
http://api.bitmars.one  
https://rpc.eosys.io:443  
http://mars.fn.eosbixin.com:80  
http://user-api.eoseoul.io  
https://user-api.eoseoul.io  
http://user-api.eoseoul.io  
https://user-api.eoseoul.io  
http://api.proxy1a.sheos.org  
https://lb1.sheos.org  
http://api2.eos.ren:8883  
http://api2.eos.ren:8883  
http://eos.genesis-mining.com:8443  
http://eos.genesis-mining.com:8443  
http://mainnet.genereos.io  
https://mainnet.genereos.io  
https://api.eoslaomao.com  
http://node0.eosblocksmith.io:8888  
https://node0.eosblocksmith.io:443  
https://eosapi.blockmatrix.network  
http://api1.eosdublin.io  
https://api1.eosdublin.io  
http://api2.eosdublin.io  
https://api2.eosdublin.io  
http://api.main-net.eosnodeone.io  
https://api.main-net.eosnodeone.io  
http://api1.eosnairobi.io:8898  
https://api1.eosnairobi.io:8899  
http://api2.eosnairobi.io:8898  
https://api2.eosnairobi.io:8899  
http://api.bp.fish  
http://api.bp.fish  
http://fn001.eossv.org:80  
https://fn001.eossv.org:444  

---

From  
https://docs.google.com/spreadsheets/d/1HLAIZ242dc0R8IcHnTRjVur4-wguQ6AjRxzXia-2esU  

---

https://api.superone.io  
http://13.230.91.225:8889  
https://api.mainnet.eospace.io  
https://fn001.eossv.org:444  
https://api.eoseco.com  
https://api.helloeos.com.cn  
http://api.mainnet.eos.cybex.io:28888  
https://mainnet.eoscannon.io  
http://api.eosthu.com:8082  
http://mars.fn.eosbixin.com:80  
http://mainnet-eos.wancloud.cloud:55588  
http://api.eos.store:80  
https://api.eos.store:443  
http://api.eosbeijing.one  
http://api.eospalliums.org:8888  
http://api.jeda.one:8888  
https://user-api.eoseoul.io  
http://user-api.eoseoul.io  
https://api.main-net.eosnodeone.io  
http://boot.eostitan.com:8889  
http://209.41.67.115:9115  
http://mainnet.eoswz.com  
http://mainnet.bepal.io  
http://mainnet.eosarabia.org:2052  
https://rpc.eosys.io  
https://api.eosio.cr  
https://api.eosio.cr  
https://api.eosdetroit.io:443  
https://eos.saltblock.io  
https://bp.geos.one  
https://eos-rpc.tc.ink  
