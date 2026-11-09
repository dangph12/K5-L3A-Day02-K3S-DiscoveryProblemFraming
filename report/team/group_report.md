# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm:
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Khi nhận bài tập có nhiều file hướng dẫn, sinh viên mất thời gian xác định yêu cầu áp dụng cho phần mình làm và dễ bỏ sót điều kiện nộp.
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

|   # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
| --: | ------------ | -------------------------- | ----- | ---------- | ------------------------------------ |
|   1 |              |                            |       |            |                                      |
|   2 |              |                            |       |            |                                      |
|   3 |              |                            |       |            |                                      |
|   4 |              |                            |       |            |                                      |
|   5 |              |                            |       |            |                                      |
|   6 |              |                            |       |            |                                      |
|   7 |              |                            |       |            |                                      |
|   8 |              |                            |       |            |                                      |
|   9 |              |                            |       |            |                                      |
|  10 |              |                            |       |            |                                      |
|  11 |              |                            |       |            |                                      |
|  12 |              |                            |       |            |                                      |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
| ------- | ------------- | ------------- |
| A       |               |               |
| B       |               |               |
| C       |               |               |

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
| --------- | -------: | -----------: | -----------------: | -------------: | ----------: | -------------------------------------: | ---------------: | ---: |
|           |          |              |                    |                |             |                                        |                  |      |
|           |          |              |                    |                |             |                                        |                  |      |
|           |          |              |                    |                |             |                                        |                  |      |

**Candidate được chọn:** Tìm và đối chiếu yêu cầu trong nhiều tài liệu hướng dẫn bài tập.

**Vì sao chọn:** Actor và quy trình 4 bước đã mô tả ở mục 4; bottleneck dự kiến là đối chiếu yêu cầu giữa các file. Hai Interview Snapshot ở mục 3.2 nêu việc đọc lại hướng dẫn để phát hiện phần nộp cá nhân và khó biết file nào cần tham khảo. Thời gian 20 phút ở mục 4 vẫn là ước lượng, cần bấm giờ để xác nhận.

**Vì sao loại các candidate còn lại:**

**Xử lý bất đồng (nếu có):**

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

|   # | Giả định                                                                                                            | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước?                             |
| --: | ------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------- | ---------------: | ---------------------: | --------------------------------------------- |
|   1 | Sinh viên phải đọc và đối chiếu nhiều file để biết đủ yêu cầu cho phần việc của mình. | Value | 5 | 2 | Có — hỏi về lần làm bài gần nhất; bấm giờ |
|   2 | Sinh viên có thể nhầm yêu cầu nộp nhóm với yêu cầu nộp cá nhân. | Value | 5 | 2 | Có — kiểm trên bộ tài liệu và bài nộp thật |
|   3 | Khó xác định file hoặc phiên bản nào là nguồn chính thức khi các hướng dẫn khác nhau. | Value | 5 | 2 | Có — hỏi người phụ trách và đối chiếu file |
|   4 | Bước đối chiếu yêu cầu giữa các file là bước tốn thời gian nhất trong quy trình 4 bước. | Value | 5 | 1 | Có — bấm giờ từng bước, chưa có số đo |
|   5 | Checklist thủ công có link nguồn vẫn chưa đủ giảm thời gian mà không bỏ sót yêu cầu quan trọng. | Feasibility | 4 | 1 | Sau — thử checklist trước khi thử AI |

**Giả định nhóm kiểm chứng trước:** #1–#4 vì quan trọng nhưng mới có tự thuật của hai học viên và thời gian ước lượng trong Problem Card. Điểm bằng chứng 1–2 là đánh giá ban đầu, chưa phải kết quả đo. Nếu bước đối chiếu không phải bottleneck hoặc checklist thủ công đã đủ, nhóm cần sửa quy trình tương lai và cân nhắc No AI.

### 3.2. Kiểm chứng

