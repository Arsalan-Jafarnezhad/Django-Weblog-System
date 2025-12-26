# 🚀 Python HTTP Client Speed Comparison

A **real-world performance comparison** of popular Python HTTP clients,  
sorted by **throughput, concurrency scaling, and efficiency**.

> **Top = fastest in practice**

---

## 🏆 Ranked Comparison Table

| Rank | Library            | Async | Single Req Speed | High Concurrency | Protocols            | Notes |
|-----:|--------------------|:-----:|------------------|------------------|----------------------|------|
| 1 | **aiohttp** | ✅ | ⭐⭐⭐⭐☆ | ⭐⭐⭐⭐⭐ | HTTP/1.1 | Best raw async throughput |
| 2 | **httpx (async)** | ✅ | ⭐⭐⭐⭐☆ | ⭐⭐⭐⭐☆ | HTTP/1.1, HTTP/2 | Modern & clean |
| 3 | **trio + httpx** | ✅ | ⭐⭐⭐⭐☆ | ⭐⭐⭐⭐☆ | HTTP/1.1, HTTP/2 | Structured concurrency |
| 4 | **urllib3** | ❌ | ⭐⭐⭐⭐☆ | ❌ | HTTP/1.1 | Low-level, very efficient |
| 5 | **httpcore** | ✅ | ⭐⭐⭐⭐☆ | ⭐⭐⭐☆☆ | HTTP/1.1, HTTP/2 | Engine behind httpx |
| 6 | **pycurl** | ❌ | ⭐⭐⭐⭐☆ | ❌ | HTTP/1.1, HTTP/2 | libcurl bindings |
| 7 | **requests** | ❌ | ⭐⭐⭐☆☆ | ❌ | HTTP/1.1 | Most popular |
| 8 | **asks** | ✅ | ⭐⭐⭐☆☆ | ⭐⭐⭐☆☆ | HTTP/1.1 | Async wrapper |
| 9 | **treq** | ✅ | ⭐⭐⭐☆☆ | ⭐⭐⭐☆☆ | HTTP/1.1 | Twisted ecosystem |
| 10 | **urllib.request** | ❌ | ⭐⭐☆☆☆ | ❌ | HTTP/1.1 | Python stdlib |

---

## ⚡ Key Takeaways

### 🥇 Fastest Async
- **aiohttp** — highest throughput under load
- **httpx async** — slightly slower but much nicer API

### 🥈 Fastest Sync
- **urllib3**
- **httpx sync**

### 🧠 Best Developer Experience
- **httpx**
- **requests** (simplicity > speed)

### 🧨 Absolute Max Throughput
- **fasthttp (Go)** — not Python, but destroys all Python clients

---

## 📌 Recommendations

- **APIs / Microservices** → `httpx`
- **Scraping / Crawling** → `aiohttp`
- **Quick scripts** → `requests`
- **Low-level control** → `urllib3`
- **Extreme scale** → Go + `fasthttp`

---

> Python async beats threading.  
> HTTP/2 beats HTTP/1.1.  
> Convenience always costs performance.
