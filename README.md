## Data Encryption Standard (DES) Encryption Scheme

This [**C#**](https://en.wikipedia.org/wiki/C_Sharp_(programming_language)) project implements the **[Data Encryption Standard (DES)](https://en.wikipedia.org/wiki/Data_Encryption_Standard)** Symmetric Encryption Scheme. 

The Data Encryption Standard (DES) is a **symmetric-key algorithm** for the encryption of electronic data. Although its short key length is of 56 bits, criticized from the beginning, makes it too insecure for most current applications, it was highly influential in the advancement of modern cryptography.

Developed in the early 1970s at IBM and based on an earlier design by Horst Feistel, the algorithm was submitted to the National Bureau of Standards (NBS) following the agency's invitation to propose a candidate for the protection of sensitive, unclassified electronic government data. In 1976, after consultation with the National Security Agency (NSA), the NBS eventually selected a slightly modified version (strengthened against differential cryptanalysis, but weakened against brute-force attacks), which was published as an official Federal Information Processing Standard (FIPS) for the United States in 1977.

DES is the archetypal block cipher—an algorithm that takes a fixed-length string of plaintext bits and transforms it through a series of complicated operations into another ciphertext bitstring of the same length. In the case of DES, the block size is 64 bits. DES also uses a key to customize the transformation, so that decryption can supposedly only be performed by those who know the particular key used to encrypt. The key ostensibly consists of 64 bits; however, only 56 of these are actually used by the algorithm. Eight bits are used solely for checking parity, and are thereafter discarded. Hence the effective key length is 56 bits.


## File Description




## Compile and Run
  
  Writing C# Programs on Linux:
  
  Mono is an open-source version of the .NET Framework which includes a C# compiler and runs on several operating systems, including various flavors of Linux and Mac OS. Check for [Mono](https://www.mono-project.com/download/stable/).
  
  To Compile:
  
  > **mcs DES.cs**
  
  The compiler will create **"DES.exe"**, which you can run using:
  
  > **mono DES.exe**
  
  
  ## Execution with Pictures
  
  To Compile:
  
  ![Compile](https://github.com/arupmondal-cs/DES-Encryption/blob/master/Picture/compile.png)
  
  To Execution:
  
  ![Execution](https://github.com/arupmondal-cs/DES-Encryption/blob/master/Picture/run.png)

## References

  * https://en.wikipedia.org/wiki/Data_Encryption_Standard
  * https://docs.microsoft.com/en-us/dotnet/api/system.security.cryptography.des.create?view=netframework-4.8
