# 1.1. Giới thiệu về tập dữ liệu

## Bộ dữ liệu
Sức khỏe tâm thần đang trở thành mối quan tâm ngày càng lớn trong giới học thuật. Bộ dữ liệu này mô phỏng một cuộc khảo sát quy mô lớn với **100.000 sinh viên đại học**, tập trung vào thói quen sinh hoạt, kết quả học tập và sức khỏe tâm thần của họ. 

Bộ dữ liệu được thiết kế để cung cấp nguồn tài nguyên phong phú cho các nhiệm vụ:
* **Phân tích Dữ liệu Khám phá (EDA)**
* **Phân loại (Classification)**
* **Hồi quy (Regression)**

Nó cho phép các nhà nghiên cứu và những người đam mê khoa học dữ liệu điều tra mối tương quan giữa mô hình giấc ngủ, thói quen học tập và việc sử dụng mạng xã hội với thành tích học tập (điểm trung bình tích lũy - CGPA) và các vấn đề sức khỏe tâm thần (Trầm cảm & Căng thẳng).

## Nguồn dữ liệu
Nguồn dữ liệu được trích xuất từ Kaggle: [Student Depression and Lifestyle (100k Data)](https://www.kaggle.com/datasets/aldinwhyudii/student-depression-and-lifestyle-100k-data/data)

## Các thuộc tính chính (Data Dictionary)

| Tên cột | Mô tả | Kiểu dữ liệu |
| :--- | :--- | :--- |
| **Student_ID** | Mã định danh duy nhất cho mỗi học sinh. | Integer |
| **Age** | Độ tuổi của sinh viên (18-24). | Integer |
| **Gender** | Giới tính của học sinh (Nam/Nữ). | String |
| **Department** | Ngành học (Kỹ thuật, Kinh doanh, Nghệ thuật, v.v.). | String |
| **CGPA** | Điểm trung bình tích lũy (0.0 - 4.0). | Float |
| **Sleep_Duration** | Số giờ ngủ trung bình mỗi đêm. | Float |
| **Study_Hours** | Số giờ trung bình dành cho việc học mỗi ngày. | Float |
| **Social_Media_Hours** | Số giờ trung bình mỗi ngày dành cho mạng xã hội. | Float |
| **Physical_Activity** | Số phút hoạt động thể chất trung bình mỗi tuần. | Integer |
| **Stress_Level** | Mức độ căng thẳng tự báo cáo (thang điểm 0-10). | Integer |
| **Depression** | Tình trạng sức khỏe tâm thần (`True` = Có thể bị trầm cảm, `False` = Khỏe mạnh). | Boolean |
