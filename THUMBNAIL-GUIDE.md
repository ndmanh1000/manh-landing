# Hướng dẫn thêm Thumbnail cho Website

## 📸 Cách thêm thumbnail

### 1. Chuẩn bị ảnh thumbnail
- **Tên file**: `thumbnail.jpg` (hoặc `thumbnail.png`)
- **Kích thước**: 1200x630 pixels (tỷ lệ 1.91:1)
- **Định dạng**: JPG hoặc PNG
- **Kích thước file**: < 1MB

### 2. Đặt ảnh vào thư mục
```
manh-landing/
├── images/
│   ├── manh.jpg
│   └── thumbnail.jpg  ← Đặt ảnh thumbnail ở đây
```

### 3. Nội dung ảnh thumbnail nên có
- Logo/tên "Nguyễn Đức Mạnh"
- Tiêu đề "Thiết kế Website Chuyên Nghiệp"
- Màu sắc phù hợp với theme (gradient xanh-tím)
- Có thể thêm ảnh cá nhân hoặc logo
- Text rõ ràng, dễ đọc

## 🚀 Tính năng đã được cấu hình

### ✅ Meta Tags
- **Open Graph** (Facebook, LinkedIn)
- **Twitter Cards** (Twitter)
- **SEO meta tags** (Google)
- **Structured Data** (JSON-LD)

### ✅ Social Media Sharing
Khi chia sẻ website, thumbnail sẽ hiển thị trên:
- Facebook
- Twitter
- LinkedIn
- Zalo
- Google Search

### ✅ PWA Support
- Web App Manifest
- Apple Touch Icon
- Theme colors

## 🔧 Cấu hình đã sẵn sàng

Tất cả các meta tags và cấu hình đã được thiết lập sẵn trong `index.html`:

```html
<!-- Open Graph -->
<meta property="og:image" content="./images/thumbnail.jpg">
<meta property="og:image:width" content="1200">
<meta property="og:image:height" content="630">

<!-- Twitter -->
<meta property="twitter:image" content="./images/thumbnail.jpg">

<!-- Structured Data -->
"image": "./images/thumbnail.jpg"
```

## 📱 Kiểm tra thumbnail

Sau khi thêm ảnh, bạn có thể kiểm tra:

1. **Facebook Debugger**: https://developers.facebook.com/tools/debug/
2. **Twitter Card Validator**: https://cards-dev.twitter.com/validator
3. **LinkedIn Post Inspector**: https://www.linkedin.com/post-inspector/
4. **Google Rich Results Test**: https://search.google.com/test/rich-results

## 🎨 Gợi ý thiết kế thumbnail

- Sử dụng font chữ rõ ràng, dễ đọc
- Màu sắc tương phản tốt
- Logo/branding nổi bật
- Kích thước text phù hợp (không quá nhỏ)
- Có thể thêm icon hoặc hình ảnh minh họa

---

**Lưu ý**: Sau khi thêm ảnh thumbnail, hãy commit và push lên GitHub để Vercel deploy lại website.
