# 🔐 Cheatsheet: Hashing Algorithms

This cheatsheet highlights commonly tested hashing algorithms on the CompTIA Security+ (SY0-701) exam. Hashes are one-way functions used to verify data integrity.

---

## 🧬 What Is Hashing?
- A **one-way function** that converts input data into a fixed-size string (digest)
- Used for **integrity checking**, not encryption
- Hashes should be:
  - **Deterministic** (same input → same output)
  - **Irreversible** (cannot reverse the output)
  - **Collision-resistant** (hard to produce the same hash from two inputs)

---

## 🧪 Common Hashing Algorithms

| Algorithm | Digest Size | Use Case |
|----------|--------------|----------|
| **MD5** | 128-bit | Deprecated – used for checksums, file validation |
| **SHA-1** | 160-bit | Weak – legacy systems only |
| **SHA-2** | 224/256/384/512-bit | Strong – widely used for digital signatures, SSL |
| **SHA-256** | 256-bit | Most common variant of SHA-2 |
| **SHA-3** | Variable | Latest standard – less common in practice yet |
| **HMAC** | Varies | Hash + secret key – used for data integrity & authentication |

---

## 🛡️ Real-World Usage
- **Passwords** → Hash and compare during login
- **File integrity** → Compare hashes after download
- **Digital signatures** → Prove authenticity
- **HMAC** → API key validation and message integrity

---

## 📌 Study Tips
- Know the difference between **encryption** and **hashing**
- MD5 and SHA-1 are considered **broken** (vulnerable to collisions)
- SHA-256 and HMAC are most likely to show up on the test

---

> "Encryption hides data. Hashing proves it hasn’t changed."

