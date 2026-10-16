## **PHẦN 1: THIẾT KẾ KIẾN TRÚC PROMPT (3 PHẦN)**

 1. Bối cảnh & Vai trò (Context & Role)
Bạn là một Gia sư Công nghệ thân thiện, chuyên gia giải thích các khái niệm kỹ thuật phức tạp thành ngôn ngữ cực kỳ đơn giản, dễ hiểu cho sinh viên năm 1 ngành Nông nghiệp thông minh chưa có nền tảng lập trình hay phần cứng sâu.

2. Nội dung & Nhiệm vụ (Task & Input)
Hãy giải thích khái niệm "Mô hình IPO (Input - Process - Output) trong trang trại thông minh". 
Hãy lấy một ví dụ thực tế, gần gũi nhất (ví dụ: Hệ thống tưới nước tự động cho cây trồng) để minh họa rõ ràng cách 3 thành phần Input, Process và Output tương tác với nhau trong thực tế.

3. Yêu cầu & Không cần (Constraints & Negative Constraints)
-  Sử dụng từ vựng tiếng Việt phổ thông, hạn chế tối đa thuật ngữ tiếng Anh chuyên môn khó hiểu.
- Trình bày ngắn gọn, súc tích, độ dài tối đa không quá 300 từ.
- Định dạng kết quả sử dụng các khối danh sách và bảng Markdown để dễ theo dõi.
- Không cần đưa ra các sơ đồ mạch điện phức tạp, mã nguồn lập trình vi điều khiển hoặc các công thức toán học chuyên sâu.

## **PHẦN 2: SẢN PHẨM TỆP `.md` (MÔ PHỎNG PHẢN HỒI CỦA AI)**
[ảnh trang trại thông minh]![Đẩy mạnh mô hình nông nghiệp thông minh](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTPju5AIGC3sYWvlKant0HJQdnGs51WPTyEWMFwPdNu9A&s=10)
## 1. Thành phần cấu trúc IPO

| Thành phần IPO | Ý nghĩa cơ bản | Ví dụ thực tế (Hệ thống tưới cây) |
| :--- | :--- | :--- |
| **Input (Đầu vào)** | Dữ liệu hoặc thông tin mà hệ thống thu nhận từ môi trường. | Cảm biến đo độ ẩm đất báo cáo: *"Đất đang khô, độ ẩm chỉ còn 25%"*. |
| **Process (Xử lý)** | Bộ não trung tâm phân tích dữ liệu và đưa ra quyết định. | Vi điều khiển (như Arduino) nhận tín hiệu, so sánh với mức chuẩn (40%) và ra lệnh: *"Cần bật máy bơm!"*. |
| **Output (Đầu ra)** | Hành động thực tế mà hệ thống tác động trở lại môi trường. | Rơ-le kích hoạt máy bơm nước hoạt động trong 30 giây để cung cấp nước cho cây. |

## 2. Tóm tắt vòng đời hoạt động

1. **Thu thập (Input):** Cảm biến liên tục "nhìn" và "nghe" trạng thái đất.
2. **Suy nghĩ (Process):** Bộ điều khiển "cân nhắc" xem có cần hành động không.
3. **Hành động (Output):** Máy bơm thực hiện công việc tưới nước. 






