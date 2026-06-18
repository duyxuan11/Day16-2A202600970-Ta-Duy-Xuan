---
artifact: 01 — Case Analysis
bai-tap: Lab 1 — Phân tích "tử huyệt" chiến lược
format: Cá nhân trước → share trong bàn → chốt verdict cuối
time: 20 phút trên lớp
nop-cuoi: Có — đây là file nộp cuối của Lab 1
---

# Lab 1 — Case Analysis / Phân tích "tử huyệt" chiến lược

**Case đã chọn:** Stack Overflow  
**Người làm:** Tạ Duy Xuân - 2A202600970
**Bàn / nhóm bàn:** Bàn số 5
**Ngày:** 2026-06-18

> Đây là **file duy nhất** của Lab 1.  
> File này đồng thời đóng vai trò:
>
> - guide từng bước,
> - worksheet để điền trực tiếp,
> - và file nộp cuối cho người chấm.

Mục tiêu của bài này không phải kể lại "AI đã giết một công ty". Mục tiêu là chỉ ra, bằng bằng chứng thật:

1. **vì sao case đó bị tổn thương trước AI**
2. **điều gì đã thay đổi vĩnh viễn**
3. **và nếu rút một cảnh báo cho dự án của nhóm mình thì đó là gì**

Quy tắc xuyên suốt: **không có bằng chứng = không có nhận định.**

---

## Đầu ra bắt buộc

Người chấm cần thấy đủ 4 phần trong chính file này:

1. **3-5 bằng chứng chốt**
2. **4 nhận định bắt buộc**
3. **ghi chú sau khi share trong bàn**
4. **verdict cuối của cá nhân**

Nếu thiếu một trong bốn phần trên, bài sẽ bị xem là chưa hoàn chỉnh.

---

## Cách làm trong lớp (20 phút)

```text
2'  Chọn case
8'  Làm cá nhân: gom bằng chứng + viết 4 nhận định
7'  Share trong bàn: 90 giây / người + hỏi vặn lại
3'  Tự sửa verdict cá nhân sau thảo luận
```

---

## Bước 0 — Chọn case thật nhanh

Mặc định: **bạn tự chọn case của mình**.

### Một case phù hợp cần có 4 điều

- [ ] Có một **AI shock** hoặc mốc đổi cục diện đủ rõ
- [ ] Có thể tìm được ít nhất **3-5 bằng chứng công khai**
- [ ] Có tác động đủ nhìn thấy được ở user / doanh thu / pricing / traffic / cổ phiếu / usage / vị thế cạnh tranh
- [ ] Có thể trả lời câu hỏi: **"Điều gì đã thay đổi vĩnh viễn?"**

### Điền nhanh trước khi làm

- **Case / sản phẩm / công ty:** Stack Overflow (thuộc Prosus từ 2021)
- **AI / platform / sản phẩm mới tạo áp lực:** ChatGPT (OpenAI, ra mắt tháng 11/2022) + GitHub Copilot (Microsoft/GitHub)
- **Vì sao tôi chọn case này?**  
  > Tôi chọn case Stack Overflow vì tôi thấy nó thay đổi khá nhanh từ lúc AI được sử dụng phổ biến, 

### Nếu bí case, chọn 1 trong 6 case gợi ý này

| Case | Vì sao đáng phân tích | Một tín hiệu đáng chú ý |
|---|---|---|
| Chegg | entry point học tập đổi rất nhanh | 7,8M → 3,2M thuê bao |
| Stack Overflow | hiệu ứng mạng bị đảo chiều | câu hỏi mới giảm mạnh sau ChatGPT |
| Jasper | lớp vỏ dễ bị generic AI ép | định giá và tăng trưởng chậm lại sau ChatGPT |
| Tome | AI phổ thông "đủ tốt" làm phân khúc cũ yếu đi | nhiều đợt cắt giảm và pivot |
| Inflection / Pi | chatbot tiêu dùng bị ông lớn lấn át | đội ngũ chuyển sang Microsoft |
| Figma / Claude Design | rủi ro "đất thuê" khi platform bước xuống app layer | cổ phiếu Figma phản ứng tiêu cực khi Claude Design ra mắt |

