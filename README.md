# BIP39-Seed-Phrase-Generator
This tool randomly creates BIP39 seed phrases and computes derivation paths from given seed. This tool will allow you to easily create your own BIP39 compatible seed phrase (mnemonic) with cryptographically secure random number generator.

The main feature that distinguish that tool from other available is a default simple mode, that allows easy BIP39 seed phrase generation for everyone. However, when using advanced mode, user can access all features.

You can think of this tool as a hardware or software wallet opened up where you can tinker with stuff inside and do everything manually.

**See the tool in action - online version -  [BIP39 Seed Phrase Generator](https://getcoinplate.com/bip39-seed-phrase-mnemonics-generator-offline-online-tool/)**

Possible use cases:
- Randomly compute a seed phrase safely if you need to.
- Check if your seed phrase is correct (you will receive a notification if a given word is not from the list.
- You can check all your individual addresses without a wallet, if you would need that.
- Compute your coins addresses plus private keys so you could retrieve funds manually by using Bip44 standard or other. Could be useful if you lose your wallet and are unable to get one.
- Create a new bip39/44 wallet to create a coin address and transfer your coins ASAP, then later input the seed in a wallet and restore. Could be useful in a bad case of a compromised wallet.
- Generate some truly random seed phrase with your own entropy source if you would like, for example, you can roll your own dice yourself.
- See how things work inside your hardware or software wallet. It is easy to see here that your seed phrase is also an instruction set for setting up addresses and private keys (i.e. Bip44). You can see how keys and addresses are computed from the seed.

Advanced mode features:
- convert mnemonic code to seed (mnemonic code converter),
- calculate derivation paths/addresses from mnemonics,
- use your own entropy to create seed phrase.

**You can use this tool 100% offline.** For security it is preferable to use offline fresh system install or system on live usb. Download standalone offline .html file and open it in a browser.


This tool is based on Ian Coleman's mnemonics code converter.

**It's important to have a proper [seed phrase storage](https://getcoinplate.com/blog/the-best-crypto-seed-phrase-storage-the-ultimate-guide/).**

Source code:
You can see the full source code in standalone, offline html file. Alternatively you can check the individual css and js files in the online version folder, where the direct copy of website version is stored. This is free and opensource tool.


**If you found this tool useful, you can tip us or buy a metal crypto wallet from [our store](https://getcoinplate.com/).**

- BTC: bc1q4tq9mz6dz78qgxvrlfvpg2yp0hxn4wmtfq6rmm
- ETH: 0x77fa426AB714995a34D20A4d61fDcE2AB829c54F
- LTC: ltc1qk5s74tx445hzjgxm5xtyp2wth7f0q969leefyx
- XLM: GDXZ7YE2QZN2FT4CDY2QREQ6ZV3A76CJQIYZZQ4CTX6XU7PBO3JOKTKS
- ADA: addr1q88l806507plwz0gl3e44mw78fkjn4jekk4st8tk2yaca7u09dknhhq52pqmg70v2h45g3spnr0jxd9yz4w9a5v2j0kq0sg74f



## Check out our other tools:
**[BIP39 Recoverer - Seed Phrase recovery tool](https://getcoinplate.com/bip39-recoverer-seed-phrase-recovery-tool/)**

<details><summary> License (click to expand) </summary
<p>The MIT License (MIT) Copyright (c) 2022 Coinplate</p>

<p>Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.</p>

</details>
