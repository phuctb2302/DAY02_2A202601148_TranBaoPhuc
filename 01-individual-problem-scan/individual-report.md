# 01 — Individual Problem Scan
## Học viên: Trần Bảo Phúc — 2A202601148

## Scan rộng — 10 Problems

Bối cảnh scan: học nhóm, làm bài tập lớn, tham gia CLB lập trình, thực hành dự án môn học.

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---|---|---|---|---|
| 1 | Lặp lại | Mỗi tuần phải tổng hợp tiến độ nhóm từ nhiều chat Zalo/Discord rồi viết báo cáo cho giảng viên | Sinh viên nhóm trưởng | Mất 45–60 phút/tuần; hay bị trễ deadline nộp báo cáo |
| 2 | Tốn thời gian | Đọc tài liệu môn học dài 50–80 trang trước kỳ thi để tóm ý chính | Toàn bộ sinh viên trong lớp | Mỗi môn tốn 2–4 giờ đọc, hay bị "đọc mà không vào" |
| 3 | Lặp lại | Mỗi lần submit bài tập lên LMS phải kiểm tra thủ công từng yêu cầu trong đề bài | Sinh viên | Hay bị quên field, thiếu file, mất điểm oan; xảy ra mỗi tuần |
| 4 | AI có thể tốt hơn | Khi debug code, phải copy-paste lỗi qua nhiều tab (Google, Stack Overflow, ChatGPT) rồi đọc thủ công | Lập trình viên sinh viên | Trung bình 15–30 phút/lỗi phức tạp; hay bị mất context |
| 5 | Pain từ người khác | Bạn mới vào nhóm dự án hay hỏi lại flow làm việc, convention code và lịch deadline vì không có tài liệu onboarding | Thành viên mới, nhóm trưởng | Nhóm trưởng trả lời cùng câu hỏi 3–4 lần/thành viên mới |
| 6 | Tốn thời gian | Tìm lại quyết định cũ (chọn framework, phân công task) trong nhóm chat Zalo vì không ai ghi note | Cả nhóm | 10–20 phút/lần tìm; hay gây hiểu nhầm và làm lại việc |
| 7 | AI có thể tốt hơn | Viết mô tả commit message, tên biến, comment code — hay viết sai quy ước hoặc quá sơ sài | Lập trình viên sinh viên | Reviewer/giảng viên phải comment yêu cầu sửa lại 2–3 lần |
| 8 | Lặp lại | Sau mỗi buổi họp nhóm không ai ghi action item, tuần sau lại họp lại để nhắc | Cả nhóm | Mỗi buổi họp mất thêm 10–15 phút đầu để nhắc lại từ buổi trước |
| 9 | Pain từ người khác | Giảng viên nhận bài nộp không đúng format (thiếu bìa, sai font, đặt tên file sai) và phải nhắn từng người sửa | Giảng viên, sinh viên | Xảy ra với 30–40% sinh viên mỗi đợt nộp bài |
| 10 | Tốn thời gian | Chuẩn bị slide thuyết trình môn học: tìm nguồn, tổng hợp nội dung, tạo layout — mỗi lần mất 3–5 tiếng | Sinh viên thuyết trình | Xảy ra 2–3 lần/học kỳ; hay phải làm đêm trước buổi báo cáo |

## Top 3 Problem Cards

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Tổng hợp tiến độ nhóm hằng tuần từ nhiều nguồn chat | Workflow lặp lại rõ, bottleneck cụ thể, có thể vẽ before/after, metric thời gian đo được | "Đủ tốt" khi nào — giảng viên có thể yêu cầu format khác nhau từng môn |
| 2 | Sinh viên mới vào nhóm dự án hỏi lại flow/quy ước nhiều lần | Pain thật từ quan sát trực tiếp, tần suất cao, có thể đo bằng số lần hỏi lại | Khó đo impact nếu nhóm nhỏ; giải pháp có thể chỉ cần doc tĩnh |
| 3 | Submit bài tập LMS hay thiếu field hoặc sai format | Tần suất cao, ảnh hưởng điểm số, nhiều người gặp | Mức độ khác nhau giữa các môn/giảng viên; giải pháp rule đơn giản có thể đủ |

## Problem Card #1 — Tổng hợp báo cáo tiến độ nhóm hằng tuần

**Problem 1 câu:**
Mỗi tuần nhóm trưởng sinh viên mất 45–60 phút đọc thủ công các chat Zalo/Discord rải rác để tổng hợp tiến độ và viết báo cáo cho giảng viên, trong đó bước gom thông tin và viết narrative là tốn nhất và hay bị trễ.

**Actor:**
Nhóm trưởng sinh viên (đại diện nhóm 4–5 người) chịu trách nhiệm nộp báo cáo tiến độ tuần cho giảng viên hướng dẫn.

**Thời điểm / bối cảnh:**
Cuối mỗi tuần (thứ Sáu hoặc Chủ Nhật), trước deadline nộp báo cáo định kỳ cho giảng viên.

