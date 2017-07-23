# CTF Resources/Links
## General CTF resources
**https://trailofbits.github.io/ctf/ (The CTF Field Guide)**

http://resources.infosecinstitute.com/tools-of-trade-and-resources-to-prepare-in-a-hacker-ctf-competition-or-challenge/#gref

https://github.com/apsdehal/awesome-ctf
(list of CTF tools)

https://github.com/Gallopsled/pwntools
    (CTF challenge automation tool - usefulness of this tool may vary)
    
Past CTF writeups :) (see below)

## Past CTF Writeups:

https://writeups.easyctf.com/
(EasyCTF 2015)

https://ehsandev.com/pico2014/
(PicoCTF 2014)

https://github.com/ctfs/write-ups-2016

https://github.com/ctfs/write-ups-2017
    (collections of CTF writeups)
    
https://www.youtube.com/watch?v=BKRx_pgliQ4

## Useful specifically for problems on EasyCTF 2017:
https://cryptsec.wordpress.com/2016/03/21/bctf-2016-write-up-special-rsa-crypto-200/
(RSA challenge writeup)

https://github.com/ctfs/write-ups-2016/tree/master/angstromctf-2016/re/java-is-the-best-50

http://gmiru.com/writeups/bkp-frog/
    (Reverse engineering challenge writeups)
    
http://www.computerhope.com/unix/udiff.htm
(diff command in shell)

https://stackoverflow.com/questions/9899049/placing-every-character-on-a-new-line
(used for petty diff challenge)

http://www.garykessler.net/library/file_sigs.html
    File signature reference
## Virtual servers (for running CTF software) (some are free to use)
https://sandstorm.io/

https://c9.io/

https://www.heroku.com/

https://codeanywhere.com/

## Specific CTF Challenge Type Concepts/Tools
### Cryptography:
https://en.wikipedia.org/wiki/RSA_(cryptosystem)
(RSA challenges)

http://www.xarg.org/tools/caesar-cipher/
(Caesar cipher)

http://rumkin.com/tools/cipher/
(Collection of cryptography tools)

http://moonatnoon.com/puzzles/reference/a1b2z26.html
(Alphabet table)

### Forensics:
http://opensecuritytraining.info/CTFForensics.html

http://www.openstego.com/
(hiding secret messages in some images)

https://29a.ch/photo-forensics
    Very useful photo forensics tool, used in: https://github.com/1lastBr3ath/EasyCTF-2015-Writeup/blob/master/forensics.md#who-is-this-god---175-points

### Reverse engineering & binary exploitation:
http://askubuntu.com/a/573570
(hex editor for files)

https://github.com/radare/radare2
(for reverse engineering challenges, assembly language or similar low-level language knowledge may transition from easier to harder challenges)

#### x86 (as seen on PicoCTF 2014)

https://www.youtube.com/watch?v=75gBFiFtAb8 (x86 Crash Course, highly recommended!)

https://www.youtube.com/watch?v=qn1_dRjM6F0 (**NOTE!!!** The assembly code uses AT&T syntax)

https://www.youtube.com/watch?v=yOyaJXpAYZQ (**NOTE!!!** This also uses AT&T syntax)

https://stackoverflow.com/questions/20408884/what-does-mean-in-assembly

https://stackoverflow.com/questions/9196655/what-do-the-dollar-and-percentage-signs-represent-in-assembly-intel-x86

http://www.cs.virginia.edu/~evans/cs216/guides/x86.html (list of x86 instructions or commands)

https://cseweb.ucsd.edu/~dkohlbre/ctf/introx86talk.pdf (basics: pages 4-6, 8-11 and 18-19, and pages 12-23 for higher-point CTF problems ex. ROP exploits)

**NOTE: AT&T syntax uses the syntax: INSTRUCTION Destination, Src and Intel uses INSTRUCTION Src, Destination**

**Or in layman’s terms...
AT&T: do X from destination to source
Intel: do X from source to destination**

##### AT&T syntax specifics
https://en.wikibooks.org/wiki/X86_Assembly/GAS_Syntax

### Web exploitation (may involve the use of reverse engineering software):
Some brief background:
http://opensourceforu.com/2012/03/cyber-attacks-explained-web-exploitation/

https://www.youtube.com/watch?v=gRuW4UE9oLE (Wireshark tutorial)

**https://whois.domaintools.com/ (WHOIS lookup and backend server information lookup)**

### Tutorials (recommended: look at past CTF writeups, some writeups include links to different web tools):
https://ehsandev.com/pico2014/web_exploitation/make_a_face.html (<-- textbook [common] CTF problem style)

https://ehsandev.com/pico2014/web_exploitation/potentially_hidden_password.html

https://ehsandev.com/pico2014/web_exploitation/delicious.html

http://securityidiots.com/Web-Pentest/SQL-Injection/bypass-login-using-sql-injection.html (SQL injection)

http://sqlzoo.net/hack/16password.htm (SQL injection testing/demo)