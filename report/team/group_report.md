# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm:
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu):
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |
| 7 | | | | | |
| 8 | | | | | |
| 9 | | | | | |
| 10 | | | | | |
| 11 | | | | | |
| 12 | | | | | |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A | | |
| B | | |
| C | | |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: 
├── Opportunity A: 
├── Opportunity B: 
└── Opportunity C: 
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

-

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| | | | | | | | | |
| | | | | | | | | |
| | | | | | | | | |

**Candidate được chọn:**

**Vì sao chọn:**

**Vì sao loại các candidate còn lại:**

**Xử lý bất đồng (nếu có):**

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |

*Điền 4–6 giả định; xóa dòng thừa.*

Giả định nhóm kiểm chứng trong buổi này:

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | |
| Câu nói đáng nhớ nhất (nguyên văn) | |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | |
| Hiện đang xử lý bằng cách nào (workaround)? | |
| Mất bao lâu, bao lần? | |
| Insight / opportunity rút ra | |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| | | | |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |
| | | | | | |

---

## 4. Quy trình trước/sau (CP5)

Bài toán: **Tìm đúng yêu cầu trong nhiều tài liệu**, theo [Card #2 của Lý Thành Lập](../individual/2A202603414_LyThanhLap.md). Đầu ra cần đạt là checklist đúng phạm vi cá nhân, đầy đủ yêu cầu và có nguồn đối chiếu.

### 4.1. Quy trình hiện tại

```text
HIỆN TẠI — ước lượng 20 phút/lần nhận bài
[1 Xem danh sách tài liệu: 3'] → [2 Tìm mục liên quan: 5']
→ [3 Đối chiếu yêu cầu giữa các file: 9'] ← BOTTLENECK
→ [4 Ghi checklist: 3']
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Sinh viên | Đề, mẫu, rubric, hướng dẫn nộp | Danh sách tài liệu | 3 phút/lần nhận bài | Xác định nguồn cần đọc |
| 2 | Sinh viên | Tài liệu và phần việc được giao | Các mục liên quan | 5 phút/lần | Tìm trong từng file |
| 3 | Sinh viên | Các mục đã tìm | Yêu cầu áp dụng và điểm chưa rõ | 9 phút/lần | Đối chiếu phạm vi, điều kiện và nội dung trùng/mâu thuẫn |
| 4 | Sinh viên | Yêu cầu đã đối chiếu | Checklist để bắt đầu viết | 3 phút/lần | Ghi đầu ra và tiêu chí hoàn thành |

**Bottleneck:** Bước 3, ước lượng 9/20 phút. Yêu cầu phân tán khiến sinh viên phải đối chiếu nhiều lần, dễ nhầm nội dung ví dụ với quy định bắt buộc. Các thời gian lấy từ CP2, chưa được bấm giờ.

### 4.2. Quy trình tương lai

Sinh viên cung cấp bộ file/thư mục/link và vai trò đã biết. AI nhận diện tài liệu liên quan, xác định phần việc dựa trên phân công có trong nguồn và lập checklist. Sinh viên xác minh, chỉnh sửa và duyệt kết quả.

```text
[1 Cung cấp bộ nguồn và vai trò] ← CON NGƯỜI
→ [2 Liệt kê, đọc file và giữ vị trí nguồn] ← RULE
→ [3 Nhận diện tài liệu liên quan và phần việc] ← AI
→ [4 Trích, đối chiếu yêu cầu; lập checklist có nguồn] ← AI
→ [5 Kiểm tra, sửa và duyệt checklist] ← CON NGƯỜI
→ [6 Kiểm cấu trúc và lưu bản đã duyệt] ← RULE

Thiếu file hoặc lỗi đọc → bổ sung nguồn tại bước 1–2.
Thiếu phân công hoặc nguồn mâu thuẫn → hỏi người phụ trách, cập nhật bước 3.
Checklist sai/thiếu → sửa hoặc chạy lại bước 3–4, sau đó kiểm lại bước 5.
```

| Bước | Actor / mức can thiệp | Input | Output | Kiểm soát |
|---:|---|---|---|---|
| 1 | Sinh viên | File/thư mục/link, vai trò đã biết | Bộ nguồn và ngữ cảnh ban đầu | Không yêu cầu sinh viên đọc và chọn từng file trước |
| 2 | Công cụ — Rule | Bộ nguồn | Danh mục file, phiên bản, văn bản và vị trí nguồn | Báo file lỗi/không truy cập được; không tự loại vì không đọc được |
| 3 | AI | Danh mục, nội dung tài liệu, vai trò | Nguồn liên quan, phần việc dự kiến và căn cứ | Lưu lý do chọn/loại; hỏi lại khi thiếu phân công hoặc phiên bản mâu thuẫn |
| 4 | AI | Nguồn liên quan và phạm vi đủ rõ | Checklist nháp, trích đoạn nguồn, điểm cần làm rõ | Giữ điều kiện áp dụng; phân biệt yêu cầu bắt buộc với ví dụ |
| 5 | Sinh viên; người phụ trách khi cần | Checklist và tài liệu gốc | Checklist đã sửa/duyệt | Kiểm nguồn từng mục; rà soát đề, rubric, hướng dẫn nộp và danh sách file bị loại để tìm yêu cầu thiếu |
| 6 | Công cụ — Rule | Checklist được duyệt | Bản lưu có phiên bản, nguồn và trạng thái duyệt | Kiểm trường bắt buộc; không tự xác nhận tính đúng của nội dung |

**Checklist gồm:** yêu cầu, phạm vi áp dụng, đầu ra/tiêu chí hoàn thành, trích đoạn và vị trí nguồn, phiên bản, trạng thái xác nhận.

**Boundary:** AI chỉ đề xuất từ bộ nguồn được cung cấp; không tự phân công, bịa yêu cầu, giải quyết mâu thuẫn hoặc duyệt kết quả. Sinh viên phải kiểm cả tính đúng và đầy đủ trước khi sử dụng. Yêu cầu quan trọng còn mơ hồ phải được người phụ trách làm rõ trước khi duyệt.

**Phương án quay về:** Khi nguồn không đọc được, công cụ lỗi hoặc nháp cần sửa quá nhiều, dùng tìm kiếm trong file và checklist thủ công có nguồn. Giữ riêng các điểm mâu thuẫn để hỏi người phụ trách.

**Thời gian:** Đo từng bước và tổng thời gian từ cung cấp dữ liệu đến lưu bản đã duyệt, gồm chờ công cụ, hỏi làm rõ và sửa nháp. Chưa có số đo cho quy trình mới; chi phí thiết lập ban đầu ghi riêng.

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) |
|---|---|---|
| Số bước | 4 | 6 |
| Bước có thao tác con người | 4/4 | 2/6 thường lệ; bổ sung thông tin khi có ngoại lệ |
| Tổng thời gian | Ước lượng 20 phút/lần | Thấp hơn checklist thủ công có link, với chất lượng đạt mục 5 |
| Bottleneck | Đối chiếu giữa file: 9 phút, ước lượng | Dự kiến kiểm và sửa checklist tại bước 5; cần đo |
| Yêu cầu quan trọng bị bỏ sót | Chưa có số đo | 0 trong checklist đã duyệt |
| Khả năng truy lại nguồn | Chưa có số đo | 100% mục có nguồn đúng |
| Rủi ro | Đọc thiếu hoặc hiểu sai | AI chọn nhầm nguồn, trích sai hoặc bỏ sót; kiểm soát bằng dẫn nguồn và người duyệt |

---

## 5. Problem Statement v0 (CP5)

Sinh viên thực hiện báo cáo cá nhân phải tổng hợp yêu cầu từ đề bài, mẫu, rubric và hướng dẫn nộp. Quy trình hiện tại mất khoảng 20 phút/lần, trong đó đối chiếu giữa các file chiếm 9 phút theo ước lượng cá nhân. Mục tiêu là giảm thời gian lập checklist mà vẫn bảo đảm đúng phạm vi, đủ yêu cầu quan trọng và kiểm chứng được nguồn.

| Trường | Nội dung |
|---|---|
| **Actor** | Sinh viên phụ trách báo cáo cá nhân trong bài tập nhóm, vừa nhận nhiều tài liệu hướng dẫn. |
| **Quy trình** | Xem danh sách tài liệu → tìm mục liên quan → đối chiếu yêu cầu → ghi checklist trước khi viết. |
| **Bottleneck** | Đối chiếu phạm vi và điều kiện giữa nhiều file: ước lượng 9 phút/lần, cần đo lại. |
| **Impact** | Khoảng 20 phút chuẩn bị mỗi lần nhận bài theo ước lượng; có nguy cơ bỏ sót yêu cầu và phải sửa nội dung. Chưa định lượng số lần làm lại hoặc mức ảnh hưởng điểm. |
| **Success Metric** (baseline → target, cách đo) | Checklist sau duyệt bao phủ 100% yêu cầu quan trọng, có 0 yêu cầu sai/vô căn cứ và 100% mục có nguồn đúng. Khi đạt chất lượng này, trung vị tổng thời gian phải thấp hơn baseline đo thực tế của checklist thủ công có link trên tác vụ tương đương. |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | AI không tự tạo yêu cầu, phân công, giải quyết nguồn mâu thuẫn hoặc duyệt checklist. Sinh viên kiểm nguồn và tính đầy đủ trước khi sử dụng; người phụ trách xác nhận điểm chưa rõ. Công cụ không viết hay nộp báo cáo thay người học. |

**Cách đo:** Người rà soát lập danh sách chuẩn từ toàn bộ tài liệu trước khi đánh giá; đánh dấu các yêu cầu quan trọng về đầu ra bắt buộc, tiêu chí chấm và điều kiện nộp.

| Chỉ số | Công thức / cách ghi nhận | Mục tiêu |
|---|---|---|
| Bao phủ yêu cầu quan trọng | Số yêu cầu quan trọng ghi đúng, đủ điều kiện / tổng yêu cầu quan trọng trong danh sách chuẩn | 100% ở từng checklist thử |
| Yêu cầu sai/vô căn cứ | Đếm mục sai phạm vi, sai điều kiện hoặc không được nguồn hỗ trợ | 0 |
| Nguồn chính xác | Số mục có vị trí nguồn đúng và hỗ trợ nội dung / tổng mục checklist | 100% |
| Thời gian hoàn thành | Từ cung cấp bộ nguồn đến lưu checklist đã duyệt; gồm chờ và sửa | Trung vị thấp hơn đối chứng thủ công khi đạt ba điều kiện chất lượng trên |

**Thử nghiệm đề xuất:** So sánh checklist thủ công có link với Workflow trên ít nhất 3 cặp bộ tài liệu tương đương về số file, độ dài và độ khó. Dùng bài khác nhau, luân phiên thứ tự và ghi mức quen thuộc để hạn chế ảnh hưởng ghi nhớ. Báo cáo từng lượt, trung vị thời gian và số mục sai/thiếu; không loại lượt không đạt chất lượng khỏi kết quả. Mẫu này chỉ phục vụ pilot. Ước lượng 20 phút cần đo lại; chưa đặt ngưỡng thời gian tuyệt đối khi thiếu baseline.

**Phản biện AI đã dùng để chỉnh v0:** Ý kiến đồng ý của nhóm cần được nhóm xác nhận.

| Điểm phản biện | Điều chỉnh trong bản v0 |
|---|---|
| Baseline chưa được đo; mục tiêu dưới 8 phút thiếu cơ sở | So sánh với thời gian thủ công đo thực tế, tính cả kiểm và sửa |
| Nhanh hơn nhưng thiếu yêu cầu vẫn không đạt | Bổ sung điều kiện đúng, đủ và có nguồn |
| Chỉ kiểm mục AI trích sẽ bỏ qua mục AI bỏ sót | Rà soát độc lập tài liệu và danh sách nguồn bị loại |
| Checklist thủ công có thể đã đủ | Dùng làm đối chứng trước khi quyết định mức can thiệp tại CP6 |

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | | | | |
| **Rule** | | | | |
| **Workflow** | | | | |
| **Agent** | | | | |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | |
| **Judgment** — con người cân nhắc, quyết định gì? | |
| **Action** — hành động cuối cùng là gì, ai làm? | |
| **Outcome** — đo kết quả bằng gì? | |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** | |
| **AI intervention point** | |
| **Mức chọn** | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra** | |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| | | | |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | | |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | | |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | | |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | | |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go

**Lý do:**

**Nếu Go — pilot nhỏ nhất:**

**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-
