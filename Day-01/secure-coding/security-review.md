# Security Review

## Finding 1 — Hard-coded credentials

The application stores the username and password
directly inside the source code.

### Risk
An attacker who obtains the source code could
discover the credentials.

### Recommendation
Credentials should not be stored directly in source code.

---

## Finding 2 — Weak password

The password "123456" is extremely weak.

### Risk
The password could easily be guessed or cracked.

### Recommendation
Use strong passwords and secure password
storage mechanisms.

---

## Finding 3 — No password hashing

The example does not demonstrate secure password storage.

### Recommendation
Passwords should be securely hashed using an
appropriate password-hashing algorithm.