Dataset: User Churn													
													
Giới thiệu chung về dataset: gồm 1 bảng dim chứa thông tin về user của 1 công ty mạng viễn thông, trong đó có các trường thông tin về nhân khẩu học và thông tin liên quan đến churn của user													
													
Đề bài:	Tạo 1 dashboard tổng quan để nhà quản lý thấy được tình hình churn của user và nhận diện được nhóm user churn, từ đó đưa ra được giải pháp nhằm cải thiện tình hình này												
													
													
"Context: vấn đề sụt giảm doanh thu, lấy dữ lệu về số store churn của từng tháng quý 4/2021 và quý 1/2022 => set up meeting => empathyze data và stakeholder => mục đích để làm gì? vì thấy revenue giảm so với cùng kỳ năm trước và quý trước => assume là store churn giảm 

doanh thu giảm : 
-        số lượng người dùng giảm => tìm thấy nền tảng khác hoặc buying thấp
-        Số store giảm
-        Ko nhiều user churn nhưng sức bán của merchant giảm nên doanh thu giảm
-        Ecommerce: user, store, buyer
-        Thị trường, đối thủ, bản thân doanh nghiệp
-        Grain của bảng là gì?
-        Level nhỏ nhất của bảng dim invoice là invoice (hoá đơn) chứ ko phải từng sản phẩm của invoice
-        Khách hàng ko muốn biết số store churn 
-        Làm bước EDA, null đúng ko, null nhiều là sai? Churn label = 0 thì user ko churn
-        DEFINE: big goal => top down/ bottom up
"													
