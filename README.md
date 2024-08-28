# Phân Tích và Dự Đoán Bệnh Tiểu Đường

## Tổng Quan Dự Án
Dự án này thực hiện phân tích toàn diện về tỷ lệ mắc bệnh tiểu đường sử dụng tập dữ liệu CSV. Mục tiêu là hiểu các yếu tố chính góp phần vào bệnh tiểu đường và xây dựng các mô hình dự đoán để chẩn đoán sớm. Dự án sử dụng Google Colab để trích xuất, làm sạch và đánh giá dữ liệu.

## Trách Nhiệm Chính
- **Thu Thập Dữ Liệu:** Thu thập và nhập dữ liệu liên quan đến bệnh tiểu đường từ tệp CSV vào Google Colab.
- **Dọn Dẹp Dữ Liệu:** Thực hiện dọn dẹp dữ liệu bao gồm xử lý các giá trị bị thiếu, loại bỏ dữ liệu trùng lặp và chuẩn hóa dữ liệu để đảm bảo tính chính xác và độ tin cậy.
- **Phân Tích Dữ Liệu Thăm Dò (EDA):** Tiến hành phân tích thăm dò chi tiết để xác định các mô hình, xu hướng và mối tương quan giữa các yếu tố như tuổi tác, BMI, lượng glucose và tình trạng kháng insulin.
- **Kỹ Thuật Tính Năng:** Tạo các tính năng mới để nâng cao hiệu suất mô hình và hiểu sâu hơn về các yếu tố ảnh hưởng đến bệnh tiểu đường.
- **Xây Dựng Mô Hình:** Áp dụng nhiều thuật toán học máy, bao gồm Hồi Quy Logistic, Cây Quyết Định và Rừng Ngẫu Nhiên, để dự đoán khả năng mắc bệnh tiểu đường.
- **Đánh Giá Mô Hình:** Đánh giá hiệu suất của mô hình bằng các chỉ số như độ chính xác, độ tin cậy, khả năng thu hồi và điểm F1 để xác định mô hình tốt nhất cho việc dự đoán nguy cơ mắc bệnh tiểu đường.
- **Hình Ảnh Hóa Dữ Liệu:** Phát triển các hình ảnh hóa dữ liệu bằng Matplotlib và Seaborn để trình bày các phát hiện và kết quả mô hình một cách hiệu quả.

## Thành Tựu
- Xây dựng và tinh chỉnh thành công một mô hình dự đoán với tỷ lệ chính xác đạt được X% trong việc chẩn đoán bệnh tiểu đường.
- Xác định các yếu tố chính có tác động đáng kể đến nguy cơ mắc bệnh tiểu đường, cung cấp thông tin chi tiết hữu ích cho các chuyên gia chăm sóc sức khỏe.
- Tạo bảng thông tin tương tác để trình bày thông tin chi tiết về dữ liệu và dự đoán mô hình cho các bài thuyết trình của bên liên quan.

## Công Cụ và Công Nghệ Sử Dụng
- **Dọn Dẹp và Phân Tích Dữ Liệu:** Google Colab, Python (Pandas, NumPy)
- **Học Máy:** Naive Bayes, Decision Tree, Scikit-learn, KNN, Clustering and Classification
- **Hình Ảnh Hóa Dữ Liệu:** Matplotlib, Seaborn
- **Xử Lý Dữ Liệu:** CSV

## Kết Quả
Dự án cung cấp một khuôn khổ mạnh mẽ để dự đoán nguy cơ mắc bệnh tiểu đường và đóng góp những hiểu biết có giá trị cho các biện pháp can thiệp sớm và phòng ngừa trong quản lý bệnh tiểu đường. Kết quả được trình bày qua các báo cáo và hình ảnh chi tiết, làm nổi bật các yếu tố quan trọng ảnh hưởng đến bệnh tiểu đường và hiệu quả của mô hình dự đoán.