**Current workflow:**
```
1. Vào từng kênh Zalo/Discord của nhóm, đọc lại toàn bộ tin nhắn trong tuần
2. Ghi chú thủ công ai làm gì, xong chưa, gặp vấn đề gì
3. Hỏi lại từng thành viên qua chat để xác nhận tiến độ
4. Tổng hợp vào Google Docs theo template
5. Viết phần tóm tắt (highlight, rủi ro, kế hoạch tuần tới)
6. Review lại và format
7. Nộp lên LMS hoặc email cho giảng viên
```

**Bottleneck:**
Bước 1–3: đọc và gom thông tin từ nhiều nguồn rời rạc mất khoảng 25–30 phút và hay bị bỏ sót thông tin quan trọng.
Bước 5: viết narrative (highlight, rủi ro, kế hoạch) mất thêm 15–20 phút và dễ bị trống ý.

**Impact:**
45–60 phút/tuần cho 1 nhóm trưởng. Lớp có ~15 nhóm, ước lượng tổng 675–900 phút/tuần đang bị mất vào việc tổng hợp thủ công. Báo cáo hay trễ hoặc thiếu thông tin --> giảng viên thiếu bối cảnh để phản hồi đúng.

**Success metric:**
Giảm thời gian tổng hợp và viết báo cáo từ 45–60 phút xuống dưới 20 phút mỗi tuần. Không tăng số lần giảng viên phải hỏi lại vì báo cáo không rõ.

**Non-AI alternative:**
Template cố định + quy ước mỗi thành viên tự cập nhật status card trước thứ Sáu. Giảm được công gom nhưng vẫn cần người tổng hợp và viết narrative.

**AI hypothesis:**
AI hỗ trợ bước đọc/gom thông tin từ chat log và draft narrative. Nhóm trưởng vẫn review và chỉnh trước khi nộp.

**Quick gut:**
Workflow

### Draft current workflow — Card #1

```
CURRENT STATE — 45–60 phút/tuần

[1. Đọc Zalo/Discord từng kênh: 20–25']    <-- bottleneck gom thông tin
--> [2. Hỏi xác nhận từng thành viên: 5–10']
--> [3. Tổng hợp vào Google Docs: 5']
--> [4. Viết narrative (highlight/rủi ro/kế hoạch): 10–15']  <-- bottleneck narrative
--> [5. Review + format: 5']
--> [6. Nộp: 2']
```

### Draft future workflow — Card #1

```
FUTURE STATE — dưới 20 phút/tuần

[1. Mỗi thành viên cập nhật status card (chuẩn hóa): 2']  <-- Rule/quy ước
--> [2. AI đọc chat log + status cards, gom thông tin có cấu trúc: 2']  <-- Workflow step
--> [3. AI draft narrative (highlight, rủi ro, kế hoạch): 1']  <-- Workflow step
--> [4. Nhóm trưởng review + edit: 12']  <-- Human boundary
--> [5. Nộp: 2']

Fallback: AI gom sai hoặc bỏ sót --> Nhóm trưởng đọc lại thủ công và sửa.
```

## Problem Card #2 — Onboarding thành viên mới vào nhóm dự án

**Problem 1 câu:**
Khi thành viên mới vào nhóm dự án, họ phải hỏi lại nhóm trưởng 3–5 lần về flow làm việc, quy ước code và lịch deadline vì không có tài liệu onboarding chuẩn, gây mất thời gian cho cả hai bên.

**Actor:**
Thành viên mới và nhóm trưởng trong nhóm dự án sinh viên (3–5 người).

**Thời điểm / bối cảnh:**
Đầu học kỳ hoặc khi có thành viên mới gia nhập nhóm (xảy ra 1–3 lần/học kỳ).

**Current workflow:**
```
1. Thành viên mới vào nhóm
2. Tự đọc chat cũ (nếu có) hoặc hỏi trực tiếp
3. Nhóm trưởng giải thích flow, quy ước, deadline
4. Thành viên mới gặp vấn đề thực tế --> hỏi tiếp
5. Lặp lại bước 3–4 nhiều lần
```

**Bottleneck:**
Không có tài liệu onboarding --> nhóm trưởng phải giải thích nhiều lần, thành viên mới mất 1–2 ngày mới hiểu đủ để làm việc.

**Impact:**
Nhóm trưởng mất 30–60 phút/thành viên mới chỉ để giải thích lặp lại. Thành viên mới mất 1–2 ngày để làm quen --> delay tiến độ nhóm.

**Success metric:**
Giảm số lần hỏi lặp lại từ 3–5 lần xuống còn 0–1 lần. Thành viên mới có thể bắt đầu làm việc trong vòng 30 phút sau khi join nhóm.

**Non-AI alternative:**
Viết wiki/README tĩnh một lần, nhóm tự cập nhật. Đủ nếu nhóm có kỷ luật cập nhật tài liệu.

**AI hypothesis:**
AI tạo và duy trì tài liệu onboarding tự động từ lịch sử quyết định của nhóm. Nhóm trưởng review trước khi chia sẻ.

**Quick gut:**
Rule — viết wiki tĩnh đủ không?
Workflow — nếu cần tự cập nhật tài liệu từ chat log

