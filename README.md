## Project_Investment-Opportunity-Analysis-EDA-_Vietnamese

### Project dựa trên đồ án cuối kỳ môn Phân tích dữ liệu cho tài chính
### Đề tài 4
### Xây dựng mô hình phân tích cơ hội đầu tư (Investment Opportunity Analysis - EDA)

#### Mục tiêu :
- Phân tích dữ liệu để lựa chọn quốc gia, lĩnh vực và loại hình đầu tư phù hợp
- Chiến lược: đầu tư và những nơi mà nhiều người khác đang đầu tư

#### Dữ liệu :
Nguồn: Dự án này sử dụng bộ dữ liệu Investment Analysis, được lấy từ Kaggle. Tập dữ liệu ban đầu được [ASHISH] cung cấp và có sẵn trên Kaggle. [https://www.kaggle.com/datasets/ashydv/investment-analysis/data]. 

- Dữ liệu gồm 03 files: rounds2.csv, mapping.csv và companies.txt
- companies.txt chứa thông tin về các công ty: homepage, category_list, country,…
- mapping.csv: map các lĩnh vực kinh doanh
- round2.csv: thông tin về các vòng gọi vốn đầu tư

#### Yêu cầu :
- Tải dữ liệu và nạp dữ liệu vào chương trình 	
- Thống kê dữ liệu như max, min, mean,...
- Thực hiện tiền xử lý dữ liệu: làm sạch, điền dữ liệu bị thiếu, gộp các tập dữ liệu và chỉnh sửa sai lệch dữ liệu,...		
- Phân tích loại hình đầu tư: so sánh số tiền đầu tư điển hình trong liên doanh, vòng seed, angel, private equity,... 
- Phân tích theo quốc gia: xác định các quốc gia được đầu tư nhiều nhất trong quá khứ. 
- Phân tích ngành: sự phân bổ đầu tư trên tám lĩnh vực chính (file mapping.csv)
  
*Lưu ý: 'lĩnh vực chính' được lưu trong mapping.csv. Còn companies.txt và round2.csv đang có nhiều lĩnh vực phụ, do đó file mapping đã được gộp vào để nhập lĩnh vực phụ vào lĩnh vực chính.*

**Công cụ :**
Jupyter Notebook để xử lý dữ liệu
Power BI để tạo báo cáo trực quan

#### Về project :
- Ý tưởng về xử lý dữ liệu và phân tích được lấy từ các bài phân tích cơ hội đầu tư dựa trên tập dữ liệu có từ Kaggle . [Link1](https://www.kaggle.com/code/absheer/investment-data-cleaning-and-understanding) , [Link2](https://www.kaggle.com/code/anuranchowdhury/spark-fund-investment-analysis-eda) , [Link3](https://www.kaggle.com/code/kerneler/starter-investment-analysis-69cfb24d-6) , [Link4](https://www.kaggle.com/code/ashydv/investment-opportunity-analysis-eda)
  
**Kết luận :**
Trong dự án này, ta đã thực hiện một cuộc nghiên cứu về việc sử dụng Phân Tích Dữ Liệu Khám Phá (EDA) để phân tích mô hình cơ hội đầu tư trên các lĩnh vực khác nhau. Qua các bước phân tích tỉ mỉ và sử dụng các kỹ thuật EDA, chúng ta đã có cái nhìn tổng quan và sâu sắc hơn về cấu trúc và đặc điểm của thị trường, từ đó xác định
+ Loại hình đầu tư: Loại hình đầu tư phù hợp nhất được xác định qua phân tích là Venture Capital (Vốn mạo hiểm). Loại hình đầu tư này đã cho thấy tiềm năng lớn về lợi nhuận và là lựa chọn ưu tiên trong hầu hết các vòng gọi vốn.
+ Phân tích quốc gia: Hoa Kỳ nổi lên là quốc gia hàng đầu cho các hoạt động đầu tư, với số lượng vòng gọi vốn và tổng số tiền đầu tư cao nhất. Điều này cho thấy thị trường Hoa Kỳ đang hoạt động rất sôi nổi và là nơi lý tưởng cho các khoản đầu tư mạo hiểm.
+ Phân tích lĩnh vực: Các lĩnh vực có hoạt động đầu tư mạnh nhất bao gồm 'Others', 'Cleantech/Semiconductors' (Công nghệ sạch/Chất bán dẫn), và 'Social, Finance, Analytics and Advertising' (Xã hội, Tài chính, Phân tích và Quảng cáo). Đây là những lĩnh vực đang thu hút sự chú ý lớn từ các nhà đầu tư, làm cho chúng trở thành mục tiêu đầu tư tiềm năng.

**Dựa trên những phát hiện từ phân tích, các đề xuất về hành động được đưa ra:**
+ Tập trung vào Đầu tư mạo hiểm (Venture Capital): Với hiệu suất cao và sự phổ biến của các khoản đầu tư mạo hiểm, nên ưu tiên loại hình đầu tư này để tối đa hóa lợi nhuận.
+ Nhắm vào thị trường Hoa Kỳ: Với Hoa Kỳ thể hiện hoạt động đầu tư mạnh mẽ nhất, nên tập trung nỗ lực đầu tư vào thị trường này, đặc biệt là trong những ngành đã chứng tỏ sự tăng trưởng mạnh mẽ.
+ Đầu tư vào các lĩnh vực tăng trưởng cao: Nên mở rộng đầu tư vào các lĩnh vực như 'Cleantech/Semiconductors' và 'Social, Finance, Analytics and Advertising'. Đây là những lĩnh vực đã cho thấy tiềm năng lớn và có khả năng mang lại cơ hội sinh lời cao trong tương lai.
  
**Trực quan :**
Dự án này bao gồm báo cáo được tạo bằng Power BI để cung cấp hình ảnh trực quan mang tính tương tác và sâu sắc. Nó có nhiều biểu đồ và đồ thị khác nhau để hiển thị xu hướng và mẫu trong dữ liệu, giúp người dùng dễ dàng hiểu và khám phá mối quan hệ giữa các biến trong tập dữ liệu.
![Report](https://github.com/ViaThanh/Project_Investment_Opportunity_Analysis_Vietnamese/blob/537ba9207d4dc10d61cbccac22f6a3e9ad2ea92a/%E1%BA%A2nh%20ch%E1%BB%A5p%20m%C3%A0n%20h%C3%ACnh%202024-09-03%20232145.png)