> Nếu có case riêng rõ hơn, dùng case riêng.

---

## Bước 1 — Gom 3-5 bằng chứng chốt

Không cần chép lại mọi số. Chỉ giữ những bằng chứng đủ mạnh để đỡ toàn bộ lập luận của bạn.

### Tìm bằng chứng theo 4 cụm

1. **Case trước AI**
   Sản phẩm là gì, user là ai, họ trả tiền cho cái gì, case từng thắng nhờ gì.

2. **AI shock**
   Mốc Big Tech AI / platform AI / sản phẩm mới xuất hiện và đổi luật chơi.

3. **Tác động quan sát được**
   User, doanh thu, ARR, pricing, traffic, usage, cổ phiếu, sa thải, pivot.

4. **Cục diện mới của thị trường**
   Ai phản ứng tốt hơn, ai thay thế tốt hơn, entry point mới nằm ở đâu, phân khúc còn sống không.

### Ưu tiên nguồn thế nào?

| Mức ưu tiên | Loại nguồn | Ví dụ |
|---|---|---|
| 1 | Nguồn gốc | báo cáo tài chính, investor relations, pricing page, blog chính thức |
| 2 | Báo uy tín | Reuters, CNBC, Bloomberg, FT, TechCrunch |
| 3 | Dữ liệu công khai / tổng hợp | MacroTrends, Similarweb, Stack Overflow Survey, Sacra |

### Bảng bằng chứng chốt

| # | Bằng chứng / số liệu chốt | Vì sao số này quan trọng? | Nguồn |
|---|---|---|---|
| E1 | Monthly visits giảm từ ~279M (Nov 2022) xuống ~247M (Dec 2022) — tức ~12% chỉ trong 1 tháng; tiếp tục giảm ~14% MoM vào đầu 2023 | Chỉ số sức khỏe trực tiếp của mô hình quảng cáo — traffic là nguồn thu chính phía Reach (~$44M/năm) | SimilarWeb, May 2023 |
| E2 | Số câu hỏi mới mỗi tháng: đỉnh ~200,000 (2020), sụp xuống dưới 50,000 cuối 2025 (>75% giảm); tháng 4/2025 số bài đăng giảm 64% so với tháng 4/2024 | Đây không phải triệu chứng — đây là bằng chứng rằng cả supply lẫn demand tri thức đều đã rời nền tảng | Stack Overflow Data Explorer; The Pragmatic Engineer, 2025 |
| E3 | Nghiên cứu Oxford INET (2024): user activity trên Stack Overflow giảm 25% trong vòng 6 tháng đầu sau khi ChatGPT ra mắt, so với các nền tảng tương tự không có ChatGPT | Cung cấp quan hệ nhân-quả trực tiếp: không phải xu hướng chung, mà là phản ứng với ChatGPT | Oxford INET / TechXplore, Sep 2024 |
| E4 | Hai đợt sa thải năm 2023: 10% (tháng 5, ~58 người) + 28% (tháng 10, ~140+ người) = ~38% tổng nhân sự trong 1 năm; InfoWorld đặt tiêu đề trực tiếp: "Generative AI forces Stack Overflow to lay off 28%" | Sa thải quy mô này cho thấy cấu trúc chi phí không còn phù hợp — không phải điều chỉnh chiến thuật mà là khủng hoảng mô hình | TechCrunch, Oct 2023; InfoWorld, Oct 2023 |
| E5 | Doanh thu 2022: $89M, chia đều 50/50 giữa Stack Overflow for Teams (enterprise, $50M ARR, 1.262 paying teams) và Reach (quảng cáo + tuyển dụng); Prosus mua với giá $1.8B năm 2021 | Cho thấy cả hai nguồn thu đều bị đe dọa đồng thời: quảng cáo (traffic giảm) và enterprise (GitHub Copilot Enterprise cạnh tranh trực tiếp) | Getlatka.com / jlericson.com blog; TechCrunch Jun 2021 |

