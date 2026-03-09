# Task 1 – Encoding Formats and Secure Data Exchange

Encoding formats play a crucial role in enabling reliable data transmission across networks. Although encoding does not provide encryption or confidentiality, it ensures that data can be safely transmitted through systems that expect text-based formats.

## Base64 Encoding

Base64 converts binary data into ASCII characters using a 64-character alphabet. It is widely used in:

* Email attachments (SMTP and MIME)
* Web authentication tokens
* REST API payloads

The advantage of Base64 is that it allows binary data such as images or certificates to be transmitted safely through text-based protocols.

However, Base64 increases data size by approximately 33 percent and does not provide security on its own.

## Hex Encoding

Hexadecimal encoding represents binary data using characters from the hexadecimal number system. Each byte is represented by two hexadecimal digits.

This format is commonly used for:

* Cryptographic hashes
* Memory debugging
* Protocol analysis

Although easy to read and debug, hexadecimal encoding doubles the size of the original data.

## URL Encoding

URL encoding replaces reserved characters in URLs with a percent symbol followed by hexadecimal values.

Example:

Space → %20

This encoding ensures that URLs remain valid when they contain special characters.

## Encoding in Secure Protocols

Encoding formats are often combined with secure protocols such as TLS and HTTPS. The encoding ensures compatibility, while TLS encryption provides confidentiality and data protection during transmission.

This layered approach allows encoded data to be safely transmitted across networks while maintaining compatibility with modern web systems.

