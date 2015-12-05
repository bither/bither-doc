#bitherwallet FAQ

####1.What is private key ? How to decipher the signature achieve trading? Deviation of private key understanding

The private key is to ensure the safety of your bitcoin most important part , when you generate a private key , while common , it will be saved to your phone , when you use your private key corresponding to this transaction at the same time address will asking you to enter the wallet code , in fact, the private key to decrypt the process , use your private key to sign this deal will be broadcasted to complete the transaction .

####2.Download Link on bitherwallet

You can download via the following links to your bitherwallet client needs , bither support android, iOS, and desktop version , small partners as needed to download oh ~

![bitherwallet](images/bither_120.png)

####3.Backup private key , restore the backup HD accounts , and how to achieve HD account ？

*Private Key Backup*：

Choose what you need to back up the private key -> Details top right corner of the interface of the three point button -> private Key Management -> Select convenient way do you think the backup

*Backup HD Account*:

HD account details Interface -> detail three points right corner of the interface buttons -> HD Account seed QR Code and HD account passphrase do backup

*Recovery HD Account*:

When you uninstall bither but you have a backup account seed HD and HD-QR code of the account passphrase (any required) -> Settings button -> Advanced Options -> Import private key -> (from Bither Private Key QR Code, from HD passphrase can be restored)

####4.How bither see if synchronized to the latest block?

Settings button -> Advanced Options -> Network Monitoring

####5.Why now bither no HDM?

We consider adjusting the HDM model, the future may be provided through different HDM, so the current is removed this feature to only support the restoration, so that users can use the old, HDM model options to the user, or too much, in safety under the premise streamline user learning costs will be significantly reduced.

####6.bitherwallet address too much, I want to clear these addresses, how to do?

Select the address you want to remove -> detail three dots button to the top right corner of the interface ->Private Key Management -> moved to the Recycle Bin

####7.bither flow relatively large consumption Why? How to solve this problem?

bitherWallet is based on P2P networks to keep pace, the traffic may be more, but certainly not browse microblogging, browse letter circle of friends spent traffic, if you flow under very tight, and there is no WIFI in the situation can be:

Settings button -> Advanced Options -> Network Setting -> Sync over wifi only

Because bither current logic is only in sync to the latest situation to publish trading block, so temporarily unable to distinguish between flow settings sync blocks and sending transactions.

####8.I completed a deal, but  [Blockchina.info] (https://blockchain.info/) or [BlockMeta.com] (https://BlockMeta.com) no inquiry into the deal on what is the reason ?

Broadcast deal also takes time, so please do not worry, you can:

Settings button -> Advanced Options -> Network Monitoring

Query whether the state can be synchronized to the latest fast, to understand your transaction.

####9.bitherwallet mobile terminal and PC terminal which is safer?

Use cold wallets are safe, but according to the logic, the better the mobile side, destruction sandbox can destroy data security, from a security point of view: the smart phone operating system (running + cross-application sandbox can not access the data) High in general desktop systems.

Smart phone operating system> Computer Operating System> Browser

####10.private key QR Code（decryption）and private key  Text What is the difference?

One is QR Code display for easy scanning, one can directly copy down the order after use.

####11.If I use the phone to do a cold wallet, and now I want to upgrade than version wallet too. So how do I do the most efficient? Even the wifi upgrade is possible, but even on wifi also dangerous, right?

You can put on your hot wallet an upgraded apk, on a cold wallet phones and use Bluetooth to, because Bluetooth is one of the transmission, but also just the transmission of what, in general, is still relatively safe.

####12.Suppose I use bither stored coins, suddenly one day, bither was deleted, I did not back up the private key, it is not meant to throw a coin?

You uninstall the default ratio too will private data is unloaded, if you take the initiative to uninstall them all, but not backed up the private key, so money can be considered lost (maybe even disk recovery?)
If you really do so, which software the currency had lost it!

####13.How hot wallet switch to cold wallet? What precautions do?

If you first install bither, and does not generate private keys at the same time, you can in the Settings -> Switch to cold wallet switch.

If you first install than too and, in the case of no network, it can be directly set up for the cold wallet.

*kindly reminder*：

  1.hotwallet Upon switching to coldwallet, the operation can not return, coldwallet can not be switched to hotwallet.

  2.In the state hotwallet only if the situation does not generate private keys you can switch to coldwallet

####14.bither official server with my local wallet a relationship? If the server is broken it will affect me?

bitherwallet is to the center of the purse, even bither company does not exist, unless a major Bitcoin network, incompatible protocol upgrade, and bitherwallet does not support, be likely to affect the operation of the wallet.
Also bither is open source project, even if the company does not exist than too open-source project itself can continue to develop.
Furthermore, please make a backup of the private key (private key is the most important), than too export the private key can be imported bitcoin-core and other wallet

####15.Message signatures have what use?

Message signature is not required to spend money to be able to prove you have an address private.

####16.Security check for private keys.What is the principle?

This function will actually complete the finish "to decrypt -> private key -> public key -> Address" process, so that users do not need to send real operating Bitcoin, we can confirm that the address for private ownership, can this operation is seen as the "Open safe, take a look at bullion is not still" in the process.
In addition, regular "test private security" operations, helping password memory, forget one of the common reasons Bitcoin user password is lost money, psychological experiments have repeatedly shown that only passwords used repeatedly, it will not It is forgotten.

####17.QR Code after backup my save was stolen by hackers, you will not lose my Bitcoin?

If stolen by hackers, the security of the private key lies in the strength of the password, brute force may exist, therefore, if hackers steal QR Code backups, will be transferred to other new Bitcoin address is generated as soon as possible.
Note: Your QR Code backup how hackers stole? Cold is the Pirates do not go.

####18.Bitcoin address is established can not be found to be bither of others? Is it possible by law enforcement agencies to track down than I held too Bitcoin?

bither is to the center of the wallet, bither generated address with bitcoin-core makes no difference, only the address nobody can infer more information. Ratio too is decentralized wallet, I do not know what are your currency.