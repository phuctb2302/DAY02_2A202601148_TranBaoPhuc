# 03 — Individual Reflection
## Học viên: Trần Bảo Phúc — 2A202601148

## Tôi đã tham gia vào phần nào?

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng |
|---|---|---|
| Scan cá nhân | Liệt kê các problem thực tế gặp phải (Báo cáo tiến độ nhóm, Tài liệu Onboarding, Bỏ sót checklist LMS) | Đóng góp idea cho nhóm |
| Pitch Problem Card | Pitch Problem "Tổng hợp báo cáo tiến độ nhóm hằng tuần" | Thuyết phục nhóm đưa vào Shortlist, tuy nhiên sau đó nhóm chọn đề tài có tính đại chúng hơn. |
| Challenge bài của bạn khác | Đặt câu hỏi phản biện cho candidate "Check thông báo công việc từ nhiều nguồn" | Giúp nhóm nhận ra scope "công việc chung chung" quá rộng, từ đó thu hẹp thành "Lọc deadline bài tập & thông báo học tập". |
| Gom trùng / cluster | Góp ý gom candidate "Checklist LMS" của mình vào chung cluster với các vấn đề về theo dõi deadline/thông báo | Giúp định hình cluster "Lọc deadline / tổng hợp thông báo học tập" - tiền đề cho bài toán nhóm chọn. |
| Chọn candidate problem | Cùng chấm điểm 7 tiêu chí và đồng ý nhường candidate của mình để vote cho "Lọc deadline" | Nhóm đạt đồng thuận nhanh chóng (35 điểm) vì problem này 100% sinh viên đều gặp. |
| Validation / research | Khảo sát mini poll với các bạn cùng lớp; research các giải pháp tích hợp Calendar (Zapier) | Xác nhận được pain point là thật (thông báo rải rác) và tìm ra pattern chuẩn (Gom input --> Lọc keyword --> Lưu Calendar). |
| Workflow nhóm | Tham gia định hình Future Workflow 5 bước | Chỉ ra rằng không nên để AI tự động lưu Calendar ngay mà phải có bước "Học viên xác nhận/sửa deadline". |
| Problem Statement | Viết và tinh chỉnh phần Metric và Boundary | Đổi metric từ "tiết kiệm thời gian chung chung" sang con số "giảm từ 30-35 phút xuống 10-12 phút". |
| Rule / Workflow / Agent | Tranh luận bảo vệ phương án Workflow thay vì Agent | Nhấn mạnh rủi ro quyền riêng tư khi để Agent tự do đọc toàn bộ Mail và Zalo cá nhân. |
| Decision | Đề xuất pilot bán thủ công (paste tay thông báo vào prompt) | Giúp nhóm chốt quyết định "Go với scope nhỏ" để test độ chính xác của AI trước. |

## Bảng dùng AI trong quá trình làm lab

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Mở rộng ý tưởng từ các khó khăn thường ngày | Đề xuất được nhiều góc nhìn như "onboarding" hay "checklist" | Đưa ra giải pháp quá vĩ mô (làm app quản lý sinh viên mới) | Tôi tự gọt giũa lại thành problem có workflow nhỏ, lặp lại. |
| Problem Card | Đổi format mô tả văn bản thành ASCII workflow | Vẽ rất nhanh, cấu trúc rõ ràng | Gộp chung bước check LMS và Zalo làm 1 | Tôi tách ra vì ngữ cảnh check 2 app này rất khác nhau, nguồn nhiễu cũng khác nhau. |
| Validation / Research | Tìm các công cụ đang có trên thị trường xử lý text/thông báo | Gợi ý Notion AI, Zapier, Slack bot | Cho rằng Slack AI có thể giải quyết được cho cả Zalo/Messenger | Nhận ra AI bot thường bị trói buộc trong nền tảng; tôi chốt lại là cần tách lớp gom data ra khỏi lớp AI. |
| Rule/Workflow/Agent | Brainstorm xem Agent có phù hợp không | Chỉ ra được những tính năng "wow" nếu làm Agent (tự nhắc, tự nộp bài) | Phớt lờ yếu tố bảo mật và khả năng API của Zalo/LMS | Bác bỏ Agent, chọn Workflow vì bài toán chỉ cần AI hỗ trợ bước "Đọc/lọc ngôn ngữ tự nhiên". |


## Reflection câu hỏi mở

