# [Phân tích] So sánh Trade-off các giải pháp ra lệnh cho Ứng dụng AI trong Học tập & Nghiên cứu
## Bước 1: 2 Prompt mẫu (Chủ đề: Con trỏ trong C)
- Giải pháp 1 (Đơn giản):

 "Đóng vai giảng viên 10 năm KN kiểm tra kiến thức về vòng lặp for. Sau khi tôi giải thích, hãy chấm điểm thang 10 (theo độ chính xác, dễ hiểu, ví dụ) và chỉ ra lỗi sai."

- Giải pháp 2 (Chi tiết, ràng buộc):

 Vai trò: Giảng viên IT 
Nhiệm vụ: Chấm bài giải thích về vòng lặp for theo Rubric: Chính xác (4đ), Dễ hiểu (3đ), Ví dụ (3đ).
Ràng buộc: Không giải thích hộ; chỉ đặt 2 câu hỏi gợi mở. Xuất đúng 3 mục: 1. Điểm Rubric, 2. Lỗi sai, 3. Câu hỏi gợi mở. 

| Tiêu chí | Giải pháp 1 (Đơn giản) | Giải pháp 2 (Chi tiết) | Đánh đổi |
| :--- | :--- | :--- | :--- |
| **Độ dễ hiểu** | Cao | Trung bình | Tốn công viết ban đầu để chạy ổn định. |
| **Tốn token** | Ít (~35 tokens) | Nhiều hơn (~85 tokens) | Tốn gấp ~2.5 lần token đầu vào. |
| **Chặn lỗi biên** | Trung bình | Cực tốt | Ngăn AI giải hộ bài và lệch định dạng. |