### Draft current workflow — Card #2

```
CURRENT STATE — không có tài liệu, hỏi lặp lại

[Thành viên mới join]
--> [Hỏi nhóm trưởng: flow làm việc là gì?]     <-- lần 1
--> [Hỏi: quy ước đặt tên/commit thế nào?]        <-- lần 2
--> [Hỏi: deadline tuần này là gì?]               <-- lần 3
--> [Gặp task thực tế, hỏi tiếp...]               <-- lần 4–5
```

### Draft future workflow — Card #2

```
FUTURE STATE — có tài liệu onboarding tự động

[Nhóm trưởng paste quyết định/quy ước mới vào AI: 2']  <-- Rule/Workflow
--> [AI cập nhật tài liệu onboarding: 1']
--> [Nhóm trưởng review: 5']
--> [Thành viên mới đọc tài liệu tự động: 10–15']
--> [Hỏi lại nếu còn thắc mắc: 0–1 lần]

Fallback: Tài liệu thiếu thông tin --> thành viên mới vẫn hỏi trực tiếp.
```

## Problem Card #3 — Kiểm tra checklist trước khi submit bài tập LMS

**Problem 1 câu:**
Sinh viên hay bỏ sót field bắt buộc, file đính kèm hoặc format sai khi nộp bài tập lên LMS vì phải tự đọc đề bài và kiểm tra thủ công, dẫn đến bị trừ điểm hoặc phải nộp lại.

**Actor:**
Sinh viên nộp bài tập, bài thi thực hành qua LMS (Moodle hoặc tương tự).

**Thời điểm / bối cảnh:**
Mỗi tuần khi có deadline nộp bài tập; tần suất cao — 2–4 lần/tuần trong học kỳ.

**Current workflow:**
```
1. Đọc đề bài
2. Làm bài
3. Kiểm tra thủ công: đối chiếu đề bài với những gì đã chuẩn bị
4. Nén file/đặt tên file theo yêu cầu
5. Upload lên LMS
6. Chờ giảng viên chấm --> nhận phản hồi thiếu gì
```

**Bottleneck:**
Bước 3: kiểm tra thủ công không có checklist --> hay bỏ sót, đặc biệt khi làm bài lúc căng thẳng gần deadline.

**Impact:**
~30–40% sinh viên bị nhắc bởi giảng viên vì nộp sai format/thiếu file (quan sát trong lớp). Mỗi lần sửa lại mất 10–20 phút và gây lo lắng.

**Success metric:**
Giảm tỷ lệ bị nhắc sửa từ ~35% xuống dưới 5% mỗi đợt nộp bài.

**Non-AI alternative:**
Checklist cố định theo template môn học. Rule đơn giản, có thể đủ nếu format ít thay đổi.

**AI hypothesis:**
AI đọc đề bài và tự sinh checklist cho từng bài nộp cụ thể. Sinh viên tick và confirm trước khi submit.

**Quick gut:**
Rule — checklist cố định có thể đủ cho nhiều trường hợp
Workflow — nếu yêu cầu thay đổi nhiều giữa các bài

### Draft current workflow — Card #3

```
CURRENT STATE — kiểm tra thủ công, hay bị sót

[Đọc đề bài]
--> [Làm bài]
--> [Tự đọc lại đề để kiểm tra: 10–15']    <-- dễ bỏ sót khi mệt/vội
--> [Nén file, đặt tên file]
--> [Upload LMS]
--> [Nhận phản hồi thiếu gì sau khi nộp]   <-- quá muộn
```

### Draft future workflow — Card #3

```
FUTURE STATE — checklist tự động từ đề bài

[Đọc đề bài]
--> [AI phân tích đề, sinh checklist yêu cầu: 1']  <-- Rule/Workflow
--> [Làm bài]
--> [Tick checklist trước khi nộp: 3']
--> [Upload LMS]

Fallback: Checklist AI sinh thiếu --> sinh viên tự đọc lại đề bài.
```


## Card tôi muốn pitch nhất

```
Card #1 — Tổng hợp báo cáo tiến độ nhóm hằng tuần
```

**Vì sao:**
```
- Workflow lặp lại mỗi tuần, dễ quan sát và đo được.
- Bottleneck rõ ở 2 bước: gom thông tin và viết narrative.
- Có metric thời gian cụ thể (45–60 phút --> dưới 20 phút).
- Nhiều nhóm sinh viên trong lớp đều gặp vấn đề tương tự --> scale rõ.
- Có thể vẽ before/after workflow rõ ràng.
- Non-AI alternative (template tĩnh) đã tồn tại nhưng chưa giải quyết phần narrative.
```

**Câu hỏi tôi muốn nhóm challenge:**
```
1. Template cố định + quy ước cập nhật status card có giải quyết được 80% pain không, chưa cần AI?
2. Đầu vào là chat log Zalo/Discord — làm thế nào để AI đọc được? Privacy của thành viên nhóm?
3. Metric "dưới 20 phút" có thực tế không nếu nhóm trưởng vẫn phải đọc lại để đảm bảo không bỏ sót?
```