**Tôi học được gì khi nghe top 3 problems của các bạn khác?**
Tôi nhận ra rằng một vấn đề dù rất gần với bản thân mình vẫn chưa chắc đã phù hợp để đưa vào nhóm nếu phạm vi ảnh hưởng của nó quá hẹp. Ví dụ như vấn đề về tổng hợp báo cáo tiến độ nhóm của tôi rất thực tế, nhưng chủ yếu ảnh hưởng đến nhóm trưởng hoặc những nhóm có workflow rõ ràng. Trong khi đó, vấn đề về lọc deadline và thông báo học tập lại có phạm vi rộng hơn, ảnh hưởng đến nhiều người hơn và dễ được cả nhóm đồng thuận hơn.

**Nhóm có lúc nào bị solution-first không?**
Có. Ở một bước trong quá trình làm việc, nhóm có xu hướng đi thẳng vào hướng xây một bot tự động đồng bộ thông báo từ Zalo vào Google Calendar. Khi đó, tôi nhận ra rằng chúng tôi đang tập trung vào giải pháp quá sớm, trước khi thật sự xác định rõ vấn đề cần giải quyết. Sau đó, nhóm đã dừng lại và quay về câu hỏi cốt lõi: đây có phải là vấn đề lọc thông tin quan trọng, hay chỉ là việc tự động hóa toàn bộ quy trình?

**Tôi có thay đổi ý kiến sau khi bị challenge không?**
Có. Ban đầu, tôi khá bảo vệ đề tài về tổng hợp báo cáo tiến độ nhóm vì đó là vấn đề mình đang gặp rất thường xuyên. Tuy nhiên, sau khi nhóm phản biện và chấm theo 7 tiêu chí, tôi nhận ra rằng đề tài đó không đủ "đại chúng" và cũng không dễ kiểm chứng bằng nhiều người như bài toán về deadline và thông báo học tập. Vì vậy, tôi đã chủ động chuyển sang ủng hộ problem chung của nhóm.

**Tôi đóng góp gì thật sự vào artifact cuối?**
Tôi góp phần giúp nhóm không bị lạc quá xa vào giải pháp phức tạp. Tôi nhấn mạnh rằng trong future workflow cần có bước người học xác nhận và chỉnh sửa deadline trước khi lưu vào Calendar hoặc checklist. Đây là điểm rất quan trọng vì thông báo trên Zalo và các kênh khác thường khá mơ hồ, nên nếu để AI tự động quyết định toàn bộ thì rất dễ sai ngày giờ và gây ra lỗi.

**Điều khó nhất khi viết Problem Statement là gì?**
Điều khó nhất là định lượng thời gian lãng phí trong current state. Với vấn đề check thông báo, mỗi lần chỉ mất vài phút, nhưng nó xảy ra nhiều lần trong ngày và thường bị phân tán. Vì vậy, rất khó để ước lượng chính xác tổng thời gian bị kéo dài nếu chỉ nhìn từng lần riêng lẻ.

**Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?**
Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở bước quick validation. Thay vì chỉ hỏi rằng “bạn có hay quên deadline không”, tôi sẽ thử lấy một đoạn thông báo thực tế từ lớp học và đưa vào ChatGPT để xem liệu AI có thật sự lọc được deadline đúng và rõ ràng hay không. Điều này sẽ giúp nhóm có căn cứ tốt hơn trước khi quyết định “go” với giải pháp.


## Tự kiểm cuối bài

- [12đ cá nhân] Cá nhân có 5+ problems và top 3 Problem Cards.
- [12đ cá nhân] Tôi đã pitch rõ và challenge nhóm đúng trọng tâm.
- Nhóm có nhật ký hội tụ từ candidates về 1 bài.
- [15đ nhóm] Nhóm có workflow trước/sau.
- [20đ nhóm] Nhóm có Problem Statement v0/v1 với metric và boundary rõ.
- [15đ nhóm] Nhóm có so sánh No AI / Rule / Workflow / Agent.
- [10đ nhóm] Nhóm có Go / Not Yet / No-Go và lý do rõ.
- [10đ cá nhân] Reflection cá nhân có nói rõ vai trò trong nhóm, cách dùng AI, điều học được và nếu làm lại sẽ đổi gì.
- [6đ cá nhân] Tôi tự giải thích được mạch problem --> workflow --> metric --> boundary --> độ phù hợp với AI.
