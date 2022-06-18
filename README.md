# signer
Authentifies your file data easily.

### Usage:
This is a library that uses openssl to create private key, public key and sign files you wishes to be signed...

You need share both signature file and your public key to let ppl ensure authenticity.

#### to use signer you must source it thru your scripting or interactive shell to use it by hand...

```shell
# signer.privkey() - creates a directory then generate and install a private key.
# signer.pubkey() - creates a public key from your private key (optionally generate one if there is none)
# signer.sign() - the signing interface that uses private key
# signer.verify() - authenticates file from public key with signature
# signer.sign.sha1() - signs data using sha1
# signer.verify.sha1() - verifies sha1 signature
# Contact Support: 555-911-911 RobCo Industries. :)
# Have fun.
```

