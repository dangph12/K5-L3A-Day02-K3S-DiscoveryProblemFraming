# Báo cáo cá nhân — 2A202603409_PhanHaiDang

## 1. Thông tin học viên

- Họ tên: Phan Hải Đăng
- MSSV: 2A202603409
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: K3S
- Link repo nhóm: https://github.com/dangph12/K5-L3A-Day02-K3S-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

|   # | Lăng kính                                        | Job Story: Khi… tôi muốn… để…                                                                                                                                                                                | Ai chịu ảnh hưởng?                                  | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng)                                                                                                                    |
| --: | ------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|   1 | Tốn thời gian                                    | Khi có đề xuất thêm tính năng trong lúc công việc cũ chưa hoàn thành, tôi muốn cùng nhóm thống nhất ưu tiên và phạm vi trong quỹ công sức còn lại, để chốt được kế hoạch khả thi cho giai đoạn cuối.         | Tôi (nhóm trưởng) và các thành viên đồ án           | Một lần nhóm dành khoảng 2 giờ sau mỗi buổi họp đưa ra tính năng mới để thảo luận.                                                                                           |
|   2 | Cần đọc, tổng hợp nhiều thông tin; Tốn thời gian | Khi muốn tổng hợp báo cáo tiến độ gửi cho mentor nhưng gặp các daily standup diễn giải chưa rõ, tôi muốn xác định chính xác thành viên đã hoàn thành những gì, để báo cáo đúng tiến độ và công việc sắp tới. | Tôi (nhóm trưởng)                                   | Gặp khó khăn trong vài lần làm báo cáo. Bình thường khoảng 30 phút/báo cáo; khi phải đọc code và hỏi lại sẽ mất khoảng 60 phút cho báo cáo, chênh lệch ước tính 30 phút/lần. |
|   3 | Lặp lại; Cần đọc, tổng hợp nhiều thông tin       | Khi code thay đổi business rule trước khi SRS được cập nhật, tôi muốn xác định đúng các quy tắc đã thay đổi để cập nhật SRS cho khớp với hành vi của sản phẩm.                                               | Tôi (nhóm trưởng, phụ trách viết SRS)               | Cập nhật business rule trung bình 3 ngày/tuần. Mỗi lần đọc code khoảng 30 phút, chưa tính thời gian sửa SRS.                                                                 |
|   4 | Pain từ người khác                               | Khi thành viên hoàn thành task nhưng chưa rõ việc tiếp theo nào cần ưu tiên trên Trello, tôi muốn giúp thành viên xác định công việc tiếp theo để họ có thể tiếp tục làm việc.                               | Thành viên vừa hoàn thành task và tôi (nhóm trưởng) | Toàn bộ hỗ trợ mất khoảng 5–10 phút/lần, xảy ra không thường xuyên, không ghi lại số liệu cụ thể.                                                                            |
|   5 |                                                  |                                                                                                                                                                                                              |                                                     |                                                                                                                                                                              |
|   6 |                                                  |                                                                                                                                                                                                              |                                                     |                                                                                                                                                                              |
|   7 |                                                  |                                                                                                                                                                                                              |                                                     |                                                                                                                                                                              |
|   8 |                                                  |                                                                                                                                                                                                              |                                                     |                                                                                                                                                                              |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- Tôi kể trải nghiệm thật và dùng AI đặt câu hỏi để làm rõ. Giữ lại các candidate đã được thống nhất.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Thứ tự tạm | Problem                                                               | Vì sao đưa vào CP2                                                             | Điều còn chưa chắc                                                                         |
| ---------: | --------------------------------------------------------------------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
|          1 | Khó thống nhất phạm vi tính năng mới khi công việc cũ chưa hoàn thành | Actor và tình huống rõ, có một lần thảo luận khoảng 2 giờ và cách nhóm đã chốt | Bao nhiêu thời gian là cần thiết; tần suất; có thể cải thiện bằng tiêu chí chung hay không |
|          2 | Mất công xác minh tiến độ khi daily standup diễn giải chưa rõ         | Có quy trình, ví dụ chunking và so sánh 30 với 60 phút/báo cáo                 | Thời gian từng bước; số lần gặp; nguồn đối chiếu không còn                                 |
|          3 | Mất công cập nhật business rule trong SRS sau thay đổi code           | Lặp lại khoảng 3 ngày/tuần, có bước đọc code khoảng 30 phút                    | Số lần/ngày; cách đo baseline; thời gian sửa SRS; nguồn đối chiếu không còn                |

