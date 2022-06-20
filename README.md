# GoogleAuth
 Google Authenticator API

## Usage
**Get secret key**
```
GoogleAuthenticator gAuth = new GoogleAuthenticator();
GoogleAuthenticatorKey key = gAuth.createCredentials();
String secretKey = key.getKey();
```

**Check the code of secret key**
```
GoogleAuthenticator gAuth = new GoogleAuthenticator();
boolean codeIsValid = gAuth.authorize(secretkey, code);
```
