# Báo cáo nhóm — Day 02 Discovery & Problem Framing

## 1. Thông tin nhóm

- Tên nhóm: K3S
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Sinh viên khó tìm và đối chiếu đúng yêu cầu cho phần báo cáo cá nhân giữa nhiều file hướng dẫn trong lab repo.
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # / Mã | Người đưa ra   | Candidate (Job Story ngắn)                                                                                                    | Actor                                                          | Bottleneck                                                                                                                    | Câu hỏi phản biện nhận được (ai hỏi)                                     |
| ------ | -------------- | ----------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| 1      | Phan Hải Đăng  | Khi có đề xuất tính năng mới lúc việc cũ chưa xong, tôi muốn thống nhất ưu tiên và phạm vi để chốt kế hoạch khả thi.          | Nhóm trưởng đồ án, thành viên và mentor                        | Thảo luận giá trị và phạm vi: khoảng 120 phút trong lần đã kể; chưa biết bao nhiêu là thời gian có thể giảm.                  | Làm sao giảm thời gian thảo luận mà vẫn chốt được kế hoạch khả thi?      |
| 2      | Phan Hải Đăng  | Khi daily và task diễn giải chưa rõ, tôi muốn xác minh việc đã hoàn thành để báo cáo đúng tiến độ cho mentor.                 | Nhóm trưởng tổng hợp báo cáo                                   | Đọc code và hỏi lại qua Zalo; chưa tách thời gian. Tổng báo cáo khoảng 60 phút khi cần xác minh, so với 30 phút khi daily rõ. | Dùng mẫu daily rõ ràng đã đủ giải quyết vấn đề chưa?                     |
| 3      | Phan Hải Đăng  | Khi business rule trong code thay đổi trước SRS, tôi muốn xác định đúng rule đã đổi để cập nhật tài liệu khớp sản phẩm.       | Nhóm trưởng phụ trách SRS                                      | Đọc code để xác định rule: khoảng 30 phút/lần; công việc diễn ra 3 ngày/tuần, chưa biết số lần/ngày.                          | Làm thế nào để đo lường thời gian impact trước và sau khi áp dụng AI?    |
| 4      | Trần Việt Tiến | Khi chức năng báo lỗi, tôi muốn xác định nguyên nhân và cách tái hiện để sửa đúng lỗi, giảm thử sai.                          | Sinh viên/intern phát triển chức năng trong dự án đã chạy được | Nối log với code và kiểm tra giả thuyết qua nhiều vòng; chưa có số phút, bottleneck dự kiến.                                  | Bối cảnh hiện tại đang chưa rõ ràng và quá rộng, làm thế nào để thu hẹp? |
| 5      | Trần Việt Tiến | Khi chuẩn bị bàn giao chức năng, tôi muốn xác định ca bình thường, biên và đầu vào không hợp lệ để giảm lỗi bỏ sót.           | Sinh viên/intern kiểm tra chức năng mình phát triển            | Liệt kê ca và kết quả mong đợi từ yêu cầu; chưa có số phút, bottleneck dự kiến.                                               | Phạm vi actor quá rộng, làm sao để xác định được?                        |
| 6      | Trần Việt Tiến | Khi tra thư viện/API, tôi muốn tìm tài liệu đúng phiên bản và ngữ cảnh để áp dụng được vào chương trình.                      | Sinh viên/intern tích hợp thư viện/API                         | Đối chiếu phiên bản, cú pháp và điều kiện sử dụng; chưa có số phút, bottleneck dự kiến.                                       | Việc nào thể hiện success metric?                                        |
| 7      | Lý Thành Lập   | Khi bài tập được thông báo qua LMS và chat, tôi muốn biết việc sắp đến hạn để sắp xếp thời gian và không bỏ sót.              | Sinh viên theo dõi bài tập nhiều môn                           | Đọc hai nhóm chat, phân biệt thông báo với trao đổi: ước lượng 5 phút trong tổng 15 phút/lần, chưa bấm giờ.                   | Có bằng chứng nào cho thấy sinh viên đã bỏ sót hạn nộp?                  |
| 8      | Lý Thành Lập   | Khi nhận bài có nhiều file hướng dẫn, tôi muốn tìm đúng yêu cầu cho phần mình làm để bắt đầu đúng và hạn chế sửa lại.         | Sinh viên phụ trách báo cáo cá nhân trong bài tập nhóm         | Đối chiếu đề, mẫu, rubric và hướng dẫn nộp: ước lượng 9 phút trong tổng 20 phút/lần, chưa bấm giờ.                            | Làm sao xác định checklist đã đủ và đúng yêu cầu?                        |
| 9      | Lý Thành Lập   | Khi thảo luận nhóm qua nhiều tin nhắn, tôi muốn tìm quyết định cuối và người phụ trách để tiếp tục làm mà không phải hỏi lại. | Thành viên nhận việc sau thảo luận nhóm                        | Phân biệt ý kiến đang bàn với quyết định đã chốt: ước lượng 6 phút trong tổng 15 phút/lần, chưa bấm giờ.                      | Bước nghẽn là tìm lại hay chưa ghi rõ quyết định cuối?                   |

