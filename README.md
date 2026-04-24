# 📊 Olist E-Commerce Analysis

## 📌 Tổng quan dự án
Dự án này phân tích bộ dữ liệu công khai từ Olist - một nền tảng thương mại điện tử của Brazil nhằm mục đích rút ra những insight về tình hình kinh doanh và những cải tiến nhằm tăng doanh thu và khách hàng.
<img width="3300" height="2550" alt="Power BI Dashboard_page-0001" src="https://github.com/user-attachments/assets/44dcca90-661b-46c8-a06c-97efec61588e" />
<img width="3300" height="2550" alt="Power BI Dashboard_page-0002" src="https://github.com/user-attachments/assets/a364ea70-8567-41aa-9c2b-9c2471841c83" />
<img width="3300" height="2550" alt="Power BI Dashboard_page-0003" src="https://github.com/user-attachments/assets/a4c6343f-b4d8-4301-ac8c-618cf5915932" />

---

## 🗂 Dataset
- Tên dataset: Brazilian E-Commerce Public Dataset by Olist
- Nguồn: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

---

## 🔄 Quy trình phân tích
1. Tải bộ dữ liệu
2. Import dữ liệu vào Power BI
3. Làm sạch dữ liệu:
- Sửa định dạng đúng cho các cột
- Xoá các dòng trống
- Tạo cột thời gian
4. Tính toán các measure sử dụng hàm DAX
5. Xây dựng báo cáo

---

## 🛠 Công cụ
- Power BI
- Excel/CSV
- GitHub

---

## 🎯 Câu hỏi kinh doanh
1. Doanh thu của Olist là bao nhiêu? Doanh thu thay đổi như nào theo thời gian? Mùa cao điểm diễn ra vào thời gian nào?
2. Tổng sản phẩm đã bán ra là bao nhiêu? Các danh mục sản phẩm bán chạy nhất? Các danh mục sản phẩm đem lại doanh thu cao nhất?
3. Khách hàng là những đối tượng nào? Số lượng khách hàng theo thời gian có tăng không?
4. Các hình thức thanh toán được lựa chọn?
5. Số đơn hàng đặt giao hàng là bao nhiêu? Tỷ lệ giao muộn và sớm?
6. Phản hồi của khách hàng như thế nào?

---

## 📊 Phân tích dữ liệu và báo cáo
**1. Doanh thu của Olist**
<img width="1136" height="542" alt="image" src="https://github.com/user-attachments/assets/711d3d1d-ea58-46f7-b04e-f83bca052253" />
- Nhìn chung, cửa hàng có doanh thu tăng trưởng theo thời gian, với tổng doanh thu trong giai đoạn 2016-2018 đạt $15,84M. 
- Trong giai đoạn tháng 10-12 năm 2017 doanh thu của cửa hàng đạt mức tăng trưởng đột biến. Sự tăng trưởng này có thể đã đến từ các chiến dịch quảng cáo, hoặc các ngày lễ có thể kể đến như: Halloween, Black Friday, Christmas,...

**2. Sản phẩm của Olist**
<img width="1316" height="436" alt="image" src="https://github.com/user-attachments/assets/30117968-0e7a-4404-be7f-063b0ade4cac" />
- Tổng sản phẩm đã bán ra trong giai đoạn 2016-2018 là gần 135 nghìn sản phẩm.
- Qua biểu đồ ta có thể thấy rằng, các dòng sản phẩm được ưa chuộng nhất đem lại doanh thu cao nhất.
- Cửa hàng nên triển khai các chương trình marketing đối với các dòng sản phẩm này nhằm mở rộng tệp khách hàng và nâng cao doanh thu.
- Đối với những dòng sản phẩm có doanh thu cao nhưng số lượng bán thấp và ngược lại, cửa hàng có thể áp dụng các chương trình khuyến mãi phù hợp, ví dụ như: bán theo combo, mua 1 tặng 1, bán tặng kèm,... nhằm đa dạng hoá lựa chọn tiêu dùng của khách hàng, cũng như giới thiệu sản phẩm để tăng khả năng khách mua lại trong tương lai.

**3. Khách hàng của Olist**
<img width="1805" height="402" alt="image" src="https://github.com/user-attachments/assets/67504268-f77a-4145-8387-2bdd3d766548" />
- Số lượng khách hàng của cửa hàng tăng trưởng cùng với sự tăng trưởng của doanh thu, đạt gần 99 nghìn khách hàng vào cuối năm 2018.
- Khách hàng chủ yếu là khách nội địa Nam Mỹ của nước Brazil, phần lớn tập trung ở các thành phố lớn như Sao Paulo, Rio de Janeiro,...
- Ta có thể kết luận rằng: số đông tệp khách hàng của cửa hàng là dân thành thị.

