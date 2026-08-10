# Data Visualization - Xuất khẩu nông sản Việt Nam

## 1. Giới thiệu

Đồ án phân tích và trực quan hóa dữ liệu xuất khẩu nông sản
của Việt Nam trong giai đoạn 2017–2025.

Dữ liệu được xử lý, khám phá và trực quan hóa nhằm tìm ra
các xu hướng xuất khẩu theo thời gian, sự khác biệt giữa các
mặt hàng và mối quan hệ giữa sản lượng và trị giá xuất khẩu.

---

## 2. Mục tiêu

- Làm sạch và chuẩn hóa dữ liệu xuất khẩu từ năm 2017 đến 2025.
- Chuẩn hóa tên cột, tên mặt hàng và đơn vị dữ liệu.
- Khám phá đặc điểm và chất lượng của dữ liệu.
- Phân tích sản lượng và trị giá xuất khẩu theo năm.
- Phân tích sản lượng và trị giá theo từng mặt hàng.
- Phân tích biến động theo tháng.
- Phân tích mối quan hệ giữa sản lượng và trị giá.
- Trực quan hóa các kết quả phân tích bằng biểu đồ.

---

## 3. Phạm vi dữ liệu

- Thời gian: 2017–2025
- Đối tượng: các mặt hàng nông sản được lựa chọn.
- Chỉ tiêu chính:
  - Sản lượng (tấn)
  - Trị giá (nghìn USD)

Các mặt hàng được phân tích gồm:

- Thủy sản
- Rau quả
- Hạt điều
- Cà phê
- Chè
- Hạt tiêu
- Gạo
- Sắn và sản phẩm của sắn
- Cao su
- Xơ, sợi dệt các loại

---

## 4. Cấu trúc thư mục

```text
DATA-VISUALIZATION/
│
├── DATA_raw/
│   └── Dữ liệu gốc 2017–2025
│
├── DATA_processed/
│   └── Dữ liệu sau khi làm sạch
│
├── Notebooks/
│   ├── 01_clean_data.ipynb
│   ├── 02_eda.ipynb
│   └── 03_visualization.ipynb
│
├── README.md
└── .gitignore

---
## 5. Quy trình thực hiện 
Dữ liệu RAW
     ↓
01. Clean Data
     ↓
Dữ liệu Processed
     ↓
02. EDA
     ↓
Phân tích và tìm Insight
     ↓
03. Visualization
     ↓
Biểu đồ và trình bày kết quả

Author: Ngô Uy 