### 2.2. Cluster

| Cluster                                              | Các candidate | Pattern chung                                                                                                                                                                  |
| ---------------------------------------------------- | ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| A — Tìm và đối chiếu thông tin áp dụng cho công việc | 6, 7, 8       | Thông tin nằm ở nhiều nguồn hoặc phiên bản; người làm phải tìm, lọc và xác định phần áp dụng trước khi hành động. L2 có phạm vi hẹp là yêu cầu báo cáo cá nhân trong lab repo. |
| B — Xác minh trạng thái và thay đổi trong nhóm       | 2, 3, 9       | Tiến độ, rule hoặc quyết định chưa được ghi nhận đủ rõ; phải đọc lại nguồn và hỏi người liên quan để biết trạng thái đúng.                                                     |
| C — Xác định nguyên nhân và độ đầy đủ của kiểm tra   | 4, 5          | Phải biến log hoặc yêu cầu thành giả thuyết/ca kiểm tra cụ thể, rồi xác nhận bằng thực thi và review.                                                                          |
| D — Thống nhất phạm vi theo nguồn lực                | 1             | Cần cân đối giá trị, công sức và việc còn lại trước khi chốt phạm vi khả thi.                                                                                                  |

Các card được gom theo pattern, không gộp thành một bài toán bao trùm. Ví dụ T3 và L2 cùng cần đối chiếu tài liệu nhưng khác nguồn dữ liệu, tiêu chuẩn đúng và cách kiểm chứng.

### 2.3. Opportunity Solution Tree rút gọn

```text
OUTCOME: Giảm thời gian từ lúc gặp vướng mắc đến khi xác định được
việc cần làm đúng trong bài tập/dự án, đo bằng phút/tình huống;
đồng thời theo dõi số lần phải sửa hoặc hỏi lại do hiểu thiếu/sai.
├── Opportunity A: Khó xác định thông tin nào áp dụng giữa nhiều nguồn
│   ├── 8: Yêu cầu cho báo cáo cá nhân nằm rải rác trong nhiều file lab
│   ├── 6: Hướng dẫn thư viện/API có phiên bản và điều kiện khác nhau
│   └── 7: Đầu việc và hạn nộp nằm ở LMS và nhóm chat
├── Opportunity B: Khó biết trạng thái hoặc thay đổi cuối cùng của nhóm
│   ├── 2: Daily chưa rõ phần việc đã hoàn thành
│   ├── 3: Rule trong code thay đổi trước khi tài liệu được cập nhật
│   └── 9: Khó phân biệt ý kiến đang bàn với quyết định đã chốt
├── Opportunity C: Khó xác định nguyên nhân lỗi và ca kiểm tra cần thiết
│   ├── 4: Khó nối thông báo lỗi với nguyên nhân trong code
│   └── 5: Dễ thiếu ca biên và đầu vào không hợp lệ khi thiết kế test
└── Opportunity D: Khó thống nhất phạm vi khi việc cũ còn dang dở
    └── 1: Chưa thống nhất đánh đổi giá trị, công sức và thời hạn
```

### 2.4. Chấm điểm shortlist (1–5)

Shortlist đề xuất gồm **8**, **3**, **4**: 8 là candidate đã ghi trong `TEAM.md`; Đ3 là card Đăng muốn pitch nhất; T1 là card đang được đề xuất pitch nhất trong bài của Tiến. Cách chọn này giữ một phương án gắn với lab, một phương án tài liệu nhóm và một phương án kỹ thuật để so sánh.

**Thang điểm:** 1 = rất yếu/chưa rõ, 3 = mô tả được nhưng còn thiếu dữ liệu, 5 = rất rõ/phù hợp. Riêng “pain có bằng chứng”: tự thuật chưa có log hoặc đo trực tiếp chỉ ở mức 2–3. “Impact đo được” đánh giá khả năng thiết kế phép đo, không khẳng định đã đo impact. Điểm “so sánh 4 mức” đánh giá khả năng phân tích cả phương án đơn giản lẫn phức tạp, không yêu cầu phải chọn AI.

**Bảng điểm đề xuất từ tài liệu, chưa phải điểm nhóm đã đồng thuận:**

