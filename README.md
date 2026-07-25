# 📊 Business Analysis Case Study: Hệ Thống Bán Hàng Trực Tuyến Kinh Đô

Dự án phân tích nghiệp vụ nhằm giải quyết bài toán quá tải đơn hàng, sai lệch tồn kho và hạn chế của quy trình bán hàng thủ công tại chuỗi cửa hàng Kinh Đô trong mùa vụ cao điểm (Tết Trung Thu). Dự án đề xuất giải pháp số hóa toàn diện, thiết kế lại luồng quy trình (To-Be) và tự động hóa 70-80% tác vụ vận hành.

## 👨‍💻 Thông tin đồ án
* **Sinh viên thực hiện:** Đỗ Trí Tường (MSSV: 2321004127)
* **Giảng viên hướng dẫn:** ThS. Mai Thanh Tâm
* **Trường:** Đại học Tài chính – Marketing (Khoa Khoa học Dữ liệu)

## 🛠 Công cụ & Kỹ thuật Phân tích (BA Techniques)
* **Mô hình hóa quy trình:** BPMN (Business Process Model and Notation), DFD (Data Flow Diagram)
* **Phân tích chiến lược & Nhu cầu:** Khung BACCM, Phân tích SWOT, Mô hình kinh doanh Canvas (BMC)
* **Quản trị dự án & Đánh giá:** Ma trận RACI, Thẻ điểm cân bằng (BSC), KPIs
* **Công cụ hỗ trợ:** Draw.io / Enterprise Architect / MS Visio

## 🚀 Các Giai Đoạn Phân Tích Cốt Lõi

### 1. Phân tích Hiện trạng (As-Is Analysis)
* Khảo sát 45 người dùng và phỏng vấn sâu các bên liên quan (Stakeholders) để tìm ra 3 "điểm nghẽn" lớn: Phụ thuộc 100% vào ghi chép thủ công, kiểm kho chậm trễ và kế toán đối soát mất 2-3 giờ/ngày.
* Vẽ sơ đồ BPMN As-Is và DFD mức ngữ cảnh để minh họa sự phân tán dữ liệu giữa các bộ phận Bán hàng - Kho - Giao hàng - Kế toán.

### 2. Định hình Giải pháp (To-Be Design)
* Xây dựng luồng quy trình mới (BPMN To-Be) với trọng tâm: Khách hàng tự đặt đơn 24/7, tự động trừ tồn kho ngay khi duyệt đơn và cung cấp tính năng Tracking đơn hàng thời gian thực.
* Xác định 19 Quy tắc nghiệp vụ (Business Rules) chặt chẽ, ví dụ: Chặn duyệt đơn nếu số lượng đặt lớn hơn tồn kho (BR-02), quy tắc hủy đơn trước 24h (BR-08).

### 3. Tài liệu hóa Yêu cầu (Requirements Documentation)
* Phân rã hệ thống thành các User Stories và Đặc tả Yêu cầu Chức năng (FR) / Phi chức năng (NFR).
* Xây dựng Ma trận Truy xuất Yêu cầu (Requirement Traceability Matrix - RTM) để đảm bảo mọi chức năng thiết kế đều giải quyết đúng "nỗi đau" ban đầu của doanh nghiệp.
* Hoàn thiện **Tài liệu Yêu cầu Nghiệp vụ (BRD - Business Requirement Document)** làm cơ sở bàn giao cho đội ngũ phát triển (Dev Team).

## 📂 Cấu trúc Kho lưu trữ (Repository Structure)
* `1_Research_and_Strategy/`: Chứa dữ liệu khảo sát, phân tích BACCM, SWOT và BMC.
* `2_Process_Models/`: Chứa hình ảnh sơ đồ BPMN (As-Is, To-Be), DFD, Decision Trees.
* `3_Requirements_Documentation/`: Chứa file tài liệu BRD, User Stories và Ma trận RACI.

## 📸 Sơ đồ Quy trình Bán hàng Tương lai (BPMN To-Be)
<img width="1344" height="730" alt="BPMN_Tobe" src="https://github.com/user-attachments/assets/17cfa4dc-927a-414b-8e9f-d0d4aa1975d3" />
