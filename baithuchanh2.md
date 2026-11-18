# [Bài thực hành 2] Xây dựng chuỗi Prompt viết bài PR sản phẩm công nghệ

Sản phẩm → Prompt 1 → {{PAIN_POINTS}} → Prompt 2 → {{OUTLINE}} → Prompt 3 → Bài PR
## Prompt 1: Nghiên cứu khách hàng và pain points
Bạn là chuyên gia nghiên cứu thị trường công nghệ tại Việt Nam.

SẢN PHẨM: [tên chatbot] | Tính năng: [24/7, tích hợp Zalo/Facebook, kết nối CRM...]
Điểm khác biệt: [triển khai nhanh, không cần code...] | Ngành: [bán lẻ, tài chính...]

Hãy làm từng bước:
1. Xác định 3 khách hàng (chức danh, quy mô, mục tiêu, kênh thông tin).
2. Mỗi persona: 3-4 pain points kèm biểu hiện và hậu quả thực tế.
3. Ghép mỗi pain point với 1 tính năng giải quyết.
4. Xếp hạng mức cấp bách, chọn 3 pain points trục chính cho bài PR.

Quy tắc: không bịa số liệu, thiếu thì ghi "[cần bổ sung nguồn]".
Đầu ra: bảng Markdown (Persona | Pain point | Hậu quả | Tính năng | Mức cấp bách)
+ 3 pain points trục chính + 5-8 từ khóa SEO.
## Prompt 2: Dàn ý chi tiết
Bạn là biên tập viên PR công nghệ, am hiểu SEO.

ĐẦU VÀO: {{PAIN_POINTS}}

Hãy làm từng bước:
1. Chọn góc tiếp cận từ pain point mạnh nhất.
2. Đề xuất 3 tiêu đề (có từ khóa chính, dưới 70 ký tự), chọn 1 và giải thích.
3. Lập dàn ý bài 1000-1500 từ: Mở đầu (100-150 từ) → 3-4 phần thân H2 (kèm H3)
   → ứng dụng thực tế → Kết luận + CTA.
4. Mỗi mục ghi: mục tiêu | ý chính | số từ | từ khóa.
5. Kiểm tra tổng số từ và độ tương xứng giữa tiêu đề con với nội dung.

Đầu ra: tiêu đề chọn + 2 phương án dự phòng, dàn ý dạng cây H1>H2>H3, bảng tổng số từ.
## Prompt 3: Viết bài và tối ưu SEO
Bạn là copywriter PR công nghệ kiêm chuyên gia SEO.

ĐẦU VÀO: {{OUTLINE}}
Từ khóa chính: [...] | Từ khóa phụ: [3-5 từ] | Giọng văn: chuyên nghiệp, gần gũi.

Viết bài 1000-1500 từ, bám sát dàn ý. Bắt buộc có:
- Tiêu đề hấp dẫn: có từ khóa chính, gợi lợi ích/nỗi đau, dưới 70 ký tự.
- Mở đầu gây ấn tượng: tình huống thực tế hoặc câu hỏi, nêu vấn đề, hứa hẹn giải pháp.
- Tiêu đề con H2/H3 tương xứng nội dung, không trùng lặp, chèn từ khóa phụ.
- CTA rõ ràng: một hành động chính (dùng thử/đặt demo) + lý do làm ngay + liên hệ [placeholder].

SEO: từ khóa chính ở tiêu đề, 100 từ đầu, 1 H2 và kết luận (mật độ 1-1,5%);
đoạn ngắn 3-4 câu; không bịa số liệu.

Đầu ra: (A) bài PR Markdown, (B) meta title ≤ 60 ký tự + meta description ≤ 155 ký tự,
(C) bảng tự kiểm tra: Tiêu chí | Đạt/Chưa đạt (số từ, tiêu đề, mở đầu, tiêu đề con, CTA, từ khóa).
