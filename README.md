----------------------------------------------------------------

# Copyright © 01-10-2021 [Tyler R. Drury](https://vigilance91.github.io/) (vigilance.eth), All Rights Reserved.

----------------------------------------------------------------

# [web-bundle][1]™

**web-bundle™** is a bundled collection of common free, open-source software (FOSS) javascript and css libraries, used in web development including:

* **[underscore](https://underscorejs.org/)** - broad range of utilities
* **[jQuery](https://jquery.com/) v3.3** - utilities for manipulating the DOM, making HTTP requests and more
* **[bootstrap](https://getbootstrap.com/) v4.1** - core UI and styles
* **[highlightjs](https://highlightjs.org/) v9.12** - text highlight for displaying code
* **[qUnit](https://qunitjs.com/) 2.6.0** - javascript unit testing framework, developed by the jQuery team

**./javascript/bundle.js** and **./css/bundle.css** are for production,
while **./javascript/bundle-test.js** and **./css/bundle-test.css** contain code for unit testing and are intended for unit testing during development.

The **original licenses** of all composite libraries are preserved, as is, in the bundled files.

This project is provided for free, on an **AS IS BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND**, either express or implied.


If you or your organization own the rights to any of the third-party libraries used in this project or have concerns regarding their use,
please [contact me](https://vigilance91.github.io/contact.html).


----------------------------------------------------------------

### Future Developments

As this project expands and other new projects come into use,
more libraries will be added.


----------------------------------------------------------------

## Before Starting

**Be aware** this project is currently in development and intended for use in a browser that is compatible with at least Javascript ES5.
It does not support ES6 module syntax nor is it currently designed for use in a nodeJS environment.

This project has the following directory structure

* **/javascript** - bundled Javascript files
* **/css** - bundled CSS files
* **LICENSE.md** - project license file
* **README.md** - project readme file
* **AUTHORS.md** - authors and other contributors to this project
* **.gitignore** - file specifying which files and directory patterns not to include when pushing commits


----------------------------------------------------------------

## Get the Project

The most recent, stable release of this project may be cloned or forked from the official [GitHub repo][1].

Start by cloning the web-bundle repo (either using the command line, github desktop or the github website)
into the root directory which contains or will contain a web project.

Once cloned to a local machine, link the javascript and css files in the **head** element of an html document, like normal.

```
<head>
    <link rel='stylesheet'
        type='text/css'
        href="/web-bundle/css/bundle.css">
    
    <script type='application/javascript'
        src="/web-bundle/javascript/bundle.js"></script>
</head>
```

Ensure to link to the fields suffixed with **-test** for unit testing, during development.

```
<head>
    <link rel='stylesheet'
        type='text/css'
        href="/web-bundle/css/bundle-test.css">
    
    <script type='application/javascript'
        src="/web-bundle/javascript/bundle-test.js"></script>
</head>
```

----

## Hashes


|Source File | SHA256 | SHA512 |
| --- | --- | --- |
|bundle.js | 98361125a0f6b66692d3c4204a8cd85c044fd68df434f402922b3153eb6a4d1f | 828f859820d1dfc1ea8347ede12dff13a4f65c149461554fff5aa0d32739efa1e125d66d246c4d4f87cdb737229864135d4ab13777a8a25819c1dbdb97fef7b9
|bundle.css | 5db0deebde2f1dfa7f3906cf9dff0ab699cb500e2dc280f2e292fac8ca04778a | 94a56462b68c3976227c251e1dae68308eb700426c061cc129e5f70e8fdfad08b493460c3b40fbce9de70df5007910a66921ef3845256aeb29fdd95893ee6deb
|bundle-test.js | e886a9c44121805460df648b004e16184ab4ba26f689e918e846bf6ce0590fea | 160d8abd3bfb61165ebf40aabab223bcbff30d4c05e4851cde929355710ed1265f03a97a9bb2712e7fd4d2e36a39b323545acf28f0bbf2f583c8bb5444a116be
|bundle-test.css | ac6613bee2f84694cd2519040a45c46be4d7f9fcb9ace809e44cb934b489ca64 | b3abeb3c88cb07a1991ade4bbcd8f4e76d0b0623bd479b4fa3beab9b0af8a0020c40dd85786d78bbd7a243e6cf14d1c4334194bb960ef6dedcf2452f926ed880


---- 

## Signatures

### Public Key
```
-----BEGIN PUBLIC KEY-----
MIIBIjANBgkqhkiG9w0BAQEFAAOCAQ8AMIIBCgKCAQEAuWuo3ACD9S1TEi7Q49/1
fyczqjRBs2TR13PGpfwZMnFXyIrUe8nggsWQ7mDE+KAoXgwPzACJWQcsrPsfvi3i
2Xf1w5T2gd5JAFB4UKJtzGcjVYoH0EyjA0u/AHyRqgwUqb79Pjd3RaDNdc0O4STd
filBn44nD0ECAVJmYIwoORSs+ACJ8HWXhUSqdwd24n6v33bgVogTFg4hY+7GqEZV
QhmnPXCDtcwci3UzLxwqMIkx5j/1XYWAAEvMWjktkpRICiYSruBWbEXZW8+5KJVF
l6WV5hYnMZxCQxCtWv590ensrHPFKFZEdasHhf46Ip49QKnxwjNyuGhklsPFe3XJ
CwIDAQAB
-----END PUBLIC KEY-----
```

### Hexadecimal Encoded Signatures


| Source File | SHA256 | SHA512 |
| --- | --- | --- |
| bundle.js | 4ba9c293d6d5ccb652c7e4e657bce6a9918949431f6e3a4b8100ccba4d452d7aa124785f900b2d357dd56752a7c202dc4fd7cded8716475ff46310c20443c740323902d8298a9a47c840e2c9baf769d22ad50a3f1aa431f17d2ca03f28417615214e72eb9aaae7b41b8243352872206de506ece7dcb0c60e7ea01b4d2bc7ba86fed806e4adddc78f1e13910fad2fbfd86c2f66803afa0032562231175a77b07b49742bc5682f7ffe14c14b3e3cf0eb497dba67ac9a70d762818440a258222940a5e563eb077da4428467b83485717dedc50c31175031d7e44ebcfb4ab50c6e1c42369fa351ad4736b2a0b19066f2b28bb467fe39e3d978b1fb9f87a370154d21 | 781a51640d68a7c237fe786b87e32c98f22b1feaf3d9ca33a21c3c8b4b0c921fba588e9eca6baf393c6b052ad2c819a0924a297f80138063a19714297849750379c8741bc561927496fca9ebcfee38f172c935e6d4a2989fb18967f08f92de9e9baee1d58b84c511f5da6718e490d76cf947dc51f2c49f1e522701d201b9307e1998ccccba202c254f5d8de27ad50a76b9e84c685a46810decb54e7474f1f42b5782bdcc71c48ec40331f8bd5d1e512637deb716e2ca4ed2d383ae59f15fcad185d9f8022647a4e3829556ea7e2fc13f587f1653eaf394f706012edc0d4f5b48c1da7fe7111270b120237f4691110442b44ee778eb9d0c17ad19f8e6d5ffcc43 |
| bundle.css | 86ffb5e0933460636b168c258d7839583eb656808d6058fdf83cdadc99f7e9eaa6b247a21331395610e9ee5e94c9202d86828469a6f77a777fa8fd23e22267993e051e52b234ec423c8cf16a2cb10792563f4fd0e5d5f910325ccd087f03cacff57b1efb14e46689d88ffabad19af5b5a5fe1520a9fce3626c483a2a0ed1b641116c65774ae6437ea09fb105e8f25f5a4f2bdcfcd1fb4101d02be155072a33e5115db0386cb62089ecef18254a4af1c8e6c069d95541176cbae26af18b6d83e5652db28db5e7cd1d07e88770cc1dbc44a61cad322d0a0b5e11382bddf624eb51d467f88b63b6e1b6ca20e7cc21ed0b162e75d37333806e202c2be3dab67bf071 | 0702a1a7f5a61d6146986da53717304075690f19ddf7e2c6912b46f78b04083b1c065eefe63c3a30aefc968f6eab66cc686174839b853c364ec1a5cb8bbf8b6e2e7e206ebe14a97a8a1b9e07af3ae00125fd6d6a1f965fc22722afb8d651aa10bd591f9bd70cfd1e907099ef4f0543523e9dfa6b3e6f969f4f02077fec6aff045e2acd5bd3f4bb1bb08adcb23f6c1517a3652dfacfdf9e8ddd7a73b4175262bb7f9d89daf277e8a75e00447a8d9c90222086b52e5e5e62ca394d2c24fe0b407a128436877932f84017144f9417f155beaa058848ef8cc3049f78d81034d8a88fb38c37610d0d963ca0927b5684724df6cc067616d0be0505a9fc32b27ccc4fc3 |
| bundle-test.js | b24f780816761344fbe7c69fcb6ebd4def35f099956a009b95663a16ed0b528674f946576a8b49d7fb7e51c12266b98e14f5b7cc66cf4604afb099bd2c778152ed55e935b5c0ba4d8acb3d993eea318b78dfbd5af4ce968653cb63dd17e56d42135217f57a761ff2fcf7f37ca9a6f71fee0b4a5c96b755fae93a4d09e2ffa59b0d8d76733562c7bad1b39a1db3dcd2b10bb23bdf98c475295cc4c253b723e821761338134d495c5c387c710745f74880159e71c7decdbbedc08fe6fd2edd67e01a978aa028a419485aef200e115f9fbd83b27fa0eb769c0d5251fe659c1d9fc96b24c51dec9c4997b21e6500110cfebb34ab32932851c21b83c3daa0d6b36811 | 2346e39f8f3deb6e94122617787131ce02ca3cc06a040e44e9db27574f269f4955cc191c61a71fd470a6383b342ea453b71b6f8765e90918ae9b376e314b95c0132e2f411ba70799af16355708b68545ba5fc16d23851139dea83f467259401c42dc846343fadab12d1023cc9b8c18b9a6af9b49642ba622ed0155f5393eedca98611627722e359d62e198d99f7886886835a807b1da8346c0d1f8d908ecffe811f2c99897b6279a61fae06d87fd6b06e6fe8360a7250f5f8433bc38f87ae493d22ee1090300632b9b298f9605ff6374e17f5ea58f70363c2933734c33f1904eed1876af0e77d87c416d7535d5a4ff8670a9497e0dc198c4909bbd3926654307 |
| bundle-test.css | 38f61ce113c4d850d36df7f4db002c0b997fca5ac9cc3d3b549c1e270279bb1a236a901aacff771c2c660f602108b0391165e0f548f9eb2c1f13da0f92234ed5f1b5562959e162fbc4ebbf1e90e9c515ba3b2260b36d999d8bad93f4dad65cfed6b4ee3e298d863bdd8dcf27099634ee91f282c30e8f4a52577fb2720ccdf30095a76f36abda07ca6635c3bb70f2c020d8b7d328d08b22ff1c019c33e630fd0bc58950de475509d8ee439449cea9f4e1008f2aa4d89d8002c874dd186c3b908db0bb5e5cd52dd25d2bee13fdc0d46fdd499cc3c4482386664b8294e8997a7f043d46872dfb93371d4b6868dff86b16df1519c7dea9e45b5e625caa497bd759ec | 6a6a8ce098a70f0b05fbc34561939be1e1bd263828475ade673e2c09c18bf58e34934e022a16f3a1a9940ab77bfbb2bfbdf4e7d8355af2b62daa0e8e753a4f814750acebee6b060d29c086663855a5d91a772a4aa484c3836a544f53dc0b0e9a1a5e61d372e0f48589a3bb074c952ff8bdde6b7a856152f47ba9b031a46439a66c20b333a6f45c151b4c0d7dfe74fc74e5fce6d1e83ca59482995c2eb1a3f7eb1343761cf405fbc60737dd942692b8aa546e18a6fd74b558e0285b609b79faf1ecc8395960925d6fbd068c8cb20ffd91502ffdd35cedfac2aa0e2d2aa07353cf67924b004a1569a5273d4be007c57730a2ad6ef1be9d227cc1520a0bd3f53bd6 |


### Base64 Encoded Signatures

bundle.js SHA256
```
S6nCk9bVzLZSx+TmV7zmqZGJSUMfbjpLgQDMuk1FLXqhJHhfkAstNX3VZ1KnwgLc
T9fN7YcWR1/0YxDCBEPHQDI5AtgpippHyEDiybr3adIq1Qo/GqQx8X0soD8oQXYV
IU5y65qq57QbgkM1KHIgbeUG7OfcsMYOfqAbTSvHuob+2Abkrd3Hjx4TkQ+tL7/Y
bC9mgDr6ADJWIjEXWnewe0l0K8VoL3/+FMFLPjzw60l9umesmnDXYoGEQKJYIilA
peVj6wd9pEKEZ7g0hXF97cUMMRdQMdfkTrz7SrUMbhxCNp+jUa1HNrKgsZBm8rKL
tGf+OePZeLH7n4ejcBVNIQ==
```

bundle.js SHA512
```
eBpRZA1op8I3/nhrh+MsmPIrH+rz2cozohw8i0sMkh+6WI6eymuvOTxrBSrSyBmg
kkopf4ATgGOhlxQpeEl1A3nIdBvFYZJ0lvyp68/uOPFyyTXm1KKYn7GJZ/CPkt6e
m67h1YuExRH12mcY5JDXbPlH3FHyxJ8eUicB0gG5MH4ZmMzMuiAsJU9djeJ61Qp2
uehMaFpGgQ3stU50dPH0K1eCvcxxxI7EAzH4vV0eUSY33rcW4spO0tODrlnxX8rR
hdn4AiZHpOOClVbqfi/BP1h/FlPq85T3BgEu3A1PW0jB2n/nERJwsSAjf0aREQRC
tE7neOudDBetGfjm1f/MQw==
```

bundle.css SHA256
```
hv+14JM0YGNrFowljXg5WD62VoCNYFj9+Dza3Jn36eqmskeiEzE5VhDp7l6UySAt
hoKEaab3end/qP0j4iJnmT4FHlKyNOxCPIzxaiyxB5JWP0/Q5dX5EDJczQh/A8rP
9Xse+xTkZonYj/q60Zr1taX+FSCp/ONibEg6Kg7RtkERbGV3SuZDfqCfsQXo8l9a
Tyvc/NH7QQHQK+FVByoz5RFdsDhstiCJ7O8YJUpK8cjmwGnZVUEXbLriavGLbYPl
ZS2yjbXnzR0H6IdwzB28RKYcrTItCgteETgr3fYk61HUZ/iLY7bhtsog58wh7QsW
LnXTczOAbiAsK+PatnvwcQ==
```

bundle.css SHA512
```
BwKhp/WmHWFGmG2lNxcwQHVpDxnd9+LGkStG94sECDscBl7v5jw6MK78lo9uq2bM
aGF0g5uFPDZOwaXLi7+Lbi5+IG6+FKl6ihueB6864AEl/W1qH5Zfwicir7jWUaoQ
vVkfm9cM/R6QcJnvTwVDUj6d+ms+b5afTwIHf+xq/wReKs1b0/S7G7CK3LI/bBUX
o2Ut+s/fno3denO0F1Jiu3+didryd+inXgBEeo2ckCIghrUuXl5iyjlNLCT+C0B6
EoQ2h3ky+EAXFE+UF/FVvqoFiEjvjMMEn3jYEDTYqI+zjDdhDQ2WPKCSe1aEck32
zAZ2FtC+BQWp/DKyfMxPww==

```

bundle-test.js SHA256
```
sk94CBZ2E0T758afy269Te818JmVagCblWY6Fu0LUoZ0+UZXaotJ1/t+UcEiZrmO
FPW3zGbPRgSvsJm9LHeBUu1V6TW1wLpNiss9mT7qMYt4371a9M6WhlPLY90X5W1C
E1IX9Xp2H/L89/N8qab3H+4LSlyWt1X66TpNCeL/pZsNjXZzNWLHutGzmh2z3NKx
C7I735jEdSlcxMJTtyPoIXYTOBNNSVxcOHxxB0X3SIAVnnHH3s277cCP5v0u3Wfg
GpeKoCikGUha7yAOEV+fvYOyf6DrdpwNUlH+ZZwdn8lrJMUd7JxJl7IeZQARDP67
NKsykyhRwhuDw9qg1rNoEQ==
```

bundle-test.js SHA512
```
I0bjn489626UEiYXeHExzgLKPMBqBA5E6dsnV08mn0lVzBkcYacf1HCmODs0LqRT
txtvh2XpCRiumzduMUuVwBMuL0EbpweZrxY1Vwi2hUW6X8FtI4UROd6oP0ZyWUAc
QtyEY0P62rEtECPMm4wYuaavm0lkK6Yi7QFV9Tk+7cqYYRYnci41nWLhmNmfeIaI
aDWoB7Hag0bA0fjZCOz/6BHyyZiXtieaYfrgbYf9awbm/oNgpyUPX4QzvDj4euST
0i7hCQMAYyubKY+WBf9jdOF/XqWPcDY8KTNzTDPxkE7tGHavDnfYfEFtdTXVpP+G
cKlJfg3BmMSQm705JmVDBw==
```

bundle-test.css SHA256
```
OPYc4RPE2FDTbff02wAsC5l/ylrJzD07VJweJwJ5uxojapAarP93HCxmD2AhCLA5
EWXg9Uj56ywfE9oPkiNO1fG1VilZ4WL7xOu/HpDpxRW6OyJgs22ZnYutk/Ta1lz+
1rTuPimNhjvdjc8nCZY07pHygsMOj0pSV3+ycgzN8wCVp282q9oHymY1w7tw8sAg
2LfTKNCLIv8cAZwz5jD9C8WJUN5HVQnY7kOUSc6p9OEAjyqk2J2AAsh03RhsO5CN
sLteXNUt0l0r7hP9wNRv3Umcw8RII4ZmS4KU6Jl6fwQ9Roct+5M3HUtoaN/4axbf
FRnH3qnkW15iXKpJe9dZ7A==
```

bundle-test.css SHA512
```
amqM4JinDwsF+8NFYZOb4eG9JjgoR1reZz4sCcGL9Y40k04CKhbzoamUCrd7+7K/
vfTn2DVa8rYtqg6OdTpPgUdQrOvuawYNKcCGZjhVpdkadypKpITDg2pUT1PcCw6a
Gl5h03Lg9IWJo7sHTJUv+L3ea3qFYVL0e6mwMaRkOaZsILMzpvRcFRtMDX3+dPx0
5fzm0eg8pZSCmVwusaP36xNDdhz0BfvGBzfdlCaSuKpUbhim/XS1WOAoW2Cbefrx
7Mg5WWCSXW+9BoyMsg/9kVAv/dNc7frCqg4tKqBzU89nkksAShVppSc9S+AHxXcw
oq1u8b6dInzBUgoL0/U71g==

```


----------------------------------------------------------------

## License

[web-bundle][1]™ is released under the Apache-2.0 License.

See the [LICENSE][2] file for more details.


----------------------------------------------------------------

## Authors

All respective authors and contributors are attributed in [AUTHORS][3].


[1]: https://github.com/vigilance91/web-bundle
[2]: https://github.com/vigilance91/web-bundle/LICENSE.md
[3]: https://github.com/vigilance91/web-bundle/AUTHORS.md
