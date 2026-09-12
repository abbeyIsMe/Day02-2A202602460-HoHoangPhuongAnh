# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Hồ Hoàng Phương Anh
- Mã học viên: 2A202602460
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): sv
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem): tổng hợp lại kiến thức đã học, hiểu theo ý mình, luyện tập, ôn lại phần chưa hiểu, test cả bài

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Lặp lại & Tốn thời gian | Di chuyển giữa nhà và trường | Bản thân| Mất 3 tiếng cả đi cả về
| 2 | Tốn thời gian | Tài xế đã di chuyển đến nơi nhưng bị huỷ chuyến | Tài xế| Mất 10' để di chuyển đến nơi |
| 3 | AI có thể tốt hơn | Trả lời câu hỏi nhập học cơ bản của học sinh | Bộ phận tuyển sinh | 5-10' mỗi người |
| 4 | AI có thể tốt hơn | Gửi work statement cho nhân viên mỗi kỳ lương, kiểm tra lương match với số giờ làm | Bộ phận tài chính, kế toán |  10-15' mỗi nhân viên|
| 5 | Pain từ mọi người| Quyết định xem hôm nay ăn gì | Đa số | min 15'|
| 6 | AI có thể tốt hơn| Research trường để nhập học | SInh viên| 30-45'|
| 7 | AI có thể tốt hơn| Support phải phân loại ticket thủ công theo sản phẩm, mức độ và nguyên nhân |Team tech support |300 ticket/tuần × 45 giây = 3,75 giờ/tuần|
| 8 | | | | |
| 9 | | | | |
| 10 | | | | |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: Đưa danh sách đời thường về những công viêc lặp lại/ tốn thời gian, và đưa ra thời gian/ số liệu tiêu tốn vào việc đó
- Ý dùng được: Support phải phân loại ticket thủ công theo sản phẩm, mức độ và nguyên nhân 
- Ý bỏ vì không phải pain thật:

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 |Trả lời các câu hỏi nhập học cơ bản của học sinh | Bộ phận tuyển sinh phải kiểm tra email sinh viên gửi, trả lời lặp lại những câu hỏi về quy trình nhập học, tiền học,... | Kiểm tra thời gian cho mỗi email, đếm số câu hoỏi lặp lại
| 2 | Gửi work statement cho từng nhân viên mỗi kỳ lương và kiểm tra lương có khớp số giờ làm|Bộ phận Kế toán kiểm tra số tiền lương được duyệt có khớp với giờ làm và trừ đi các thanh khoản khác |Kiểm tra timesheet, pay check, email của 1-2 kỳ lương |
| 3 | Support phải phân loại ticket thủ công theo sản phẩm, mức độ và nguyên nhân| Đọc email, lọc email theo các mức độ như emergency hay có thời gian trả lời được | Kiểm tra ticket log, đo thời gian và tỷ lệ phân loại sai |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — [Tên problem]

```text
Problem 1 câu: Trả lời các câu hỏi nhập học cơ bản của học sinh

Actor: Bộ phận tuyển sinh

Thời điểm / bối cảnh: Khá rush và vất vả trước mùa tuyển sinh

Current workflow 3-7 bước:
1. Kiểm tra và phân loại, email nào cần thiết phải tra lời ngay
2. Check xem câu hỏi có liên quan tới các phòng/ban khác không (VD: tiền học đã đóng nhưng nhận email xác nhận -> liên lạc phòng kế toán)
3. Đợi phản hồi/xác nhận
4. Lấy thông tin chuẩn xác và gửi cho học sinh
5. Đợi phản hồi

Bottleneck: Thời gian đợi phản hồi 

Impact: 5-10' mỗi email, mùa rush tuyển sinh dồn nhiều email cùng lúc → tốn vài giờ/ngày của nhân viên tuyển sinh

Success metric: Thời gian phản hồi trung bình giảm từ ~20-30' xuống dưới 10'; % câu hỏi AI trả lời đúng ngay không cần sửa

Non-AI alternative: Làm FAQ/email template có sẵn cho các câu hỏi lặp lại nhiều nhất

AI hypothesis: AI đọc email, tự trả lời câu hỏi thường gặp, chỉ escalate cho người khi liên quan phòng ban khác hoặc case đặc biệt

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 15-30 phút

[Phân loại email: 5'] → [Check liên quan phòng ban: 5'] → [Đợi phản hồi: 20']  <-- bottleneck → [Gửi thông tin: 5']  <-- bottleneck

FUTURE STATE — 8 phút

[AI phân loại & trả lời câu hỏi thường gặp: <1'] → [AI escalate câu phức tạp đúng phòng ban: 1'] → [Phòng ban review & gửi: 5']  <-- human boundary

Fallback: nếu AI không chắc câu trả lời thì báo cho người, không tự gửi, hoặc chủ động cho human-in-the-loop, nhân viên phòng ban ở cuối quy trình, kiểm tra lại toàn bộ, tránh sai sót

---

#### Problem Card #2 — [Tên problem]

```text
Problem 1 câu: Gửi work statement cho từng nhân viên mỗi kỳ lương và kiểm tra lương có khớp giờ làm

Actor: Bộ phận kế toán/tài chính

