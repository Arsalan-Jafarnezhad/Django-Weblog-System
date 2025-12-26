# 🔐 Python Hashing & Cryptography Libraries

Sorted by **overall usefulness** (number of ✅).

---

## 🏆 Comparison Table

| # | Library | Enc | Hash | Pwd | Modern | Maint | Popular |
|---:|---|:--:|:--:|:--:|:--:|:--:|:--:|
| 1 | [cryptography](https://github.com/pyca/cryptography) | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| 2 | [PyNaCl](https://github.com/pyca/pynacl) | ✅ | ✅ | ❌ | ✅ | ✅ | ✅ |
| 3 | [argon2-cffi](https://github.com/hynek/argon2-cffi) | ❌ | ✅ | ✅ | ✅ | ✅ | ✅ |
| 4 | [bcrypt](https://github.com/pyca/bcrypt) | ❌ | ✅ | ✅ | ✅ | ✅ | ✅ |
| 5 | [hashlib](https://github.com/python/cpython) | ❌ | ✅ | ❌ | ✅ | ✅ | ✅ |
| 6 | [passlib](https://github.com/passlib/passlib) | ❌ | ✅ | ✅ | ❌ | ⚠️ | ✅ |
| 7 | [itsdangerous](https://github.com/pallets/itsdangerous) | ❌ | ✅ | ❌ | ❌ | ✅ | ✅ |
| 8 | [PyJWT](https://github.com/jpadilla/pyjwt) | ❌ | ✅ | ❌ | ❌ | ✅ | ✅ |
| 9 | [jwcrypto](https://github.com/latchset/jwcrypto) | ✅ | ✅ | ❌ | ❌ | ⚠️ | ❌ |
| 10 | [pycryptodome](https://github.com/Legrandin/pycryptodome) | ✅ | ✅ | ❌ | ❌ | ⚠️ | ❌ |
| 11 | [pyOpenSSL](https://github.com/pyca/pyopenssl) | ✅ | ❌ | ❌ | ❌ | ⚠️ | ✅ |
| 12 | [pbkdf2](https://github.com/pyca/pbkdf2) | ❌ | ✅ | ✅ | ❌ | ⚠️ | ❌ |
| 13 | [rsa](https://github.com/dlitz/python-rsa) | ✅ | ❌ | ❌ | ❌ | ⚠️ | ❌ |
| 14 | [python-olm](https://github.com/matrix-org/python-olm) | ✅ | ❌ | ❌ | ✅ | ⚠️ | ❌ |
| 15 | [oscrypto](https://github.com/wbond/oscrypto) | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ |
| 16 | [ed25519](https://github.com/warner/python-ed25519) | ❌ | ❌ | ❌ | ✅ | ❌ | ❌ |
| 17 | [secure-cookie](https://github.com/tiran/secure-cookie) | ❌ | ✅ | ❌ | ❌ | ⚠️ | ❌ |
| 18 | [python-jose](https://github.com/jpadilla/python-jose) | ❌ | ✅ | ❌ | ❌ | ⚠️ | ❌ |
| 19 | [fernet](https://github.com/pyca/fernet) | ✅ | ❌ | ❌ | ⚠️ | ⚠️ | ❌ |
| 20 | [blake3]() | ❌ | ✅ | ❌ | ✅ | ⚠️ | ❌ |

---

## 🧠 Rules of Thumb

- **Passwords** → `argon2-cffi`
- **General crypto** → `cryptography`
- **Misuse-resistant** → `PyNaCl`
- **JWT / tokens** → `PyJWT`
- **Never invent crypto**

> Secure crypto is boring — and that’s a good thing.