**Cách đã dùng:** Phỏng vấn 2 học viên trong lớp về lần gần nhất phải đọc hướng dẫn để xác định việc cần làm và nộp. Hai buổi được ghi thành Interview Snapshot dưới đây. Ngày và cách phỏng vấn chưa được ghi trong snapshot; nhóm cần bổ sung từ ghi chép thật, không suy đoán. Khảo sát 5 người về hạn nộp thuộc candidate khác, được lưu ở mục 9 và không tính là kiểm chứng trực tiếp cho problem nhiều tài liệu.

Interview snapshot — người thứ 1:

| Trường                                            | Nội dung                                                                                                                                                                                                              |
| ------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Người được hỏi (vai trò, không ghi tên thật)      | Học viên                                                                                                                                                                                                              |
| Câu nói đáng nhớ nhất (nguyên văn)                | Mình nhớ hạn nộp báo cáo của nhóm, nhưng lại quên phần đánh giá cá nhân cũng phải nộp riêng.                                                                                                                          |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Tối thứ 6 tuần trước, tôi mở hệ thống học tập để kiểm tra bài tập. Báo cáo nhóm đã được nhóm trưởng nộp nên tôi nghĩ đã hoàn thành. Khi đọc lại hướng dẫn, tôi mới phát hiện mỗi thành viên còn phải nộp bài cá nhân. |
| Hiện đang xử lý bằng cách nào (workaround)?       | Đọc lại yêu cầu bài tập hỏi mọi người trong nhóm phần nào nộp chung và phần nào nộp riêng, rồi đánh dấu từng phần đã hoàn thành trong ghi chú.                                                                        |
| Mất bao lâu, bao lần?                             | khoảng 12 phút                                                                                                                                                                                                        |
| Insight / opportunity rút ra                      | ra Học viên có thể nhớ đúng hạn nhưng chưa nắm đủ các phần cần nộp. Cơ hội là giúp học viên theo dõi từng đầu việc, phân biệt trách nhiệm cá nhân và nhóm, cùng trạng thái hoàn thành.                                |

Interview snapshot — người thứ 2:

| Trường                                            | Nội dung                                                                                                                                                                                    |
| ------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Người được hỏi (vai trò, không ghi tên thật)      | Học viên                                                                                                                                                                                    |
| Câu nói đáng nhớ nhất (nguyên văn)                | Có nhiều file hướng dẫn đôi lúc khoogn biết tham khảo file nào cho đúng và chính xác nhất                                                                                                   |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Thứ 5 tuần trước                                                                                                                                                                            |
| Hiện đang xử lý bằng cách nào (workaround)?       | đọc kĩ lại tất cả các file hoặc hỏi mọi người xung quanh                                                                                                                                    |
| Mất bao lâu, bao lần?                             | khoảng 20-30 phút để có thể hiểu các yêu cầu                                                                                                                                                |
| Insight / opportunity rút ra                      | ra Học viên mất thời gian đối chiếu vì chưa xác định được tài liệu nào là bản chính thức. Cơ hội là giúp học viên nhận biết bản hướng dẫn cần sử dụng và những thay đổi giữa các phiên bản. |

Tổng hợp:

| Nguồn                                                                 | Số người / số mẫu | Tín hiệu xác nhận                                                                                                                                                                                                 | Tín hiệu phản bác                                                                                                                                                        |
| --------------------------------------------------------------------- | ----------------: | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Phỏng vấn học viên, 2 Interview Snapshot ở trên | 2 | Người thứ nhất phát hiện thêm phần nộp cá nhân khi đọc lại hướng dẫn, mất khoảng 12 phút; người thứ hai cho biết phải đọc lại nhiều file hoặc hỏi người khác, mất khoảng 20–30 phút để hiểu yêu cầu. | Chưa có số đo riêng cho bước đối chiếu; snapshot thứ hai mới ghi “thứ 5 tuần trước”, chưa kể rõ một tình huống và file cụ thể. Hai trường hợp chưa chứng minh pain phổ biến ở nhiều sinh viên. |