**4. Các phương thức thanh toán được lựa chọn**
<img width="774" height="316" alt="image" src="https://github.com/user-attachments/assets/27650586-cfbf-4638-8953-5b935947a851" />
- Do tệp khách hàng chủ đạo là dân thành thị, phương thức thanh toán được sử dụng cũng sẽ hiện đại hơn, với gần 74 nghìn lượt thanh toán sử dụng thẻ tín dụng, chiếm 73,92% số lượt thanh toán.
- Tiếp đó là phương thức thanh toán boleto. Đây là một loại hình thanh toán đặc thù của Brazil được quản lý bởi NHTW, với gần 20 nghìn lượt thanh toán.
- Do đó, ta lại càng thấy rằng có sự phân hoá lớn giữa khu vực thành thị lớn với các tỉnh thành nhỏ khác.

**5. Số đơn hàng đặt giao hàng là bao nhiêu? Tỷ lệ giao muộn và sớm?**
<img width="603" height="337" alt="image" src="https://github.com/user-attachments/assets/c9db93b5-d5c3-48c1-a7b7-7bb7ab635978" />
- Phương thức mua hàng chủ yếu là đặt giao hàng với 96 nghìn đơn đặt giao hàng trên tổng số 99 nghìn đơn hàng.
- Thời gian giao hàng trung bình là 12,5 ngày với tỷ lệ giao hàng đúng hẹn đạt 94,96%. Đây là một ưu thế rất lớn đối với một cửa hàng online khi dịch vụ giao hàng của họ mang về kết quả tốt như vậy.
- Tuy nhiên cửa hàng cũng cần phải xem lại lý do tại sang lại có tới 5 nghìn đơn giao hàng muộn. Đối với những trường hợp này, cửa hàng nên xem xét miễn phí đơn hàng hoặc gửi tặng voucher giảm giá cho lần mua hàng tiếp theo tuỳ thuộc vào thời gian trễ hẹn.

**6. Phản hồi của khách hàng**
<img width="742" height="436" alt="image" src="https://github.com/user-attachments/assets/3e70b6a8-9d6a-4a19-91ba-8713943695db" />
- Nhìn chung, cửa hàng được đánh giá tốt với 57 nghìn lượt đánh giá 5 sao, 19 nghìn lượt đánh giá 4 sao. Tuy nhiên số lượt đánh giá 1 và 2 sao lần lượt là 11 nghìn và 3 nghìn. Do đó, ta có thể thấy rằng, cửa hàng hoặc là được đánh giá rất tốt, hoặc là được đánh giá rất tệ.
- Việc người tiêu dùng không hài lòng với sản phẩm không phải chuyện hiếm gặp. Do đó, cửa hàng cần nâng cao chất lượng dịch vụ chăm sóc khách hàng, bởi khách hàng mua lại luôn là mạch sống đối với các cửa hàng.
- Cửa hàng cần liên lạc với tất cả những khách đã mua hàng, đặc biệt là khách hàng đánh giá thấp để gửi lời xin lỗi, tìm hiểu nguyên nhân, cũng như có quà tặng kèm là voucher giảm giá hay các sản phẩm tặng miễn phí cho khách hàng.

---

## 🔍 Insight
1. Cửa hàng có doanh thu tăng trưởng theo thời gian, đặc biệt là vào các dịp lễ.
2. Các dòng sản phẩm được ưa chuộng nhất đem lại doanh thu cao nhất.
3. Tệp khách hàng chủ yếu là dân thành thị, tập trung ở các thành phố lớn như Sao Paulo, Rio de Janeiro.
4. Phương thức thanh toán phổ biển nhất là thẻ tín dụng và boleto.
5. Dịch vụ giao hàng được đánh giá tốt với tỷ lệ giao đúng hẹn cao.

---

## 🧠 Đề xuất
1. Tập trung truyền thông cho các sản phẩm được yêu thích nhằm phổ cập tới nhiều khách hàng khác có cùng nhân khẩu học, giúp mở rộng tệp khách hàng và tăng doanh thu.
2. Có nhiều chương trình khuyến mãi hơn vào các dịp lễ lớn trong năm.
4. Có các chương trình liên kết với các ngân hàng để có các chương trình ưu đãi cho khách hàng thanh toán qua thẻ tín dụng như giảm giá khi mua hàng, hoàn tiền, tích điểm,...
5. Đào tạo đội ngũ chăm sóc khách hàng để luôn đồng hành cùng khách hàng, tăng tỷ lệ giữ chân khách hàng, qua đó tăng doanh số và nhận về phản hồi tích cực.

---

## 🏁 Kết luận
Olist đang làm rất tốt trong việc phát triển kinh doanh. Cửa hàng chắc chắn sẽ phát triển tốt trong tương lai thông qua việc thúc đẩy các sản phẩm được ưa chuộng, cùng với việc nắm bắt tốt nhân khẩu học của khách hàng để nâng cao trải nghiệm khách hàng.
