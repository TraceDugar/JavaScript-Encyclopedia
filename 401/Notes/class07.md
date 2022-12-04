## Class 07 Notes

(https://jwt.io/introduction/)
What is a JSON Web Token (JWT)?
JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed. JWTs can be signed using a secret (with the HMAC algorithm) or a public/private key pair using RSA or ECDSA.
<br>

When should we use JSON Web Tokens?
Here are some scenarios where JSON Web Tokens are useful:

Authorization: This is the most common scenario for using JWT. Once the user is logged in, each subsequent request will include the JWT, allowing the user to access routes, services, and resources that are permitted with that token. Single Sign On is a feature that widely uses JWT nowadays, because of its small overhead and its ability to be easily used across different domains.

Information Exchange: JSON Web Tokens are a good way of securely transmitting information between parties. Because JWTs can be signed—for example, using public/private key pairs—you can be sure the senders are who they say they are. Additionally, as the signature is calculated using the header and the payload, you can also verify that the content hasn't been tampered with.
<br>

Claims are expected in which structural component of a JWT?
Payload
The second part of the token is the payload, which contains the claims. Claims are statements about an entity (typically, the user) and additional data. There are three types of claims: registered, public, and private claims.

Registered claims: These are a set of predefined claims which are not mandatory but recommended, to provide a set of useful, interoperable claims. Some of them are: iss (issuer), exp (expiration time), sub (subject), aud (audience), and others.

<br>

(https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)
If I get a JWT and I can decode the payload, how can we call that secure?
It uses a hash
<br>

If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.
The Hash
<br>

Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.
In order to achieve this we use a HASH which is an extremely long alphanumeric string, and each one is unique.
<br>

(https://www.youtube.com/watch?v=926mknSW9Lo)
Why use JWT?
Securley transfer information between two bodies.
<br>

JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.
It is fast because it is small and the token contains the information about the user.
<br>

What are the three components (the structure) of a JWT signature?
Header, Paylod, and Signature
<br>
