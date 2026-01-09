# Newhomes Quote Tool

Tool báo giá nội thất cho Newhomes.

## 🌐 Live URL

**Subdomain:** https://baogia.noithatnewhomes.vn

## Cấu trúc

```
├── data/
│   └── data.json           ← Dữ liệu giá, vật liệu
├── index.html              ← Tool báo giá (có Hero + FAQ)
├── admin.html              ← Admin panel quản lý giá
├── quote-tool-embed.html   ← Code nhúng WordPress (backup)
├── CNAME                   ← Custom domain config
└── README.md
```

## Cách sử dụng

### 1. Xem Tool báo giá
https://baogia.noithatnewhomes.vn

### 2. Admin Panel (quản lý giá)
https://baogia.noithatnewhomes.vn/admin.html

## Cập nhật giá

1. Vào Admin Panel
2. Sửa giá/vật liệu theo ý muốn
3. Click "Tải file data.json"
4. Upload file lên GitHub (thay thế file cũ trong folder `data/`)
5. Chờ ~5-10 phút để GitHub Pages cập nhật

## Setup Subdomain

### DNS (Cloudflare)
```
Type: CNAME
Name: baogia
Target: windlyu12.github.io
Proxy: OFF (DNS only)
```

### GitHub Pages
- Settings → Pages → Custom domain: `baogia.noithatnewhomes.vn`
- Enforce HTTPS: ✅

## SEO

Tool đã được tối ưu SEO với:
- Title & Description
- Open Graph tags
- Canonical URL
- Hero section với background
- FAQ section (6 câu hỏi)

## Changelog

### v11 (2026-01-08)
- Thêm Hero section với background image
- Thêm FAQ section (6 câu hỏi)
- Clone header/footer từ website chính
- Thêm SEO meta tags
- Setup custom domain (subdomain)
- Background đen kịt (#000000)
- Footer xanh đậm (#0b1220)