**Nhóm đã sửa problem thế nào sau kiểm chứng:** Thu hẹp từ “khó theo dõi bài tập” thành “khó xác định đầy đủ yêu cầu áp dụng cho phần việc của mình khi thông tin nằm trong nhiều file hướng dẫn”. Trường hợp thứ nhất cho thấy rủi ro bỏ sót phần nộp cá nhân dù nhớ đúng hạn; trường hợp thứ hai gợi ý khó nhận biết file cần tham khảo. Chưa thể kết luận bản mới nhất là bản chính thức hay bước đối chiếu thực sự mất 9 phút nếu chưa kiểm file và bấm giờ.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
| ------------------------ | ---- | ------------------------------ | --------- | --------------------- | ---------------- |
| Google Drive Search | https://support.google.com/drive/answer/2375114?co=GENIE.Platform%3DDesktop&hl=en | Bước 2: tìm file và đoạn liên quan theo từ khóa, loại file, người liên quan, ngày sửa. | Thu hẹp bộ file cần đọc mà không cần AI. | Chỉ tìm trong file được phép truy cập; kết quả tìm kiếm không xác nhận file nào là nguồn chính thức. | Thử tìm kiếm có bộ lọc trước khi dùng AI. |
| Lịch sử phiên bản Google Docs | https://support.google.com/docs/answer/190843 | Bước 3: xem thay đổi, người sửa và phiên bản của tài liệu trong Google Docs. | Giúp đối chiếu các lần sửa của cùng một file. | Cần quyền phù hợp; phiên bản mới nhất không tự động là hướng dẫn có thẩm quyền, và tính năng này không so sánh mọi file khác nhau. | Hỏi người phụ trách xác nhận tài liệu chính thức khi nguồn mâu thuẫn. |
| Gemini Notebook (NotebookLM) | https://support.google.com/gemininotebook/answer/16179559 | Bước 3: hỏi về yêu cầu trong bộ nguồn đã chọn, mở trích dẫn để kiểm đoạn gốc. | Có thể tạo nháp yêu cầu kèm vị trí nguồn để sinh viên kiểm. | Chỉ xử lý nguồn được đưa vào; không bảo đảm đủ yêu cầu hoặc tự quyết nguồn nào có thẩm quyền. | Chỉ thử bước hỗ trợ trích nháp nếu checklist thủ công chưa đủ; sinh viên vẫn kiểm toàn bộ nguồn quan trọng. |

**Kết luận research:** Công cụ có sẵn đã hỗ trợ tìm file, xem thay đổi và trích nháp yêu cầu kèm nguồn. Khoảng trống chính là xác định tài liệu nào có thẩm quyền và bảo đảm không bỏ sót yêu cầu; người học phải kiểm hai việc này. Nhóm nên thử tìm kiếm trong file + checklist có link nguồn trước, rồi mới so sánh với Workflow dùng Gemini Notebook nếu phương án thủ công chưa đạt. Chưa có bằng chứng cần xây Agent.

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

```text
HIỆN TẠI — ước lượng 20 phút/lần nhận bài, chưa bấm giờ
[1 Xem danh sách tài liệu: 3'] → [2 Tìm mục liên quan: 5']
→ [3 Đối chiếu yêu cầu giữa các file: 9'] ← BOTTLENECK
→ [4 Ghi checklist để bắt đầu viết: 3']
```

| Bước | Actor     | Input                                   | Output                                          | Thời gian / tần suất                         | Ghi chú                                                                                   |
| ---: | --------- | --------------------------------------- | ----------------------------------------------- | -------------------------------------------- | ----------------------------------------------------------------------------------------- |
|    1 | Sinh viên | Đề bài và danh sách file được cung cấp  | Danh sách tài liệu cần đọc                      | Ước lượng 3 phút/lần nhận bài nhiều tài liệu | Nhận diện đề, mẫu, rubric và hướng dẫn nộp                                                |
|    2 | Sinh viên | Các file và phần việc cá nhân được giao | Các đoạn có thể liên quan đến phần mình làm     | Ước lượng 5 phút/lần                         | Mở và tìm từng mục, ghi vị trí để quay lại                                                |
|    3 | Sinh viên | Các đoạn yêu cầu tìm được ở bước 2      | Các yêu cầu áp dụng, điểm trùng và điểm chưa rõ | Ước lượng 9 phút/lần                         | Bottleneck: đối chiếu nội dung giữa nhiều file; không tự suy đoán khi các nguồn mâu thuẫn |
|    4 | Sinh viên | Yêu cầu đã đối chiếu                    | Checklist để bắt đầu viết báo cáo cá nhân       | Ước lượng 3 phút/lần                         | Ghi đầu ra cần có, điều kiện nộp và nguồn đối chiếu                                       |

