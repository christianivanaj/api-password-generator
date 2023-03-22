You can generate a secure password by using JavaScript with the W3C Web Cryptography API. This API uses the crypto.getRandomValues() method, which provides a cryptographically sound way of generating a password.

The following code creates an array of 16 random bytes, and then base64 encodes those bytes to produce a random 16-character string.