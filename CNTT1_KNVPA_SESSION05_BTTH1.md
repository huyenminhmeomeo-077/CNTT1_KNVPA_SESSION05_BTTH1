## **3\. Yêu cầu**

Thiết kế prompt yêu cầu AI lập kế hoạch tài chính hàng tháng từ dữ liệu đầu vào gồm: Thu nhập, Chi phí cố định, Các khoản nợ, Mục tiêu tiết kiệm.

> **Vai trò:** Bạn là một chuyên gia tư vấn tài chính cá nhân thông minh và cực kỳ cẩn thận với các con số.

> **Nhiệm vụ:** Dựa vào dữ liệu tài chính của tôi dưới đây, hãy lập kế hoạch phân bổ ngân sách tháng này để vừa trả nợ đúng hạn, vừa đảm bảo tiết kiệm tối thiểu 20% và có quỹ dự phòng.

> **Dữ liệu đầu vào của tôi:**

- **Thu nhập tháng này :** \[Nhập số tiền\]  
- **Chi phí cố định bắt buộc (tiền nhà, điện nước, ăn uống):** \[Nhập số tiền\]  
- **Các khoản nợ cần trả tối thiểu tháng này:** \[Nhập số tiền\]  
- **Mục tiêu tiết kiệm cam kết:** Tối thiểu 20% tổng thu nhập.

> **Quy tắc suy luận :** Tuyệt đối không nhảy cóc ra kết quả cuối cùng, phải ghi rõ từng phép tính cộng, trừ, nhân, chia trung gian theo đúng 4 bước sau:

- **Bước 1:** Tính tổng thu nhập khả dụng còn lại sau khi lấy tổng thu nhập trừ đi chi phí cố định bắt buộc.  
- **Bước 2:** Trích tiền từ phần khả dụng ở bước 1 để thanh toán các khoản nợ tối thiểu. Tính số tiền còn lại.  
- **Bước 3:** Trích lập quỹ tiết kiệm theo tỷ lệ cam kết. Kiểm tra xem số tiền còn lại ở bước 2 có đủ để trích tiết kiệm không; nếu thiếu hãy đề xuất phương án điều chỉnh.  
- **Bước 4:** Lấy phần tiền còn lại cuối cùng chia cho các khoản chi tiêu linh hoạt theo tinh thần sao cho hợp lý nhất.

> **Định dạng đầu ra yêu cầu:** Trình bày câu trả lời thành 2 phần rõ rệt:

- **Phần 1: Nhật ký suy luận logic (Reasoning Steps):** Ghi chi tiết từng bước tính toán từ Bước 1 đến Bước 4 kèm công thức và số liệu trung gian.  
- **Phần 2: Bảng phân bổ ngân sách cuối cùng:** Trình bày bằng bảng Markdown gồm 4 cột: Hạng mục \| Số tiền \| Tỷ lệ % \| Ghi chú. Lưu ý: Tổng cột Tỷ lệ % bắt buộc phải bằng chính xác **100%** (tính trên tổng thu nhập ban đầu).

**Kết luận**

Theo em , sử dụng chain-of-thought giúp AI xử lý bài toán tài chính có trình tự, hạn chế sai sót khi tính toán và dễ kiểm tra kết quả

