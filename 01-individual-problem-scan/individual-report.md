# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Nguyễn Hồng Thái
- Mã học viên: 2A202602894
- Vai trò / bối cảnh: học viên chương trình AI20K, lớp K4B (VinUni) — Batch 02
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
  - Dự buổi lecture + buổi lab, mỗi buổi nhận 1-2 repo từ giảng viên
  - Set up repo nộp bài: fork / use-template → clone → đổi tên đúng convention → mở IDE
  - Ghi note buổi học vào `Note/YYYY_MM_DD/{lec,lab}/`
  - Làm bài cá nhân + phối hợp nhóm 3-4 người cho bản nộp nhóm
  - Theo dõi thông báo, deadline, cách nộp trong Discord lớp

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Lặp lại | Set up repo nộp bài mỗi buổi: fork hoặc use-template → clone → đổi tên đúng convention `DayXX-MãHV-HọTên` → mở IDE | Mình + mọi học viên K4B, lặp lại mỗi buổi lab/lec | Ngày 12/09 mất ~15' cho 1 repo. Đã clone xong mới nhớ ra phải đổi tên theo convention → phải rename cả trên GitHub lẫn local; rename local còn fail vì VS Code đang giữ folder. 1-2 repo/buổi. ⚠️ đếm lại số buổi/tuần |
| 2 | Lặp lại + Pain từ người khác | Tìm lại thông tin đã trao đổi trong Discord lớp (deadline, cách nộp, link repo, convention đặt tên) | Học viên trong lớp, nặng nhất với người vào muộn hoặc lỡ buổi | ⚠️ cần đo: số lần/tuần phải scroll tìm lại + screenshot 2-3 câu hỏi bị hỏi lặp trong channel |
| 3 | Tốn thời gian | Điền worksheet lab dài trong timebox cứng: chuyển ý trong đầu thành đúng field của ~20 bảng markdown | Học viên trong 4 tiếng lab | Worksheet Day02 = 835 dòng, 7 phase. Phase 5 chỉ có 45' cho workflow trước/sau + Problem Statement 6 field. ⚠️ bấm giờ Phase 1-2 hôm nay để lấy số thật |
| 4 | Pain từ người khác | Bản nộp nhóm phải copy thủ công sang repo cá nhân của từng người → dễ lệch phiên bản | Cả nhóm 3-4 người | README yêu cầu rõ: "mỗi học viên copy bản cuối vào repo cá nhân của mình" — handoff thủ công 3-4 lần/bài. ⚠️ hỏi nhóm đã từng nộp nhầm bản cũ chưa |
| 5 | AI có thể tốt hơn | Ôn lại kiến thức khi note nằm rải rác nhiều định dạng: `lec_*.md`, notebook `.ipynb`, repo lab, slide, Discord | Mình + học viên ôn bài trước buổi kế tiếp | Folder `Note/` sau 2 buổi đã có 2 ngày × 3-5 nguồn khác định dạng, không có index chung. ⚠️ đo thời gian lần ôn gần nhất |
| 6 | Tốn thời gian | Không biết bài nộp đã đủ field chưa: rubric và checklist nằm rải ở README và cuối worksheet | Học viên ngay trước giờ nộp | Rubric chia 8 thành phần chấm + 3 mục bonus (README); checklist tự kiểm 9 dòng nằm cuối worksheet, file khác. ⚠️ đếm số lần phải mở lại README để đối chiếu |
| 7 | Lặp lại | Tạo folder ngày mới và phân loại note vào đúng `lec/` hay `lab/` mỗi buổi học | Mình | Cấu trúc `Note/YYYY_MM_DD/{lec,lab}` lặp y hệt mỗi buổi, làm tay 100%. ⚠️ đo thời gian mỗi lần |
| 8 | Pain từ người khác | Trong 4 tiếng lab, nhóm không nhìn được ai đang làm phase nào, ai đã push, phần nào còn trống | Nhóm 3-4 người | ⚠️ quan sát ngay trong lab hôm nay: đếm số lần có người hỏi "phần đó xong chưa" hoặc "ai đang sửa file này" |
| 9 | AI có thể tốt hơn | Đọc hiểu khái niệm kỹ thuật dài trước buổi lec để theo kịp bài giảng | Học viên chưa có nền ML | Buổi 11/09 có `lec_Self_attention_demo.ipynb` cần hiểu trước. ⚠️ đo thời gian đọc + đếm số thuật ngữ phải tra lại |
| 10 | Tốn thời gian | Chuẩn bị môi trường chạy notebook/code lab (Python, dependency, kernel) mỗi khi đổi repo hoặc đổi máy | Học viên chạy code trong lab | ⚠️ đếm số lần gặp lỗi môi trường trong 2 buổi đầu và thời gian mất mỗi lần |

