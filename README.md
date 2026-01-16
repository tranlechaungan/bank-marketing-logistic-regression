
# 🏦 Bank Marketing – Customer Deposit Prediction

<div align="center">

**📊 Phân tích & Dự báo hành vi khách hàng ngân hàng bằng Machine Learning**  
*Các Mô Hình Học Máy: Logistic Regression, Decision Tree, Random Forest, XGBoost*

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-ML-FF6B35?style=for-the-badge&logo=xgboost&logoColor=white)
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
Dự án thử nghiệm và so sánh nhiều thuật toán học máy cho bài toán phân loại nhị phân:

- **Logistic Regression**: Mô hình tuyến tính cho phân loại nhị phân, dễ giải thích và hiệu quả với dữ liệu có cấu trúc.
- **Decision Tree Classifier**: Mô hình cây quyết định, dễ hiểu và trực quan, nhưng có thể overfitting.
- **Random Forest Classifier**: Ensemble của nhiều cây quyết định, cải thiện độ chính xác và giảm overfitting.
- **XGBoost Classifier**: Thuật toán boosting mạnh mẽ, thường đạt hiệu suất cao trên nhiều bài toán.

**Lý do lựa chọn các mô hình**:
- Phù hợp với chương trình *Máy học cơ bản*
- Bao gồm cả mô hình tuyến tính và phi tuyến tính để so sánh
- Tập trung vào phân loại nhị phân với dữ liệu mất cân bằng

---

## 🔬 Quy trình thực hiện
1. Khám phá và làm sạch dữ liệu  
2. Mã hóa biến phân loại (One-Hot Encoding)  
3. Chuẩn hóa dữ liệu số (`StandardScaler`)  
4. Chia tập huấn luyện / kiểm tra (70/30)  
5. Huấn luyện và đánh giá các mô hình: Logistic Regression, Decision Tree, Random Forest, XGBoost  
6. So sánh hiệu suất dựa trên Accuracy, Precision, Recall, F1-Score  

---

## 📈 Kết quả
Sau khi thử nghiệm và so sánh các mô hình trên tập kiểm tra:

- **XGBoost**: Độ chính xác cao nhất (~90.71%), cân bằng tốt giữa Precision và Recall (F1-Score: 0.5591)
- **Random Forest**: Độ chính xác cao (~90.58%), Precision tốt nhất (0.6695)
- **Logistic Regression**: Độ chính xác ~89.98%, ổn định và dễ giải thích
- **Decision Tree**: Độ chính xác thấp nhất (~87.21%), dễ overfitting

📌 **Nhận xét**: XGBoost là mô hình hoạt động tốt nhất tổng thể, đặc biệt trong việc cân bằng giữa phát hiện đúng và giảm sai sót. Tuy nhiên, Logistic Regression vẫn phù hợp cho phạm vi môn học Khoa học dữ liệu cho tài chính (DAT706_251_L08) do tính đơn giản và khả năng giải thích.

---

## 📁 Cấu trúc thư mục
```
.
├── data/
│   └── bank-full.csv
├── notebooks/
│   └── bank-marketing-logistic-regression.ipynb
├── README.md
```

---

## ⚙️ Cài đặt
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
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
- XGBoost Documentation  
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