### 3 phát hiện ban đầu

Trước khi viết nhận định, ghi nhanh 3 dòng:

1. **Case này từng thắng nhờ...**  
   > 15+ năm tích lũy Q&A được vote và kiểm chứng bởi cộng đồng — tạo ra corpus không ai nhân bản nhanh được — kết hợp với hiệu ứng mạng hai chiều: developer tìm câu trả lời ở đây vì câu trả lời ở đây, và người trả lời tham gia vì đây là nơi được nhìn thấy
2. **AI shock làm thay đổi...**  
   > Entry point của workflow: thay vì "gặp lỗi → Google → Stack Overflow → đọc thread → tự ghép code", developer giờ hỏi thẳng ChatGPT hoặc Copilot ngay trong IDE — cả bước tìm kiếm lẫn bước ghép code đều bị rút ngắn
3. **Dấu hiệu mạnh nhất cho thấy luật chơi mới là...**  
   > Số câu hỏi mới giảm >75% từ đỉnh 2020 về dưới 50,000/tháng cuối 2025 — không phải người dùng bỏ đọc Stack Overflow, mà là họ không còn cần đặt câu hỏi ở đây nữa; supply tri thức cạn kiệt

---

## Bước 2 — Viết 4 nhận định bắt buộc

### Nhận định 1 — Trước AI, case này thắng nhờ giả định gì?

Gợi ý:

- Người dùng thuê sản phẩm này để làm gì?
- Giá trị lõi trước AI là gì?
- Họ thắng nhờ workflow, switching cost, brand, distribution, data hay một giả định hành vi nào?
- Job-to-be-done (công việc người dùng "thuê" sản phẩm làm hộ) là gì?

**Trả lời của tôi:**  
> Stack Overflow thắng nhờ giả định rằng **tìm câu trả lời lập trình đáng tin cậy đòi hỏi cộng đồng người kiểm chứng**. JTBD của user là: *"giúp tôi giải quyết lỗi cụ thể này nhanh nhất có thể, với câu trả lời tôi tin được"*. Stack Overflow "thắng" job đó nhờ 3 thứ: (1) Google search đưa thẳng vào, (2) câu trả lời đã có vote nên user không cần đánh giá lại, (3) accepted answer tạo cảm giác an toàn khi copy code vào production.  
> Giả định ngầm định quan trọng nhất: **người dùng sẵn sàng rời khỏi nơi mình đang làm việc (IDE) để vào trình duyệt và tự ghép câu trả lời**. Đây chính là điểm yếu bị khai thác.

**Bằng chứng đỡ nhận định này:** E1, E5

---

### Nhận định 2 — Kỳ vọng người dùng và luật chơi cạnh tranh đã đổi ở đâu?

#### Nhắc nhanh 7 Dịch chuyển Kỳ vọng

1. Làm xong giúp tôi
2. May đo cho tôi
3. Tự lo việc lặt vặt
4. Trả theo kết quả
5. Phản hồi ngay
6. Giao diện tự thay đổi
7. Thấu hiểu ngữ cảnh

#### Nhắc nhanh 5 Competitive Dynamics

- switching costs giảm
- data advantages tăng
- platform risk
- build-copy cycles tăng tốc
- GTM + distribution quan trọng hơn

**Shift kỳ vọng quan trọng nhất:** Shift #1 — "Làm xong giúp tôi" (từ "cho tôi câu trả lời để tự ghép" → "giải thẳng vào context code của tôi")  
**Competitive dynamic quan trọng nhất:** Switching costs giảm về gần bằng 0 — trước đây cần học cách search đúng tag/từ khóa trên Stack Overflow; giờ chỉ cần hỏi tự nhiên bằng ngôn ngữ thường

