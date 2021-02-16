Test date: 2021 Feb 15



## should check to make sure that the owner of the contract is the msg.sender
[link to test...](http://github.com/cds-amal/crypto-fpl/blob/34472c11912f7281a066bfa50cc485d67a6b6112/test/cryptoFPLCards.test.js#L24)

##### d1, tx: 0x6348b143b88b91e896e66a23078625de92b0b423fa540c091e92bab6a9778f0a

[SVG :telescope:]()


```plantuml
```



## should allow the leagueAdmin to pause the contract
[link to test...](http://github.com/cds-amal/crypto-fpl/blob/34472c11912f7281a066bfa50cc485d67a6b6112/test/cryptoFPL.test.js#L40)

##### d1, tx: 0x5d9bdfb44090e5165339d4233d6415dbc27bfe18adab299f43fa39e885e339f6

[SVG :telescope:]()


```plantuml
```

##### d2, tx: 0xa516503f5be63020db1fdc19cde3121e2491687bd0e92fe2b5d90b07ea6129ca

[SVG :telescope:]()


```plantuml
```



## should not let players call certain functions if the contact is currently paused
[link to test...](http://github.com/cds-amal/crypto-fpl/blob/34472c11912f7281a066bfa50cc485d67a6b6112/test/cryptoFPL.test.js#L46)

##### d1, tx: 0xf2e4a80a5b16ce7a9f021217b177bdd84ee66c4bcfc4dacef447a213b8da389f

[SVG :telescope:]()


```plantuml
```

##### d2, tx: 0x894e98b3bb8dfe8ce9ac9a04cadafdc268a4f1880593106e315ac324903d4a0e

[SVG :telescope:]()


```plantuml
```

##### d3, tx: 0xdc8ad2fa52a09656b1fa8b30d4037bd6bbb4360ea5d02f6217e7131caa09e9c1

[SVG :telescope:]()


```plantuml
```



## viewGameDetails() should return correct game details
[link to test...](http://github.com/cds-amal/crypto-fpl/blob/34472c11912f7281a066bfa50cc485d67a6b6112/test/cryptoFPL.test.js#L68)

##### d1, tx: 0x0bc98fb7e1f199b1e9cb24662edabe646acfb8bd297ea46d9ea3a70cece21679

[SVG :telescope:]()


```plantuml
```

##### d2, tx: 0x48efdf9658e34462685140d6d9f392f27ed45e1c79148bcaa9ee14338a22418b

[SVG :telescope:]()


```plantuml
```

##### d3, tx: 0x6958bc6df1e87757bd9a8e742e8cfc1fa5780a55a1ce0e7c67ac09e6607a6deb

[SVG :telescope:]()


```plantuml
```



## should let game creators deposit an initial wager into the game
[link to test...](http://github.com/cds-amal/crypto-fpl/blob/34472c11912f7281a066bfa50cc485d67a6b6112/test/cryptoFPL.test.js#L81)

##### d1, tx: 0xd999b84fbe106e18dac8018f3c37c3f3201ececf4201463905ebcb2f80484883

[SVG :telescope:]()


```plantuml
```

##### d2, tx: 0x8ac1b94af9f4ce6fe767993955a28e7ca307b78febd0b138d961f12dc44a45fa

[SVG :telescope:]()


```plantuml
```



## should let a second user enter a game if the game is still open
[link to test...](http://github.com/cds-amal/crypto-fpl/blob/34472c11912f7281a066bfa50cc485d67a6b6112/test/cryptoFPL.test.js#L88)

##### d1, tx: 0x5a60152fba38fc35b1646e0d3b6d21f26b0d9223b69780216f6c66cd7a6f4661

[SVG :telescope:]()


```plantuml
```

##### d2, tx: 0xf6429968bc791e611c1a6f3fa185d5300adbaf39f33843104a47105fb841b820

[SVG :telescope:]()


```plantuml
```

##### d3, tx: 0x116a822298f339decca9b3f07fe01a3792d8496cfec11d78ef5bcb8cc1692cb5

[SVG :telescope:]()


```plantuml
```



## should not let a third player into the game
[link to test...](http://github.com/cds-amal/crypto-fpl/blob/34472c11912f7281a066bfa50cc485d67a6b6112/test/cryptoFPL.test.js#L95)

##### d1, tx: 0xbec050ffe4abdd7e2a6158b88ea6bc1a396734e050db304e498b20b43499b305

[SVG :telescope:]()


```plantuml
```

##### d2, tx: 0x6bbc098a6c06450df234911cda26cb5849ebe1f4adc18689f2e55ea91918ba15

[SVG :telescope:]()


```plantuml
```

##### d3, tx: 0x3fbf473db64b9a41cc2f34e37e917dac305629a32f7cfdabee27373df14008d2

[SVG :telescope:]()


```plantuml
```

##### d4, tx: 0x2fdb10f698354a2b8ea26b2f8ce095948cdd1ca0f5a4929f15081da6526a9dff

[SVG :telescope:]()


```plantuml
```



## should not let a second user enter a game with less than the required deposit
[link to test...](http://github.com/cds-amal/crypto-fpl/blob/34472c11912f7281a066bfa50cc485d67a6b6112/test/cryptoFPL.test.js#L101)

##### d1, tx: 0x5ff9cd67a8008d3580af749e39de15ffb185d6e61738b7ea92f496f7ce21ac35

[SVG :telescope:]()


```plantuml
```

##### d2, tx: 0xde5658dda04bcc0def935586b94304f67fa22805d3379e24db0647eee6af28ba

[SVG :telescope:]()


```plantuml
```

##### d3, tx: 0xd3052f8e7a6f0406b8768435fa2e09441ead782bf590e1d93ea8b6033f1536a8

[SVG :telescope:]()


```plantuml
```



## should give refunds if second user deposits more than the stated wager
[link to test...](http://github.com/cds-amal/crypto-fpl/blob/34472c11912f7281a066bfa50cc485d67a6b6112/test/cryptoFPL.test.js#L106)

##### d1, tx: 0x95a7d9ad9bf6b9970215416abaef824efec2782b92a4742dd26258577bb9afea

[SVG :telescope:]()


```plantuml
```

##### d2, tx: 0xdd61ad3d20b77022be8fff684ee48d8f9ea63bd2af2ed51034f3753c6e81c248

[SVG :telescope:]()


```plantuml
```

##### d3, tx: 0xdc1030b98a0f319cea5dff0929cee544a73e52ea16853770b2351c091b68a956

[SVG :telescope:]()


```plantuml
```

##### d4, tx: 0x498314c653ceec7ec08cc8159f234821f4a0d67b9b686c691fe1ebfc4348358e

[SVG :telescope:]()


```plantuml
```



## should store the correct available payout for each game
[link to test...](http://github.com/cds-amal/crypto-fpl/blob/34472c11912f7281a066bfa50cc485d67a6b6112/test/cryptoFPL.test.js#L116)

##### d1, tx: 0xe6c93fdfa62cd83d2c588404f66f79f0577cc48a2487e89e3d409c29f5b97e4c

[SVG :telescope:]()


```plantuml
```

##### d2, tx: 0x3c4abe5b620cba087619beed05dc2a7054fe562a5a335f20764d9ea5b1b3a9a3

[SVG :telescope:]()


```plantuml
```

##### d3, tx: 0x2d2b61eab3bef3be2e03f77a67b5affa1fc14ccfc1a31bc1aa5917ecacdee02a

[SVG :telescope:]()


```plantuml
```



## should return the correct number of games that have ever been created
[link to test...](http://github.com/cds-amal/crypto-fpl/blob/34472c11912f7281a066bfa50cc485d67a6b6112/test/cryptoFPL.test.js#L123)

##### d1, tx: 0xff364b544548aab9052f583e2416fb582aabfab7dfa50ca96c4495de639c15ec

[SVG :telescope:]()


```plantuml
```

##### d2, tx: 0xdb05c4f4ca6c02e4e32292578985b8073a8d6b072b4c27f517498706492503d8

[SVG :telescope:]()


```plantuml
```

##### d3, tx: 0x6cb8db164d84adb9e308af49e5108705fcf15c71796b33f8fb8ec270cd1307d8

[SVG :telescope:]()


```plantuml
```

##### d4, tx: 0x6b98e8b76f32124ff4c0b9eec42351d6c8db094015f7c01b449254bc1721bf7f

[SVG :telescope:]()


```plantuml
```

##### d5, tx: 0x988ba47de6be700ba0abf02848812ee33dd5fdf51c47ffecb3963bdf56713678

[SVG :telescope:]()


```plantuml
```

##### d6, tx: 0x3cb9c6825cec8159510f7f79da88570674a4a3d2fbca6874c6d34519e2763247

[SVG :telescope:]()


```plantuml
```

##### d7, tx: 0x50c9b7851dbcd0f9b47a73f5413f2e254aca4a3582fdbe74020a009c98b16243

[SVG :telescope:]()


```plantuml
```

##### d8, tx: 0x3d2a04a930560cd9d2be4f1e8fe408c4707a91656bde8c40a47db312b94c8c16

[SVG :telescope:]()


```plantuml
```

##### d9, tx: 0x4929c5d10cddf481fefc725f7550461f70f780c832e993cb22b9a920d25872f2

[SVG :telescope:]()


```plantuml
```

##### d10, tx: 0x33bfdf16ccaaa340fdb3c61905b6034d389f233d93a78b697f2333fa8f90e3fb

[SVG :telescope:]()


```plantuml
```

##### d11, tx: 0xab416dff4e8ef9612bb9e321631aeaa43789f9ffda9f9e4e7abae388d1707ea4

[SVG :telescope:]()


```plantuml
```

##### d12, tx: 0xced00a8346732fe72dedac08a44ad84ab69a4bf572d8534be581a7327d0a5108

[SVG :telescope:]()


```plantuml
```

##### d13, tx: 0xe452cdae1e21058dfd159d5f5cbf74d91d604a166123b6000dc4c2093d5f3954

[SVG :telescope:]()


```plantuml
```



## should not let players create more games if they already have 3 open games
[link to test...](http://github.com/cds-amal/crypto-fpl/blob/34472c11912f7281a066bfa50cc485d67a6b6112/test/cryptoFPL.test.js#L131)

##### d1, tx: 0x38c0d02b0078bc6f23c828f0386b0470e6cafa8973b0e34787b250a1ad18ba8a

[SVG :telescope:]()


```plantuml
```

##### d2, tx: 0xadb11a057da902f58b647f651c23570157f22bbb2f0775f094891f7c2ecd8914

[SVG :telescope:]()


```plantuml
```

##### d3, tx: 0x1399fe09a47053558ef523bb0eb52ff4eac69b98da56dd3c72c17b4e2891b315

[SVG :telescope:]()


```plantuml
```

##### d4, tx: 0xac6bb62b2fbc30c7e4a58daac0c2ac023b07e69c28728a6f877e018690f63075

[SVG :telescope:]()


```plantuml
```

##### d5, tx: 0xb1275f3a0cafaf2a490b44656f2c596135d610fd92ba137465c5547112545c3d

[SVG :telescope:]()


```plantuml
```



## should emit events for games that the player is currently active in
[link to test...](http://github.com/cds-amal/crypto-fpl/blob/34472c11912f7281a066bfa50cc485d67a6b6112/test/cryptoFPL.test.js#L142)

##### d1, tx: 0x567ef6f0140294dcad1dcb8b9345fab63ac496eaa9ac02d74e54e37b46ba1870

[SVG :telescope:]()


```plantuml
```

##### d2, tx: 0x7a65dcf6771f916dbc18a936a74fe7fac97262ca3c11207d6a590b96c9e34b01

[SVG :telescope:]()


```plantuml
```

##### d3, tx: 0xd990650a150b785e7f7ff3075f6952b548992d9f4742bbbf232dd15a87f022a3

[SVG :telescope:]()


```plantuml
```

##### d4, tx: 0x4f81d5871bb9c46e64845f5a5e29e0e4d81ac717864dd5f95b2471f7163cb058

[SVG :telescope:]()


```plantuml
```

##### d5, tx: 0x38a373f1434dd7f5d28ae0fe33084385dd73950ff4273f50d89306bef277bbdd

[SVG :telescope:]()


```plantuml
```



## should let users commit their selected team
[link to test...](http://github.com/cds-amal/crypto-fpl/blob/34472c11912f7281a066bfa50cc485d67a6b6112/test/cryptoFPL.test.js#L157)

##### d1, tx: 0x65ec62cde3ed1be3ef6f7fda392c3fe34872d27d903cddb78c593084e2fa9710

[SVG :telescope:]()


```plantuml
```

##### d2, tx: 0x2ee7acbd6fd2ad166439042acf4c358925b392d366b92aedeb0abc9640233b24

[SVG :telescope:]()


```plantuml
```

##### d3, tx: 0x3ad234350cf57a6d96555bfa02213009f8d34de7d887f9d901ed24ba7adf9651

[SVG :telescope:]()


```plantuml
```

##### d4, tx: 0xfad7db226c3a640a71da817f83cdea79e4794a6047cb32cebba7a6a7fa14a67b

[SVG :telescope:]()


```plantuml
```

##### d5, tx: 0x047bb805d521897f71b30a605d53f436f3afdc2613dc807bdb66d9a0bd6d2069

[SVG :telescope:]()


```plantuml
```



## should let users reveal their selected team if the submitted hashes are valid
[link to test...](http://github.com/cds-amal/crypto-fpl/blob/34472c11912f7281a066bfa50cc485d67a6b6112/test/cryptoFPL.test.js#L178)

##### d1, tx: 0xe58cb90d014f183f418124eeb39b674dfd788923d27b79452df90c4ea4550e13

[SVG :telescope:]()


```plantuml
```

##### d2, tx: 0x50ce6b92c23f3d7d9e45fadd4bc7bfb41bddeb17270f339202aed3c537f6a3bb

[SVG :telescope:]()


```plantuml
```

##### d3, tx: 0xda1033925c1add86c30505c76143e1f4eb62fc134354cc3237339088342966b6

[SVG :telescope:]()


```plantuml
```

##### d4, tx: 0x30c49f0e1f80f929849c827395553fa366a6f8cabcebfc318fba7af2b1f529f9

[SVG :telescope:]()


```plantuml
```

##### d5, tx: 0x9c01c526bdb6fc4624f732dd63c90d1bc063796b633cf01093188bcfd22ee049

[SVG :telescope:]()


```plantuml
```

##### d6, tx: 0x4aa2640a1162b1be4e949b80d7d261b04f704150cd218f6662d6cf544abb6b7e

[SVG :telescope:]()


```plantuml
```



## should not let player reveal their team if revealHash is not valid
[link to test...](http://github.com/cds-amal/crypto-fpl/blob/34472c11912f7281a066bfa50cc485d67a6b6112/test/cryptoFPL.test.js#L196)

##### d1, tx: 0xb4fc796c6087dc838d11739ffa43c237d22c6d8a7c75647abd6d27b6937ccd48

[SVG :telescope:]()


```plantuml
```

##### d2, tx: 0xdae905f42d20ea2887e9fd96b77c15234a4855f52c54c8dc3826cb0fa3fc6ba7

[SVG :telescope:]()


```plantuml
```

##### d3, tx: 0x5193acf954716eb0d68e667b590dd8e7ff68275aef421321af38f6e6480973ca

[SVG :telescope:]()


```plantuml
```

##### d4, tx: 0xa68b0c7484ddd2e3028c3960e172b3d3f54bfe645866654191c06aa6b536fdbb

[SVG :telescope:]()


```plantuml
```

##### d5, tx: 0x352f2e7b60969ce2258c43b1c10a3ed0d7eb13e1efc79cbf78c83277dded9955

[SVG :telescope:]()


```plantuml
```

##### d6, tx: 0x377b53d99c2885ae4803387a468c8bc3d7f92e812ed30c281aca71d3a52e845d

[SVG :telescope:]()


```plantuml
```



## should record the player score upon team reveal
[link to test...](http://github.com/cds-amal/crypto-fpl/blob/34472c11912f7281a066bfa50cc485d67a6b6112/test/cryptoFPL.test.js#L220)

##### d1, tx: 0x2d8eea28251fa683e3e9daee16ca4852ff476ec5d138e9e21effb67ae7662a66

[SVG :telescope:]()


```plantuml
```

##### d2, tx: 0x3a547a9fb28ee583f86321e977b960a854e3da0106e41beae7683c63ce662a80

[SVG :telescope:]()


```plantuml
```

##### d3, tx: 0x24ae3eeedd4f0af7810c281af1b170414cf5f247a384199309e30719bf19fa98

[SVG :telescope:]()


```plantuml
```

##### d4, tx: 0x60f8d91e75110159a48cc7a37404b2f31399b22e27b1a7730d4dde2d094e8ac4

[SVG :telescope:]()


```plantuml
```

##### d5, tx: 0xb1566686edfc33a7b246525d7724e1f64296c365c885d9bfa1e91d5f4511a21e

[SVG :telescope:]()


```plantuml
```

##### d6, tx: 0xeae5940c9122dcc559e868a10661c9526d03e0cc458d7ba6e6588e1e32069d68

[SVG :telescope:]()


```plantuml
```

##### d7, tx: 0x16217efb084313af651a7aa8e0f1de7f5252f22782eb11dbba920a865b19d09e

[SVG :telescope:]()


```plantuml
```

##### d8, tx: 0xdbcf32a0613d55b849d27ef92ed2712829399a51b8572b4e4a9cdc69458aebd1

[SVG :telescope:]()


```plantuml
```

##### d9, tx: 0xb479e5c1a88a828f38cbcdb86a45bdfb22de193a7c09af7c32530ea412c35dac

[SVG :telescope:]()


```plantuml
```

##### d10, tx: 0xcc71413c7e89f9a0b2ba176373ee444cf2ddb9aa18ed8118d101b4ef5c4ff398

[SVG :telescope:]()


```plantuml
```



## should return the correct final score for a player once they have revealed their team
[link to test...](http://github.com/cds-amal/crypto-fpl/blob/34472c11912f7281a066bfa50cc485d67a6b6112/test/cryptoFPL.test.js#L257)

##### d1, tx: 0xfef3cac4b4ec3ecc8c9f150108d9eb32c4a09f631523847a196f9fe1dc49770d

[SVG :telescope:]()


```plantuml
```

##### d2, tx: 0x8a349d02f14587f0199a6713698e04864c55f3c85cdbcddeb15264d169a0f864

[SVG :telescope:]()


```plantuml
```

##### d3, tx: 0x5ba293c00990531e8e64db7bbd87ca8ef9f87a005be7bf03d7bbca9b0fbae02e

[SVG :telescope:]()


```plantuml
```

##### d4, tx: 0x65f4bc37e15a21e46c3c3d906fc37c43eea8de6597737efbfc815a5ea79d25e7

[SVG :telescope:]()


```plantuml
```

##### d5, tx: 0x87e679a5afbb8b0efe9417a1713cbed36b00fa3da1fe011228f6d3fc252518d9

[SVG :telescope:]()


```plantuml
```

##### d6, tx: 0x8a6fc39c880a24521ac4925f5ef478ad0b33a35aa2dc66490441c93cce656597

[SVG :telescope:]()


```plantuml
```



## should allow winner to withdraw the payout
[link to test...](http://github.com/cds-amal/crypto-fpl/blob/34472c11912f7281a066bfa50cc485d67a6b6112/test/cryptoFPL.test.js#L292)

##### d1, tx: 0xf230cc883964e8c773cb713499a562ef13d1900d489418845dabd7d493aa17ef

[SVG :telescope:]()


```plantuml
```

##### d2, tx: 0x905ed34fcf6085710c08f5e7fd97b7fba774a1f7b727df043d37b450f9e60865

[SVG :telescope:]()


```plantuml
```

##### d3, tx: 0xf5d8774fff8934a161ac65bdf6e031d2a43f7fd03b480f9ad3343bee1aa68d78

[SVG :telescope:]()


```plantuml
```

##### d4, tx: 0xa0c68081aa7ef37770e19e1f9d72845a83fe7daa7e2f62a7dfd137a57234d7f0

[SVG :telescope:]()


```plantuml
```

##### d5, tx: 0xc3af19db0941990277886139b14a9026b9165de0cc056f006c6b9f04748d79d0

[SVG :telescope:]()


```plantuml
```

##### d6, tx: 0x9811a7ddbcc739506551d0f348429fd4ebb9f18e3318bf6f09cb6cb0c4bd8169

[SVG :telescope:]()


```plantuml
```

##### d7, tx: 0xb04c73191f4c18741c1414537c0299e949ce6e0ca81e0ecc6e04834b7f988e65

[SVG :telescope:]()


```plantuml
```

##### d8, tx: 0x56c3e69d5cab9b6cf39d225299eb967a40d4451141e3416af87c2b9da0626fe0

[SVG :telescope:]()


```plantuml
```

##### d9, tx: 0x7b4749d09586c2699d56bf0447cdfd5035cd38062c57324b1bde76737d16f2c9

[SVG :telescope:]()


```plantuml
```

##### d10, tx: 0xb719e456b52bef5c7173b98af1faa0c5bf8de9c7036e06eca85a307dfaa986b3

[SVG :telescope:]()


```plantuml
```

##### d11, tx: 0x1e996c43c3698ee7f33a68ce6be71a6aaa2544845f12e30d839ced8eedfb8f34

[SVG :telescope:]()


```plantuml
```



## should not allow payout withdrawal if player has not won
[link to test...](http://github.com/cds-amal/crypto-fpl/blob/34472c11912f7281a066bfa50cc485d67a6b6112/test/cryptoFPL.test.js#L328)

##### d1, tx: 0xa3ecd527fec7916e1c80e100d4035481d3d91ab6c058f51f6737643642bbaedc

[SVG :telescope:]()


```plantuml
```

##### d2, tx: 0x414c9f961708fb5d440189f08dba3a19232e2cf6f3d71a9b7564a2525473099c

[SVG :telescope:]()


```plantuml
```

##### d3, tx: 0x8f7f98e98b0eb85a0323ce1d19bf82a9240943c6967cd7bebdf6d71f37db8011

[SVG :telescope:]()


```plantuml
```

##### d4, tx: 0x5a6acc4481dad577f84426a550e1441230bfeea0e0684693f260a4347f884fe4

[SVG :telescope:]()


```plantuml
```

##### d5, tx: 0x5c130c2a173996def60482cdda987c470b9d4c6a0dab7b609dd6726ceba1b7e7

[SVG :telescope:]()


```plantuml
```

##### d6, tx: 0xdad9e168f94af75f8dfec8390f5b0540ee6baafdfb49fe609b31220a29096c38

[SVG :telescope:]()


```plantuml
```

##### d7, tx: 0x8ebf9ce395fa0bd18c5acddfb87fcb38f6eaa8d7b5ce3d4564ac065b73dc4638

[SVG :telescope:]()


```plantuml
```

##### d8, tx: 0x5f784d495b417a42c0ab4d3876525e79b55ee0c7df23afb34ffa12a0164990d3

[SVG :telescope:]()


```plantuml
```

##### d9, tx: 0x75b0a691533cc81e35b0b65414dff5eb5dadb8918e4a9c8bd89585ac88195b08

[SVG :telescope:]()


```plantuml
```

##### d10, tx: 0xa67c2a0dc6ce029644005fe1e09640acf9ad9724fc20417f4f9782dc703343b8

[SVG :telescope:]()


```plantuml
```

##### d11, tx: 0xeeed11a8977113669b2bb566463a0e6c36e5949bab362c03eb0e32da8bef2060

[SVG :telescope:]()


```plantuml
```



## should check to make sure that the owner of the contract is the msg.sender
[link to test...](http://github.com/cds-amal/crypto-fpl/blob/34472c11912f7281a066bfa50cc485d67a6b6112/test/cryptoFPLCards.test.js#L24)



## should have the correct contract name and symbol
[link to test...](http://github.com/cds-amal/crypto-fpl/blob/34472c11912f7281a066bfa50cc485d67a6b6112/test/cryptoFPLCards.test.js#L29)



## should mint a team to a user if given sufficient payment
[link to test...](http://github.com/cds-amal/crypto-fpl/blob/34472c11912f7281a066bfa50cc485d67a6b6112/test/cryptoFPLCards.test.js#L42)

##### d1, tx: 0x81f1b8646792e36f556246e4358bf35fd315ee659d11e348b6449e2d57aca518

[SVG :telescope:]()


```plantuml
```



## should return the correct position of a footballer once initialized
[link to test...](http://github.com/cds-amal/crypto-fpl/blob/34472c11912f7281a066bfa50cc485d67a6b6112/test/cryptoFPLCards.test.js#L55)

##### d1, tx: 0xdf2a88debb02f22acf217d20974250332b8f49bee21c9c4d5d86aebc0e3df8fb

[SVG :telescope:]()


```plantuml
```



## should give a list of footballers that a user owns
[link to test...](http://github.com/cds-amal/crypto-fpl/blob/34472c11912f7281a066bfa50cc485d67a6b6112/test/cryptoFPLCards.test.js#L68)

##### d1, tx: 0x8ba7c33617bcaf618654f441ca85f81800bf7c2114a445cc2f97ca2c7cf1c0f2

[SVG :telescope:]()


```plantuml
```



## should check to make sure that the owner of the contract is the msg.sender
[link to test...](http://github.com/cds-amal/crypto-fpl/blob/34472c11912f7281a066bfa50cc485d67a6b6112/test/cryptoFPLCards.test.js#L24)



## should have the correct contract name and symbol
[link to test...](http://github.com/cds-amal/crypto-fpl/blob/34472c11912f7281a066bfa50cc485d67a6b6112/test/cryptoFPLCards.test.js#L29)



## should mint a team to a user if given sufficient payment
[link to test...](http://github.com/cds-amal/crypto-fpl/blob/34472c11912f7281a066bfa50cc485d67a6b6112/test/cryptoFPLCards.test.js#L42)

##### d1, tx: 0x8ea1e368af10224a863f8dd52df47ea4dd6b2fb6f98270c3d5033f8d93548dd9

[SVG :telescope:](https://www.planttext.com/api/plantuml/svg/tPTHRzCm4CVV_IbEumN41exjfCaq9hgsOPD0cw0I3mnLRknqqL8dSXnOeNntBbrMji5Wj20g8YLExVFr_h-SaZj2dbTEMbTFSq9axGfJJyVQakeyCwMqSWgvdcYZ3cHoFh55RLIlo0iB3-91FEWD2Dcht2pN-mGMnvcMIblutFu4E2nizgamJkRTF9kOgJOEFQPkQH3ZugNBihPbhcyilCa-QV34Skv4AfMP2NYqdVgo6FUUja6Gzl-FJ9LDpbm5unaCRPscw9UupEKQXXS63cLrjWlq8jJIqpm8PUfHneGC0vw6IlbCfQAZfL0g6BDq7AHHo3equSgdlB68k2_GBYA8B74O-k2u2xA2BHot269pMPAL4gNsxAnqHNpoiYUjgaRKMvXzDxj5o68lxEp_Q1KUFzw5QMRSKClfmrDpIlPQ_jljk3z_1cvMQi3HoEbY_23p6cyQypaWEAkh2kOmAZuQH3H7_MdOuUbOoBx7-ufJBgJdYsuKH77K2pfn5DAmwmUfltHYhPpXpamrZjw1jmri6_Ws27X_swRCvKpRawBAN5QONzlBAIQNMzfv54yVxUcLwIFuZBFjyOJ2YxU38tp-FyBr4ueZ134iphMfXiNQ95sn5aRSZu4StGcpKRoQqfsTNVXjCcFfahDNc6N_dCjzycjqhuHPFL5GpceSQYJOv7E3uDRS64_lJppRrzhLri1Q0LwBPMFOq4s2GpUDZhz9TFmDeyCsANVOAhcpqakxBfLq-kepkrRSxTVestjXkLAsxl_KwsipLBAxLRB_HoM_MoN_VrIAkrMAlwhoicflBCXbeqHEhfN_IZkPvTKrWNtQn_Ar4OZz4FO2UDF3HiTY7x6Kshsgf9RxzkUB5WEl5qvR8_Dy1iTOnYle9abJ1YtgBK4zlnCprezu6WVzW_GW3ZmzPaoAJXXoYIk3e7EGtdJyVOjoUsxXFEu87lRzL50Q3XB6kYnAkGmYpONoeyWV-8dmM1IXSwJGiY3FyOgjvLS0)


```plantuml


@startuml

autonumber
skinparam legendBackgroundColor #FEFECE

<style>
      header {
        HorizontalAlignment left
        FontColor purple
        FontSize 14
        Padding 10
      }
    </style>

header Insights by Truffle

title Txn Hash: 0x8ea1e368af10224a863f8dd52df47ea4dd6b2fb6f98270c3d5033f8d93548dd9


actor EOA as "EOA"
participant CryptoFPLCards_01 as "CryptoFPLCards_01"

"EOA" -> "CryptoFPLCards_01" ++: mintTeam(\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| address | _owner | 0xf873fb4aD13Dd3034a154A969F9C67F9808A56f5 |\n\
| array | ids | [ 1, 2, 3, 4 ] |\n\
| array | playerPositions | [ 1, 2, 3, 4 ] |\n\
| array | amounts | [ 1, 10, 15, 20 ] |\n\
) { 100000000.0 GWEI }
"CryptoFPLCards_01" -> "CryptoFPLCards_01" ++: _addTokensTo(\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| address | _to | 0xf873fb4aD13Dd3034a154A969F9C67F9808A56f5 |\n\
| array | _tokenIds | [ 1, 2, 3, 4 ] |\n\
) { 0.0 GWEI }
"CryptoFPLCards_01" -> "CryptoFPLCards_01" --: 
"CryptoFPLCards_01" -> "CryptoFPLCards_01" ++: _batchMint(\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| address | _to | 0xf873fb4aD13Dd3034a154A969F9C67F9808A56f5 |\n\
| array | _ids | [ 1, 2, 3, 4 ] |\n\
| array | _amounts | [ 1, 10, 15, 20 ] |\n\
) { 0.0 GWEI }
"CryptoFPLCards_01" -> "CryptoFPLCards_01" ++: add(\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| uint | a | 0 |\n\
| uint | b | 1 |\n\
) { 0.0 GWEI }
"CryptoFPLCards_01" -> "CryptoFPLCards_01" --: Return (\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| uint |  | 1 |\n\
)
"CryptoFPLCards_01" -> "CryptoFPLCards_01" ++: add(\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| uint | a | 0 |\n\
| uint | b | 10 |\n\
) { 0.0 GWEI }
"CryptoFPLCards_01" -> "CryptoFPLCards_01" --: Return (\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| uint |  | 10 |\n\
)
"CryptoFPLCards_01" -> "CryptoFPLCards_01" ++: add(\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| uint | a | 0 |\n\
| uint | b | 15 |\n\
) { 0.0 GWEI }
"CryptoFPLCards_01" -> "CryptoFPLCards_01" --: Return (\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| uint |  | 15 |\n\
)
"CryptoFPLCards_01" -> "CryptoFPLCards_01" ++: add(\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| uint | a | 0 |\n\
| uint | b | 20 |\n\
) { 0.0 GWEI }
"CryptoFPLCards_01" -> "CryptoFPLCards_01" --: Return (\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| uint |  | 20 |\n\
)
"CryptoFPLCards_01" -> "CryptoFPLCards_01" --: 
"CryptoFPLCards_01" -> "CryptoFPLCards_01" ++: _updatePosition(\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| uint | tokenId | 1 |\n\
| uint | position | 1 |\n\
) { 0.0 GWEI }
"CryptoFPLCards_01" -> "CryptoFPLCards_01" --: 
"CryptoFPLCards_01" -> "CryptoFPLCards_01" ++: _updatePosition(\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| uint | tokenId | 2 |\n\
| uint | position | 2 |\n\
) { 0.0 GWEI }
"CryptoFPLCards_01" -> "CryptoFPLCards_01" --: 
"CryptoFPLCards_01" -> "CryptoFPLCards_01" ++: _updatePosition(\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| uint | tokenId | 3 |\n\
| uint | position | 3 |\n\
) { 0.0 GWEI }
"CryptoFPLCards_01" -> "CryptoFPLCards_01" --: 
"CryptoFPLCards_01" -> "CryptoFPLCards_01" ++: _updatePosition(\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| uint | tokenId | 4 |\n\
| uint | position | 4 |\n\
) { 0.0 GWEI }
"CryptoFPLCards_01" -> "CryptoFPLCards_01" --: 
"CryptoFPLCards_01" -> "EOA" --: 

legend
Participant details
<#FEFECE,#D0D000>|= Alias |= Contract name |= Address |
<#FEFECE>| EOA | Externally Owned Account | 0x40157F22D93fF6DBfBF61eb22a47883a22DE67Bf |
<#FEFECE>| CryptoFPLCards_01 | CryptoFPLCards | 0xF7438D5f4008Ec22A29f3a69e34d5995E5c41299 |
endlegend

@enduml
```



## should return the correct position of a footballer once initialized
[link to test...](http://github.com/cds-amal/crypto-fpl/blob/34472c11912f7281a066bfa50cc485d67a6b6112/test/cryptoFPLCards.test.js#L55)

##### d1, tx: 0xcfadfc803eb05715b821b9d3bc88750c70281d07f236428b1c64963b26ebade2

[SVG :telescope:](https://www.planttext.com/api/plantuml/svg/xPTjRzCm4CVV-rESnXiG7SJEypIgzI5baq2he18l6AgSnEcYfKxaEB1kvRjpwR9gwnw0TcXeMjJ6gNrtyV-NKtD7o5wfkTBLD2E4LpgNrJGKYfGdgIouubF8n4J8kCkZaudAAndtyYnNy68G389UGCXkgMUPQ1DO7CU2nqB1UVCJO3zNwLakDSywMJgHKo4rHapqqc20YnSXYqeLcRYsy3az4q2jvToGnt4g9q2DPkhdOjnzsso2DFS_a6KwETObX3COgIf9C2xHgSu4Z4ubxFFoU0UCqoZXSH9vXYb2mtQf7NgCXdviXf7dkROHkGRpQ6ou2JCTYtaXZHpBTyoGEIB4-p22o2ADMmyEEy1BsC9nYo0sdKPfmL5gJyqAdG-67tfSnUNOe0kp6xDRX2nyORjzsogyVhq3qrJgaU3JbqVoYEms_5lDs9w_0pqh1E0e-NGnVkTPXHUr-HmGd19b2NCOvpya8fgZ_g1h2XOoPfg6BmnFkDHrBS4fjJqHcbQF2HRu3lMNGPJYC_HCuphGLw1s2nXjWUctmBVWswfTaV6PKCEyJ7MQoyO7NT2Z1RVOyoacc5xQDPzBkrTmZW--ETuOyFvBS809S1klUp2EaSGeFn6o7EKRezJvHXpH7pToS2_DMlLwQhUtT-2lwOHSHySVCTKUdSsV9jduzrcpVhQWdlL0L8YmpkYQmSfSY5_w40_taz2Lah3H1g_ivPdDCvjdDe_7Pgt_wwg8kHQNhzYDjjsyZEhTsojBHHF_eIZ_7p8PlLicUpeoJVzkcURJaOcrmPqohNygyw9ohot8HRD4XbTQW5XedcRb5OLzeuyLRAqGUoBi1_2YXysEmbvYgRLpMKWj_ThpHPk1vrCjbEHPDeD3BELZw4HHNG4joYtBeBOxOAplcyd0wNUJxi2X0kilRhcUPt9S2HotcrmFVBDDMPrR11-ubkdrxSGo32-86EimFp6vumlJYctVjmCxiYZpCTy8KcXOa3qyOtlv2m00)


```plantuml


@startuml

autonumber
skinparam legendBackgroundColor #FEFECE

<style>
      header {
        HorizontalAlignment left
        FontColor purple
        FontSize 14
        Padding 10
      }
    </style>

header Insights by Truffle

title Txn Hash: 0xcfadfc803eb05715b821b9d3bc88750c70281d07f236428b1c64963b26ebade2


actor EOA as "EOA"
participant CryptoFPLCards_01 as "CryptoFPLCards_01"

"EOA" -> "CryptoFPLCards_01" ++: mintTeam(\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| address | _owner | 0xEB3e2b223309e08e71774ea1158eb34C2e2E9619 |\n\
| array | ids | [ 15, 21, 39, 94 ] |\n\
| array | playerPositions | [ 1, 2, 3, 4 ] |\n\
| array | amounts | [ 1, 1, 1, 1 ] |\n\
) { 100000000.0 GWEI }
"CryptoFPLCards_01" -> "CryptoFPLCards_01" ++: _addTokensTo(\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| address | _to | 0xEB3e2b223309e08e71774ea1158eb34C2e2E9619 |\n\
| array | _tokenIds | [ 15, 21, 39, 94 ] |\n\
) { 0.0 GWEI }
"CryptoFPLCards_01" -> "CryptoFPLCards_01" --: 
"CryptoFPLCards_01" -> "CryptoFPLCards_01" ++: _batchMint(\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| address | _to | 0xEB3e2b223309e08e71774ea1158eb34C2e2E9619 |\n\
| array | _ids | [ 15, 21, 39, 94 ] |\n\
| array | _amounts | [ 1, 1, 1, 1 ] |\n\
) { 0.0 GWEI }
"CryptoFPLCards_01" -> "CryptoFPLCards_01" ++: add(\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| uint | a | 0 |\n\
| uint | b | 1 |\n\
) { 0.0 GWEI }
"CryptoFPLCards_01" -> "CryptoFPLCards_01" --: Return (\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| uint |  | 1 |\n\
)
"CryptoFPLCards_01" -> "CryptoFPLCards_01" ++: add(\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| uint | a | 0 |\n\
| uint | b | 1 |\n\
) { 0.0 GWEI }
"CryptoFPLCards_01" -> "CryptoFPLCards_01" --: Return (\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| uint |  | 1 |\n\
)
"CryptoFPLCards_01" -> "CryptoFPLCards_01" ++: add(\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| uint | a | 0 |\n\
| uint | b | 1 |\n\
) { 0.0 GWEI }
"CryptoFPLCards_01" -> "CryptoFPLCards_01" --: Return (\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| uint |  | 1 |\n\
)
"CryptoFPLCards_01" -> "CryptoFPLCards_01" ++: add(\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| uint | a | 0 |\n\
| uint | b | 1 |\n\
) { 0.0 GWEI }
"CryptoFPLCards_01" -> "CryptoFPLCards_01" --: Return (\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| uint |  | 1 |\n\
)
"CryptoFPLCards_01" -> "CryptoFPLCards_01" --: 
"CryptoFPLCards_01" -> "CryptoFPLCards_01" ++: _updatePosition(\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| uint | tokenId | 15 |\n\
| uint | position | 1 |\n\
) { 0.0 GWEI }
"CryptoFPLCards_01" -> "CryptoFPLCards_01" --: 
"CryptoFPLCards_01" -> "CryptoFPLCards_01" ++: _updatePosition(\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| uint | tokenId | 21 |\n\
| uint | position | 2 |\n\
) { 0.0 GWEI }
"CryptoFPLCards_01" -> "CryptoFPLCards_01" --: 
"CryptoFPLCards_01" -> "CryptoFPLCards_01" ++: _updatePosition(\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| uint | tokenId | 39 |\n\
| uint | position | 3 |\n\
) { 0.0 GWEI }
"CryptoFPLCards_01" -> "CryptoFPLCards_01" --: 
"CryptoFPLCards_01" -> "CryptoFPLCards_01" ++: _updatePosition(\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| uint | tokenId | 94 |\n\
| uint | position | 4 |\n\
) { 0.0 GWEI }
"CryptoFPLCards_01" -> "CryptoFPLCards_01" --: 
"CryptoFPLCards_01" -> "EOA" --: 

legend
Participant details
<#FEFECE,#D0D000>|= Alias |= Contract name |= Address |
<#FEFECE>| EOA | Externally Owned Account | 0x40157F22D93fF6DBfBF61eb22a47883a22DE67Bf |
<#FEFECE>| CryptoFPLCards_01 | CryptoFPLCards | 0xF7438D5f4008Ec22A29f3a69e34d5995E5c41299 |
endlegend

@enduml
```



## should give a list of footballers that a user owns
[link to test...](http://github.com/cds-amal/crypto-fpl/blob/34472c11912f7281a066bfa50cc485d67a6b6112/test/cryptoFPLCards.test.js#L68)

##### d1, tx: 0x3ccbc15b2aafb78e719fd9ca34ff315f32948a44b2d062ba77a058ec962030c1

[SVG :telescope:](https://www.planttext.com/api/plantuml/svg/pPPjRvim4CVV-rESkZURbcx6G82gYve7M2jjQhH5sejrYWumAIenaJ5RqsRVVKUQHdrQrwMJ5YGmdC_7tO-J-JDsK1dKffuMZ65jIbLFOwbPTPQh6MgSGY4dKgKzJCuckgnLsY-BKiEBA8p2ViZOVcNcXUmmM1wd4bEfuNBr271OwloYL0QBRf5Fr5GgGn4pitQ8QF8gvApMiqBUclYSNqYmdBLjY6cQgmbOV6NwkHpttwwIOAlt7wagdvoQ2k8vZ7ITPHINcTmK4aRd2WwnEjq3VcudIPnORYmGizZpfMS5MHeaQ3jPPbjkPel0yT5nOf7ojeZHyv2xlao2jk0sJon6o193gOV7NS0ATcZSOOJDv4a-Gogrh-SpKqR33ttKQJNcrjBjddM7iULQsEqyD0klN-_1D5Tc977wyaITiFqL_zPgx2pUWPdF9D2eSBeSlsDHqqtZlW02fsLLmGB6vGz5Y1PKlzjtkEMXpD3tUD_skHsYxSLzAZRgkexNZaNRiNhMEeZMEAULUTe4-WfM2qGBx1OuyEskpwp0kTJ3iifDNge_--EKciki_InEfql-_Dhr5LoITNMyuV3-ItX4t_yXN8zG71E8KNacLJKgdqtIbC_2IEifaQFVmcmgtgpItTqz-6ioCPhaz2DrsN_dyfJ-6Z-fOJPl52fdCmur4MpwkK5mnnRJQVsBR_j9cbehU5Q2DtBP6ZPyc-3mRQFZRXCTTyleY6tg7R59xpowQL-fWyQ3NGaoDhmXCr9fC2-g6oaF-81-aqtAfBj8Sz1DdmIL9hsoJhvxlMElrtKMIob3rtCZjSAYcCCnoOKKkadIRBVBVPrsTTUBX1W4TXQr1xsi5xKj6Gk1ZkVxDj9CsFPwsUt0zwNGNTioUEGvjZzmCuTpFqo4w8eWix4TIDj9tI1mGpTnB14459meh5Ym0xgIXFq5)


```plantuml


@startuml

autonumber
skinparam legendBackgroundColor #FEFECE

<style>
      header {
        HorizontalAlignment left
        FontColor purple
        FontSize 14
        Padding 10
      }
    </style>

header Insights by Truffle

title Txn Hash: 0x3ccbc15b2aafb78e719fd9ca34ff315f32948a44b2d062ba77a058ec962030c1


actor EOA as "EOA"
participant CryptoFPLCards_01 as "CryptoFPLCards_01"

"EOA" -> "CryptoFPLCards_01" ++: mintTeam(\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| address | _owner | 0x5C4017aefa870C3803Ea37bC062FA5476b2641B1 |\n\
| array | ids | [ 1, 2, 3, 4 ] |\n\
| array | playerPositions | [ 1, 2, 3, 4 ] |\n\
| array | amounts | [ 1, 10, 15, 20 ] |\n\
) { 100000000.0 GWEI }
"CryptoFPLCards_01" -> "CryptoFPLCards_01" ++: _addTokensTo(\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| address | _to | 0x5C4017aefa870C3803Ea37bC062FA5476b2641B1 |\n\
| array | _tokenIds | [ 1, 2, 3, 4 ] |\n\
) { 0.0 GWEI }
"CryptoFPLCards_01" -> "CryptoFPLCards_01" --: 
"CryptoFPLCards_01" -> "CryptoFPLCards_01" ++: _batchMint(\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| address | _to | 0x5C4017aefa870C3803Ea37bC062FA5476b2641B1 |\n\
| array | _ids | [ 1, 2, 3, 4 ] |\n\
| array | _amounts | [ 1, 10, 15, 20 ] |\n\
) { 0.0 GWEI }
"CryptoFPLCards_01" -> "CryptoFPLCards_01" ++: add(\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| uint | a | 0 |\n\
| uint | b | 1 |\n\
) { 0.0 GWEI }
"CryptoFPLCards_01" -> "CryptoFPLCards_01" --: Return (\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| uint |  | 1 |\n\
)
"CryptoFPLCards_01" -> "CryptoFPLCards_01" ++: add(\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| uint | a | 0 |\n\
| uint | b | 10 |\n\
) { 0.0 GWEI }
"CryptoFPLCards_01" -> "CryptoFPLCards_01" --: Return (\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| uint |  | 10 |\n\
)
"CryptoFPLCards_01" -> "CryptoFPLCards_01" ++: add(\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| uint | a | 0 |\n\
| uint | b | 15 |\n\
) { 0.0 GWEI }
"CryptoFPLCards_01" -> "CryptoFPLCards_01" --: Return (\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| uint |  | 15 |\n\
)
"CryptoFPLCards_01" -> "CryptoFPLCards_01" ++: add(\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| uint | a | 0 |\n\
| uint | b | 20 |\n\
) { 0.0 GWEI }
"CryptoFPLCards_01" -> "CryptoFPLCards_01" --: Return (\n\
<#FEFECE,#FEFECE>|= type |= name |= value |\n\
| uint |  | 20 |\n\
)
"CryptoFPLCards_01" -> "CryptoFPLCards_01" --: 
"CryptoFPLCards_01" -> "EOA" --: 

legend
Participant details
<#FEFECE,#D0D000>|= Alias |= Contract name |= Address |
<#FEFECE>| EOA | Externally Owned Account | 0x40157F22D93fF6DBfBF61eb22a47883a22DE67Bf |
<#FEFECE>| CryptoFPLCards_01 | CryptoFPLCards | 0xF7438D5f4008Ec22A29f3a69e34d5995E5c41299 |
endlegend

@enduml
```

