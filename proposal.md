Dưới đây là tóm tắt nội dung của tài liệu "Capstone Project Proposal - Recommendation System":

### Đề xuất Dự án Capstone - Hệ thống Gợi ý

**Thông tin Nhóm:**
- Nhóm gồm 5 thành viên với vai trò khác nhau.

**Định nghĩa Vấn đề:**
- Người mua sắm trực tuyến có quá nhiều sản phẩm để lựa chọn, dẫn đến việc họ có thể rời bỏ mà không mua sắm. Hệ thống gợi ý giúp hướng dẫn người dùng đến những sản phẩm phù hợp với sở thích của họ.

**Dữ liệu:**
- Sử dụng bộ dữ liệu OTTO với 12 triệu phiên người dùng, 220 triệu sự kiện và 1.8 triệu sản phẩm.

**Phương pháp:**
1. **Lọc Hợp tác (Collaborative Filtering):** Dựa trên hành vi của nhiều người dùng để dự đoán tương tác trong tương lai.
2. **Lọc Nội dung (Content Filtering):** Sử dụng thuộc tính của sản phẩm để gợi ý sản phẩm tương tự.
3. **XGBoost Ranker:** Sử dụng để sắp xếp danh sách sản phẩm mà người dùng có khả năng tương tác cao nhất.

**Đánh giá:**
- Kết quả được đánh giá dựa trên Recall@20 cho từng loại hành động, với công thức tính điểm cụ thể.

**Lịch trình:**
- Dự án được chia thành nhiều giai đoạn từ thiết lập môi trường phát triển đến kiểm tra mô hình cuối cùng và nộp lên Kaggle.

Mục tiêu cuối cùng là đạt được vị trí trong top 200 của bảng xếp hạng Kaggle.


### Cách thức thực hiện Project: 

1. FOUNDATION - DỰ ÁN THỰC - 