> **Trạng thái các dòng trên.** Dòng 1 là quan sát trực tiếp trong ngày 12/09 (có log thao tác thật). Dòng 3, 4, 5, 6, 7, 9 dựa trên bằng chứng đọc được từ repo và cấu trúc note (số dòng worksheet, yêu cầu trong README, số nguồn trong folder `Note/`) — pain là suy ra, cần mình xác nhận là có gặp thật. Dòng 2, 8, 10 hoàn toàn là giả thuyết, chưa có bằng chứng.
>
> Mọi ô đánh dấu ⚠️ là số mình phải tự đo, không được điền ước lượng. Rubric chấm `Dấu hiệu thật` bằng số + bằng chứng kiểm được, nên một con số bịa sẽ hỏng luôn phần metric ở Phase 5.

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: nhờ AI (Claude) đọc README + worksheet của lab, rồi liệt kê các problem ứng viên theo 4 lăng kính dựa trên bối cảnh học viên AI20K và những gì quan sát được từ folder `Note/` cùng thao tác set up repo trong ngày.
- Ý dùng được: ⚠️ điền sau khi tự rà — dòng nào mình thật sự có gặp.
- Ý bỏ vì không phải pain thật: ⚠️ điền sau khi tự rà — dòng nào nghe hợp lý nhưng mình không thật sự gặp.

> Ghi chú trung thực về thứ tự làm: worksheet yêu cầu tự scan trước rồi mới hỏi AI (nguyên tắc 6, dòng 12). Lần này mình lấy danh sách ứng viên từ AI trước. Vì vậy bước bắt buộc kế tiếp là tự rà từng dòng, xoá dòng không phải trải nghiệm thật, bổ sung dòng của riêng mình, và tự đo các số ⚠️ trước khi dùng bảng này cho Phase 2.

**Self-check Phase 1:**
- [ ] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [ ] Dùng ít nhất 3/4 lăng kính
- [ ] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — [Tên problem]

```text
Problem 1 câu:

Actor:

Thời điểm / bối cảnh:

Current workflow 3-7 bước:
1.
2.
3.
4.
5.

Bottleneck:

Impact:

Success metric:

Non-AI alternative:

AI hypothesis:

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — ___ phút

[1 ...: __'] → [2 ...: __'] → [3 ...: __'] → [4 ...: __']  <-- bottleneck

FUTURE STATE — ___ phút

[1 ...: __'] → [2 ...: __'] → [3 ... review: __']  <-- human boundary

Fallback: nếu AI sai thì ...
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — [Tên problem]

```text
Problem 1 câu:

Actor:

Thời điểm / bối cảnh:

Current workflow 3-7 bước:
1.
2.
3.
4.
5.

Bottleneck:

Impact:

Success metric:

Non-AI alternative:

AI hypothesis:

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — ___ phút

[1 ...] → [2 ...] → [3 ...]  <-- bottleneck

FUTURE STATE — ___ phút

[1 ...] → [2 ...] → [3 ... review]  <-- human boundary

Fallback: ...
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — [Tên problem]

```text
Problem 1 câu:

Actor:

Thời điểm / bối cảnh:

Current workflow 3-7 bước:
1.
2.
3.
4.
5.

Bottleneck:

Impact:

Success metric:

Non-AI alternative:

AI hypothesis:

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — ___ phút

[1 ...] → [2 ...] → [3 ...]  <-- bottleneck

FUTURE STATE — ___ phút

[1 ...] → [2 ...] → [3 ... review]  <-- human boundary

Fallback: ...
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text

```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text

```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text

```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra:
- Tôi sửa gì:

### Self-check nộp phần 01
- [ ] Có 5+ problems + top 3 Cards đủ field
- [ ] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [ ] Đã chọn 1 card pitch + câu hỏi challenge
