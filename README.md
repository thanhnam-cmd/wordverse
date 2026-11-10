# WordVerse – Vũ Trụ Từ Vựng

Website quản lý từ vựng và trình chiếu thẻ hình cho lớp học tiếng Anh.

- Ném file từ vựng (.txt, .docx, .xlsx, .csv, .pdf) → tự nhận diện **từ tiếng Anh · phiên âm · nghĩa tiếng Việt**
- Tự tạo bộ thẻ có hình (Emoji / Ảnh thật / ảnh tự tải lên), có ô từ khoá ảnh cho từng thẻ
- Trình chiếu: Phát thẻ · Thẻ trước · Bắt đầu lại · Tự động phát, lật thẻ xem nghĩa, đọc phát âm
- Xuất video bài học

Định dạng file mẫu: xem `mau-tu-vung.txt`.

## Chạy trên máy

```bash
npx http-server -p 5180
```

## Deploy

Trang tĩnh (static site), deploy lên Render bằng `render.yaml` (Blueprint).
