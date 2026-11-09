# SOS NOW — ESMARCH

SOS NOW là ứng dụng hỗ trợ sơ cứu và tìm cơ sở y tế gần nhất, phát triển bởi nhóm **ESMARCH**.

## Cấu trúc

| Thư mục | Nội dung |
|---|---|
| `sos-now/` | Ứng dụng web chính (React + Vite) |
| `demo-voice/` | Demo trợ lý giọng nói (Next.js) |
| `asr/` | Dịch vụ nhận dạng giọng nói (Python) |
| `tts/` | Giọng đọc tổng hợp |
| `map-data/` | Dữ liệu bản đồ Sài Gòn cho tính đường đi |
| `vendor/` | Leaflet, MapLibre GL |

## Chạy local

```bash
cd sos-now
npm install
npm run dev
```

## Quy trình làm việc

Xem [CONTRIBUTING.md](CONTRIBUTING.md): `feat/*` → PR vào `dev` → PR `dev` vào `main`.

## Nguồn gốc

Dự án được phát triển dựa trên [christian-hoang-04/first-aid](https://github.com/christian-hoang-04/first-aid) (MIT License). Xem [LICENSE](LICENSE).
