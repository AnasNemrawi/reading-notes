# Bearer Authorization

1. What is a JSON Web Token (JWT)?

> JWT is a compact and self-contained way of transmitting information between parties as a JSON object.

2.When should we use JSON Web Tokens?

> JWTs are commonly used in authentication and authorization scenarios, where a user logs in and subsequent requests include the token to prove their identity and access privileges.
3.Claims are expected in which structural component of a JWT?

> Claims are expected in the payload component of a JWT.

## Are JWTs Secure?

1.If I get a JWT and I can decode the payload, how can we call that secure?
>while the payload of a JWT can be decoded, the security of the token relies on the implementation of digital signatures and encryption to ensure the integrity and confidentiality of its contents.

2.If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.

>When sending a JSON Web Token (JWT), the sender and receiver must both know a shared secret key. The shared secret key is used for generating and verifying the signature of the JWT.

3.Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.

>The content and secret are concatenated or combined together, creating a single string of characters. This combined string represents the confidential information or token in a secure manner.

## JWTs Explained

1. If I get a JWT and I can decode the payload, how can we call that secure?

> Just being able to decode the payload of a JWT doesn’t automatically make it secure. Security depends on how well the secret key used to sign the token is protected.

2. If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.

> When sending a JWT, both the sender and receiver need to know the secret key. It’s added to the signature part of the JWT and helps ensure its integrity.

3. Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.

> To securely send concatenated content and a secret to a non-technical recruiter, take these steps: Share the secret through a secure method, explain how to receive the content securely (encrypted email, password-protected files), guide on combining the secret and content, stress confidentiality, and offer support if needed.