### Problem Card #1 — thống nhất phạm vi tính năng sát deadline

| Trường                                    | Nội dung                                                                                                                                                                          |
| ----------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story                                 | Khi có đề xuất thêm tính năng trong lúc việc cũ chưa hoàn thành, tôi muốn cùng nhóm thống nhất ưu tiên và phạm vi trong quỹ công sức còn lại, để chốt kế hoạch khả thi.           |
| Actor                                     | Tôi (nhóm trưởng đồ án), các thành viên và mentor tham gia đề xuất/thảo luận.                                                                                                     |
| Thời điểm / bối cảnh                      | Mentor đề xuất tính năng người dùng đóng góp/gửi phản hồi về sản phẩm; cần xác nhận tên gọi thống nhất. Luồng chính chưa kiểm thử đầy đủ, tài liệu chưa hoàn thiện.               |
| Quy trình hiện tại (3–7 bước)             | Nhận đề xuất → xem việc còn lại và quỹ công sức → thảo luận giá trị, thời gian và chất lượng → thu hẹp tính năng và chốt phạm vi.                                                 |
| Bottleneck (bước nào, mất bao nhiêu phút) | Thảo luận để thống nhất có làm và làm ở mức nào. Khoảng 120 phút cho lần thảo luận đã kể.                                                                                         |
| Impact (nếu không giải thì sao)           | Đã ghi nhận công sức thảo luận; chưa ghi nhận làm lại hay chậm công việc.                                                                                                         |
| Success metric (baseline → target)        | Thời gian thảo luận một đề xuất tương tự từ khoảng 120 xuống tối đa 60 phút, vẫn chốt được phạm vi, lý do và công sức trong giới hạn. Ghi giờ bắt đầu/kết thúc các lượt trao đổi. |
| Phương án không dùng AI                   | Trước khi bàn, ghi lại giá trị mong đợi, công sức, deadline và việc phải đánh đổi để thống nhất tiêu chí.                                                                         |
| Giả thuyết về AI (nếu có)                 | Chưa xác định cần AI. Có thể thử hỗ trợ tổng hợp các lập luận nếu đã ghi lại; con người tự đánh giá và chốt.                                                                      |
| Cảm nhận nhanh                            | Chưa biết; nên thử phương án No AI trước.                                                                                                                                         |

Quy trình nháp hiện tại:

```text
[Nhận đề xuất: chưa có số phút]
→ [Xem việc còn lại và quỹ công sức: chưa có số phút]
→ [THẢO LUẬN GIÁ TRỊ VÀ PHẠM VI — BƯỚC NGHẼN: khoảng 120 phút]
→ [Thu hẹp và chốt tính năng: chưa tách được số phút, có thể nằm trong thảo luận]
```

### Problem Card #2 — xác minh tiến độ từ daily report

| Trường                                    | Nội dung                                                                                                                                                                                                                       |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Job Story                                 | Khi tổng hợp báo cáo tiến độ từ daily standup và task trên Trello diễn giải chưa rõ, tôi muốn xác định chính xác thành viên đã hoàn thành những gì, để báo cáo đúng tiến độ và việc sắp tới cho mentor.                        |
| Actor                                     | Tôi (nhóm trưởng tổng hợp báo cáo); thành viên cung cấp thông tin khi được hỏi lại.                                                                                                                                            |
| Thời điểm / bối cảnh                      | Báo cáo mentor qua Zalo hai lần/tuần: việc đã làm, khó khăn và việc sắp tới.                                                                                                                                                   |
| Quy trình hiện tại (3–7 bước)             | Đọc daily → xem task hoàn thành trên Trello → nếu chưa rõ, đọc code → hỏi lại qua Zalo → tổng hợp và gửi báo cáo.                                                                                                              |
| Bottleneck (bước nào, mất bao nhiêu phút) | Xác minh tiến độ khi daily chưa rõ, qua đọc code và hỏi lại. Chưa có thời gian riêng từng bước. Toàn bộ báo cáo khoảng 60 phút khi cần xác minh, so với 30 phút khi daily rõ ràng.                                             |
| Impact (nếu không giải thì sao)           | Chênh lệch ước tính khoảng 30 phút/báo cáo trong vài lần gặp khó khăn. Chưa ghi nhận báo sai, gửi muộn hoặc phải đổi kế hoạch.                                                                                                 |
| Success metric (baseline → target)        | Giảm tổng thời gian một báo cáo cần xác minh từ khoảng 60 xuống tối đa 30 phút; nội dung hoàn thành phải được thành viên xác nhận, không bỏ kiểm tra để đạt target. Ghi thời gian đọc, đối chiếu, hỏi và viết cho từng báo cáo |
| Phương án không dùng AI                   | Đề xuất: daily theo mẫu nêu task, phần đã xong, phần chưa xong, khó khăn và link bằng chứng; thống nhất tiêu chí hoàn thành.                                                                                                   |
| Giả thuyết về AI (nếu có)                 | Có thể hỗ trợ chỉ ra điểm diễn giải mơ hồ để hỏi lại; chưa được xem lời tóm tắt của AI là bằng chứng công việc đã hoàn thành. Chưa kiểm chứng nhu cầu và hiệu quả.                                                             |
| Cảm nhận nhanh                            | Chưa biết; thử làm rõ mẫu daily và tiêu chí hoàn thành trước.                                                                                                                                                                  |

