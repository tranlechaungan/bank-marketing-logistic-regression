
# 🏦 Bank Marketing – Customer Deposit Prediction

<div align="center">

**📊 Phân tích & Dự báo hành vi khách hàng ngân hàng bằng Machine Learning**  
*Mô hình Hồi quy Logistic (Logistic Regression)*

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)
![License](https://img.shields.io/badge/Use-Academic-green?style=for-the-badge)

[📌 Tổng quan](#-tổng-quan) • [📊 Dữ liệu](#-dữ-liệu) • [🤖 Mô hình](#-mô-hình-học-máy) • [📈 Kết quả](#-kết-quả) • [⚙️ Cài đặt](#️-cài-đặt)

</div>

---

## 📌 Tổng quan
Dự án này sử dụng **Machine Learning** để dự báo khả năng **khách hàng đăng ký tiền gửi có kỳ hạn** dựa trên dữ liệu chiến dịch marketing của ngân hàng.

📚 Đây là **bài tập nhóm học phần Khoa học dữ liệu / Máy học**, được thực hiện theo đúng yêu cầu giảng viên.

---

## 📊 Dữ liệu
- **Tên bộ dữ liệu**: Bank Marketing Dataset  
- **Nguồn**: UCI Machine Learning Repository  
- **Số lượng mẫu**: > 4.000  
- **Biến mục tiêu**: `y` (yes / no)

### 🔹 Biến phân loại (Dimensions)
- job
- marital
- education
- housing
- loan
- contact

### 🔹 Biến số (Metrics)
- age
- balance
- duration
- campaign
- pdays
- previous

---

## 🤖 Mô hình học máy
- **Thuật toán**: Logistic Regression  
- **Loại bài toán**: Phân loại nhị phân (Binary Classification)  
- **Lý do lựa chọn**:
  - Phù hợp chương *Máy học cơ bản*
  - Dễ giải thích
  - Hiệu quả với bài toán dự đoán xác suất

---

## 🔬 Quy trình thực hiện
1. Khám phá và làm sạch dữ liệu  
2. Mã hóa biến phân loại  
3. Chuẩn hóa dữ liệu (`StandardScaler`)  
4. Chia tập huấn luyện / kiểm tra  
5. Huấn luyện mô hình Logistic Regression  
6. Đánh giá mô hình  

---

## 📈 Kết quả
- **Accuracy**: ~ **90%**
- Mô hình dự đoán tốt nhóm khách hàng *không đăng ký*
- Recall của nhóm *đăng ký* thấp hơn do dữ liệu mất cân bằng

📌 **Nhận xét**: Logistic Regression là lựa chọn phù hợp cho bài toán và phạm vi môn học Khoa học dữ liệu cho tài chính.

---

## 📁 Cấu trúc thư mục
```
.
├── data/
│   └── bank-full.csv
├── notebooks/
│   └── Bank_Marketing_Analysis.ipynb
├── README.md
```

---

## ⚙️ Cài đặt
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 👥 Nhóm thực hiện
- Phân công cân bằng giữa:
  - Lý thuyết
  - Trực quan hóa dữ liệu
  - Xây dựng & đánh giá mô hình
  - Viết báo cáo

---

## 📚 Tài liệu tham khảo
- UCI Machine Learning Repository – Bank Marketing Dataset  
- Scikit-learn Documentation  
- Bài giảng *Máy học cơ bản*  

---

## ✅ Ghi chú
- Dự án phục vụ **mục đích học tập**
- Không sử dụng cho mục đích thương mại

## 😎 Tác giả
**Châu Ngân**

- 📧 Email: tranlechaungan.com  
- 🔗 GitHub: [https://github.com/tranlechaungan](https://github.com/tranlechaungan)

  
---

<div align="center">

**Made with ❤️ in Vietnam**

⭐ Star this repo if you find it helpful!

[![GitHub](https://img.shields.io/badge/GitHub-tranlechaungan-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/tranlechaungan)


</div>