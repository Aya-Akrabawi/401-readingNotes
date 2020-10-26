# Calss 12:

**Open Authorization**
OAuth (Open Authorization) is an open standard for token-based authentication and authorization on the Internet. OAuth, allows an end user's account information to be used by third-party services, such as Facebook, without exposing the user's password.

**How does OAuth authentication work?**
It works by delegating user authentication to the service that hosts the user account, and authorizing third-party applications to access the user account.

OAuth work through a series of handshakes, the app asks the user if it is ok to login as them at some remote service and then begins the process of authentication and access.


**Access Code**
The authorization code grant is used when an application exchanges an authorization code for an access token. After the user returns to the application via the redirect URL, the application will get the authorization code from the URL and use it to request an access token. This request will be made to the token endpoint.

* Request Parameters The access token request will contain the following parameters.

* grant_type (required) The grant_type parameter must be set to “authorization_code”.

* code (required) This parameter is the authorization code that the client previously received from the authorization server.

* redirect_uri (possibly required) If the redirect URI was included in the initial authorization request, the service must require it in the token request as well. The redirect URI in the token request must be an exact match of the redirect URI that was used when generating the authorization code. The service must reject the request otherwise.

**Review**
because it enables organizations to keep their networks secure by permitting only authenticated users (or processes) to access its protected resources, which may include computer systems, networks, databases, websites and other network-based applications or services.


**Why should we be careful about storing a user’s password?**
If you do not take the right precautions when storing passwords, you could expose your user passwords to an attacker. Many people use the same email and password combination all over the Internet. If you expose their password, they could be left vulnerable on other websites or web applications as well.


**What is the difference between hashing and encryption?**
Encryption is a two-way function; what is encrypted can be decrypted with the proper key. Hashing, however, is a one-way function that scrambles plain text to produce a unique message digest. With a properly designed algorithm, there is no way to reverse the hashing process to reveal the original password.


**What is the difference between encryption and encoding?**
Encoding is for maintaining data usability and can be reversed by employing the same algorithm that encoded the content, i.e. no key is used. Encryption is for maintaining data confidentiality and requires the use of a key (kept secret) in order to return to plaintext.


**What is a token used for?**
A token is used to make security decisions and to store tamper-proof information about some system entity. While a token is generally used to represent only security information, it is capable of holding additional free-form data that can be attached while the token is being created.