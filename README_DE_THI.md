# Bài kiểm tra cuối môn Computer Vision

Tổng điểm: 100.

## Chuẩn bị môi trường

Máy cần cài các thư viện trong `requirements.txt` và chọn được kernel `Python (CV Final)`. Video và model đã được cung cấp sẵn.

## Học viên thực hiện

1. Mở `Bai_kiem_tra_Cuoi_mon_CV.ipynb`.
2. Hoàn thành các vị trí `TODO`.
3. Chạy notebook từ đầu.
4. Kiểm tra thư mục `outputs/`.
5. Nén bài thành `MSSV_HoTen_FinalCV.zip`.

Không thay video hoặc model đã cung cấp. Video mới đã nằm trong data/exam_video.mp4; học viên không cần tải thêm.

## Nội dung bài

Đọc frame đại diện, chọn vạch dọc và ROI, hoàn thành tracking và counting, so sánh hai confidence, viết nhận xét 2–3 câu và trả lời năm câu phân tích.

Tự viết hàm run_tracking_pipeline trả bốn giá trị: tracks_df, events_df, video_out, run_info. Đề nêu các trường CSV cần có; học viên tự bảo đảm file rỗng vẫn có header. Notebook cung cấp import và các TODO, học viên tự viết phần chuẩn bị dữ liệu, metadata và pipeline dựa trên bài mẫu.

Nguồn video: Pixabay trên Pexels. Xem data/NGUON_VIDEO.md.
