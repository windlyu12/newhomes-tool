# Newhomes Quote Tool

Tool báo giá nội thất cho Newhomes.

## Cấu trúc

```
├── data/
│   └── data.json       ← Dữ liệu giá, vật liệu
├── index.html          ← Tool báo giá (standalone)
├── admin.html          ← Admin panel quản lý giá
└── quote-tool-embed.html ← Code nhúng WordPress
```

## Cách sử dụng

### 1. Xem Tool báo giá
https://windlyu12.github.io/newhomes-tool/

### 2. Admin Panel (quản lý giá)
https://windlyu12.github.io/newhomes-tool/admin.html

### 3. Nhúng vào WordPress
Copy nội dung file `quote-tool-embed.html` vào Custom HTML block trong WordPress.

## Cập nhật giá

1. Vào Admin Panel
2. Sửa giá/vật liệu theo ý muốn
3. Click "Tải file data.json"
4. Upload file lên GitHub (thay thế file cũ trong folder `data/`)
5. Chờ ~10 phút để CDN cập nhật

## Lưu ý

- Data được cache bởi jsDelivr CDN
- Sau khi update data.json, có thể mất 10-15 phút để CDN refresh
- Để force refresh: thêm `?v=2` vào cuối URL (sửa trong code nếu cần)
