## Phần 1: Bảng so sánh

| Tiêu chí | Cách 1: Tuyệt đối (`C:\Users\...`) | Cách 2: Tương đối (`../Data/...`) |
| :---- | :---- | :---- |
| **Tính di động** | **Kém**. Lỗi ngay khi đổi máy hoặc ổ đĩa. | **Cao**. Chạy tốt trên mọi máy tính. |
| **Độ dài câu lệnh** | Dài, dễ rối mắt. | Ngắn gọn, dễ đọc. |
| **Tính an toàn** | Thấp. Lộ tên User và cấu trúc ổ đĩa. | Cao. Chỉ lộ cấu trúc nội bộ dự án. |

Phần 2: Giải pháp tối ưu  
An nên chọn **Cách 2 (Đường dẫn tương đối)** để chạy được trên máy của bạn bè.  
**Ý nghĩa ký hiệu:**  
**Ký hiệu `.`**: **thư mục hiện tại** (`src`).  
**Ký hiệu `..`**: **thư mục cha** (lùi ra ngoài `src`).