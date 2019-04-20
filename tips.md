# Handy CTF Resources

Please keep in alphabetical order so they are easier to find.

## Online tools

### Binary tools

* [Online Disassembler](https://www.onlinedisassembler.com/odaweb/)
* [ROP shell](http://ropshell.com)
* [Binvis](http://binvis.io)
* [binwalk](https://github.com/devttys0/binwalk) Analyze a blob and find files within

### Code Formatters

* [JS Beautifier](http://jsbeautifier.org)
* [JSON Formatter](https://jsonformatter.curiousconcept.com)

### Converters and decoders

* [lots of encodings simultaneously](https://www.xil.se/ctf/tools/tools.html#conv/)
* [base64 encoder/decoder](http://www.motobit.com/util/base64-decoder-encoder.asp)
* [hex, dec, bin and ascii converter](https://www.branah.com/ascii-converter)
* [ook and brainfuck encoder/decoder](http://www.splitbrain.org/services/ook)
* [rot13](http://www.rot13.com)

### Hash / RSA cracking 

* [crackstation](https://crackstation.net/) Cracks unsalted md5, sha1 etc.
* [factordb](http://factordb.com/) online factor tool/database.

### Image tools

* [Reverse image search](http://tineye.com)

### Network tools

* [Port scanner](http://www.t1shopper.com/tools/port-scan/)
* [Reverse IP domain search](http://www.yougetsignal.com/tools/web-sites-on-web-server/)






## Local tools

### Android
* [Android APK Decompiler](http://www.javadecompilers.com/apk) Online decompile tool
* [apktool](http://ibotpeaches.github.io/Apktool/) APK extractor, uses smali do disassemble dex
* [dex2jar](https://github.com/pxb1988/dex2jar) Dex to java decompiler, fails sometimes
* [jadx](https://github.com/skylot/jadx) Alternative dex to java decompiler, might not fail when dex2jar fails

### Binary unpackers
* [Detect It Easy](http://ntinfo.biz/)
* [FUU Fast Universal Unpacker](https://github.com/crackinglandia/fuu)
* [PEiD](http://www.softpedia.com/get/Programming/Packers-Crypters-Protectors/PEiD-updated.shtml)
* [Universal Extractor](http://legroom.net/software/uniextract)

### Crypto
* [numpy](http://www.numpy.org/) powerful number cruncher
* [pycrypto](http://pythonhosted.org/pycrypto/) various crypto and hash implementations (sha-1, aes, ...)
* [pynacl](https://pypi.python.org/pypi/PyNaCl/) python bindings to nacl (elliptic curve etc)
* [pyopenssl](https://github.com/pyca/pyopenssl) python bindings to openssl
* Factoring RSA keys
 * [sympy](http://www.sympy.org/en/index.html) includes ntheory.factorint() which is the best allround factoring algo. Solves most ctf-cases.
 * [yafu](https://sourceforge.net/projects/yafu/) includes factor(), not good at pq that are similar for big modulo
 * [primefac](https://pypi.python.org/pypi/primefac) python module to factor large numbers, works in parallell
 * [ECM factorization applet](https://www.alpertron.com.ar/ECM.HTM) Horrible java applet but it can find p and q fast if they are close.
* [quipqiup](http://quipqiup.com/) Substitution cracker

### Forensics tools

* [Volatility](https://github.com/volatilityfoundation)

### Hash
* [hashcat](https://hashcat.net/oclhashcat/) Powerful hash cracker
* [HashPump](https://github.com/bwall/HashPump) Hash length extention attack tool
* [jtr/John The Ripper](http://www.openwall.com/john/) Password cracker that supports many standard formats (/etc/shadow etc)

### Network tools
* [aircrack-ng](http://www.aircrack-ng.org/)
* [Scapy](http://www.secdev.org/projects/scapy/)

### PRNG
 * [untwister](https://github.com/altf4/untwister) Can recover seed from various PRNG such as Mersenne Twister, PHP, Ruby.

### PWN / Binary exploitation
 * ~~pwntools~~ [binjitsu](https://github.com/binjitsu/binjitsu)
 * [libc database](https://github.com/niklasb/libc-database)
 * [ROPGadget](https://github.com/JonathanSalwan/ROPgadget)
 * [How to preload libc fakes](https://rafalcieslak.wordpress.com/2013/04/02/dynamic-linker-tricks-using-ld_preload-to-cheat-inject-features-and-investigate-programs/), implement them and use LD_PRELOAD, but it can be nice to copypaste
 * [GDB-PEDA](https://github.com/longld/peda) Make GDB great again!

### Signal decoding
* [Digital radio transmission decoder](https://github.com/EliasOenal/multimon-ng)
* [PRAAT](http://www.fon.hum.uva.nl/praat/) Used to map [sound of keystrokes to keys](https://www.xil.se/post/sharifctf-2016-misc-sound-rspkt/)

### SSL tools
 * [heartleech](https://github.com/robertdavidgraham/heartleech) snoop private key from heartbleed pcap data [see writeup](https://github.com/hexpresso/WU-2016/tree/master/insomnihack-ctf-2016/crypto/pcapbleeding).

### Stegano
 * [SmartDeblur](https://github.com/Y-Vladimir/SmartDeblur)



## Programming languages

* [Malbolge](http://www.tutorialspoint.com/execute_malbolge_online.php)
* [Piet](http://www.bertnase.de/npiet/npiet-execute.php)