| Candidate                                           | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain |   Tổng |
| --------------------------------------------------- | -------: | -----------: | -----------------: | -------------: | ----------: | -------------------------------------: | ---------------: | -----: |
| 8 — Tìm đúng yêu cầu báo cáo cá nhân trong lab repo |        5 |            5 |                  2 |              4 |           5 |                                      4 |                5 | **30** |
| 3 — Xác định business rule thay đổi để cập nhật SRS |        5 |            4 |                  3 |              4 |           2 |                                      4 |                4 | **26** |
| 4 — Tìm nguyên nhân lỗi khi chạy chức năng          |        5 |            4 |                  2 |              3 |           3 |                                      4 |                4 | **25** |

**Căn cứ phân biệt điểm:**

- **8:** Actor và bốn bước công việc đã được mô tả; nguồn tài liệu lab có ngay trong repo và có thể kiểm tra checklist bằng nguồn. Điểm bằng chứng chỉ 2 vì ghi chép về xác nhận số liệu còn chưa nhất quán. Impact có thể đo bằng thời gian kèm độ đầy đủ checklist, nhưng chưa có baseline hay tần suất. So sánh các mức có thể bắt đầu từ tìm kiếm/checklist; chưa có lý do chọn Agent.
- **3:** Có tự thuật khoảng 30 phút đọc code và công việc diễn ra 3 ngày/tuần nên bằng chứng ban đầu rõ hơn L2. Tuy nhiên bài cá nhân ghi nguồn đối chiếu không còn; chưa có bộ code–SRS–thay đổi cụ thể để thử trong lab. Quy trình chưa tách rõ thời gian đọc code với đối chiếu SRS. Nhóm có trải nghiệm của Đăng, chưa xác nhận mức hiểu hệ thống của các thành viên còn lại.
- **4:** Có quy trình và cách xác nhận sửa lỗi bằng test, nhưng chưa có lỗi mẫu, log hoặc thời gian thực tế. Khó so sánh tốc độ nếu độ khó lỗi khác nhau hoặc người làm đã biết lời giải. Chỉ vừa sức lab khi thu hẹp thành một lỗi tái hiện được và có test liên quan; chưa xác nhận các điều kiện này.

**Candidate được chọn để đào sâu:** Chọn **8 — Tìm đúng yêu cầu trong nhiều file hướng dẫn của lab repo**.

**Job Story:** Khi bắt đầu phần báo cáo cá nhân trong một lab có nhiều file hướng dẫn và mẫu, sinh viên muốn xác định đúng các yêu cầu áp dụng cho mình để bắt đầu viết đúng và hạn chế bỏ sót nội dung.

**Vì sao chọn:**

- Actor, thời điểm và đầu ra công việc rõ: sinh viên vừa nhận bài, cần biết yêu cầu trước khi viết báo cáo cá nhân.
- Bước nghẽn dự kiến cụ thể là đối chiếu yêu cầu giữa các file; tài liệu nguồn có sẵn trong repo, thuận tiện cho CP4 kiểm chứng.
- Có thể đo cả thời gian tìm/đối chiếu và số yêu cầu quan trọng bị bỏ sót; tránh đánh giá bằng tốc độ đơn thuần.
- Có phương án không dùng AI rõ để đối chiếu: checklist có link nguồn và tìm kiếm trong tài liệu. Chưa chọn mức can thiệp ở CP3.
- Phạm vi hẹp hơn bài toán tìm mọi tài liệu hoặc hỗ trợ toàn bộ quá trình làm bài. Không bao gồm tự viết báo cáo, làm bài hộ hay tự chấm điểm.

**Vì sao chưa chọn các candidate còn lại:**

- **3:** Pain lặp lại và có tự thuật định lượng, nhưng thiếu nguồn code/SRS để đối chiếu; khó xác nhận rule đúng và tạo phép thử ngay trong buổi lab. Cần phân biệt nguyên nhân do đọc code khó với thiếu ghi nhận thay đổi. Đây là phương án dự phòng nếu có bộ dữ liệu phù hợp.
- **4:** Chưa có lỗi mẫu tái hiện được; kết quả phụ thuộc độ khó lỗi và kinh nghiệm người sửa. Phạm vi dễ lan sang tự sửa code trước khi chứng minh bottleneck.
- **1:** Mới có một lần thảo luận khoảng 120 phút; chưa biết phần thời gian nào là cần thiết cho quyết định và phần nào có thể giảm. Khó tổ chức một đề xuất tương đương trong lab.
- **2:** Nguồn đối chiếu cũ không còn; chưa tách thời gian đọc code/hỏi lại. Mẫu daily rõ ràng có thể giải quyết trước khi cần hỗ trợ khác.
- **5:** Cần một chức năng cụ thể và checklist ca quan trọng được người review xác nhận để đo tỷ lệ bỏ sót; hiện chưa có bộ chuẩn đó.
- **6:** Cần chốt thư viện, phiên bản và tác vụ cụ thể; L2 có nguồn tài liệu gần hơn với công việc cả nhóm đang làm trong lab.
- **7:** Chưa rõ tần suất và sự cố hạn nộp đã xảy ra; lịch chung và ghi nhận thông báo có thể đủ. Dữ liệu LMS/chat cũng chưa được tập hợp để kiểm.
- **9:** Chưa có đoạn trao đổi thật được người chốt xác nhận. Cần kiểm tra việc không ghi decision log có phải nguyên nhân chính trước khi mở rộng hỗ trợ tìm kiếm/tóm tắt.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

