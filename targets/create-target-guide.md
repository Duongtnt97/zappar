# 🎯 Tạo Image Target nhanh

## Cách tạo target .zpt từ Zappar Studio:

### 1. Truy cập Zappar Studio:
👉 https://studio.zappar.com/

### 2. Tạo project mới:
- Click "Create New Project"
- Chọn "Image Tracking"
- Đặt tên project (ví dụ: "Facebook Video AR")

### 3. Upload ảnh target:
**Ảnh tốt cho tracking:**
- Logo có nhiều chi tiết
- Ảnh có góc cạnh rõ ràng
- Contrast cao (đen/trắng)
- Kích thước tối thiểu 512x512px

**Ví dụ ảnh tốt:**
- Logo công ty
- Poster phim
- Bìa sách
- QR code phức tạp

### 4. Export target:
- Click "Publish" → "Download"
- Chọn "Image Target (.zpt)"
- Save file as `your-target.zpt`

### 5. Đặt vào project:
```
public/targets/your-target.zpt
```

## 🚀 Test ngay:

1. **Chạy dev server:**
   ```bash
   npm run dev
   ```

2. **Mở browser:** http://localhost:5173

3. **Cho phép camera access**

4. **Hướng camera về ảnh target** → Video Facebook sẽ xuất hiện!

## 📱 Lưu ý:
- Desktop: Dùng webcam
- Mobile: Cần HTTPS (deploy hoặc dùng ngrok)
- Target cần đủ sáng và rõ nét