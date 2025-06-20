# Báo cáo phân tích biến động giá cổ phiếu GOOGL

## Mục tiêu
Phân tích dữ liệu giá cổ phiếu GOOGL từ năm 2023–2024 để:
- Tính toán các chỉ số kỹ thuật: Daily Return, Volatility, RSI,...
- Trực quan hóa xu hướng giá
- Đánh giá khả năng đầu tư và rủi ro

## Nội dung dự án
- `Bao_cao_cuoi_ky.ipynb`: Jupyter Notebook phân tích đầy đủ
- `Data/raw_Data/`: Dữ liệu gốc
- `Data/processed_Data/`: Dữ liệu sau xử lý
- `Bao_cao_cuoi_ky.pdf`: Bản PDF xuất từ Notebook
## Cách sử dụng

1. **Chuẩn bị môi trường:**
   - Đảm bảo đã cài đặt Python (khuyến nghị >=3.8).
   - Cài đặt các thư viện cần thiết bằng lệnh:
     ```bash
     pip install -r requirements.txt
     ```
2. **Dữ liệu:**
   - Repo có 2 file dữ liệu CSV:
     - `raw_Data.csv`: Dữ liệu thô
     - `processed_Data.csv`: Dữ liệu đã xử lí, chỉ xóa đi dòng đầu tiên thuận tiện cho việc phân tích, do dữ liệu thô vốn không missing và không cần xử lí Outliers. 

3. **Chạy notebook:**
   - Mở file notebook (`final.ipynb`) bằng Jupyter Notebook hoặc Jupyter Lab:
     ```bash
     jupyter notebook final.ipynb
     ```
   - Thực hiện lần lượt các cell để xem quá trình phân tích.