Quy trình nháp hiện tại:

```text
[Đọc daily: chưa có số phút]
→ [Xem Trello: chưa có số phút]
→ Nếu chưa rõ:
  [Đọc code — BƯỚC NGHẼN: chưa có số phút]
  → [Hỏi qua Zalo — BƯỚC NGHẼN: chưa có số phút]
→ [Tổng hợp và gửi: chưa có số phút]

Tổng: khoảng 60 phút khi phải xác minh; khoảng 30 phút khi daily rõ.
Chênh lệch 30 phút không phải thời gian đã đo riêng của bước đọc code/hỏi lại.
```

### Problem Card #3 — cập nhật business rule trong SRS

| Trường                                    | Nội dung                                                                                                                                                                                                                    |
| ----------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story                                 | Khi code thay đổi business rule trước khi SRS được cập nhật, tôi muốn xác định đúng quy tắc đã thay đổi để cập nhật SRS khớp hành vi sản phẩm.                                                                              |
| Actor                                     | Tôi (nhóm trưởng, phụ trách SRS); thành viên thay đổi code hoặc báo thay đổi.                                                                                                                                               |
| Thời điểm / bối cảnh                      | Nhóm ưu tiên thay đổi code trước tài liệu. Cập nhật business rule là phần làm nhiều và khó nhất khi viết SRS.                                                                                                               |
| Quy trình hiện tại (3–7 bước)             | Tự phát hiện hoặc nhận thông báo thay đổi → đọc code để hiểu rule → đối chiếu SRS → cập nhật tài liệu.                                                                                                                      |
| Bottleneck (bước nào, mất bao nhiêu phút) | Đọc code để xác định business rule cần cập nhật: khoảng 30 phút/lần, chưa xác nhận cách đo.                                                                                                                                 |
| Impact (nếu không giải thì sao)           | Tốn công tái dựng rule từ code; công việc diễn ra trung bình 3 ngày/tuần, chưa biết số lần/ngày. Chưa ghi nhận hiểu sai hoặc làm lại do lệch SRS; chưa có tổng thời gian sửa tài liệu.                                      |
| Success metric (baseline → target)        | Giảm thời gian xác định rule thay đổi từ khoảng 30 xuống tối đa 15 phút/lần, vẫn ghi đúng phạm vi quyền và ngoại lệ. Đo thời gian đọc/đối chiếu riêng với thời gian sửa SRS; kiểm tra lại nội dung với người thay đổi code. |
| Phương án không dùng AI                   | Mỗi thay đổi business rule ghi mô tả trước/sau, role bị ảnh hưởng, link code và mục SRS cần sửa; thêm bước kiểm tra tài liệu trong checklist review.                                                                        |
| Giả thuyết về AI (nếu có)                 | Có thể thử dùng diff và đoạn SRS liên quan để gợi ý chỗ cần cập nhật kèm nguồn code; người phụ trách kiểm tra. Không mặc định hành vi code hiện tại là yêu cầu đúng vì code có thể có lỗi.                                  |
| Cảm nhận nhanh                            | Chưa biết; thử ghi nhận thay đổi và checklist trước khi cân nhắc AI.                                                                                                                                                        |

Quy trình nháp hiện tại:

```text
[Tự phát hiện / thành viên báo thay đổi: chưa có số phút]
→ [ĐỌC CODE ĐỂ XÁC ĐỊNH RULE — BƯỚC NGHẼN: khoảng 30 phút]
→ [Đối chiếu SRS: chưa có số phút, chưa rõ có nằm trong 30 phút không]
→ [Cập nhật SRS: chưa có số phút]

Tổng thời gian: chưa xác định. Tần suất: trung bình 3 ngày/tuần, chưa biết số lần.
```