**Trả lời của tôi:**  
> Kỳ vọng của developer đã dịch chuyển từ "tìm câu trả lời đúng" sang "nhận solution sẵn, trong IDE, ngay lúc này". ChatGPT và Copilot đáp ứng shift này tốt hơn vì họ tích hợp vào workflow thay vì yêu cầu user rời khỏi nó. Quan trọng: Stack Overflow không sai — câu trả lời của họ vẫn tốt — nhưng **format và điểm giao tiếp (entry point) của họ không còn khớp với workflow mới**.  
> Competitive dynamic: GitHub Copilot (của Microsoft — cũng sở hữu GitHub, nơi developer làm việc) tạo ra **platform risk** — Microsoft tiếp cận developer ngay tại IDE mà không cần Stack Overflow làm trung gian.

**Bằng chứng đỡ nhận định này:** E2, E3

---

### Nhận định 3 — Giả định nào không còn đúng nữa? Điều gì đã thay đổi vĩnh viễn?

Gợi ý:

- Switching cost cũ có từng giữ user ở lại không? Vì sao giờ không còn đủ?
- Entry point cũ của sản phẩm có còn tồn tại không, hay người dùng đã chuyển sang một điểm bắt đầu mới?
- Workflow cũ có còn được chấp nhận không, hay chuẩn mới là "làm xong giúp tôi / ngay trong nơi tôi đang làm việc"?
- "Thay đổi vĩnh viễn" không phải là giá cổ phiếu giảm; nó là **chuẩn mới trong đầu người dùng** hoặc **luật chơi mới của thị trường**.
- Phân khúc này còn tồn tại không? Nếu còn, nó đang được phục vụ theo cách khác ra sao?

**Điều đã thay đổi vĩnh viễn theo tôi là:**  
> **Thứ nhất — Entry point bị đứt vĩnh viễn:** Developer sẽ không quay lại workflow "Google → Stack Overflow" khi đã biết AI trả lời trong vòng 5 giây ngay trong IDE. Khi một thói quen bị thay thế bởi thứ nhanh hơn và tích hợp hơn, không có con đường quay lại.  
> **Thứ hai — Chuẩn kỳ vọng mới đã hình thành trong đầu người dùng:** "Câu trả lời nên được cá nhân hóa theo context code của tôi, không phải câu trả lời chung cho cộng đồng." Một khi user đã biết điều đó có thể đạt được, họ không còn chấp nhận câu trả lời generic. Đây là thay đổi trong *chuẩn*, không phải trong *preference*.

**Bằng chứng đỡ nhận định này:** E2, E4

---

### Nhận định 4 — Case này còn cứu được không? Nếu có, phải đổi bằng cách nào?

Gợi ý:

- Nếu cứu được: họ phải đổi ở moat nào, workflow nào, distribution nào?
- Nếu không cứu được: vì sao đã quá muộn?
- So với một đối thủ phản ứng tốt hơn, họ chậm ở đâu?

**Verdict ban đầu của tôi:** Có nhưng phải đổi rất mạnh 
> Có thể nhưng cũng hơi khó, Stack Overflow là diễn đàn để trao đổi, mọi người trao đổi ý kiến, nó có thể
> giải quyết vấn đề của người này nhưng người kia thì không, nên solution nó cần xem xét.


**Phân tích để đỡ verdict:**  
> **Nếu còn cứu được**, con đường duy nhất là pivot khỏi "public Q&A community" sang hai hướng: (1) **Stack Overflow for Teams** làm internal knowledge base dành cho enterprise — tức là trở thành layer kiểm chứng tri thức tổ chức trên nền AI, không phải thay thế AI; (2) trở thành **human-verified ground truth** mà các LLM cần — vị trí hiếm có và không ai khác làm được.  
> **Rào cản:** Community trust đang giảm khi content creation cạn kiệt (E2). Enterprise đã có GitHub Copilot Enterprise và Microsoft 365 Copilot. Stack Overflow phản ứng chậm: ban ChatGPT content năm 2022 thay vì pivot, sa thải 38% năm 2023 chứng tỏ không có đủ runway để đổi mạnh.

