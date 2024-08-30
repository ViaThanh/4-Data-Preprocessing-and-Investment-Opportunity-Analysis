## Project_Investment-Opportunity-Analysis-EDA-_Vietnamese

### Project cuối kỳ môn Phân tích dữ liệu cho tài chính
### Đề tài 4
### Xây dựng mô hình phân tích cơ hội đầu tư (Investment Opportunity Analysis - EDA)

**Mục tiêu :**
- Phân tích dữ liệu để lựa chọn quốc gia, lĩnh vực và loại hình đầu tư phù hợp
- Chiến lược: đầu tư và những nơi mà nhiều người khác đang đầu tư

**Dữ liệu :**
Nguồn: Dự án này sử dụng bộ dữ liệu Investment Analysis, được lấy từ Kaggle. Tập dữ liệu ban đầu được [ASHISH] cung cấp và có sẵn trên Kaggle. [https://www.kaggle.com/datasets/ashydv/investment-analysis/data]. 

**Mô tả :**
- Dữ liệu gồm 03 files: rounds2.csv, mapping.csv và companies.txt
- companies.csv chứa thông tin về các công ty: homepage, category_list, country,…
- mapping.csv: map các lĩnh vực kinh doanh
- round2.csv: thông tin về các vòng gọi vốn đầu tư

**Yêu cầu :**
- Tải dữ liệu và nạp dữ liệu vào chương trình 	
- Thống kê dữ liệu 		
- Thực hiện tiền xử lý dữ liệu: làm sạch, điền dữ liệu bị thiếu, gộp các tập dữ liệu và chỉnh sửa sai lệch dữ liệu,...		
- Phân tích loại hình đầu tư: so sánh số tiền đầu tư điển hình trong liên doanh, vòng seed, angel, private equity,... 	
- Phân tích theo quốc gia: xác định các quốc gia được đầu tư nhiều nhất trong quá khứ. 
- Phân tích ngành: sự phân bổ đầu tư trên tám lĩnh vực chính (file mapping.csv)
  
*Lưu ý: 'lĩnh vực chính' được lưu trong mapping.csv. Còn companies.txt và round2.csv đang có nhiều lĩnh vực phụ, do đó cần map lĩnh vực phụ vào lĩnh vực chính.*

**Về project :**
- Ý tưởng về xử lý dữ liệu và phân tích được lấy từ các bài phân tích cơ hội đầu tư dựa trên tập dữ liệu có từ Kaggle . [Link1](https://www.kaggle.com/code/absheer/investment-data-cleaning-and-understanding) , [Link2](https://www.kaggle.com/code/anuranchowdhury/spark-fund-investment-analysis-eda) , [Link3](https://www.kaggle.com/code/kerneler/starter-investment-analysis-69cfb24d-6) , [Link4](https://www.kaggle.com/code/ashydv/investment-opportunity-analysis-eda)
- Kết luận :
Trong dự án này, ta đã thực hiện một cuộc nghiên cứu về việc sử dụng Phân Tích Dữ Liệu Khám Phá (EDA) để phân tích mô hình cơ hội đầu tư trên các lĩnh vực khác nhau. Qua các bước phân tích tỉ mỉ và sử dụng các kỹ thuật EDA, chúng ta đã có cái nhìn tổng quan và sâu sắc hơn về cấu trúc và đặc điểm của thị trường, từ đó xác định
+ Loại hình đầu tư phù hợp nhất với số liệu là loại hình 'Venture'
+ Quốc gia có số lượng và số tiền đầu tư nhiều nhất là Mỹ, là quốc gia phù hợp để đầu tư nhất dựa trên chiến lược được đưa ra.
+ Những lĩnh vực được đầu tư nhiều nhất phù hợp để phát triển các cơ hội đầu tư tiềm năng đó là các lĩnh vực 'Others', 'Cleantech/Semiconductors' và 'Social, Finance, Analytics and Advertising'
  
**Trực quan :**
Dự án này bao gồm dashboard được tạo bằng Power BI để cung cấp hình ảnh trực quan mang tính tương tác và sâu sắc. Nó có nhiều biểu đồ và đồ thị khác nhau để hiển thị xu hướng và mẫu trong dữ liệu, giúp người dùng dễ dàng hiểu và khám phá mối quan hệ giữa các biến trong tập dữ liệu.
