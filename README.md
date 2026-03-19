# mini-hsm
A tiny Security Module for the [MM-2350 board](https://minimacy.net/MM-2350.html), the bare-metal Raspberry Pi 4 board and any computer with an operating system.

The application offers these functionalities:
-	key management: RSA, elliptic curves, ED25519, X25519, AES, DES, DES3
-	key-based operations: encryption/decryption, signing/verification, Diffie-Hellman key exchange
-	keyless operations: hashing, base64/ascii/hex encoding, random sequence generation
-	access via console, http(s) and ssh
-	user management
-	authentication by ssh key, ssl certificate or password
-	fine-grained access rights management
-	customisable formatting of result display

The application can run on any type of platform:
-	on a computer or mobile device with an OS: Windows, Unix-like, MacOS, iOS, Android
-	bare-metal on the Raspberry Pi 4 board
-	bare-metal on the MM-2350 board

Documentation is here: [MiniHSM](https://minimacy.net/book/#/tag/MiniHsm)

## About MINIMACY
Computing is something too serious to be left to machines.
Humans must be able to understand 100% of what's going on in the machine. Otherwise, there can be no serious talk of cybersecurity or sovereignty.
No technology allows it today... except MINIMACY!

MINIMACY is an open-source minimalist computation system based on the principle “Less is more”, so that a single human can understand 100% of the system operation.
It is designed and programmed by [Sylvain Huet](https://sylvain-huet.com/).

Website: [https://minimacy.net/](https://minimacy.net/)

You'll find a release including binaries in the github's "Releases" section.

All the documentation is centralized in The Book: [https://minimacy.net/book](https://minimacy.net/book)
