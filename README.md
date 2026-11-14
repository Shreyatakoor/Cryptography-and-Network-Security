RSA Cryptanalysis: Small Factorization Attack

Project Overview

RSA Cryptanalysis: Small Factorization Attack is an educational project that demonstrates how RSA encryption can be compromised when weak key-generation parameters are used.

The project explores different integer factorization techniques to identify the prime factors of an RSA modulus. Once the factors are obtained, the private key can be reconstructed, allowing the original encrypted message to be decrypted.

This project also includes an interactive RSA Cryptanalysis Virtual Lab to demonstrate RSA key generation, encryption, decryption, and small factorization attacks.

🚀 Live Demo

Try the deployed application here:

https://leafy-bavarois-c7d3cd.netlify.app/

🎯 Objectives

- Understand the working principle of RSA cryptography.
- Demonstrate the importance of secure RSA key generation.
- Implement different integer factorization techniques.
- Recover RSA private keys from weak public keys.
- Demonstrate encryption, decryption, and cryptanalysis.

🔐 Algorithms Implemented

1. Trial Division

Tests possible factors of the RSA modulus to identify its prime factors.

2. Pollard's Rho Algorithm

Uses a pseudo-random sequence and greatest common divisor calculations to find non-trivial factors.

3. Fermat's Factorization

Uses the difference of two squares to factorize an RSA modulus when its two prime factors are close together.

4. RSA Private Key Recovery

After obtaining the prime factors, the algorithm reconstructs Euler's totient function and calculates the private exponent.

⚙️ Working Procedure

1. Generate RSA keys using two prime numbers.
2. Calculate the modulus (n) and Euler's totient function φ(n).
3. Generate the public and private keys.
4. Encrypt a plaintext message using the public key.
5. Apply factorization techniques to identify the prime factors.
6. Reconstruct the private key.
7. Decrypt the ciphertext and recover the original message.

✨ Features

- RSA key generation.
- Public and private key display.
- Message encryption.
- Message decryption.
- Input validation for prime numbers.
- Small factorization attack demonstration.
- Private key recovery.
- Interactive cryptanalysis demonstration.

🧪 Testing and Validation

The deployed virtual lab was verified using six test cases:

1. Initial page loading.
2. Valid RSA keypair generation.
3. Input validation for non-prime numbers.
4. Message encryption.
5. Message decryption using the private key.
6. Small factorization attack and plaintext recovery.

All six application test cases were verified successfully.

The Python implementation was also evaluated using an automated test suite containing 21 test cases, all of which passed.

💻 Technologies Used

- Python
- RSA Cryptography
- Number Theory
- Integer Factorization Algorithms
- Netlify (Deployment)

📌 Key Learning Outcomes

- Understanding RSA encryption and decryption.
- Learning different integer factorization methods.
- Understanding RSA vulnerabilities caused by weak prime selection.
- Learning private key reconstruction.
- Understanding the importance of strong cryptographic key generation.


Course: Cryptography and Network Security (BCS703)

⚠️ Disclaimer

This project is developed strictly for academic and educational purposes to demonstrate RSA cryptanalysis using intentionally weak demonstration keys. It does not demonstrate a practical break of correctly generated, secure RSA keys.
