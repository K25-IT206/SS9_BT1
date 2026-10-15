# Nhận diện và sửa kế hoạch Sprint Review

## Phần 1 - Rà kế hoạch

| Mã | Phù hợp / Chưa phù hợp | Quy tắc làm căn cứ | Cách sửa ngắn gọn |
|---|---|---|---|
| K-01 | Phù hợp | — | Giữ phần nhắc Sprint Goal để mọi người cùng định hướng buổi Review. |
| K-02 | Chưa phù hợp | QT1 | Bỏ báo cáo phần trăm hoàn thành và giải thích nhóm bận. Developers trình bày kết quả thực tế so với Sprint Goal, những gì đã Done và những gì chưa Done. |
| K-03 | Chưa phù hợp | QT2 | Chỉ demo PBI-41 là Increment đã Done. Developers demo hành trình: khách nhập mã đơn trên website, xem trạng thái đơn được trả về; sau đó mời Stakeholders thao tác và đặt câu hỏi. Nêu rõ PBI-42 và PBI-44 chưa Done, kèm các kiểm thử lỗi và lỗi nghiêm trọng còn tồn tại. |
| K-04 | Chưa phù hợp | QT1 | Thay nghiệm thu và câu hỏi đóng bằng trao đổi mở: “Kết quả này ảnh hưởng thế nào đến cách anh/chị hỗ trợ khách hàng, và anh/chị muốn chúng tôi tìm hiểu thêm điều gì?” Ghi Feedback, câu hỏi và đề xuất vào danh sách để Product Owner cùng Scrum Team xem xét khi cập nhật Product Backlog; không xem đó là cam kết tự động. |

## Phần 2 - Trạng thái PBI

| PBI | Done / Chưa Done | Câu thông báo trong Sprint Review |
|---|---|---|
| PBI-41 | Done | PBI-41 đã chạy trên môi trường thử nghiệm, cả 60/60 kiểm thử chính đều đạt và không còn lỗi mức nghiêm trọng cao; chúng tôi giới thiệu đây là Increment của Sprint. |
| PBI-42 | Chưa Done | PBI-42 đã tích hợp nhưng còn 8 ca kiểm thử lỗi dịch vụ đơn hàng chưa đạt, nên chưa đáp ứng điều kiện Done và chưa được giới thiệu là Increment. |
| PBI-44 | Chưa Done | PBI-44 chưa được xem là Done vì 6/80 ca bị phân loại sai và vẫn còn 01 lỗi mức nghiêm trọng cao; chúng tôi công khai các kết quả này để cùng xem xét bước tiếp theo. |

## Phần 3 - Xử lý tình huống

Chúng ta không nên giấu 6 ca phân loại sai hoặc lỗi mức nghiêm trọng cao của PBI-44; Sprint Review cần trình bày trung thực cả kết quả đạt được lẫn phần chưa Done.  
PBI-44 chưa đạt điều kiện Done nên không thể giới thiệu là Increment, dù nhóm muốn Sprint trông thành công hơn.  
Feedback của Chủ cửa hàng sẽ được ghi nhận và xem xét khi Product Owner cập nhật Product Backlog; chúng ta không hứa sẽ thực hiện ngay mọi góp ý.  
Nên mời Trưởng nhóm CSKH tham dự vì họ có góc nhìn trực tiếp về việc chuyển hội thoại sớm khi AI không chắc chắn, bổ sung cho mong muốn AI tự trả lời nhiều hơn của Chủ cửa hàng.  
Trong buổi Review, Developers làm rõ kết quả, còn Stakeholders được đặt câu hỏi và chia sẻ Feedback để Scrum Team cùng thích ứng.
