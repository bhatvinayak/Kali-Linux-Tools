# Hashcat

Hashcat is the world's fastest and most advanced password recovery utility, supporting five unique modes of attack for over 300 highly-optimized hashing algorithms. hashcat currently supports CPUs, GPUs, and other hardware accelerators on Linux, Windows, and macOS, and has facilities to help enable distributed password cracking.

**Syntax**

> # hashcat [options] hash|hashfile|hccapxfile [dictionary|mask|directory]


**Options**

* Hash type :

> -m [number]

* Attack mode :

> -a [number]

    0 | Straight
    1 | Combination
    3 | Brute-force
    6 | Hybrid Wordlist + Mask
    7 | Hybrid Mask + Wordlist
    
* For help :

> --help

