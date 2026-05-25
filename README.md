# 🚀 Credit Risk Assessment & Fintech Business Strategy

**(Đánh giá Rủi ro Tín dụng & Chiến lược Kinh doanh Fintech)**
---
## 📖 Bối cảnh kinh doanh

Trong bối cảnh nền kinh tế Việt Nam giai đoạn 2025-2026 đang phục hồi và tầng lớp trung lưu gia tăng mạnh mẽ, nhu cầu vay tiêu dùng tín chấp qua các nền tảng Fintech kỹ thuật số đang trở thành xu hướng tất yếu. Cùng lúc đó, các ngân hàng truyền thống đang có xu hướng "thắt lưng buộc bụng", siết chặt điều kiện vay vốn do tỷ lệ nợ xấu nội bảng tăng nhẹ.

Đây là "thời điểm vàng" để **FinInnovate** (công ty Fintech) chiếm lĩnh thị trường thông qua các mô hình quản trị rủi ro thông minh và các chiến lược tín dụng "đại dương xanh", đặc biệt là việc sử dụng dữ liệu phi truyền thống (Alternative Data) để phê duyệt khoản vay nhanh chóng và chính xác.

## 🎯 Mục tiêu dự án

* **Phân tích dữ liệu (EDA):** Khám phá tập dữ liệu 50.000 hồ sơ tín dụng để tìm ra các mẫu hành vi trả nợ và vỡ nợ của khách hàng.
* **Xây dựng mô hình Học máy (Machine Learning):** Định lượng rủi ro vỡ nợ (Credit Default Risk) của từng cá nhân.
* **Phân khúc thị trường (Market Segmentation):** Ứng dụng K-Means Clustering và Ma trận Thị phần - Tăng trưởng (BCG Matrix) để đề xuất phân khúc khách hàng mục tiêu mang lại biên độ lợi nhuận cao nhất với rủi ro thấp nhất.

## 🛠 Công cụ & Thư viện sử dụng

* **Ngôn ngữ:** Python
* **Xử lý dữ liệu:** Pandas, NumPy
* **Trực quan hóa:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-learn (Random Forest Classifier, K-Means Clustering)
* **Giải thích mô hình (XAI):** SHAP (SHapley Additive exPlanations)

## 📊 Những phát hiện chính (Key Insights)

### 1. Phân tích Khám phá (EDA)

* **Tỷ lệ nợ xấu chung:** Đạt mức **31.0%** trên tổng tệp khách hàng.
* **Thu nhập & Nợ xấu:** Khách hàng thu nhập thấp (dưới 8 triệu VNĐ/tháng) có tỷ lệ nợ xấu cao nhất (42.3%). Ngược lại, nhóm thu nhập rất cao chỉ có tỷ lệ vỡ nợ 14.9%.
* **Nhân khẩu học:** Khách hàng trẻ tuổi (20-30 tuổi) có rủi ro vỡ nợ cao hơn nhẹ (~32.8%) so với nhóm lớn tuổi (46-65 tuổi).

### 2. Mô hình Học máy & SHAP

* Mô hình **Random Forest Classifier** được tối ưu hóa để ưu tiên tỷ lệ Recall đối với lớp "Defaulted" (nhận diện sớm các rủi ro vỡ nợ).
* **Các yếu tố quyết định rủi ro (Theo SHAP):**
1. **Credit Score (Điểm tín dụng):** Yếu tố quan trọng nhất.
2. **Savings Amount (Tiền tiết kiệm):** Bộ đệm tài chính quan trọng.
3. **Net Financial Position (Vị thế tài chính ròng):** Tiết kiệm trừ đi nợ hiện tại. Vị thế dương giúp giảm đáng kể xác suất vỡ nợ.



## 💎 Phát hiện "Viên ngọc ẩn" (Hidden Gems) - Chiến lược Đại dương xanh

Thông qua phân tích dữ liệu và thuật toán phân cụm K-Means, dự án đã phát hiện ra một tệp khách hàng chiến lược bị hệ thống ngân hàng truyền thống bỏ qua:

* **Chân dung:** Chuyên gia trẻ, Gen Z, Freelancer có thu nhập cao/rất cao nhưng **điểm tín dụng thấp** do chưa từng có lịch sử vay vốn (Credit Invisible).
* **Nghịch lý tài chính:** Dù điểm tín dụng thấp hơn mặt bằng chung, thu nhập của họ cao gấp 2.2 lần và tiền tiết kiệm cao gấp 3.9 lần. Vị thế tài chính ròng của họ hoàn toàn dương.
* **Giải pháp:** Cung cấp sản phẩm **'Credit Builder'** (thẻ tín dụng ảo, khoản vay nhỏ) xét duyệt dựa trên *dòng tiền thực tế (Cash-flow based)* thay vì chỉ dựa vào điểm CIC truyền thống.

## 📈 Chiến lược Kinh doanh (BCG Matrix Framework)

Dựa trên thuật toán K-Means, tệp khách hàng được phân thành các nhóm chiến lược:

1. **Ngôi sao (Stars - Rủi ro thấp, Tiềm năng cao):** Khách hàng thu nhập cao, điểm tín dụng xuất sắc.
* *Hành động:* Áp dụng phê duyệt tự động "One-click Lending", giảm lãi suất ưu đãi để giữ chân KH VIP.


2. **Bò sữa (Cash Cows - Rủi ro trung bình, Quy mô khổng lồ):** Khách hàng thu nhập khá, tín dụng tốt.
* *Hành động:* Duy trì, tối ưu chi phí vận hành, tung các chương trình Loyalty & Cross-selling.


3. **Dấu hỏi (Question Marks - Nhóm Hidden Gems):** Thu nhập cao, tài sản dương, nhưng điểm tín dụng thấp.
* *Hành động:* Áp dụng Alternative Scoring (chấm điểm bằng dữ liệu thay thế), cấp tín dụng dựa trên dòng tiền. Đây là trọng tâm tăng trưởng thị phần đột phá.


4. **Chó mực (Dogs - Rủi ro cao, Lợi nhuận thấp):** Thu nhập thấp, thất nghiệp, nợ xấu cao.
* *Hành động:* Siết chặt điều kiện giải ngân, yêu cầu tài sản đảm bảo, chỉ cung cấp Micro-loans.



## 💡 Đề xuất hành động (Actionable Solutions)

* **Chuyển đổi số trong Thẩm định:** Sử dụng ML Model làm "chốt chặn" tự động. Hồ sơ có rủi ro vỡ nợ >80% sẽ chuyển sang thẩm định thủ công.
* **Risk-based Pricing (Cá nhân hóa lãi suất):** Tăng/giảm lãi suất linh hoạt dựa trên phân khúc rủi ro và độ tuổi khách hàng.
* **Cạnh tranh bằng tốc độ:** Tận dụng tốc độ của AI (phê duyệt dưới 5 phút) để đánh bật quy trình rườm rà mất nhiều tuần của các ngân hàng truyền thống.