**Trả lời của tôi:**  
> Stack Overflow còn cứu được, nhưng chỉ khi từ bỏ hoàn toàn định danh "public Q&A community". Con đường khả thi duy nhất là tập trung vào **Stack Overflow for Teams** như một enterprise knowledge layer — nơi AI tóm tắt, còn con người kiểm chứng — tức là không cạnh tranh với ChatGPT mà làm lớp kiểm chứng phía trên nó.  
> Họ đã chậm: phản ứng đầu tiên năm 2022 là ban ChatGPT content thay vì pivot, và đến khi sa thải 38% nhân sự năm 2023 thì runway để đổi mạnh đã rất hạn chế. Đối thủ phản ứng tốt hơn là GitHub — họ không cần chống lại AI vì họ đã sở hữu IDE và Copilot, tức là chiếm entry point mới từ sớm.

**Bằng chứng đỡ nhận định này:** E4, E5

---

## Tóm tắt cá nhân trước khi share trong bàn

Viết đúng 3 câu:

1. `Case này yếu đi vì...`
2. `Điều thay đổi vĩnh viễn là...`
3. `Verdict của tôi là...`

**Bản tóm tắt 3 câu của tôi:**  
1. Case này yếu đi vì sự phát triển nó diễn ra phá vỡ đi cái rào cản quá khứ, (rào cản là cái mọi người phải đi tìm tòi, áp dụng rồi tìm tiếp), thời gian xử lý vấn đề  
2. Điều thay đổi là entry point bị đứt, workflow mới nó hiệu quả, làm thay đổi thói quen người dùng. Kỳ vọng thay đổi cao hơn, cảm thấy tiện hơn.
3. Verdict là có thể nhưng phải mạnh

---

## Bước 3 — Share trong bàn (7')

### Mỗi người chỉ nói 4 thứ trong 90 giây

1. **Case bạn chọn là gì**
2. **Bằng chứng mạnh nhất bạn có là gì**
3. **Điều gì đã thay đổi vĩnh viễn**
4. **Verdict của bạn**

### Nếu chưa biết hỏi ngược gì, dùng 4 câu này

1. **"Bằng chứng mạnh nhất cho nhận định đó là gì?"**
2. **"Điều gì ở đây là triệu chứng, còn điều gì là thay đổi vĩnh viễn?"**
3. **"Nếu switching cost từng cao, vì sao người dùng vẫn rời đi?"**
4. **"Platform mới hoặc đối thủ mới đã chiếm entry point ở đâu?"**

### Ghi nhanh khi nghe các bạn cùng bàn

| Người | Case | Bằng chứng mạnh nhất họ nêu | Điều họ cho là "thay đổi vĩnh viễn" | Verdict của họ |
|---|---|---|---|---|
| Bạn 1 | Chegg | Cổ phiếu giảm | Chuẩn mới trong đầu người dùng, luật chơi thay đổi | Có, đổi mạnh |
| Bạn 2 | Figma | Chức năng design mạnh | Thay đổi cuộc chơi, chuẩn mới | Có thể thay đổi nhưng phải đổi mạnh |
| Bạn 3 | Chegg | Kho bài giảng không còn duy nhất khi ChatGPT có thể thực hiện | Chuẩn mới | Có thể thay đổi |
| Bạn 4 | Stack Overflow | Sa thải 38% nhân sự trong 1 năm (2023) — bằng chứng rõ nhất rằng mô hình kinh doanh không còn khả thi | Cộng đồng contributor tan rã — khi không còn ai đặt câu hỏi mới, network effect đảo chiều và tự phá vỡ | Có nhưng đổi rất mạnh |

### Sau khi cả bàn share xong, chốt 3 ý chung

**1. Bàn tôi thấy case nào có bằng chứng mạnh nhất? Vì sao?**  
> _______________________________________________