**Bottleneck chính:** Bước 3 chiếm 9/20 phút theo ước lượng của card. Người học phải phân biệt yêu cầu cho cá nhân/nhóm, tìm điều kiện nằm ở rubric hoặc hướng dẫn nộp, và kiểm tra phần nào của bài mẫu chỉ dùng để tham khảo. Thời gian và nguyên nhân nghẽn cần được xác nhận bằng quan sát thực tế.

### 4.2. Quy trình tương lai

**Phương án cần thử trước:** checklist thủ công có link đến từng mục nguồn, kết hợp tìm kiếm trong file. Nếu cách này đủ đạt thời gian và chất lượng mong muốn, giữ No AI. Quy trình có AI dưới đây là phương án Workflow đề xuất trong Card #2 để so sánh; các bước được định sẵn, người học vẫn xác nhận checklist.

```text
TƯƠNG LAI — mục tiêu 7,5 phút/lần, chưa đo
[1 Chọn tài liệu + xác định phần mình làm: 1,5'] ← CON NGƯỜI
→ [2 Kiểm file đọc được, gắn mã nguồn/vị trí: 0,5'] ← RULE
→ [3 Trích nháp yêu cầu kèm nguồn: 1'] ← AI
→ [4 Mở nguồn, đối chiếu rubric và sửa checklist: 3,5'] ← CON NGƯỜI; BOTTLENECK DỰ KIẾN
→ [5 Kiểm trường bắt buộc + lưu checklist: 0,5'] ← RULE + CON NGƯỜI xác nhận lưu
Nguồn thiếu/không đọc được → báo thiếu, quay lại bước 1.
Yêu cầu mâu thuẫn → đánh dấu chờ xác nhận, hỏi người phụ trách rồi kiểm lại bước 4.
```

| Bước | Actor / mức can thiệp               | Input                                       | Output                                                 | Thời gian mục tiêu | Kiểm soát / bàn giao                                                                                                  |
| ---: | ----------------------------------- | ------------------------------------------- | ------------------------------------------------------ | ------------------ | --------------------------------------------------------------------------------------------------------------------- |
|    1 | Sinh viên — con người               | Tài liệu được phép sử dụng, mô tả phần việc | Bộ tài liệu và phạm vi cần tìm                         | 1,5 phút           | Chọn đúng phiên bản; nêu rõ làm phần cá nhân nào                                                                      |
|    2 | Công cụ — Rule                      | Bộ file đã chọn                             | Văn bản đọc được, mã file và số trang/mục              | 0,5 phút           | Báo file lỗi, trang không đọc được; không báo đã xử lý đầy đủ khi thiếu nội dung                                      |
|    3 | AI                                  | Văn bản, phạm vi, mã nguồn và mẫu checklist | Nháp yêu cầu, loại yêu cầu, trích đoạn và vị trí nguồn | 1 phút             | Phân biệt yêu cầu bắt buộc với ví dụ; đánh dấu mơ hồ/mâu thuẫn, không tự giải quyết                                   |
|    4 | Sinh viên — con người               | Nháp, tài liệu gốc và rubric                | Checklist đã sửa, nguồn đã kiểm và câu hỏi còn chờ     | 3,5 phút           | Kiểm mọi yêu cầu; quét độc lập rubric/hướng dẫn nộp để phát hiện cả mục AI bỏ sót, không chỉ kiểm các mục AI đã trích |
|    5 | Công cụ — Rule; sinh viên duyệt lưu | Checklist sau rà soát                       | Bản checklist có trạng thái xác nhận và link nguồn     | 0,5 phút           | Rule kiểm ô bắt buộc/trùng lặp; người học quyết định nội dung đủ để bắt đầu viết                                      |

