# Steghide

Steghide is a steganography program that is able to hide data in various kinds of image- and audio-files.
The color- respectivly sample-frequencies are not changed thus making the embedding resistant against first-order statistical tests. 

 Features:

      compression of embedded data
      encryption of embedded data
      embedding of a checksum to verify the integrity of the extraced data
      support for JPEG, BMP, WAV and AU files

**Usage**

* Encryption :

      steghide embed -cf file1 -ef file2
      Enter passphrase:
      Re-Enter passphrase:
      embedding "file1" in "file2"... done

* Decryption :

      steghide extract -sf file1
      Enter passphrase:
      wrote extracted data to "file2"
      
* For information about the encrypted file :

> steghide info file
