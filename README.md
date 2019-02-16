# A primer on Public Private Cryptography by using SJCL.js

* This is a small illustration of the concept of public private cryptography.
* The workflow is as follows:
1. Open sjcl.html in your browser of choice
2. You see your serialized public and private key which is the basic block of every public private cryptography action.
3. Select a file on your computer
4. The encrypted object containing the ciphertext will be base64 enoced and printed out on the html page for you to inspect closer.
5. Your selected file will be encrypted first with your public key and then decrypted with your private key. The newly decrypted file will be opened as base64 string in your browser (use Firefox for ease of use).
6. Inspect if you get the same file or not ;)

Background info:
* NO files will be uploaded to anywhere nor sent around. All action is entirely constrained to within your local browser. 
