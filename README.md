# 🌐 FreeLang HTTP Engine

[![Language](https://img.shields.io/badge/language-Rust-orange.svg)](#)
[![Status](https://img.shields.io/badge/status-Production%20Ready-brightgreen.svg)](#)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE)
[![GitHub](https://img.shields.io/badge/GitHub-kimjindol2025%2Ffreelang--http--engine-blue?logo=github)](https://github.com/kimjindol2025/freelang-http-engine)

**고성능 HTTP/HTTPS 서버 엔진**

## 🎯 기능

- ✅ HTTP/1.1 & HTTP/2 지원
- ✅ TLS/SSL 암호화
- ✅ Keep-Alive 연결
- ✅ Request/Response 파이프라인
- ✅ Middleware 지원

## 🚀 사용법

```freeLang
let server = HttpServer::new()
server.route("/", get(index))
server.route("/api/data", get(fetch_data))
server.listen(8080)
```

## 📊 성능

- 처리량: 50K+ req/s
- 지연시간: <1ms p99
- 메모리: <100MB baseline

## 라이선스

MIT License © 2026

---

**버전**: 2.5.0 | **업데이트**: 2026-03-16 | **상태**: 🟢 프로덕션
