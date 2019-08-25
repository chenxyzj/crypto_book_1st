![avatar](https://github.com/locomotive-crypto/crypto_book_1st/blob/master/resource/0001.jpg)
***
***

# crypto_book_1st仓库

##	作者：韩露露、杨波

##	仓库简介：
>	&nbsp;&nbsp;&nbsp;&nbsp;该仓库存放了《深入浅出CryptoPP密码学库》的随书电子文档，这些文档仅包含书中的示例代码。任何人都可以复制、传播、使用这些代码。

***
***

##	《深入浅出CryptoPP密码学库》内容简介：
>	&nbsp;&nbsp;&nbsp;&nbsp;本书向读者介绍密码学库CryptoPP（或Crypto++）的使用方法和设计原理。CryptoPP是一个用C++语言编写的、开源的、免费的密码程序库，它最初由Wei Dai开发，现由开源社区维护。CryptoPP库广泛应用于学术界、开源项目、非商业项目以及商业项目，它几乎包括了目前已经公开的所有密码算法，支持当前主流的多种系统平台，并且具有良好的设计结构和较高的执行效率。

>	&nbsp;&nbsp;&nbsp;&nbsp;全书共15章，主要内容包括随机数发生器、Hash函数、流密码、分组密码、消息认证码、密钥派生和基于口令的密码、公钥加密系统、数字签名、密钥协商等，本书涵盖C++程序设计、设计模式、数论和密码学等知识。

>	&nbsp;&nbsp;&nbsp;&nbsp;本书最大的特点就是以应用为导向、以解决实际工程问题为目标，理论结合实践，将抽象的密码学变成保障信息安全的实际工具。

>	&nbsp;&nbsp;&nbsp;&nbsp;本书可以作为密码学、网络安全等专业在校学生的上机实验教材，也可以作为信息安全产品开发者、科研人员、密码算法实现者的参考手册。

>	Wei Dai主页：http://www.weidai.com/

>	Jeffrey Walton：

>>	GitHub地址：https://github.com/noloader

>>	Stack Overflow地址：https://stackoverflow.com/users/608639/jww

***
***

##	网络资源：
>	本书更多示例代码：https://github.com/locomotive-crypto

>	Crypto++网站：https://www.cryptopp.com/

>	Crypto++库GitHub地址：https://github.com/weidai11/cryptopp

>	Crypto++库SourceForge地址：https://sourceforge.net/projects/cryptopp/

>	Crypto++库Google论坛：

>>	公告通知地址：https://groups.google.com/forum/#!forum/cryptopp-announce

>>	用户群组地址：https://groups.google.com/forum/#!forum/cryptopp-users

***
***

##	声明：
>	由于作者水平有限，错误之处在所难免。欢迎通过如下方式反馈相关问题：

>	email:locomotive_crypto@163.com

>	同时，也欢迎任何人向该仓库提交更好的范例程序。

***
***

##	其他密码（安全）类程序库：
>	OpenSSL：

>>	GitHub：https://github.com/openssl/openssl

>>	官网：https://www.openssl.org/

>	Botan：

>>	GitHub：https://github.com/randombit/botan

>>	官网：https://botan.randombit.net/

>	Bouncy Castle：

>>	官网：https://www.bouncycastle.org/	

>	NaCl：

>>	官网：https://nacl.cr.yp.to/

>	cryptlib：

>>	官网：https://www.cryptlib.com/

>	GnuTLS：

>>	官网：https://www.gnutls.org/

>	CryptoComply：

>>	官网：https://www.safelogic.com/cryptocomply/

>	wolfSSL：

>>	GitHub：https://github.com/wolfSSL/wolfssl

>>	官网：https://www.wolfssl.com/products/wolfcrypt-2/

>	GmSSL(支持国密SM2/SM3/SM4/SM9/ZUC/SSL的密码工具箱):

>>	GitHub: https://github.com/guanzhi/GmSSL

>>	The GmSSL Project:http://gmssl.org/

>	TaSSL——完全支持国密体系的OpenSSL:

>>	官网:http://www.tass.com.cn/portal/research/viewpoint_view-36.html

>>	源代码:http://www.tass.com.cn/images/TASSL-openssl_1.0.2o.rar

***
***

##	密码算法（待补充）：
####	随机数发生器（待补充）：
* MT19937ar:http://www.math.sci.hiroshima-u.ac.jp/~m-mat/MT/ARTICLES/mt.pdf
* MT19937:http://www.math.sci.hiroshima-u.ac.jp/~m-mat/MT/MT2002/emt19937ar.html
* HMAC_DRBG:https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-90Ar1.pdf
* Hash_DRBG:https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-90Ar1.pdf

####	Hash函数（待补充）：
* MD2(The MD2 Message-Digest Algorithm):https://tools.ietf.org/html/rfc1319
* MD4(The MD4 Message-Digest Algorithm):https://tools.ietf.org/html/rfc1320
* MD5(The MD5 Message-Digest Algorithm):https://datatracker.ietf.org/doc/rfc1321/
* SHA1(US Secure Hash Algorithm 1 (SHA1)):https://tools.ietf.org/html/rfc3174
* SHA2(SHA-224、SHA-256、SHA-384、SHA-512):
> Secure Hash Standard (SHS):https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.180-4.pdf

> US Secure Hash Algorithms (SHA and HMAC-SHA):https://www.rfc-editor.org/rfc/pdfrfc/rfc4634.txt.pdf
* SM3:
> SM3 Hash function(draft-shen-sm3-hash-01):https://tools.ietf.org/html/draft-shen-sm3-hash

> SM3 Cryptographic Hash Algorithm:http://www.gmbz.org.cn/upload/2018-07-24/1532401392982079739.pdf

> 国家密码管理局关于发布《SM3密码杂凑算法》公告:http://www.oscca.gov.cn/sca/xxgk/2010-12/17/content_1002389.shtml

>  The SM3 Cryptographic Hash Function draft-sca-cfrg-sm3-02:https://tools.ietf.org/pdf/draft-sca-cfrg-sm3-02.pdf

>  The SM3 Cryptographic Hash Function draft-sca-cfrg-sm3-01:https://tools.ietf.org/pdf/draft-sca-cfrg-sm3-01.pdf

>  The SM3 Cryptographic Hash Function draft-sca-cfrg-sm3-00:https://tools.ietf.org/pdf/draft-sca-cfrg-sm3-00.pdf

* SHA3:https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.202.pdf>
* GOST R 34.11-2012(Hash Function):https://www.rfc-editor.org/rfc/pdfrfc/rfc6986.txt.pdf
* RIPEMD:
> The hash function RIPEMD-160:https://homes.esat.kuleuven.be/~bosselae/ripemd160.html#Outline

> RIPEMD-160:A Strengthened Version of RIPEMD:https://homes.esat.kuleuven.be/~bosselae/ripemd160/pdf/AB-9601/AB-9601.pdf

* HAVAL - A one-way hashing algorithm with variable length output:https://ro.uow.edu.au/cgi/viewcontent.cgi?referer=&httpsredir=1&article=2096&context=infopapers
* The Whirlpool Secure Hash Function:https://www2.seas.gwu.edu/~poorvi/Classes/CS381_2007/Whirlpool.pdf
* Tiger:A Fast New Cryptographic Hash Function (Designed in 1995):http://www.cs.technion.ac.il/~biham/Reports/Tiger/

####	分组密码（待补充）：
* CAST-128(The CAST-128 Encryption Algorithm):https://tools.ietf.org/html/rfc2144
* CAST-256(The CAST-256 Encryption Algorithm):https://tools.ietf.org/html/rfc2612
* Camellia(A Description of the Camellia Encryption Algorithm):https://www.rfc-editor.org/info/rfc3713
* Camellia(The Camellia Cipher Algorithm and Its Use With IPsec):https://tools.ietf.org/html/rfc4312
* RC5(The RC5, RC5-CBC, RC5-CBC-Pad, and RC5-CTS Algorithms):https://www.rfc-editor.org/info/rfc2040
* AES(Rijndael Encryption Algorithm):http://www.efgh.com/software/rijndael.htm
* AES(Advanced Encryption Standard):https://csrc.nist.gov/csrc/media/publications/fips/197/final/documents/fips-197.pdf
* IDEA(International Data Encryption Algorithm):http://www.quadibloc.com/crypto/co040302.htm
* SM4(SMS4 Encryption Algorithm for Wireless Networks):https://eprint.iacr.org/2008/329.pdf
* Blowfish(Schneier on Security):https://www.schneier.com/academic/blowfish/
* MISTY1(A Description of the MISTY1 Encryption Algorithm):https://www.rfc-editor.org/rfc/pdfrfc/rfc2994.txt.pdf
* Twofish(Twofish: A 128-Bit Block Cipher):https://www.schneier.com/academic/paperfiles/paper-twofish-paper.pdf
* SAFER(Secure And Fast Encryption Routine):http://www.quadibloc.com/crypto/co040301.htm
* KASUMI(Specification of the 3GPP Confidentiality and Integrity Algorithms):https://www.garykessler.net/library/crypto/3G_KASUMI.pdf
* SEED(The SEED Encryption Algorithm):https://www.rfc-editor.org/rfc/pdfrfc/rfc4269.txt.pdf
* ARIA:
> Specification of ARIA:http://210.104.33.10/ARIA/doc/ARIA-specification-e.pdf

> A Description of the ARIA Encryption Algorithm:https://www.rfc-editor.org/rfc/pdfrfc/rfc5794.txt.pdf
* CLEFIA:
> The 128-bit Blockcipher:https://www.sony.net/Products/cryptography/clefia/

> RFC6114(The 128-Bit Blockcipher CLEFIA):https://www.rfc-editor.org/rfc/pdfrfc/rfc6114.txt.pdf
* Simon and Speck(THE SIMON AND SPECK FAMILIES OF LIGHTWEIGHT BLOCK CIPHERS):https://eprint.iacr.org/2013/404.pdf
* KLEIN(KLEIN: A New Family of Lightweight Block Ciphers):http://rfid-cusp.org/rfidsec/files/RFIDSec2011DraftPapers/GongEtAl.pdf
* Light Encryption Device (LED)(The LED Block Cipher∗):https://eprint.iacr.org/2012/600.pdf
* GOST R 34.12-2015(Block Cipher "Kuznyechik"):https://www.rfc-editor.org/rfc/pdfrfc/rfc7801.txt.pdf

###	分组密码操作模式（待补充）：

* ECB、CBC、CFB、OFB、CTR:
> Modes of operation of the AES algorithm:https://pdfs.semanticscholar.org/8822/66e916ec18ea7022bfa149954a29593f7490.pdf

* CCM:
> Counter with CBC-MAC (CCM):https://tools.ietf.org/pdf/rfc3610.pdf

> the CCM Mode for Authentication and Confidentiality:https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-38c.pdf

* GCM:
>  Galois/Counter Mode (GCM) and GMAC:https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-38d.pdf

* EAX:
> The EAX Mode of Operation:https://web.cs.ucdavis.edu/~rogaway/papers/eax.pdf

> A Conventional Authenticated-Encryption Mode:https://csrc.nist.gov/csrc/media/projects/block-cipher-techniques/documents/bcm/proposed-modes/eax/eax-spec.pdf

####	流密码（待补充）：
* ChaCha20(ChaCha20 and Poly1305 for IETF Protocols):https://tools.ietf.org/html/rfc8439
* KCipher-2(A Description of the KCipher-2 Encryption Algorithm):https://www.rfc-editor.org/rfc/pdfrfc/rfc7008.txt.pdf
* ZUC:
> The ZUC-256 Stream Cipher:http://www.is.cas.cn/ztzl2016/zouchongzhi/201801/W020180126529970733243.pdf

> 祖冲之序列密码算法：第1部分：算法描述:http://www.gmbz.org.cn/main/viewfile/20180117202410524608.html

> 祖冲之序列密码算法：第2部分：基于祖冲之算法的机密性算法:http://www.gmbz.org.cn/main/viewfile/20180107233806310781.html

> 祖冲之序列密码算法：第3部分：基于祖冲之算法的完整性算法:http://www.gmbz.org.cn/main/viewfile/20180107234058336917.html

* RC4:
> A Survey on RC4 Stream Cipher:https://pdfs.semanticscholar.org/de34/b0849688e14ea057804a9fed76967143ae83.pdf?_ga=2.259674122.1497617209.1566207401-536567378.1562132951

> (Not So) Random Shuffles of RC4:https://eprint.iacr.org/2002/067.pdf

> Test Vectors for the Stream Cipher RC4:https://tools.ietf.org/pdf/rfc6229.pdf

* RC4变种:
> RC4A:A New Weakness in the RC4 Keystream Generator and an Approach to Improve the Security of the Cipher:http://www.cosic.esat.kuleuven.be/publications/article-40.ps

> VMPC One-Way Function and Stream Cipher:https://www.iacr.org/archive/fse2004/30170209/30170209.pdf

> Spritz—a spongy RC4-like stream cipher and hash function:http://people.csail.mit.edu/rivest/pubs/RS14.pdf

> RC4+:Analysis of RC4 and Proposal of Additional Layers for Better Security Margin:https://eprint.iacr.org/2008/396.pdf
####	消息认证码（待补充）：
* Poly1305(ChaCha20 and Poly1305 for IETF Protocols):https://tools.ietf.org/html/rfc8439
* VMAC(VMAC: Message Authentication Code using Universal Hashing):http://www.fastcrypto.org/vmac/draft-krovetz-vmac-01.txt
* GOST 28147-89(Encryption, Decryption, and Message Authentication Code (MAC) Algorithms):https://www.rfc-editor.org/rfc/pdfrfc/rfc5830.txt.pdf
* SipHash:
> SipHash: a fast short-input PRF:https://131002.net/siphash/siphash.pdf

> SipHash:https://131002.net/siphash/
####	密钥派生和基于口令的密钥派生（待补充）：
* NIST SP 800-108(Recommendation for Key Derivation Using Pseudorandom Functions):https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-108.pdf
* NIST SP 800-132(Recommendation for Password-Based Key Derivation: Part 1: Storage Applications):https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-132.pdf
* RFC2898(PKCS #5: Password-Based Cryptography Specification  Version 2.0):https://tools.ietf.org/html/rfc2898
* RFC5869(HMAC-based Extract-and-Expand Key Derivation Function (HKDF)):https://tools.ietf.org/html/rfc5869
* RFC7914(The scrypt Password-Based Key Derivation Function):https://tools.ietf.org/html/rfc7914.pdf

####	公钥加密（待补充）：
* RSA:
> PKCS#1-2.2(PKCS #1: RSA Cryptography Specifications Version 2.2):https://tools.ietf.org/pdf/rfc8017.pdf

> PKCS#1-2.1( Public-Key Cryptography Standards (PKCS) #1: RSA Cryptography Specifications Version 2.1):https://tools.ietf.org/pdf/rfc3447.pdf

> PKCS#1-2.0(PKCS #1: RSA Cryptography Specifications Version 2.0):https://tools.ietf.org/pdf/rfc2437.pdf
####	数字签名（待补充）：
* RFC6979-Digital Signature(Deterministic Usage of the Digital Signature Algorithm (DSA) and Elliptic Curve Digital Signature Algorithm (ECDSA)):https://tools.ietf.org/pdf/rfc6979.pdf
* RWSS:
> 	RSA signatures and Rabin–Williams signatures:the state of the art:http://cr.yp.to/sigs/rwsota-20080131.pdf
* SM2:
>	《SM2椭圆曲线公钥密码算法》公告:http://www.oscca.gov.cn/sca/xxgk/2010-12/17/content_1002386.shtml
* Digital Signature Standard (DSS):https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.186-4.pdf
* GOST R 34.10-2012(Digital Signature Algorithm):https://www.rfc-editor.org/rfc/pdfrfc/rfc7091.txt.pdf
####	密钥协商（待补充）：
* DH(Diffie-Hellman Key Agreement Method):https://tools.ietf.org/pdf/rfc2631.pdf

####	PKCS标准（待补充）:
* PKCS #1(RSA Cryptography Standard):
>	Version 2.2:https://web.archive.org/web/20150319063720/http://www.emc.com/emc-plus/rsa-labs/pkcs/files/h11300-wp-pkcs-1v2-2-rsa-cryptography-standard.pdf

>	Version 2.2:https://www.rfc-editor.org/rfc/pdfrfc/rfc8017.txt.pdf

>	Version 2.1:https://www.rfc-editor.org/rfc/pdfrfc/rfc3447.txt.pdf

>	Version 2.0:https://www.rfc-editor.org/rfc/pdfrfc/rfc2437.txt.pdf

>	Version 1.5:https://www.rfc-editor.org/rfc/pdfrfc/rfc2313.txt.pdf

* PKCS #3(Diffie-Hellman Key-Agreement Standard):
>	Version 1.4:https://www.teletrust.de/fileadmin/files/oid/oid_pkcs-3v1-4.pdf

* PKCS #5(Password-Based Cryptography Standard):
>	Version 2.1:https://www.rfc-editor.org/rfc/pdfrfc/rfc8018.txt.pdf

>	Version 2.0:https://www.rfc-editor.org/rfc/pdfrfc/rfc2898.txt.pdf

* PKCS #6(Extended-Certificate Syntax Standard):

* PKCS #7(Crytographic Message Syntax):
>	Version 1.5:https://tools.ietf.org/pdf/rfc2315.pdf

* PKCS #8(Private-Key Information Syntax Specification):
>	Version 1.2:https://www.rfc-editor.org/rfc/pdfrfc/rfc5208.txt.pdf

* PKCS #9(Selected Object Classes and Attribute Types):
>	Version 2.0:https://www.rfc-editor.org/rfc/pdfrfc/rfc2985.txt.pdf

* PKCS #10(Certification Request Syntax Specification):
>	Version 1.7:https://www.rfc-editor.org/rfc/pdfrfc/rfc2986.txt.pdf

>	Version 1.5:https://www.rfc-editor.org/rfc/pdfrfc/rfc2314.txt.pdf

* PKCS #11(Cryptographic Token Interface Standard):

* PKCS #12(Personal Information Exchange Syntax):
>	Version 1.1:https://www.rfc-editor.org/rfc/pdfrfc/rfc7292.txt.pdf

* PKCS #13(Elliptic Curve Cryptography Standard):
* PKCS #14(Pseudorandom Number Generation Standard):
* PKCS #15(Cryptographic Token Information Format Standard):
####	口令Hash函数
PHC(Password Hashing Competition)是一个类似于NIST的AES和SHA3密码算法竞赛。它发起于2013年，到2014年3月31日为止提交的算法共有24个。2015年7月，该竞赛公布最终获胜的算法————Argon2。
* Argon2:https://password-hashing.net/submissions/specs/Argon-v3.pdf
* AntCrypt:https://password-hashing.net/submissions/specs/AntCrypt-v0.pdf
* battcrypt:https://password-hashing.net/submissions/specs/battcrypt-v0.pdf
* Catena:https://password-hashing.net/submissions/specs/Catena-v5.pdf
* Centrifuge:https://password-hashing.net/submissions/specs/Centrifuge-v0.pdf
* EARWORM:https://password-hashing.net/submissions/specs/EARWORM-v0.pdf
* Gambit:https://password-hashing.net/submissions/specs/Gambit-v1.pdf
* Lanarea:https://password-hashing.net/submissions/specs/Lanarea-v0.pdf
* Lyra2:https://password-hashing.net/submissions/specs/Lyra2-v3.pdf
* Makwa:https://password-hashing.net/submissions/specs/Makwa-v1.pdf
* MCS_PHS:https://password-hashing.net/submissions/specs/MCS_PHS-v2.pdf
* Omega Crypt:https://password-hashing.net/submissions/specs/OmegaCrypt-v0.pdf
* Parallel:https://password-hashing.net/submissions/specs/Parallel-v1.pdf
* PolyPassHash:https://password-hashing.net/submissions/specs/PolyPassHash-v1.pdf
* POMELO:https://password-hashing.net/submissions/specs/POMELO-v3.pdf
* RIG:https://password-hashing.net/submissions/specs/RIG-v2.pdf
* Schvrch:https://password-hashing.net/submissions/specs/Schvrch-v0.pdf
* Tortuga:https://password-hashing.net/submissions/specs/Tortuga-v0.pdf
* TwoCats:https://password-hashing.net/submissions/specs/TwoCats-v0.pdf
* Yarn:https://password-hashing.net/submissions/specs/Yarn-v2.pdf
* yescrypt:https://password-hashing.net/submissions/specs/yescrypt-v2.pdf
* Pufferfish:（待补充）
* M3lcrypt:（待补充）
* Catfish：（待补充）
###		其他：
* Performance of Optimized Implementations of the NESSIE Primitives:https://www.cosic.esat.kuleuven.be/nessie/deliverables/D21-v2.pdf