**Cấu trúc checklist:** yêu cầu; áp dụng cho cá nhân/nhóm; đầu ra cần có; tiêu chí hoàn thành; tên file và trang/mục nguồn; trạng thái đã kiểm/chờ làm rõ. Mục chưa xác nhận phải hiển thị riêng, không được âm thầm bỏ khỏi danh sách.

**Boundary:** AI chỉ trích nháp trong bộ tài liệu được cung cấp, không tạo thêm quy định, không biến nội dung ví dụ thành yêu cầu bắt buộc và không tự chọn nguồn ưu tiên khi các file mâu thuẫn. Mỗi yêu cầu phải dẫn đến đoạn nguồn để sinh viên kiểm tra. Sinh viên duyệt trước khi dùng checklist để viết; các yêu cầu quan trọng về nội dung, tiêu chí chấm và điều kiện nộp phải được kiểm trực tiếp. Quy trình không viết báo cáo hay nộp bài thay người học.

**Phương án quay về:** Nếu thiếu nguồn, AI trích sai hoặc không dẫn được vị trí, bỏ phần nháp đó và dùng tìm kiếm trong file + checklist thủ công. Nếu lỗi công cụ hoặc thời gian rà soát nháp không giúp ích, quay về toàn bộ quy trình hiện tại. Khi tài liệu mâu thuẫn, giữ cả các đoạn nguồn và hỏi giảng viên/người phụ trách; chỉ cập nhật checklist sau khi làm rõ.

**Điều kiện thử:** Bộ file có thể đọc được và có phiên bản xác định. Chi phí chuẩn bị công cụ/mẫu một lần ghi riêng; thời gian chọn, đọc/chuyển đổi file, chờ AI và kiểm lại đều tính trong mỗi lần thực hiện. Nếu cần OCR hay thời gian hỏi người phụ trách, ghi thêm thay vì cố ép tổng vào 7,5 phút.

### 4.3. Before / after

| Chỉ số                        | Trước                             | Sau (kỳ vọng)                                                       | Ghi chú                                                                                |
| ----------------------------- | --------------------------------- | ------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| Số bước                       | 4                                 | 5                                                                   | Tăng bước kiểm soát và dẫn nguồn; không lấy số bước ít hơn làm mục tiêu                |
| Tổng thời gian                | Ước lượng 20 phút/lần             | Mục tiêu 7,5 phút/lần, dưới 8 phút theo card                        | Gồm 1,5 + 0,5 + 1 + 3,5 + 0,5; chưa có kết quả đo                                      |
| Số bước có thao tác con người | 4/4                               | 3/5: bước 1, 4 và duyệt lưu ở 5                                     | Bước 5 kết hợp Rule và con người; không coi toàn bộ bước này là tự động                |
| Bottleneck chính              | Đối chiếu giữa file: 9 phút       | Dự kiến kiểm nguồn và sửa checklist: 3,5 phút                       | Giữ người học kiểm cả tính đúng và tính đầy đủ                                         |
| Yêu cầu quan trọng bị bỏ sót  | Chưa có số lượng xác nhận         | Mục tiêu 0                                                          | Đối chiếu với danh sách chuẩn do người phụ trách/reviewer xác nhận từ toàn bộ tài liệu |
| Khả năng truy lại nguồn       | Chưa có số đo trong card          | Mục tiêu mọi mục đã duyệt có nguồn kiểm được                        | Link/mã file và số trang/mục phải dẫn đúng nội dung                                    |
| Rủi ro mới phát sinh          | Đọc thiếu hoặc hiểu thiếu yêu cầu | AI bịa yêu cầu, bỏ sót mục, dùng sai phiên bản hoặc trích sai nguồn | Báo thiếu file, giữ nhãn chờ xác nhận, kiểm nguồn và fallback thủ công                 |

