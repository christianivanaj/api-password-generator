You can generate a secure password by using JavaScript with the W3C Web Cryptography API. This API uses the crypto.getRandomValues() method, which provides a cryptographically sound way of generating a password.

The following code creates an array of 32 random bytes, and then base64 encodes those bytes to produce a random 16-character string.

----------
Changelog
----------
2023/06/26
  - Stylized the page to make it more appealing
  - Added a "copy to clipboard" feature to make it easier with copying
  - Switched to a 32-bit array
  - Grabbing from the middle of the array instead of the first 16 characters
  - Incorporated Google Fonts with the "Roboto" font family
    
2023/03/22
  - CSS changes, switched from 16-bit array to 24-bit
    
2023/03/27
  - Class assigning for generator and button. Will need to have "fixed" positions so that way the button doesn't shift with the password characters
    
