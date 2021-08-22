# ElGamal cryptosystem
The ElGamal cryptosystem is defined over a (sub)group \\(\mathbb{G}\\) in which the [DDH assumption](./ddh.md) is assumed to hold.

- **Setup**: 
- **KeyGen**\\((\lambda) \mapsto \langle \mathit{pk}, \mathit{sk} \rangle\\): 
- **Encrypt**\\((m, \mathit{pk}) \mapsto c\\): 
- **Decrypt**\\((c, \mathit{pk}) \mapsto m\\): 

> **Symbol definitions**
> - \\(q\\) - the order \\(|\mathbb{G}|\\) of the (sub)group
> - \\(\lambda\\) - security parameter
> - \\(\mathit{pk} \in \mathbb{G}\\) - public key
> - \\(\mathit{sk} \in \mathbb{Z}_q\\) - secret key
> - \\(m \in \mathbb{G}\\) - plaintext
> - \\(c \in \mathbb{G}\\) - ciphertext

