<img src="https://github.com/user-attachments/assets/f1bda9fd-f038-4afc-be13-0ea34fa28323" alt="image" style="display: block; margin: auto;">

# 1. Giới thiệu đồ án môn học

- **Tên môn học**: Kho dữ liệu và OLAP
- **Mã lớp**: IS217.P13
- **Tên đồ án**: Xây dựng và phân tích kho dữ liệu giao dịch thẻ tín dụng

# 2. Nhóm thực hiện

| Họ và tên          | MSSV     | Vai trò     | Liên hệ                     |
|--------------------|----------|-------------|-----------------------------|
|🌱  Trần Vũ Bão   | 22520124 | Team member | tranvubao2004@gmail.com          |
|🌱  Phan Thành Công       | 22520170 | Team member | phanthanhcong982004@gmail.com          |

# 3. Bảng phân công và đánh giá
![image](https://github.com/user-attachments/assets/69cf9dcb-5a52-48fa-9c4f-080f0772a235)
![image](https://github.com/user-attachments/assets/26bfe96c-4590-4936-878a-f2177ca05e7c)

# 4. Mô tả
Đồ án môn học được thực hiện theo 5 chương:
- Chương 1: Tìm hiểu và giới thiệu về bộ dữ liệu. Tiến hành thiết kế sơ đồ bông tuyết hoặc sơ đồ hình sao để xây dựng kho dữ liệu.
- Chương 2: Quá trình SSIS - ETL đổ dữ liệu vào kho dữ liệu đã thiết kế.
- Chương 3: Quá trình SSAS - Đề xuất các câu truy vấn và thực hiện quá trình phân tích dữ liệu trực tuyến (OLAP) thông qua 3 công cụ:
  - Truy vấn ngôn ngữ đa chiều (MDX) ở SQL Server.
  - Thao tác với khối Cube ở Visual Studio.
  - Excel Pivot.
- Chương 4: Quá trình SSRS - Trực quan hoá dữ liệu và tạo report
  - Power BI
  - Looker Studio
- Chương 5: Quá trình Data mining - Khai phá dữ liệu
  - Decision Tree
  - Random Forest
  - XGBoost

# 5. Công nghệ và các kỹ năng học được thông qua đồ án
- Data Warehouse
- Data Modeling
- Extract, Transform, Load (ETL)
- SQL Server Integration Services (SSIS)
- SQL Server Analysis Services (SSAS)
- MultiDimensional eXpressions (MDX)
- Excel Pivot
- Microsoft Power BI
- Looker Studio
- Python
- Machine Learning
- Microsoft SQL Server

# 6. Tham chiếu
- Nguồn dataset: [Kaggle](https://www.kaggle.com/datasets/priyamchoksi/credit-card-transactions-dataset)
- Xem chi tiết [tại đây](https://drive.google.com/drive/folders/1uMrZ78hLpDvbqrB4dthKEhHFHsKbK5OV?usp=drive_link). Cấu trúc thư mục trong link drive như sau:
    1. Data: chứa dataset.
    2. Source:
       - PowerBI & Looker Studio: chứa 6 file pdf tương ứng với các report được tạo với công cụ Power BI (3 report) và Looker Studio (3 report).
       - SSIS: chứa source của quá trình SSIS.
       - SSAS: chứa source của quá trình SSAS.
       - Pivot Excel: chứa 15 file excel pivot tương ứng với 15 câu truy vấn đa chiều trong quá trình phân tích dữ liệu trực tuyến của chương 3.
       - Data Mining: chứa file jupyter notebook mã nguồn Python cho quá trình khai phá dữ liệu ở chương 5 với 3 thuật toán Decision Tree, Random Forest, XGBoost.
       - MDX: chứa script ngôn ngữ MDX với 15 câu truy vấn đa chiều trong quá trình phân tích dữ liệu trực tuyến của chương 3.
    3. Database: chứa file mdf và file ldf của kho dữ liệu trong suốt quá trình thực hiện đồ án.
    4. Video: chứa video thực hiện chi tiết step-by-step toàn bộ các quá trình SSIS, SSAS, Power BI, Looker Studio.
    5. The information of group: chứa thông tin của các thành viên.
    6. Document: chứa file word và file pdf quyển báo cáo đồ án.
    7. Slide trình bày đồ án môn học: chứa file pdf trình bày tóm tắt về các chương của đồ án.