Thời điểm / bối cảnh: Mỗi kỳ trả lương (2 tuần/laafn hoặc mỗi tháng), việc dồn lại cùng lúc cho tất cả nhân viên

Current workflow 3-7 bước:
1. Tổng hợp giờ làm của nhân viên
2. Đối chiếu số giờ làm thực tế với hợp đồng/rate lương
3. Tính lương và các khoản trừ bao gồm (thuế, bảo hiểm, ứng lương...)
4. Tạo work statement cho mỗi người
5. Gửi email work statement và xử lý thắc mắc nếu có sai lệch

Bottleneck: Đối chiếu thủ công timesheet với bảng lương

Impact: 10-15' mỗi nhân viên, mỗi kỳ lương có thể tốn hàng giờ hoặc ngày nếu nhân viên nhiều, nhân viên phògn ban ít

Success metric: Giảm thời gian xử lý, giảm số ca sai lệch lương phải sửa lại sau khi gửi

Non-AI alternative: Dùng Excel/Google Sheet có công thức tự đối chiếu timesheet vơid lương

AI hypothesis: AI tự động đối chiếu timesheet với bảng lương, tự phát hiện điểm bất thường và soạn bản nháp work statement, nhân viên phòng kế toán tài chính chỉ cần duyệt

Quick gut:
[ ] No AI / process fix
[x] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 15 phút

[Tổng hợp timesheet: 5'] → [Đối chiếu giờ với lương: 5'] → [Tạo & gửi work statement: 5']  <-- bottleneck ở giai đoạn 2và 3


FUTURE STATE — 5 phút

[AI lấy dữ liệu chấm công, tổng hợp time sheet: 2'] → [AI tự đối chiếu & bắt điểm bất thường: 1'] → [AI soạn nháp work statement: 1'] → [Kế toán xem lại & gửi: 2']  <-- human boundary

Fallback: nếu số liệu lệch quá ngưỡng thì AI không tự tạp bản nháp, chuyển cho người kiểm tra thủ công

---

#### Problem Card #3 — [Tên problem]

```text
Problem 1 câu: Support phải phân loại ticket thủ công theo sản phẩm, mức độ và nguyên nhân

Actor: Team tech support

Thời điểm / bối cảnh: Diễn ra liên tục, ticket đổ về theo thời gian thực suốt ngày

Current workflow 3-7 bước:
1. Nhận ticket từ khách hàng
2. Đọc nội dung để xác định sản phẩm liên quan
3. Xác định mức độ ưu tiên (khẩn cấp/bình thường/thấp)
4. Xác định nguyên nhân (bug, lỗi người dùng, feature request...)
5. Gắn tag và route ticket tới đúng người/team xử lý

Bottleneck: Đọc hiểu + phân loại thủ công (bước 2-4)

Impact: nhièue thời gian để xác định mức độ khẩn cấp của email, thêm thời gian nếu bug phải chuyển qua team kỹ thuật level 1, 2 và những level cao hơn mà vấn đề vẫn chưa được giải quyết

Success metric: Giảm thời gian phân loại trung bình/ticket; giảm % ticket bị route sai phải chuyển lại

Non-AI alternative: Bộ rule lọc theo từ khóa (keyword-based filter) cho các case đơn giản, rõ ràng

AI hypothesis: Dùng AI/LLM đọc nội dung ticket, tự động gắn tag sản phẩm + mức độ + nguyên nhân, chỉ đẩy case mơ hồ/độ tin cậy thấp cho người review

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[x] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 1'/ticket

[Nhận ticket: 5s] → [Đọc & xác định sản phẩm: 20s] → [Xác định mức độ và nguyên nhân: 25s] → [4 Gắn tag & route: 15s]   <-- bottleneck ở 2 và 3

FUTURE STATE — ~30 giây/ticket

[AI đọc & tự gắn tag sản phẩm/mức độ/nguyên nhân: 5s] → [AI phân loại tự động: 5s] → [Người review case những trường hợp khó: 15-20s]  <-- human boundary

Fallback: nếu AI confidence <ngưỡng đặt trước → giữ nguyên workflow thủ công cho ticket đó
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Phân loại ticket support thủ công

```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Đây là workflow có số liệu rõ và đo được trong 3 trường hợp 45s/ticket,tầm 6h môi  tuần bị mất vào việc phân loại thủ công. Đây cũng là task rất phù hợp với AI vì nó lặp đi lặp lại, phân loại cũng dễ, dựa trên đọc hiểu ngôn ngữ tự nhiên, không đòi hỏi phán đoán phức tạp như 2 trường hợp trc

Impact: nếu AI làm được 80% ticket rõ ràng, team support tiết kiệm hàng giờ mỗi tuần để tập trung xử lý ticket khó
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

- Ngưỡng để AI tự tin là gì thì nên để tự chuyển hướng thay vì đẩy cho người review?
- Nếu AI định hướng ticket sai, hệ quả và chi phí sửa sai đó có lớn hơn thời gian tiết kiệm được không?

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: chưa có baseline % ticket hiện tại bị phân loại sai bởi con người, nên khó chứng minh AI "tốt hơn" nếu không so sánh
- Tôi sửa gì: nên đề ra bảng, hoặc tiêu chí để cho AI dựa theo để đánh giá, điều hướng ticket đó

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