**2. Có pattern nào lặp lại giữa nhiều case không?**  
Ví dụ: switching costs giảm, platform bước xuống app layer, user chuyển sang "làm xong giúp tôi", moat cũ quá mỏng…  
> _______________________________________________

**3. Một cảnh báo cho chính dự án của nhóm tôi là gì?**  
> _______________________________________________

---

## Bước 4 — Chốt lại verdict cá nhân sau thảo luận (3')

### Sau khi nghe bàn phản biện, verdict của tôi:

- [x] Giữ nguyên
- [ ] Đổi nhẹ
- [ ] Đổi mạnh

### Vì sao tôi giữ / đổi verdict?

> Các bạn cùng bàn phân tích Chegg và Figma — cả hai đều có pattern giống: bị đe dọa ở entry point, không phải ở chất lượng sản phẩm. Điều đó củng cố thêm nhận định của tôi rằng Stack Overflow thua ở chỗ người dùng không còn đi qua họ nữa, chứ không phải vì câu trả lời của họ kém hơn ChatGPT.  
> Verdict "Có nhưng đổi rất mạnh" vẫn đúng — nhưng sau khi nghe bàn, tôi thấy rõ hơn rằng thời điểm để đổi mạnh đó đã qua từ năm 2022-2023, làm cho con đường sống ngày càng hẹp hơn.

### Verdict cuối cùng của tôi (phiên bản nộp)

**Case này tổn thương trước AI vì:**  
> Stack Overflow bị tấn công ở entry point, không phải ở sản phẩm. Toàn bộ mô hình của họ dựa trên giả định người dùng sẽ rời IDE, Google, vào site, đọc thread, rồi tự ghép code. ChatGPT và Copilot phá vỡ giả định đó bằng cách đưa câu trả lời cá nhân hóa vào ngay trong IDE. Moat của Stack Overflow — corpus 15 năm và network effect — không có giá trị gì khi người dùng không còn đi qua cổng của họ nữa.

**Điều thay đổi vĩnh viễn là:**  
> Hai thứ: (1) entry point "Google → Stack Overflow" bị đứt — không có lý do để quay lại khi AI nhanh hơn và tích hợp hơn; (2) chuẩn kỳ vọng của developer đã reset — họ giờ kỳ vọng câu trả lời được cá nhân hóa theo context code của mình, không phải câu trả lời chung cho cộng đồng. Khi chuẩn đã đổi, không có con đường quay lại chuẩn cũ.

**Nếu phải rút 1 bài học cho dự án của nhóm mình, tôi rút ra:**  
> Dự án AI trợ lý tư vấn và đặt phòng của nhóm phải tránh bẫy của Stack Overflow: đừng chỉ trả lời câu hỏi rồi để người dùng tự hành động. Nếu AI chỉ tư vấn mà không đặt phòng được luôn, người dùng sẽ hỏi ChatGPT cho nhanh rồi tự vào Booking.com — entry point của nhóm bị cắt đứt theo đúng cách Stack Overflow bị cắt. Moat thực sự phải nằm ở chỗ AI hoàn thành được job hoàn chỉnh ("đặt xong giúp tôi"), không phải chỉ ở bước tư vấn.

---

## Checklist trước khi nộp

- [ ] Tôi đã chọn ít nhất 3 bằng chứng chốt có nguồn.
- [ ] Mỗi nhận định đều chỉ vào ít nhất 1 bằng chứng.
- [ ] Tôi đã ghi lại phần share trong bàn.
- [ ] Tôi đã viết verdict cuối sau thảo luận.

---

## Nếu còn thời gian / làm về nhà

- Bổ sung thêm một case "đối thủ phản ứng tốt hơn" để so.
- Thêm một đoạn ngắn: **nếu tôi là PM của case này trong 6 tháng đầu sau AI shock, tôi sẽ làm gì đầu tiên?**
- Kiểm lại xem case này yếu vì expectation shift, competitive dynamics, hay cả hai cùng lúc.
