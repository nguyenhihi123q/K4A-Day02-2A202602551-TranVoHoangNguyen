# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Trần Võ Hoàng Nguyên
- Mã học viên: 2A202602551
- Nhóm: Nhóm K4A — Day 02 (Minh, Đức Anh, Tùng, Nguyên)
- Candidate problem nhóm chọn: Dựng lại UA report định kỳ từ nhiều nguồn (User Acquisition / Business Development reporting)

---

## 1. Em đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Em đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Quét đủ 10 bài toán thực tế qua 4 lăng kính từ 5 công việc hằng tuần (nghiên cứu AI, đi dạy, học VB2 tiếng Anh, quản trị web Viện CĐS, học AI thực chiến). | Đưa vào kho ý tưởng chung của nhóm các góc nhìn về hỗ trợ giảng dạy và xử lý tài liệu học thuật; đạt tiêu chí bonus cá nhân. |
| Pitch Problem Card | Trình bày Problem Card #1: Hỗ trợ giải đáp lỗi dùng AI cho học viên (45 phút/ngày); phân tích quy trình 5 bước và điểm nghẽn ở khâu soạn câu trả lời lặp lại. | Nhóm thảo luận sôi nổi về ranh giới sư phạm giữa việc giải đáp kỹ thuật nhanh bằng AI và việc học viên bị hổng tư duy căn bản. |
| Challenge bài của bạn khác | Đặt 2 câu hỏi phản biện trực diện cho bài UA report của bạn Minh: (1) Nguy cơ lộ dữ liệu tài chính/ad spend nhạy cảm khi đưa vào LLM; (2) AI thiếu bối cảnh kinh doanh bên ngoài sẽ viết insight sáo rỗng. | Nhóm nhận ra điểm yếu về bảo mật và sự phụ thuộc context, từ đó bổ sung quy định che số (masking data) và giới hạn AI chỉ làm bản nháp. |
| Gom trùng / cluster | Cùng nhóm phân loại 12 candidate problems thành 4 cụm (A: Reporting, B: Research, C: Phối hợp nhóm, D: Vận hành). | Nhận diện cụm Reporting có workflow ổn định nhất, phân định rõ ràng giữa bước kéo số (deterministic) và bước viết nhận định. |
| Chọn candidate problem | Đồng thuận chọn UA report định kỳ của Minh vì có artifact thực tế (4 tab input → 9 phần output); đồng thời chỉ ra vấn đề bài toán mới chỉ có evidence từ 1 người. | Giúp nhóm chốt được bài toán có tính khả thi kỹ thuật cao nhất trong lab, nhưng không chủ quan về mức độ sẵn sàng triển khai. |
| Validation / research | Đảm nhận vai trò Research & Reviewer; rà soát năng lực của Google Ads API, Google Ads Scripts và Looker Studio; xây dựng kế hoạch validation. | Xác định rõ không tự xây lại hệ thống kéo dữ liệu/dashboard; đề xuất kế hoạch phỏng vấn 2–3 người ngoài nhóm để kiểm chứng độ rộng. |
| Workflow nhóm | Góp ý phân tách ranh giới trong Future Workflow: khâu ghép số dùng Rule/Script, AI chỉ sinh draft biến động có trích dẫn nguồn, và đặt chốt chặn Human Boundary. | Workflow nhóm mạch lạc, thấy rõ vai trò của từng công nghệ, tránh việc để AI can thiệp vào các bước tính toán số học thuần túy. |
| Problem Statement | Rà soát các trường trong bản v0; kiên quyết yêu cầu ghi nhận baseline thời gian dưới dạng T0 đo thực nghiệm 3 kỳ thay vì dùng số giả định. | Problem Statement v1 chặt chẽ, trung thực về mặt khoa học dữ liệu, không bị giám khảo bắt bẻ về số liệu ảo. |
| Rule / Workflow / Agent | Phản biện xu hướng muốn chọn Agent tự hành toàn phần; phân tích 5 câu hỏi chốt để chứng minh bài toán này mức **Workflow (Human-in-the-loop)** là tối ưu nhất. | Nhóm thống nhất chọn Workflow, tránh rủi ro hệ thống tự động phát hành báo cáo sai số liệu tài chính cho cấp lãnh đạo. |
| Decision | Đề xuất nhóm chọn quyết định **Not Yet** thay vì vội vàng chọn Go; lập danh mục các điều kiện cần kiểm chứng trước khi chuyển sang Go. | Nhóm có một quyết định chín chắn, thể hiện tư duy kỹ thuật thực tế: biết dừng lại để kiểm chứng thay vì cố ép làm AI cho bằng được. |