**Cách kiểm chứng:** So sánh quy trình hiện tại, checklist thủ công có link và Workflow đề xuất trên các bộ tài liệu tương đương về số file/độ dài/độ khó. Ghi cả mức quen thuộc để tránh đo lại cùng bài đã nhớ yêu cầu. Bấm giờ từ mở bộ tài liệu đến khi checklist được kiểm xong; reviewer đối chiếu độc lập để đếm mục thiếu/sai và nguồn không hợp lệ. Chỉ giữ phương án AI nếu có lợi so với checklist thủ công mà vẫn đạt 0 yêu cầu quan trọng bị bỏ sót; nếu chưa đạt, ghi nhận kết quả và điều chỉnh thay vì kết luận đã cải thiện.

---

## 5. Problem Statement v0 (CP5)

| Trường                                                                     | Nội dung |
| -------------------------------------------------------------------------- | -------- |
| **Actor**                                                                  | Sinh viên phụ trách một phần của bài tập có nhiều file hướng dẫn. |
| **Quy trình**                                                              | Xem danh sách tài liệu → tìm mục liên quan → đối chiếu yêu cầu giữa các file → ghi checklist để bắt đầu viết. |
| **Bottleneck**                                                             | Đối chiếu yêu cầu giữa các file, ước lượng 9/20 phút trong Problem Card; chưa bấm giờ thực tế. |
| **Impact**                                                                 | Có thể bỏ sót phần nộp cá nhân hoặc dùng sai hướng dẫn. Một người phỏng vấn kể đã phải đọc lại để phát hiện phần nộp riêng; người khác cho biết mất 20–30 phút để hiểu yêu cầu. Chưa có số liệu về tần suất trong lớp. |
| **Success Metric** (baseline → target, cách đo)                            | Baseline tạm ước lượng 20 phút/lần → mục tiêu dưới 8 phút/lần; bấm giờ từ lúc mở bộ file đến khi checklist được kiểm xong trên các bài tương đương. Điều kiện chất lượng: 0 yêu cầu quan trọng bị bỏ sót so với danh sách chuẩn do người kiểm độc lập xác nhận. Cần đo baseline thực tế trước khi đánh giá kết quả. |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | Không tự tạo yêu cầu, không coi ví dụ là quy định bắt buộc, không tự chọn nguồn ưu tiên khi tài liệu mâu thuẫn. Sinh viên mở nguồn kiểm từng mục và hỏi người phụ trách khi chưa rõ trước khi dùng checklist. |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

- Chưa ghi nhận phản biện cụ thể cho bản v0; nhóm cần bổ sung câu hỏi và cách sửa sau khi nhận phản biện.

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức                       | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
| ------------------------- | -------------------------- | ---------- | ------ | ----- |
| **No AI** (sửa quy trình) |                            |            |        |       |
| **Rule**                  |                            |            |        |       |
| **Workflow**              |                            |            |        |       |
| **Agent**                 |                            |            |        |       |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần                                                        | Nội dung |
| ----------------------------------------------------------------- | -------- |
| **Prediction** — AI dự đoán / tạo ra gì?                          |          |
| **Judgment** — con người cân nhắc, quyết định gì?                 |          |
| **Action** — hành động cuối cùng là gì, ai làm?                   |          |
| **Outcome** — đo kết quả bằng gì?                                 |          |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? |          |
| **Feedback** — lấy phản hồi ở đâu để cải thiện?                   |          |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường                                          | Nội dung                        |
| ----------------------------------------------- | ------------------------------- |
| **Actor**                                       |                                 |
| **Quy trình**                                   |                                 |
| **Bottleneck**                                  |                                 |
| **Impact**                                      |                                 |
| **Success Metric** (baseline → target, cách đo) |                                 |
| **Boundary**                                    |                                 |
| **AI intervention point**                       |                                 |
| **Mức chọn**                                    | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra**                     |                                 |

**Thay đổi so với v0 và lý do:**

| Trường | v0  | v1  | Vì sao đổi |
| ------ | --- | --- | ---------- |
|        |     |     |            |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

|   # | Tiêu chí | Đạt khi | Không đạt khi |
| --: | -------- | ------- | ------------- |
|   1 |          |         |               |
|   2 |          |         |               |
|   3 |          |         |               |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro          | Câu hỏi                                                           | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
| --------------- | ----------------------------------------------------------------- | ----------------------------------------------------- | ------------------ |
| **Value**       | Người dùng có thật sự cần và sẽ dùng không?                       | Cao | Mới có 2 phỏng vấn; baseline 20 phút chưa đo, chưa thử checklist thủ công. |
| **Usability**   | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | Trung bình | Chưa thử sinh viên kiểm yêu cầu AI trích sai hoặc bỏ sót. |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không?                     | Trung bình | Có công cụ trích dẫn nguồn, nhưng chưa thử trên bộ file thật. |
| **Viability**   | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành?     | Trung bình | Chưa xác nhận quyền đưa tài liệu học tập vào công cụ AI. |

### 8.2. Kết luận

**Quyết định:** Not Yet.

**Lý do:** Rủi ro Value còn Cao; chưa chứng minh Workflow tốt hơn checklist thủ công.

**Nếu Go — pilot nhỏ nhất:** Chưa áp dụng.

**Nếu Not Yet — cần kiểm chứng gì trước:** Bấm giờ trên 3 bộ tài liệu tương đương; thử checklist thủ công, sau đó mới so với AI. Người kiểm độc lập đếm yêu cầu quan trọng bị bỏ sót.

**Nếu No-Go — nên làm gì thay AI:** Chưa áp dụng.

**Ngưỡng dừng** (nếu sau … mà … thì quay về …): Nếu checklist thủ công đạt dưới 8 phút và không bỏ sót yêu cầu quan trọng, dừng hướng AI. Nếu AI bỏ sót 1 yêu cầu quan trọng hoặc dẫn sai nguồn, quay về checklist thủ công.

---

## 9. Hạn chế và hướng tiếp theo

- CP3 chưa có bảng pitch, chấm điểm và lý do loại các candidate khác; cần bổ sung bằng ghi chép họp nhóm thật, không suy đoán từ CP4–CP5.
- CP4 mới có 2 Interview Snapshot; snapshot thứ hai còn thiếu diễn biến cụ thể, cả hai chưa ghi ngày và cách hỏi. Cần bổ sung từ ghi chép thật và bấm giờ từng bước để kiểm baseline 20 phút, bottleneck 9 phút.
- Khảo sát 5 người về theo dõi hạn nộp là bằng chứng cho **candidate khác**, không tính là kiểm chứng trực tiếp cho problem nhiều tài liệu. [Xem bản xuất khảo sát](../assets/cp4-survey-han-nop.pdf). Trong mẫu đó, 4/5 kiểm nhóm chat cùng LMS và 4/5 ước lượng lần kiểm gần nhất mất 5–15 phút; 0/5 báo bỏ sót hẳn bài tập. Có thể nghiên cứu riêng ở vòng sau.
- Chưa có phép thử so sánh checklist thủ công với Workflow đề xuất; mục tiêu thời gian và chất lượng ở mục 4–5 vẫn là giả thuyết.

## 10. Tài liệu tham khảo

- Google Drive Help, “Search for files in Google Drive”: https://support.google.com/drive/answer/2375114?co=GENIE.Platform%3DDesktop&hl=en
- Google Docs Editors Help, “Find what's changed in a file”: https://support.google.com/docs/answer/190843
- Gemini Notebook Help, “Use chat in Gemini Notebook”: https://support.google.com/gemininotebook/answer/16179559
- Kết quả khảo sát candidate theo dõi hạn nộp: [report/assets/cp4-survey-han-nop.pdf](../assets/cp4-survey-han-nop.pdf)
