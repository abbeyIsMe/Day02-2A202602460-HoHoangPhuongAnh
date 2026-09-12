# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
|1   |    Hồ Hoàng Phương Anh         |      2A20260460       |           research                                                    |
| 2   |           |             |                                                               |
| 3   |           |             |                                                               |
| 4   |           |             |                                                               |

**Candidate problem nhóm chọn (1 câu):**
Mỗi lần đi chơi, nhóm 4–8 người mất 20–40 phút vòng "đi đâu?" trên chat; người đứng ra book phải tự đọc hết preference rồi đoán.


---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 |2 |Tìm quán ăn phù hợp tại nơi mới | Khách du lịch, người nhập cư|Không có nguồn tổng hợp gu ăn cá nhân |Actor rõ nhưng khó đo pain lặp lại thường xuyên |
| 2 | 1|Thuê nhà tại thành phố mới |Người đi làm/sinh viên xa nhà | Quá nhiều nguồn tin (web, group, môi giới) phải tự lọc| Impact lớn (1-3 tháng) nhưng workflow khó vẽ gọn 3-7 bước|
| 3 | 3| Trả lời câu hỏi khách hàng về chính sách công ty| Nhân viên CSKH| Câu hỏi lặp lại nhưng phải trả lời thủ công từng người|Actor rõ, tần suất cao (15-20 lần/ngày), dễ đo|
| 4 |2 |Soạn hồ sơ, văn bản hành chính |Chuyên viên HC/pháp chế/thư ký |Nhập tay lại 70-80% nội dung mẫu cố định |phụ thuộc domain đặc thù, nhóm ít hiểu |
| 5 |1 |Lên danh sách & chuẩn bị thức ăn |Người nấu ăn gia đình |Không có, cần soi thêm | Quá cá nhân, khó tổng quát hoá cho actor chung|
| 6 |4 |Di chuyển giữa nhà và trường | Sinh viên|Không có bottleneck 1 bước rõ (do khoảng cách vật lý) | Impact lớn (3h/ngày) nhưng AI không giải quyết được gốc rễ (khoảng cách), chỉ có thể cài agent giúp tìm hướng đi nhanh nhất |
| 7 | 3| Quên task sau Daily Meeting |Lập trình viên | Không ghi chép lại action item ngay sau meeting|Actor rõ, dễ đo (15-20'/ngày), nhưng quy mô nhỏ |
| 8 | 4| Hỏi đi hỏi lại câu hỏi cơ bản| Tech Lead/HR/Admin| Không có kênh tra cứu tự phục vụ| Actor rõ, tần suất cao (15-20 lần/ngày), dễ đo|
| 9 | 3|Bơi trong thông tin Workshop| Học viên/người tham dự| Tài liệu dài (50+ trang) không có tóm tắt| Actor rõ, dễ đo (30'/lần đọc), nhưng xảy ra không thường xuyên|
| 10 | 4| Trả lời câu hỏi nhập học cơ bản|Bộ phận tuyển sinh |Đợi phản hồi xác nhận giữa các phòng ban |Bottleneck rõ, có sẵn Problem Card chi tiết từ 1 thành viên |
| 11 |2 | Chọn địa điểm đi chơi ("đi đâu?")|Nhóm bạn 4-8 người / người đứng ra book| Đọc 30-80 tin nhắn rải rác, tự đoán preference| Actor rõ, workflow đã vẽ chi tiết, impact đo được (20-40')|
| 12 | 3|Chia bill & tổng hợp chi phí chuyến đi |Trip leader + thành viên nhóm |Đối soát 15-25 giao dịch chuyển khoản thủ công |Có số liệu khảo sát bên ngoài hỗ trợ (Experian), impact rõ (1-2h/chuyến) |

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A |#3, #8, #10 |Actor phải trả lời câu hỏi giống nhau nhiều lần cho nhiều người khác nhau |Phù hợp Rule/Workflow đơn giản (FAQ bot), nhưng domain rải rác nhiều phòng ban khác nhau|
| B | #1, #2, #5|Actor phải tự tổng hợp thông tin rải rác để ra quyết định cá nhân | Impact cao nhưng workflow khó chuẩn hoá, mỗi người 1 kiểu|
| C |#11, #12 |Người đứng ra tổ chức phải tự tổng hợp thủ công (preference hoặc giao dịch tiền) từ nhiều nguồn rải rác trong nhóm bạn | Nhóm chọn cluster này, gộp thành 1 bài "điều phối chuyến đi nhóm"|
| D (nếu có) |#6, #7, #9 | Không có bottleneck rõ 1 bước, hoặc quy mô quá nhỏ| Loại — quá rộng hoặc quá hẹp để build|

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| #10 — FAQ nhập học|Actor rõ, đã có Problem Card chi tiết, bottleneck rõ (đợi phản hồi) | access không có, nhóm khó lấy dữ liệu |
| #11+#12|Actor là chính nhóm, có sẵn số liệu bên ngoài hỗ trợ, 2 sub-problem cùng 1 actor nên gộp hợp lý | Gộp 2 bài có thể làm workflow dài hơn 7 bước, cần cắt gọn khi build|
| | | |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
|10 |4 | 4|3 |4 |3 |4 |2 | 24|
| 11,12| 5| 4| 4| 4| 4|4 |5 | 30|
| 3| 3|3 |3 |4 |3 | 4| 2| 22|

**Candidate nhóm chọn (1 bài duy nhất):**

```text
Mỗi lần đi chơi, nhóm 4–8 người mất 20–40 phút vòng "đi đâu?" trên chat; người đứng ra book phải tự đọc hết preference rồi đoán.
```

**Vì sao chọn (4-5 câu):**

```text
Actor chính là chính các thành viên trong nhóm nên data thật (chat log, giao dịch chuyển khoản thật) thay vì phải xin phép truy cập domain của công ty/tổ chức khác như candidate #10, #3. Cả 2 vấn đề (chọn địa điểm, chia bill) đều có cùng actor gốc (người đứng ra tổ chức) và cùng nguyên nhân: thông tin rải rác, phải tổng hợp thủ công -> dễ gộp 
Impact đã có số đo cụ thể (20-40'/lần chọn địa điểm, 1-2h/lần chia bill) và có thêm số liệu bên ngoài 
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
#10 (nhập học): actor thuộc về 1 tổ chức bên ngoài (trường/trung tâm), cả nhóm khó lấy dữ liệu hay hiểu sâu quy trình nội bộ.

#3 (khách hàng): phụ thuộc dữ liệu chính sách công ty mà nhóm không tiếp cận được, 
khó đo baseline thật.

Cluster D (di chuyển, quên task, chuẩn bị ăn): mỗi bài đều thiếu 1 trong các tiêu chí bắt buộc — hoặc không có bottleneck 1 bước rõ ràng (di chuyển), hoặc quy mô quá nhỏ để tách thành 1 problem statement riêng (quên task, chuẩn bị ăn).
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
Có thể tìm nguồn trên mạng/ mở survey gửi cho mọi người
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview | | | | |
| Survey / poll | | | | |
| Log / ticket / review (nếu có) | research bên ngoài| Đa số người được khảo sát từng tranh cãi tiền bạc trong chuyến đi; phần khác từng mất đoàn kết vì tiền; chỉ nhóm nhỏ có thiết lập ngân sách minh bạch từ đầu| số liệu tổng quát (Gen Z/Millennial nói chung)|Cần thêm 1 vòng hỏi nhanh nhiều người, đa dạng nhóm tuổi, để sữ liệu không bị bias |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Vấn đề không chỉ nằm ở việc "mất thời gian tính toán" mà còn ở rủi ro xã hội cao hơn — số liệu Experian cho thấy tranh cãi tiền bạc có thể ảnh hưởng tới cả tình bạn, nên phần "chia bill minh bạch, tránh nhầm lẫn" có thể còn quan trọng hơn phần "tiết kiệm thời gian"
```

Bằng chứng đính kèm (nếu có): `https://ijrpr.com/uploads/V6ISSUE10/IJRPR54314.pdf`, ``

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Wanderlog|wanderlog.com | Lên lịch trình, tối ưu tuyến đường, cộng tác nhóm, chia tiền| Trực quan, cộng tác realtime, có tính năng split cost thực tế|Ma sát khởi đầu cao — vẫn phải tự nghĩ đi đâu, nhập tay nhiều | Không nên bắt người dùng tự nhập từ đầu — nên tận dụng dữ liệu có sẵn (chat log) thay vì form nhập tay|
| TripIt (SAP)|tripit.com | Tổng hợp mã đặt chỗ, tạo timeline tự động từ email| Tự động hoá tốt (forward email → timeline), xem offline tốt|Chỉ quản lý, không gợi ý địa điểm hay chia tiền | Tự động hoá từ nguồn có sẵn (email/chat) là điểm mạnh nên học theo, nhưng nhóm cần thêm phần gợi ý + chia tiền mà TripIt không có|
| Mindtrip AI| mindtrip.ai| Gợi ý ý tưởng, tạo lịch trình nháp qua AI chat| Tốc độ nhanh (10s ra lịch trình từ 1 câu chat), giao diện hội thoại thân thiện| Rủi ro AI "ảo giác" (gợi ý sai giờ mở cửa, sai thời gian di chuyển); không quản lý booking/ngân sách chi tiết|Đúng hướng AI hypothesis của nhóm (đọc input tự nhiên → đề xuất), nhưng cần thêm bước review con người để tránh ảo giác trước khi chốt |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Chưa có tool nào giải quyết trọn vẹn cả 2 khâu "chọn địa điểm" + "chia bill" cho nhóm bạn nhỏ, không chính thức (Wanderlog/TripIt thiên về du lịch có booking thật, nặng nề; Mindtrip mạnh về gợi ý nhưng thiếu quản lý tiền). Nhóm nên build hẹp: tận dụng nguồn dữ liệu có sẵn (chat + lịch sử chuyển khoản) như TripIt làm với email, kết hợp khả năng gợi ý tự nhiên như Mindtrip, nhưng luôn có bước người review trước khi chốt để tránh rủi ro AI đề xuất sai.
```

> Lưu ý: không dùng số liệu AI đưa nếu không verify được link chính thức. Ghi rõ giả định chưa chắc.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

Dán workflow hoặc link file: `02-group-problem-statement-workflow.png/pdf/md`

```text
[1 ...: __' - ai làm] → [2 ...: __'] → [3 ...: __'] → [4 ... bottleneck: __'] → ...
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1 | Người khởi xướng | Ý định đi chơi | Tin nhắn rủ | 1' | |
| 2 | Cả nhóm | Lời rủ | 30-80 tin nhắn | 10-15' | Thông tin phân tán |
| 3 | Trip leader | Toàn bộ thread | Danh sách lọc | 15-25' | Bottleneck 1 |
| 4 | Cả nhóm | Option | Quyết định | 5-10' | |
| 5 | Trip leader | Hoá đơn/giao dịch | Danh sách chi phí thô | Rải rác | Handoff |
| 6 | Trip leader | 15-25 giao dịch | Bảng chia tiền | 60-120' | Bottleneck 2 |
| 7 | Trip leader | Bảng chia tiền | Nhắc nợ | Vài ngày | Rủi ro mâu thuẫn |

**Bottleneck chính (2-3 câu):**

```text
Có 2 bottleneck riêng biệt nhưng cùng bản chất: trip leader phải tự tổng hợp thủ công từ nguồn thông tin 
rải rác (tin nhắn ở bước 3, hoá đơn/giao dịch ở bước 6) mà không có công cụ hỗ trợ trích xuất và tính toán 
tự động. Bottleneck 2 (chia bill) rủi ro cao hơn vì sai sót ở đây trực tiếp ảnh hưởng tới mối quan hệ 
(theo số liệu Experian: 20% từng mất tình bạn vì tiền).
```

### 5.2. Future workflow bản nhóm

Phải nhìn ra 5 thứ: bước nào máy (Rule), bước nào AI, bước nào người, boundary ở đâu, fallback khi AI sai.

```text
[1 Rủ đi chơi: 1' - người] → [2 Thả ý trong thread: 10-15' - người] → [3 AI đọc thread, đề xuất 2-3 option kèm trade-off: <1' - AI] → [4 Nhóm vote/chốt: 3-5' - human boundary] → [5 Đi chơi, thành viên gửi ảnh hoá đơn/note giao dịch vào thread: rải rác - người] → [6 AI tự trích xuất số tiền, tự tính chia đầu người, sinh bảng công nợ nháp: 1-2' - AI] → [7 Trip leader review & gửi bảng chốt cho nhóm: 5' - human boundary]

Fallback: 
- Nếu AI đề xuất địa điểm dở → nhóm vote trực tiếp trên 3 lựa chọn AI đưa ra, không quay lại đọc thread thủ công
- Nếu AI tính sai số tiền/chia nhầm → trip leader luôn review bảng nháp trước khi gửi, có thể sửa tay từng dòng
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Thời gian chọn địa điểm | 20-40' | 5-8' | Bấm giờ 5 lần trước/sau |
| Thời gian chia bill | 60-120' | 10-15' | Bấm giờ đối soát tới lúc gửi bảng |
| Số bước thủ công | 6/7 | 3/7 | Đếm bước người vs AI |
| Bottleneck chính | Đọc/đối soát thủ công | AI trích xuất tự động | Đo riêng bước 3, 6 |
| Risk mới | — | AI trích xuất sai hoá đơn/chia nhầm | % lần trip leader phải sửa tay |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung | |---|---|
| **Actor** | Trip leader trong nhóm bạn 4-8 người |
| **Workflow** | Rủ đi → thả ý rải rác → trip leader tự lọc chọn địa điểm → đi chơi → thu hoá đơn rải rác → tự đối soát chia tiền → giục nợ |
| **Bottleneck** | Đọc thread thủ công (chọn địa điểm) + đối soát giao dịch thủ công (chia bill) |
| **Impact** | 20-40'/lần chọn địa điểm, 60-120'/lần chia bill; rủi ro mâu thuẫn xã hội (theo research) |
| **Success Metric** | Chọn địa điểm <10', chia bill <15', giảm số lần tranh cãi/sửa bảng |
| **Boundary** | AI đề xuất địa điểm + tính chia tiền; người chốt địa điểm và xác nhận bảng cuối |

**Câu hỏi AI phản biện v0 (nếu có):**
- Field nào mơ hồ: "Impact" phần chia bill mới chỉ dựa trên 1 case mẫu (villa Ba Vì, 10 người) — cần thêm ít nhất 1-2 case khác để chắc con số 15-25 giao dịch/60-120' là phổ biến chứ không phải ngoại lệ
- Tôi sửa gì: hỏi thêm 2-3 thành viên khác trong nhóm về chuyến đi gần nhất của họ để có thêm data point, tránh generalize từ 1 mẫu duy nhất

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [ ] Thấp (có đúng/sai rõ) / [x] Cao (nhiều cách trả lời vẫn OK) — Vì sao: "chỗ nào hợp" và "chia sao cho công bằng khi có người ăn ít/vắng mặt 1 phần" đều không có đáp án đúng/sai tuyệt đối
- Độ phức tạp: [ ] Thấp (1-2 bước) / [x] Cao (3+ bước/nguồn, phụ thuộc nhau) — Vì sao: khác nhau (đọc ngôn ngữ tự nhiên để gợi ý địa điẻm, và đọc ảnh/số liệu để tính tiền), mỗi cái cần xử lý input khác dạng

**Bài toán nhóm nằm ở ô nào:**

```text
Mơ hồ cao, Phức tạp cao
```

**Vì sao (2-3 câu):**

```text
Bài toán gộp 2 loại input khác nhau (text tự nhiên cho việc chọn địa điểm, số liệu/ảnh hoá đơn cho việc chia tiền), mỗi loại cần một dạng xử lý AI khác nhau nhưng đều theo trình tự cố định (đọc → trích xuất → tổng hợp → đề xuất), không cần AI tự ra quyết định ngoài trình tự đã định.
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?)  |
|---|---|---|---|---|
| **Rule** | Từ khoá lọc tên quán/số tiền cố định | Nhóm luôn dùng đúng 1 format | Không xử lý câu tự nhiên/ảnh hoá đơn đa dạng | Không chọn |
| **Workflow** | AI đọc thread đề xuất địa điểm; AI đọc hoá đơn tính chia tiền; người review chốt | Trình tự cố định, không cần AI tự quyết ngoài kịch bản | Preference/giao dịch mâu thuẫn cần rẽ nhánh nhẹ | Chọn |
| **Agent** | AI tự đặt chỗ, tự nhắc nợ, tự thương lượng giờ | Cần AI tự gọi nhiều tool, tự quyết hành động | AI tự nhắn nợ/đặt chỗ sai không ai duyệt | Không chọn |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. Rule có giải được 70-80% case không? → Không, input là ngôn ngữ tự nhiên và ảnh hoá đơn đa dạng.
2. Các bước có đi thẳng một đường không? → Có, cả 2 sub-flow đều theo trình tự đọc → trích xuất → tổng hợp → đề xuất → người chốt, không rẽ nhánh phức tạp.
3.Có thật sự cần Agent tự lập kế hoạch + gọi tool không? → Không, chưa cần AI tự đặt chỗ hay tự nhắn riêng từng người ở giai đoạn này.
4.Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu? → Trip leader phát hiện khi review bảng nháp/đề xuất, sửa trong 1-2 phút trước khi gửi cho nhóm.
5. Có hạ được từ Agent → Workflow → Rule không? → Hạ được xuống Workflow (đã chọn); khó hạ tiếp xuống Rule vì input không cấu trúc.

**Mức chọn:**

```text
[Rule / Workflow / Agent] Workflow
```

**Vì sao chọn (3-4 câu):**

```text
Cả 2 vấnđè đều theo trình tự cố định (đọc input → trích xuất → tổng hợp → đề xuất/tính toán → người chốt), không cần AI tự quyết định như Agent. Workflow đủ mạnh để xử lý input không cấu trúc mà Rule không làm được, đồng thời giữ human boundary rõ ở bước chốt — quan trọng vì sai chia tiền có hệ quả xã hội thật.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Rule không đủ vì cả tin nhắn chat và ảnh hoá đơn đều là dữ liệu tự do, không thể liệt kê hết bằng từ khoá 
hay pattern cố định — cần khả năng hiểu ngữ cảnh của AI/LLM.
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | Trip leader trong nhóm bạn 4-8 người |
| **Workflow** | Rủ đi → thả ý → AI đề xuất địa điểm → nhóm chốt → đi chơi → gửi hoá đơn → AI tính chia tiền → trip leader review & gửi |
| **Bottleneck** | Đọc/đối soát thủ công ở cả 2 khâu |
| **Impact** | 20-40'/chọn địa điểm + 60-120'/chia bill; rủi ro mâu thuẫn xã hội cao hơn giá trị thời gian |
| **Success Metric** | Chọn địa điểm <10', chia bill <15', giảm tranh cãi/sửa bảng |
| **Boundary** (làm/không) | Làm: đề xuất địa điểm, trích xuất & tính tiền. Không: tự đặt chỗ, tự nhắn nợ, tự chốt thay nhóm |
| **AI intervention point** | Sau "thả ý"/"gửi hoá đơn", trước "chốt"/"gửi bảng" |
| **Mức chọn**  | Workflow — trình tự cố định, không cần AI tự lập kế hoạch |
| **Rủi ro & người thật kiểm tra** | AI tính sai/chia nhầm khi có người vắng 1 phần; trip leader review trước khi gửi |

### 6.3. Final decision

| Câu hỏi | Yes/Not Yet/No | Ghi chú |
|---|---|---|
| Actor + workflow rõ chưa? | Yes | Đã vẽ 7 bước trước/sau |
| Baseline + metric đo được chưa? | Not Yet | Mới 1 case mẫu (villa Ba Vì) |
| Data/input đủ dùng chưa? | Not Yet | Cần thêm mẫu thread chat + hoá đơn thật |
| AI sai, hậu quả chấp nhận được không? | Yes | Có bước review trước khi gửi |
| Có người review/owner không? | Yes | Trip leader |
| Có cách non-AI đơn giản hơn không? | Yes | Excel/Sheet công thức, app split-bill có sẵn |

**Decision:**

```text
Not Yet
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
Actor, workflow và mức chọn (Workflow) đã rõ ràng, nhưng baseline số liệu hiện chỉ dựa trên 1 case mẫu (villa Ba Vì) và số liệu bên ngoài (Experian) chưa phải data thật của chính nhóm. Cần thêm 1 vòng thu thập data thật (thread chat mẫu + bộ hoá đơn mẫu) trước khi build pilot để tránh xây sai theo giả định.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text

```

**Nếu Not Yet — cần validate gì trước:**

```text
1. Xin 1-2 thread chat thật (đã ẩn danh) từ các lần đi chơi trước của nhóm để đếm số tin nhắn thật, không dùng con số ước lượng "30-80 tin nhắn" nữa.
2. Xin 1 bộ hoá đơn/giao dịch thật (ngoài case villa Ba Vì) từ 1-2 chuyến đi khác để xác nhận con số 15-25 giao dịch có phổ biến không.

```

**Nếu No-Go — làm gì thay AI:**

```text

```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text

```

---

### Self-check nộp phần 02 (nhóm)
- [ ] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [ ] Có validation (quote thật) + research (link kiểm được)
- [ ] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [ ] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [ ] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do
