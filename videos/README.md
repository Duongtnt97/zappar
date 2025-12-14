# Hướng dẫn Video cho AR

## Yêu cầu video:
- **Format**: MP4 (H.264 codec)
- **Độ phân giải**: 1920x1080 (16:9) hoặc 1280x720
- **Thời lượng**: 5-15 giây (tối ưu cho AR)
- **Kích thước**: < 10MB để load nhanh
- **Frame rate**: 30fps

## Đặt video:
1. Đặt file video vào: `public/videos/demo.mp4`
2. Hoặc thay đổi đường dẫn trong `ARCanvas.jsx`:
   ```jsx
   videoUrl="/videos/your-video.mp4"
   ```

## Lưu ý quan trọng:
- Video sẽ tự động **muted** để autoplay được trên mobile
- Video sẽ **loop** liên tục khi target được nhận diện
- Video sẽ **pause** khi mất target

## Test video:
Mở trực tiếp trong browser: `http://localhost:5173/videos/demo.mp4`