### Card muốn pitch nhất

- **Card số:** 3 — cập nhật business rule trong SRS.
- **Vì sao:** Bước nghẽn đọc code để xác định rule rõ, công việc lặp lại và có thể so sánh phương án checklist với hỗ trợ bằng công cụ.
- **Câu hỏi phản biện đề xuất:** Nút thắt là đọc hiểu code, hay vì thay đổi rule chưa được ghi nhận ngay khi sửa? Một checklist có đủ giải quyết không?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra                                                                                                         | Đồng ý? | Đã sửa gì trong bản nháp                                                                                    |
| -------------------------------------------------------------------------------------------------------------------------- | ------- | ----------------------------------------------------------------------------------------------------------- |
| Card #1: 2 giờ thảo luận chưa chứng minh toàn bộ là thời gian lãng phí; tên tính năng trong CP1 và ghi chú chưa thống nhất | Đồng ý  | Ghi giới hạn impact và yêu cầu xác nhận tên tính năng                                                       |
| Card #2: 60 phút là toàn bộ báo cáo; dùng AI viết daily standup chưa chắc là nguyên nhân                                   | Đồng ý  | Không gán 60 phút cho bước đọc code; giữ 30 phút là chênh lệch ước tính và không kết luận nguyên nhân do AI |
| Card #3: 3 ngày/tuần không tương đương 3 lần/tuần; 30 phút chưa gồm sửa SRS                                                | Đồng ý  | Tách thời gian đọc code và sửa tài liệu; không tự nhân ra tổng giờ/tuần                                     |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động                  | Tôi đã làm gì?         | Kết quả / ảnh hưởng tới bài nhóm |
| -------------------------- | ---------------------- | -------------------------------- |
| Pitch Problem Card         |                        |                                  |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt:    |                                  |
| Nhận phản biện             | Câu hỏi tôi nhận được: | Tôi đã sửa gì:                   |
| Gom cluster / cây OST      |                        |                                  |
| Chọn candidate problem     |                        |                                  |
| Kiểm chứng / research      |                        |                                  |
| Quy trình nhóm             |                        |                                  |
| Problem Statement          |                        |                                  |
| Mức can thiệp AI           |                        |                                  |
| Quyết định                 |                        |                                  |

---

## 5. Dùng AI

| Checkpoint                     | Tôi dùng AI để làm gì?                                                                           | AI hữu ích ở đâu?                                                      | AI sai hoặc hời hợt ở đâu?                                                          | Tôi sửa gì bằng nhận định của mình?                                                                                                                                                            |
| ------------------------------ | ------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------- | ----------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CP1 Scan                       | Dùng AI hỏi lại và ghi chép trải nghiệm tôi cung cấp.                                            | Giúp phân biệt tổng hợp phản hồi, hiểu ý mentor và thống nhất ưu tiên. | Ban đầu diễn giải lệch sang khó hiểu lời mentor và gợi ý gắn tình huống với DevOps. | Tôi xác nhận đây là bất đồng về phát triển tính năng trong vai trò nhóm trưởng; làm rõ thời gian, lý do bất đồng và cách nhóm thu hẹp phạm vi.                                                 |
| CP2 Problem Card               | Nhờ AI tổng hợp ba trải nghiệm đầu CP1 thành card, quy trình nháp và phản biện giới hạn dữ liệu. | Phân biệt tổng thời gian với thời gian từng bước, số ngày với số lần.  | Thời gian từng bước còn thiếu; target và phương án vẫn là đề xuất cần tôi xác nhận. | Tôi chọn card #3 để pitch và đồng ý với các phản biện: không coi toàn bộ thảo luận là lãng phí, không gán tổng thời gian báo cáo cho bước đọc code, không suy số lần cập nhật từ số ngày/tuần. |
| CP4 Research                   |                                                                                                  |                                                                        |                                                                                     |                                                                                                                                                                                                |
| CP5 Quy trình                  |                                                                                                  |                                                                        |                                                                                     |                                                                                                                                                                                                |
| CP5–6 Problem Statement        |                                                                                                  |                                                                        |                                                                                     |                                                                                                                                                                                                |
| CP6 Mức can thiệp / quyết định |                                                                                                  |                                                                        |                                                                                     |                                                                                                                                                                                                |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi _problem → quy trình → metric → boundary → mức can thiệp AI → quyết định_ của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