|   # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
| --: | -------- | -------------------------------------------------- | ---------------: | ---------------------: | ----------------- |
|   1 |          |                                                    |                  |                        |                   |
|   2 |          |                                                    |                  |                        |                   |
|   3 |          |                                                    |                  |                        |                   |
|   4 |          |                                                    |                  |                        |                   |
|   5 |          |                                                    |                  |                        |                   |
|   6 |          |                                                    |                  |                        |                   |

_Điền 4–6 giả định; xóa dòng thừa._

Giả định nhóm kiểm chứng trong buổi này:

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường                                            | Nội dung |
| ------------------------------------------------- | -------- |
| Người được hỏi (vai trò, không ghi tên thật)      |          |
| Câu nói đáng nhớ nhất (nguyên văn)                |          |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? |          |
| Hiện đang xử lý bằng cách nào (workaround)?       |          |
| Mất bao lâu, bao lần?                             |          |
| Insight / opportunity rút ra                      |          |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
| ----- | ----------------: | ----------------- | ----------------- |
|       |                   |                   |                   |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
| ------------------------ | ---- | ------------------------------ | --------- | --------------------- | ---------------- |
|                          |      |                                |           |                       |                  |
|                          |      |                                |           |                       |                  |
|                          |      |                                |           |                       |                  |

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
[1 Tải tài liệu về : 1,5'] ← CON NGƯỜI
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

**Bản mô tả v0:** Khi bắt đầu phần báo cáo cá nhân của bài tập nhóm có nhiều tài liệu hướng dẫn, sinh viên phải tìm và đối chiếu yêu cầu giữa đề bài, mẫu, rubric và hướng dẫn nộp trước khi viết. Quy trình hiện tại mất khoảng 20 phút/lần theo ước lượng trong Card #2 của Lý Thành Lập; bước đối chiếu chiếm khoảng 9 phút. Bài toán cần giải là giảm thời gian tạo checklist đúng và đủ yêu cầu áp dụng cho phần cá nhân, đồng thời giữ khả năng kiểm tra từng yêu cầu từ tài liệu gốc. Mục tiêu thử nghiệm là dưới 8 phút/lần, không bỏ sót yêu cầu quan trọng; chưa có số đo xác nhận hiệu quả hay kết luận cần dùng AI.

| Trường                                                                     | Nội dung                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| -------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Actor**                                                                  | Sinh viên phụ trách phần báo cáo cá nhân trong một bài tập nhóm, vừa nhận bộ tài liệu và chưa xác định đủ yêu cầu cho phần mình làm. Người phụ trách/reviewer hỗ trợ xác nhận yêu cầu còn mơ hồ.                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Quy trình**                                                              | Xem danh sách tài liệu (3 phút) → tìm mục liên quan (5 phút) → đối chiếu đề, mẫu, rubric và hướng dẫn nộp (9 phút) → ghi checklist trước khi viết (3 phút). Đầu ra gồm yêu cầu, đầu việc/tiêu chí hoàn thành, nguồn và trạng thái xác nhận. Các thời gian là ước lượng từ CP2, chưa bấm giờ.                                                                                                                                                                                                                                                                                                                                                      |
| **Bottleneck**                                                             | Bước 3 — đối chiếu yêu cầu nằm ở nhiều file, ước lượng 9/20 phút mỗi lần: phân biệt phần cá nhân/nhóm, yêu cầu bắt buộc/nội dung ví dụ và phát hiện điểm chưa thống nhất. Cần đo từng bước để xác nhận đây là bước nghẽn thực tế.                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **Impact**                                                                 | Tốn khoảng 20 phút chuẩn bị trước khi bắt đầu viết theo ước lượng cá nhân; có nguy cơ bỏ sót yêu cầu, hỏi lại hoặc sửa nội dung sau khi đã làm. Chưa có số lần làm lại, mức ảnh hưởng điểm hay số người gặp để suy rộng cho cả lớp.                                                                                                                                                                                                                                                                                                                                                                                                               |
| **Success Metric** (baseline → target, cách đo)                            | Tốc độ: baseline tạm thời 20 phút/lần → dưới 8 phút/lần; phương án phần 4 đặt mục tiêu 7,5 phút. Đo từ mở bộ tài liệu đến khi checklist được kiểm xong, gồm chọn file, chờ công cụ và rà soát. Chất lượng: 0 yêu cầu quan trọng bị bỏ sót, 0 yêu cầu không có căn cứ được duyệt và mọi mục đã duyệt truy lại được nguồn. Reviewer lập danh sách chuẩn từ toàn bộ tài liệu, đánh dấu yêu cầu quan trọng trước khi đánh giá; đối chiếu checklist với danh sách này. So sánh quy trình cũ, checklist thủ công có link và phương án có AI trên các bộ tài liệu tương đương; ghi số file, độ dài và mức quen thuộc. Mục tiêu chưa phải kết quả đã đạt. |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | Phạm vi là tìm yêu cầu và lập checklist, không viết hoặc nộp báo cáo thay sinh viên. Nếu thử AI, chỉ dùng tài liệu được cung cấp, không bịa quy định, không coi ví dụ là yêu cầu bắt buộc, không tự quyết nguồn ưu tiên hoặc xóa điểm mâu thuẫn. Nháp phải có đoạn/vị trí nguồn; thiếu file, thiếu nguồn hoặc yêu cầu chưa rõ phải được đánh dấu. Sinh viên mở nguồn kiểm cả tính đúng lẫn tính đầy đủ trước khi duyệt checklist; mâu thuẫn cần hỏi người phụ trách. Khi nháp sai hoặc rà soát không hiệu quả, quay về tìm kiếm và checklist thủ công.                                                                                            |

**Phản biện từ AI và cách bản nháp đã điều chỉnh:** Các góp ý dưới đây do AI đưa ra khi rà soát; chưa ghi nhận phản biện từ nhóm khác hoặc ý kiến đồng ý của nhóm. Nhóm cần tự chốt bản v0 trước khi dùng cho CP6.

| Phản biện                                                            | Điều chỉnh trong v0                                                                                              | Trạng thái ý kiến nhóm |
| -------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------- |
| Ước lượng 20 phút và bước nghẽn 9 phút chưa phải baseline đo thực tế | Giữ nhãn ước lượng, nêu cách bấm giờ và không khẳng định đã tiết kiệm thời gian                                  | Chưa ghi nhận          |
| Checklist tạo nhanh nhưng thiếu yêu cầu vẫn có thể làm bài sai       | Bổ sung 0 yêu cầu quan trọng bị bỏ sót, 0 mục vô căn cứ được duyệt và đối chiếu với danh sách chuẩn độc lập      | Chưa ghi nhận          |
| Chỉ kiểm các mục AI trích ra sẽ không tìm được những mục AI bỏ sót   | Yêu cầu người học rà soát rubric/hướng dẫn nộp độc lập; reviewer đối chiếu toàn bộ tài liệu                      | Chưa ghi nhận          |
| Có thể chỉ cần checklist có link, chưa cần AI                        | Đưa phương án thủ công vào so sánh; chưa chọn mức can thiệp AI tại v0                                            | Chưa ghi nhận          |
| Dùng lại cùng bài để thử sẽ có lợi thế do người học đã nhớ yêu cầu   | So sánh bộ tài liệu tương đương và ghi mức quen thuộc; không coi lượt làm lại bài đã biết là bằng chứng duy nhất | Chưa ghi nhận          |

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô: Độ mơ hồ cao x độ phức tạp thấp

Vì sao: Vì tuy rằng số lượng các file hướng dẫn ít nhưng các hướng dẫn được viết dưới dạng ngôn ngữ tự nhiên, dẫn đến việc khó nhớ các yêu cầu để tạo checklist.

### 6.2. So sánh 4 mức

| Mức                       | Phương án cho bài của nhóm                                                                                                                     | Đủ khi nào                                                                                                                 | Rủi ro                                                                                           | Chọn?                                                                       |
| ------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------- |
| **No AI** (sửa quy trình) | Sinh viên dùng mẫu checklist có link, tìm kiếm trong các file và đối chiếu rubric/hướng dẫn nộp trước khi viết.                                | Checklist sau kiểm tra đạt dưới 8 phút/lần, không thiếu yêu cầu quan trọng và mọi mục có nguồn đúng.                       | Đọc sót, checklist lỗi thời hoặc mất thời gian đối chiếu; cần ghi phiên bản và rà toàn bộ nguồn. | Thử trước; giữ nếu đạt mục tiêu.                                            |
| **Rule**                  | Kiểm danh sách file, tìm tiêu đề/từ khóa, kiểm trường nguồn/trạng thái và báo mục trùng; người học diễn giải nội dung.                         | Cấu trúc tài liệu ổn định, quy tắc tìm đủ các yêu cầu và tổng thời gian kể cả kiểm tay đạt mục tiêu.                       | Từ khóa bỏ sót cách diễn đạt khác; kiểm đủ trường không chứng minh đúng/đủ nội dung.             | Dùng cho thao tác cố định; chưa có bằng chứng Rule đơn lẻ đủ hoặc không đủ. |
| **Workflow**              | Các bước cố định: chọn file → Rule kiểm nguồn → AI trích nháp → sinh viên kiểm cả nguồn lẫn mục thiếu → Rule kiểm trường, sinh viên duyệt lưu. | Sau thử No AI/Rule vẫn còn nghẽn diễn giải; đầu vào đủ, nháp có nguồn và tổng thời gian kiểm/sửa có lợi hơn cách đơn giản. | AI bịa, bỏ sót, nhầm ví dụ thành quy định; thời gian kiểm có thể xóa hết lợi ích.                | Phương án có AI được đề xuất để thử, chưa chọn triển khai chính thức.       |
| **Agent**                 | AI tự chọn file/công cụ, quyết định tìm thêm và lặp đến khi tự cho rằng đủ yêu cầu.                                                            | Chỉ cân nhắc khi có tác vụ tìm kiếm thích nghi mà Workflow cố định không xử lý được, cùng giới hạn và phép đánh giá rõ.    | Đọc vượt phạm vi, tự chọn ưu tiên nguồn, khó biết đã đủ, thêm chi phí và độ trễ.                 | Không chọn: hiện chưa có nhu cầu tự quyết bước tiếp theo.                   |

**Mức chọn:** Workflow cho phép thử có AI theo mục 4.2; bước AI chỉ trích nháp yêu cầu kèm nguồn. Thứ tự kiểm chứng là No AI → Rule nếu cần → Workflow khi mức dưới chưa đủ. Chưa đủ bằng chứng chốt mức vận hành; nếu checklist thủ công đạt mục tiêu thì chọn No AI.

**Vì sao không chọn mức đơn giản hơn:** Tìm kiếm/từ khóa hỗ trợ tìm đoạn nhưng người học vẫn tốn thời gian diễn giải, gộp yêu cầu và phân biệt phạm vi giữa các file. Chỉ thử Workflow sau khi đo được hạn chế đó; nếu phần kiểm nháp AI không nhanh hơn đối chiếu thủ công ở cùng chất lượng, không nâng mức can thiệp.

### 6.3. AI Canvas rút gọn

| Thành phần                                                        | Nội dung                                                                                                                                                                                                                                                                                                  |
| ----------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Prediction** — AI dự đoán / tạo ra gì?                          | Trích nháp yêu cầu áp dụng cho báo cáo cá nhân; phân loại bắt buộc/ví dụ, cá nhân/nhóm; gợi ý gộp mục trùng và đánh dấu mơ hồ/mâu thuẫn. Mỗi mục có trích đoạn và vị trí nguồn; đây là diễn giải cần kiểm, không phải quy định mới.                                                                       |
| **Judgment** — con người cân nhắc, quyết định gì?                 | Sinh viên mở nguồn kiểm tính đúng, rà độc lập toàn bộ rubric/hướng dẫn nộp để tìm mục bị bỏ sót. Người phụ trách/giảng viên xác nhận mâu thuẫn; AI không tự chọn nguồn ưu tiên.                                                                                                                           |
| **Action** — hành động cuối cùng là gì, ai làm?                   | Sinh viên sửa, duyệt và lưu checklist rồi tự viết báo cáo; giữ riêng các mục chờ làm rõ. Rule chỉ kiểm trường bắt buộc và hỗ trợ lưu sau khi người học xác nhận.                                                                                                                                          |
| **Outcome** — đo kết quả bằng gì?                                 | Tổng phút từ mở tài liệu đến checklist kiểm xong; số yêu cầu quan trọng bị thiếu, mục sai/vô căn cứ và nguồn không hợp lệ. So sánh với No AI/Rule ở cùng tiêu chí chất lượng; chưa có kết quả đo.                                                                                                         |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | Toàn văn bộ hướng dẫn đúng phiên bản, rubric, mẫu, hướng dẫn nộp, phạm vi phần cá nhân và cấu trúc checklist ở mục 4.2; mỗi đoạn có mã file/vị trí. Repo có tài liệu để lập bộ thử, nhưng phải xác nhận đủ file và đọc được trước mỗi lượt; không dùng riêng các đoạn tìm bằng từ khóa làm toàn bộ input. |
| **Feedback** — lấy phản hồi ở đâu để cải thiện?                   | Ghi từng mục reviewer phát hiện thiếu/sai, nguồn đúng, phần người học sửa và thời gian kiểm. Dùng lỗi để sửa hướng dẫn trích/mẫu checklist rồi đánh giá trên bộ khác; không coi sửa prompt hoặc sửa nháp là đã chứng minh hiệu quả, không tự học từ dữ liệu người học.                                    |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng: Người dùng muốn được hỗ trợ vì các checklist vẫn có thể bị nhầm và không được phép làm bài hộ người dùng
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào: AI bị bỏ sót tệ hơn, thiết kế đã xử lí khi yêu cầu người học kiểm tra lại checklist với các file hướng dẫn

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường                                          | Nội dung                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| ----------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Actor**                                       | Sinh viên vừa nhận bài tập nhóm, phụ trách báo cáo cá nhân và chưa xác định đủ yêu cầu cho phần mình; người phụ trách/reviewer hỗ trợ làm rõ yêu cầu. Giữ phạm vi actor của v0, chưa suy rộng cho cả lớp.                                                                                                                                                                                                                                                                                                                                       |
| **Quy trình**                                   | Hiện tại: xem danh sách tài liệu (3 phút) → tìm mục liên quan (5 phút) → đối chiếu (9 phút) → ghi checklist (3 phút), đều là ước lượng. Thử checklist thủ công có link trước; nếu chưa đủ thì so sánh với quy trình cố định ở 4.2: chọn file → kiểm nguồn → trích nháp → người học rà/sửa → kiểm trường và duyệt lưu.                                                                                                                                                                                                                           |
| **Bottleneck**                                  | Bước đối chiếu nhiều file: phân biệt cá nhân/nhóm, bắt buộc/ví dụ và điểm chưa thống nhất, ước lượng 9/20 phút. Cần quan sát và bấm giờ từng bước; không mặc định việc nhớ hướng dẫn là nguyên nhân duy nhất.                                                                                                                                                                                                                                                                                                                                   |
| **Impact**                                      | Ước lượng 20 phút chuẩn bị/lần từ Card #2 của Lý Thành Lập; có nguy cơ hỏi lại, bỏ sót hoặc sửa bài. Chưa đo số lần làm lại, tần suất, ảnh hưởng điểm hay số người gặp; chưa quy đổi thành số giờ tiết kiệm.                                                                                                                                                                                                                                                                                                                                    |
| **Success Metric** (baseline → target, cách đo) | Baseline tạm: 20 phút/lần, đối chiếu 9 phút → mục tiêu tổng dưới 8 phút, phương án 4.2 dự kiến 7,5 phút. Bấm giờ từ mở bộ file đến checklist kiểm xong, gồm chờ công cụ và kiểm/sửa; thời gian hỏi làm rõ cũng phải ghi. Chất lượng: 0 yêu cầu quan trọng bị thiếu, 0 mục sai/vô căn cứ được duyệt, 100% mục đã duyệt có nguồn đúng. Reviewer lập danh sách chuẩn độc lập trước đánh giá; so sánh quy trình cũ, No AI và Rule/Workflow trên bộ tương đương, ghi số file, độ dài, độ khó và mức quen thuộc. Chưa có kết quả xác nhận các target. |
| **Boundary**                                    | Chỉ tìm yêu cầu/lập checklist từ bộ tài liệu được phép dùng, đúng phiên bản; không viết, chấm hay nộp bài hộ. AI không tạo quy định, biến ví dụ thành bắt buộc hoặc tự giải quyết mâu thuẫn. Thiếu nguồn/file phải báo, mục chưa rõ giữ trạng thái chờ xác nhận; không coi checklist đã sẵn sàng nếu còn yêu cầu quan trọng chưa rõ. Sinh viên kiểm trước khi dùng; lỗi hoặc không có lợi thì quay về tìm kiếm và checklist thủ công.                                                                                                           |
| **AI intervention point**                       | Nếu đủ điều kiện thử Workflow: bước 3 của 4.2, trích nháp yêu cầu và nguồn từ văn bản đã được Rule kiểm đọc được. AI không tự tìm thêm nguồn hay tự duyệt; bước 4 vẫn do sinh viên kiểm cả tính đúng và tính đầy đủ. Với phương án No AI/Rule, không có điểm can thiệp AI.                                                                                                                                                                                                                                                                      |
| **Mức chọn**                                    | Workflow là phương án thử có AI, chưa phải mức triển khai được nhóm chốt. Bắt đầu No AI; thử Rule rồi Workflow khi có bằng chứng mức dưới chưa đủ. Không chọn Agent vì luồng và phạm vi nguồn đã xác định.                                                                                                                                                                                                                                                                                                                                      |
| **Rủi ro & người kiểm tra**                     | AI bỏ sót/bịa/diễn giải sai; nguồn cũ, thiếu file hoặc link sai; kiểm nháp lâu; người học tin nháp mà không đọc nguồn. Sinh viên kiểm từng mục và quét rubric/hướng dẫn nộp độc lập; reviewer do nhóm phân công lập danh sách chuẩn, đếm lỗi và ghi thời gian; giảng viên/người phụ trách giải quyết mâu thuẫn. Vai trò reviewer chưa gán cho cá nhân cụ thể, phải phân công trước phép thử.                                                                                                                                                    |

**Thay đổi so với v0 và lý do:**

| Trường                           | v0                                                                                 | v1                                                                                      | Vì sao đổi                                                                                     |
| -------------------------------- | ---------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| Actor, Bottleneck, Impact        | Phạm vi báo cáo cá nhân; 20/9 phút là ước lượng.                                   | Giữ nguyên phạm vi và trạng thái số liệu; nhấn mạnh cần quan sát từng bước.             | CP4 chưa bổ sung bằng chứng để đổi actor, nguyên nhân hoặc impact.                             |
| Quy trình / Success Metric       | Có phương án thủ công và AI để so sánh; dưới 8 phút và chất lượng kiểm theo nguồn. | Làm rõ thứ tự thử No AI → Rule → Workflow và tính cả thời gian kiểm/sửa, chờ làm rõ.    | Tránh chọn AI trước khi biết cách đơn giản đã đủ hay chưa; tránh đo riêng thời gian sinh nháp. |
| Boundary                         | Không làm bài hộ, không bịa/giải quyết mâu thuẫn; con người duyệt.                 | Giữ nguyên, làm rõ mục quan trọng chưa xác nhận ngăn checklist được coi là sẵn sàng.    | Tránh coi đầu ra có đủ ô là đã đúng và đủ nội dung.                                            |
| AI intervention point / Mức chọn | Chưa có trường riêng, chưa chốt cần AI.                                            | Thêm điểm trích nháp ở bước 3 và Workflow thử có điều kiện; không chọn Agent.           | Xác định chính xác AI làm gì và điều kiện được phép nâng mức.                                  |
| Rủi ro & người kiểm tra          | Rủi ro nằm trong boundary và cách đo.                                              | Tách vai trò sinh viên, reviewer, người phụ trách; chưa giả định đã có người nhận việc. | Làm rõ ai phát hiện/sửa lỗi và ai giải quyết yêu cầu mâu thuẫn.                                |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

|   # | Tiêu chí                               | Đạt khi                                                                                                                                                                       | Không đạt khi                                                                                                             |
| --: | -------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
|   1 | Đủ yêu cầu quan trọng                  | Có đủ 100% yêu cầu quan trọng mà reviewer đã đánh dấu trong danh sách chuẩn từ toàn bộ nguồn trước phép thử; ghi riêng số mục ít quan trọng còn thiếu.                        | Thiếu dù 1 yêu cầu quan trọng về nội dung, tiêu chí chấm hoặc điều kiện nộp.                                              |
|   2 | Đúng nội dung và phạm vi               | Mọi mục phản ánh đúng nguồn, phân biệt cá nhân/nhóm và bắt buộc/ví dụ; không thêm quy định, deadline hoặc tiêu chí tự suy ra.                                                 | Có mục vô căn cứ, sai nghĩa, sai phạm vi hoặc coi ví dụ là yêu cầu bắt buộc.                                              |
|   3 | Truy lại nguồn đúng phiên bản          | 100% mục đã xác nhận có tên file, trang/mục và đoạn nguồn kiểm được, thuộc đúng bộ phiên bản dùng trong lượt thử.                                                             | Link/vị trí sai, không có đoạn hỗ trợ, dùng nguồn ngoài bộ hoặc nguồn cũ.                                                 |
|   4 | Hiển thị thiếu dữ liệu và điểm chưa rõ | Với bộ thử có file thiếu/lỗi hoặc yêu cầu mâu thuẫn/mơ hồ, đầu ra báo rõ, giữ các nguồn liên quan và trạng thái chờ xác nhận; không tự kết luận đã đủ.                        | Im lặng bỏ mục, báo đã xử lý đủ khi thiếu nguồn hoặc tự chọn cách hiểu mà không có xác nhận.                              |
|   5 | Kiểm được và duyệt được trước khi dùng | Checklist có đầu việc, điều kiện hoàn thành, phạm vi, nguồn và trạng thái; người học ghi nhận đã rà nguồn độc lập, mọi mục quan trọng đã được làm rõ trước khi dùng bản cuối. | Chỉ có tóm tắt chung, thiếu trường cần kiểm, chưa rà mục bị bỏ sót hoặc dùng bản cuối khi yêu cầu quan trọng vẫn chưa rõ. |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro          | Câu hỏi                                                           | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
| --------------- | ----------------------------------------------------------------- | ----------------------------------------------------- | ------------------ |
| **Value**       | Người dùng có thật sự cần và sẽ dùng không?                       |                                                       |                    |
| **Usability**   | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? |                                                       |                    |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không?                     |                                                       |                    |
| **Viability**   | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành?     |                                                       |                    |

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