**Dấu tay rõ nhất của em trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của em là giữ vững tính kỷ luật dữ liệu cho nhóm: kiên quyết yêu cầu nhóm chọn quyết định "Not Yet" (vì chưa có baseline thời gian thật và thiếu interview người ngoài), đồng thời xác lập ranh giới Human Boundary bắt buộc UA owner phải đối chiếu số liệu nguồn trước khi gửi báo cáo, hỗ trợ cho người thuyết trình bằng cách soạn ra các phản biện để tập trước.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Em dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Em sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý mở rộng các góc nhìn từ 4 lăng kính dựa trên 5 đầu việc hằng tuần em cung cấp. | Giúp liên kết việc đi dạy và học VB2 tiếng Anh thành các pain point cụ thể (hỏi lỗi lặp lại, tra collocation). | Đưa ra các gợi ý quá vĩ mô và viển vông như "tự động hóa viết toàn bộ bài báo khoa học", "chatbot thay thế hoàn toàn giáo viên". | Gạt bỏ toàn bộ ý tưởng viển vông; tự đưa các con số đo lường thực tế (45 phút/ngày, 5–7 tin/ngày) từ nhật ký làm việc của bản thân. |
| Problem Card | Phản biện cấu trúc 3 Problem Cards cá nhân và hỗ trợ định dạng sơ đồ ASCII Before/After. | Giúp hình dung nhanh quy trình tuyến tính và ước lượng thời gian rút gọn ở từng bước. | Ban đầu AI đề xuất mô hình Agent tự động trả lời 100% tin nhắn của sinh viên trên nhóm lớp. | Em hạ xuống mức Workflow có Human Boundary: AI chỉ chuẩn bị bản nháp, giáo viên phải duyệt trước khi gửi để đảm bảo tính chuẩn xác và sư phạm. |
| Workflow | Rà soát các điểm chuyển giao (handoff) giữa các công cụ trong quy trình báo cáo UA. | Giúp nhìn ra điểm nghẽn nối tiếp giữa bước kiểm tra tính toàn vẹn số liệu và bước viết câu chữ nhận định. | AI gộp chung bước tính toán số liệu và bước viết insight thành một khối duy nhất do AI đảm nhận. | Tách đôi quy trình: phần tính toán/ghép tab bắt buộc dùng Rule/Script để đảm bảo chính xác 100%, AI chỉ can thiệp ở khâu sinh câu chữ giải thích biến động. |
| Research | Tìm kiếm tài liệu kỹ thuật và API chính thức của Google Ads Reporting, Scripts và Looker Studio. | Cung cấp nhanh chóng các liên kết tài liệu chính thức của Google, tiết kiệm thời gian tra cứu. | AI đưa ra các tuyên bố tiếp thị không có căn cứ kiểu "công cụ này giúp tiết kiệm 70% thời gian làm việc". | Xóa bỏ toàn bộ các con số quảng cáo không kiểm chứng được; chỉ giữ lại các đặc tả kỹ thuật và tài liệu lập trình chính thức. |
| Problem Statement | Thử thách (stress-test) độ chặt chẽ của các trường thông tin trong bản thảo v0. | Chỉ ra điểm yếu chí mạng của bài toán nhóm: chưa có dữ liệu bấm giờ baseline cụ thể qua các kỳ. | AI gợi ý "bịa" ra một con số ước lượng (ví dụ ghi đại 120 phút) để điền cho đủ form nộp bài. | Kiên quyết từ chối số liệu ảo; đề xuất nhóm sử dụng ký hiệu T0 và quy định rõ phải bấm giờ đo lường thực tế trên 3 kỳ liên tiếp. |
| Rule / Workflow / Agent | Đóng vai người phản biện (devil's advocate) để tìm kẽ hở nếu nhóm lựa chọn giải pháp Agent. | Liệt kê sắc bén các rủi ro: quyền truy cập API bị lạm dụng, nguy cơ rò rỉ dữ liệu chi tiêu quảng cáo và ảo giác số liệu. | Vẫn cố gắng thuyết phục rằng xây dựng multi-agent tự hành sẽ thể hiện trình độ kỹ thuật cao hơn và "ngầu" hơn. | Thuyết phục nhóm kiên định với mức Workflow; chứng minh rằng giải pháp đơn giản nhất giải quyết đúng bài toán với rủi ro thấp nhất mới là giải pháp tốt nhất. |
| Decision | Đối chiếu các tiêu chí kiểm tra giữa hai lựa chọn "Go có điều kiện" và "Not Yet". | Cung cấp khung danh mục các rào cản kỹ thuật và bảo mật cần hoàn thành trước khi triển khai pilot. | Khuyên nhóm nên chọn "Go" luôn để bài nộp trông tích cực và hoàn thiện hơn. | Giữ vững quan điểm chọn "Not Yet"; lập luận rằng dũng cảm chọn Not Yet khi thiếu bằng chứng chính là biểu hiện cao nhất của sự trung thực học thuật. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Em học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Em có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Em đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của em?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, em sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Khi nghe phần pitch của các thành viên trong nhóm, em nhận ra bài toán hỗ trợ giải đáp lỗi AI của bản thân em tuy thiết thực nhưng phạm vi còn mang tính cá nhân. Ngược lại, bài toán báo cáo UA của bạn Minh có cấu trúc nghiệp vụ rất rõ nét và có sẵn dữ liệu mẫu (4 tab input chuyển thành 9 phần output) để cả nhóm cùng đào sâu phân tích. Quá trình thảo luận nhóm có thời điểm bị cuốn vào tâm lý "solution-first". Một số thành viên ban đầu muốn thiết kế ngay một Agent tự hành toàn phần kết nối trực tiếp API để xuất bản báo cáo cho "ngầu" và nhiều tính năng. Với vai trò Reviewer, em đã phản biện quyết liệt vì dữ liệu chi phí quảng cáo và doanh thu game là bí mật kinh doanh nhạy cảm, không thể tùy tiện đưa lên mô hình AI công cộng nếu chưa có cơ chế che số (masking data). Hơn nữa, nếu AI gặp ảo giác và suy diễn sai lệch thì rủi ro tài chính cho công ty là rất lớn. Đóng góp rõ nét nhất của em trong bản nộp cuối là giữ vững lập trường kéo giải pháp từ Agent hạ về mức Workflow có con người kiểm duyệt (Human-in-the-loop). Em cũng kiên quyết bảo vệ quyết định "Not Yet" thay vì vội vàng chọn "Go" khi nhóm chưa có số liệu bấm giờ thực tế và chưa phỏng vấn người làm UA bên ngoài. Qua buổi lab, em nhận thấy điều thách thức nhất khi viết Problem Statement chính là xác lập Boundary. Nhóm phải dũng cảm vạch rõ những gì AI tuyệt đối không được phép làm (không tự gửi báo cáo, không tự đổi ngân sách) để bảo vệ tổ chức. Nếu có cơ hội làm lại lab này từ đầu, em sẽ thúc đẩy nhóm triển khai ngay một khảo sát hoặc phỏng vấn nhanh 1–2 người làm marketing bên ngoài từ Phase 4. Những bằng chứng thực nghiệm khách quan đó sẽ giúp nhóm tự tin hơn để chuyển dịch từ Not Yet sang một kế hoạch Go hoàn chỉnh.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Em đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Em tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI
