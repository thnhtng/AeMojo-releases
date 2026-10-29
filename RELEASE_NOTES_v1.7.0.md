# AeMojo 1.7.0

**Mới: Auto transcribe nhận giọng chuẩn hơn với mọi giọng nói**

- Nâng model nhận dạng giọng nói từ Whisper `medium` lên **Whisper large-v3-turbo** — huấn luyện trên 5 triệu giờ âm thanh, nhận tốt hơn hẳn giọng vùng miền, giọng nước ngoài, nói nhanh, thu âm điện thoại / có tạp âm và câu chen tiếng Anh. Tốc độ gần như model cũ.
- Tự nhận diện ngôn ngữ chắc chắn hơn: xét nhiều đoạn thay vì chỉ 30 giây đầu, nên intro nhạc hoặc câu mở đầu lạ giọng không làm nhận sai ngôn ngữ cả clip.
- Giảm lỗi lặp câu khi người nói nhanh hoặc nói dính chữ.
- Cập nhật không gián đoạn: model mới (~1.6GB) tự tải ngầm sau khi cập nhật; trong lúc tải, panel vẫn tạo sub bằng model cũ và tự chuyển sang model mới khi tải xong.
