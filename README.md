This repository contains final year project, 'Data Encryption Standard Analysis'. DES is a symmetric block cipher (shared secret key), with a key length of 56-bits. Published as the Federal Information Processing Standards (FIPS) 46 standard in 1977. After the publication of DES, it was criticized severely for the small key length, which could make the cipher vulnerable to brute-force attack. DES was officially withdrawn in 2005. For a modern-day computer, a brute force attack using 256 keys is a matter of few days. This project studies the DES algorithm by increasing the key size in order to try to overcome small key size problem. DES key generation algorithm is modified in this project to use 128-bit keys. DES is first implemented in Sage Math notebooks using Sagemath DES library to build an understanding of DES. Next step was to code DES algorithm. A modified DES is implemented after changing key scheduling algorithm and increasing the key size to 128 bits. After implementation, analysis is performed by noting differences between performance of standard DES and modified DES. The analysis is performed by measuring avalanche effect by implementing both algorithms on same plaintext.
