# Digital Signature using OpenSSL

## Objective
To generate and verify a digital signature using OpenSSL and demonstrate data integrity.

## Files
- prediction.txt : Original document
- signature : Digital signature generated using private key
- public_key.pem : Public key used for verification

## Steps
1. Generate RSA key pair
2. Sign the document using SHA-256
3. Verify the signature using public key
4. Modify the document and re-verify

## Result
- Verification succeeds for original document
- Verification fails after document modification

## Conclusion
Digital signatures ensure integrity, authentication, and non-repudiation.

## Commands Used

### Generate Private Key
```bash
openssl genrsa -out private_key.pem 2048


