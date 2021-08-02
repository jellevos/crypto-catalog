# Asymmetric cryptosystems
_Also: public-key cryptography._

An **asymmetric cryptosystem** defines the following operations:
- **Setup**: Any operation that describes prerequisites for the cryptosystem, for example the construction of a special group.
- **KeyGen**\\((\lambda) \mapsto \langle \mathit{pk}, \mathit{sk} \rangle\\): Generates a public-secret key pair used to encrypt and decrypt.
- **Encrypt**\\((m, \mathit{pk}) \mapsto c\\): Encrypts a message using the public key into a ciphertext.
- **Decrypt**\\((c, \mathit{pk}) \mapsto m\\): Decrypts a ciphertext using the secret key to recover the plaintext.
