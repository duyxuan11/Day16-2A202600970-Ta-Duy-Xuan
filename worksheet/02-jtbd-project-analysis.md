---
artifact: 02 — JTBD Project Analysis
bai-tap: Lab 2 — Dùng JTBD để soi lại dự án nhóm
format: Theo nhóm dự án → share trong bàn → chốt hypothesis cuối
time: 25 phút trên lớp
nop-cuoi: Có — đây là file nộp cuối của Lab 2
companion-reference: Strategyn_JTBD_Playbook.pdf (giảng viên gửi kèm)
---

# Lab 2 — JTBD Project Analysis / Dùng JTBD để soi lại dự án nhóm

**Tên dự án / sản phẩm:** AI Trợ lý Tư vấn và Đặt phòng Khách sạn  

> Đây là **file duy nhất** của Lab 2.  
> File này đồng thời đóng vai trò:
>
> - guide từng bước,
> - worksheet để điền trực tiếp,
> - và file nộp cuối cho người chấm.

Mục tiêu của bài này không phải brainstorm thêm thật nhiều tính năng AI.
Mục tiêu là:

1. **xác định người dùng thực sự đang cố hoàn thành job gì**
2. **hiểu họ đang dùng giải pháp nào để hoàn thành job đó hôm nay**
3. **chỉ ra AI nên chen vào đúng bước nào trong workflow**
4. **viết ra product hypothesis và assumption còn phải validate**

Quy tắc xuyên suốt: **không rõ job thì đừng bàn feature.**

---

## Cần mở song song 2 thứ

1. **File này** — để điền trực tiếp
2. **`Strategyn_JTBD_Playbook.pdf`** — giảng viên gửi kèm

### Cách dùng playbook cho đúng

Bạn **không cần đọc hết 48 trang**.  
Trong bài này, playbook chủ yếu dùng để tra 4 thứ:

1. **Cách nhìn thị trường qua JTBD lens**
2. **`Job executor` là ai**
3. **Cách viết `job statement`: `verb + object + contextual clarifier`**
4. **8 bước của `job map`**:
   `define -> locate -> prepare -> confirm -> execute -> monitor -> modify -> conclude`

### 2 chương nên mở nhiều nhất

- **Chapter 2 — Define Your Market**
- **Chapter 3 — Build Your Job Map**

> Dùng playbook để **tra framework và ví dụ**.  
> Dùng file này để **làm bài và chốt output**.

---

## Đầu ra bắt buộc

Người chấm cần thấy đủ 6 phần trong chính file này:

1. **`Project slice` + market context**
2. **`Job executor` + `core JTBD`**
3. **3 `job stories`**
4. **`JTBD lite map` + pain points**
5. **`AI leverage point` + `product hypothesis`**
6. **`Assumptions to validate` + verdict cuối sau thảo luận**

Nếu thiếu một trong sáu phần trên, bài sẽ bị xem là chưa hoàn chỉnh.

---

## Cách làm trong lớp (25 phút)

```text
3'  Chốt 1 lát cắt cụ thể của dự án
7'  Viết market context + job executor + core JTBD
6'  Viết 3 job stories + current alternatives
6'  Điền JTBD lite map + AI leverage point + hypothesis
3'  Share trong bàn và sửa version cuối
```

> Nếu dự án làm theo nhóm, cả nhóm có thể thảo luận chung.  
> Nhưng file này vẫn nên có **version chốt rõ ràng** của người nộp.

---

## Bước 0 — Khoanh đúng 1 lát cắt của dự án

Phần lớn dự án nhóm viết quá rộng ở bước này, rồi sau đó mọi thứ mơ hồ theo.

### Khoanh đúng 1 lát cắt theo 4 điểm

- [x] **1 nhóm người dùng chính**
- [x] **1 hoàn cảnh / tình huống rõ**
- [x] **1 job cốt lõi**
- [x] **1 workflow đủ cụ thể để vẽ ra được**

### Điền nhanh trước khi làm

- **Dự án của nhóm tôi là:** AI trợ lý tư vấn và đặt phòng khách sạn — chat với AI để nhận gợi ý và đặt phòng trong cùng một luồng hội thoại
- **Lát cắt tôi chọn để phân tích hôm nay là:** Người du lịch tự túc cần tìm và đặt phòng khách sạn ngắn ngày trong nước, thường vào dịp cuối tuần hoặc gấp
- **Vì sao tôi chọn lát cắt này:**  
  > Đây là nhóm người dùng lớn nhất và thường xuyên nhất — không đi qua tour, tự lên kế hoạch, và đang bị mất thời gian nhiều nhất ở bước tìm + so sánh options. Đây cũng là nơi AI có thể tạo giá trị rõ nhất nếu làm được "đặt xong giúp tôi", thay vì chỉ "tư vấn rồi để tôi tự đặt".

### Viết quá rộng vs viết sắc hơn

| Viết quá rộng | Viết sắc hơn |
|---|---|
| Giúp SME dùng AI để marketing | Giúp chủ shop online phản hồi câu hỏi trước mua hàng nhanh và nhất quán trong giờ cao điểm |
| Dùng AI để làm slide | Tạo bản nháp deck nội bộ mạch lạc cho buổi họp gấp trong thời gian rất ngắn |
| AI cho tuyển dụng | Giúp recruiter sàng lọc CV đầu vào nhanh hơn trước vòng gọi sơ bộ |

> Nếu bạn không mô tả được **một hoàn cảnh cụ thể**, khả năng cao bạn đang viết quá rộng.

---

## Bước 1 — Viết `Project Snapshot`

### Tóm tắt dự án trong 3 dòng

1. **Nhóm tôi đang nghĩ mình đang giải quyết vấn đề gì?**  
   > Người du lịch tự túc mất quá nhiều thời gian tìm, so sánh và đặt phòng khách sạn vì phải chuyển qua lại giữa nhiều nền tảng (Booking.com, Agoda, Google Maps, review sites) trước khi ra quyết định.

2. **Người dùng chính hiện nhóm đang nhắm tới là ai?**  
   > Khách du lịch tự túc trong nước, 22–40 tuổi, đặt phòng cho cá nhân hoặc nhóm nhỏ (2–4 người), không qua tour/lữ hành, có thói quen tra cứu trên điện thoại.

3. **Hiện tại người dùng đó đang giải quyết vấn đề này bằng cách nào?**  
   > Kết hợp nhiều công cụ: vào Booking.com/Agoda để lọc theo giá và tiện nghi, đọc review trên Google Maps hoặc TripAdvisor, nhờ bạn bè gợi ý qua chat, hoặc hỏi ChatGPT nhưng sau đó vẫn phải tự vào platform để đặt.

---

## Bước 2 — Viết `Market Context`

Ở đây chưa cần solution. Chỉ cần bối cảnh thị trường đủ để hiểu:
**ai đang gặp chuyện gì, trong hoàn cảnh nào, và vì sao bây giờ đáng giải.**

### Trả lời 4 câu ngắn

1. **Ai đang gặp vấn đề này?**  
   > Khách du lịch tự túc cá nhân/nhóm nhỏ, đặc biệt những người đặt phòng gấp (0–3 ngày trước chuyến đi) hoặc cần tìm phòng thoả mãn nhiều tiêu chí cùng lúc (vị trí, giá, tiện nghi, phong cách).

2. **Vấn đề xuất hiện trong hoàn cảnh nào?**  
   > Cuối tuần hoặc dịp lễ ngắn, người dùng có ý định đi nhưng chưa đặt phòng — mở Booking.com, thấy hàng trăm kết quả, đọc không xuể, so sánh mệt, cuối cùng chọn một cái "đủ được" chứ không phải "đúng nhất". Hoặc đi gấp và không có thời gian nghiên cứu kỹ.

3. **Hiện tại họ đang dùng giải pháp thay thế nào?**  
   > Booking.com/Agoda (tự lọc), Google Maps (xem review/vị trí), ChatGPT (hỏi gợi ý nhưng không đặt được), hỏi bạn bè qua mạng xã hội, hoặc nhờ travel agent (tốn phí và chậm).

4. **Vì sao đây là thời điểm đáng giải?**  
   > Du lịch nội địa Việt Nam phục hồi mạnh sau COVID, tỷ lệ người dùng di động tăng cao, LLM đã đủ mạnh để hiểu ngữ cảnh tự nhiên, và API đặt phòng (OTA) ngày càng mở. Đây là thời điểm "đặt phòng bằng chat" trở nên technically khả thi và người dùng đã quen với conversational AI qua ChatGPT.

### Tóm tắt market context trong 3-4 dòng

> Người du lịch tự túc Việt Nam đang gặp friction cao ở bước tìm và chọn phòng: quá nhiều options, interface lọc nghèo nàn, phải chuyển tab liên tục giữa booking platforms và review sites. Giải pháp hiện tại không giải được vấn đề cốt lõi — ChatGPT tư vấn được nhưng không đặt được, Booking.com đặt được nhưng tư vấn kém. Dư địa để một sản phẩm làm cả hai trong cùng một luồng là rõ.  
> Thị trường du lịch nội địa đang tăng trưởng và người dùng đã sẵn sàng với conversational AI — timing phù hợp để thử.

---

## Bước 3 — Xác định `Job Executor`

`Job executor` là người **trực tiếp dùng một giải pháp để hoàn thành job**.

### Đừng nhầm với:

- người mua tiền nhưng không trực tiếp làm job
- người ảnh hưởng quyết định
- cả một công ty hay một phòng ban quá rộng

### Gợi ý viết cho đúng

- Sai hoặc quá rộng: `SME`, `doanh nghiệp`, `thị trường`
- Tốt hơn: `chủ shop online`, `nhân viên CSKH`, `recruiter`, `sales ops manager`

### Điền

- **Job executor của dự án này là:** Khách đặt phòng tự túc — người trực tiếp ngồi tìm kiếm, so sánh, và bấm nút đặt phòng cho chuyến đi của mình hoặc nhóm nhỏ
- **Vì sao tôi tin đây là người trực tiếp "thuê" giải pháp để làm job:**  
  > Họ là người cầm điện thoại, mở app, nhập filter, đọc review, và quyết định đặt. Không có trung gian nào ra quyết định thay — khác với booking corporate (có admin/travel manager) hay booking tour (có tour operator). Đây là người trực tiếp chịu đựng friction và sẽ là người đầu tiên chuyển sang tool tốt hơn.

---

## Bước 4 — Viết `Core JTBD`

`Core JTBD` là công việc cốt lõi người dùng đang cố hoàn thành.

### Công thức gợi ý

```text
[verb] + [object] + [contextual clarifier]
```

### Ví dụ

- Chưa tốt: `trả lời inbox bằng AI`
- Tốt hơn: `giải quyết câu hỏi trước mua hàng nhanh và chính xác trong giờ cao điểm`

- Chưa tốt: `dùng AI để viết nội dung`
- Tốt hơn: `tạo bản nháp nội dung chiến dịch phù hợp với brand trong thời gian rất ngắn`

### 3 tiêu chí tự kiểm

- [x] Nếu bỏ tool hiện tại đi, job này vẫn còn tồn tại
- [x] Trong câu không có tên sản phẩm, AI, chatbot, app, màn hình
- [x] Câu đang mô tả **điều user muốn hoàn thành**, không phải thứ product đang làm

### Bản nháp 1

**Core JTBD bản nháp:**  
> Tìm và xác nhận phòng khách sạn phù hợp nhất với nhu cầu chuyến đi trong thời gian ngắn nhất, mà không cần lướt qua hàng trăm lựa chọn

### Gạch bỏ từ solution nếu có

- Các từ solution tôi đang lỡ nhét vào câu: *(không có từ nào đề cập tool, app, hay AI — câu đã solution-free)*

### Bản chốt

**Core JTBD cuối cùng:**  
> Lựa chọn và xác nhận chỗ ở phù hợp với hành trình và ngân sách cụ thể, nhanh và tự tin, ngay khi có ý định đi

---

## Bước 5 — Viết 3 `Job Stories`

Nếu `core JTBD` là job ở mức cốt lõi, thì `job story` giúp bạn thấy
**job này xuất hiện trong hoàn cảnh nào**.

### Format

```text
When [trigger], I want to [motivation], so I can [outcome].
```

### Ví dụ

`When inbox đổ dồn vào buổi tối, tôi muốn có câu trả lời nhất quán ngay lập tức, so I can không mất đơn vì phản hồi chậm.`

### Bảng 3 job stories

| # | Trigger / When | Motivation / I want to | Outcome / so I can | Điều story này cho thấy |
|---|---|---|---|---|
| JS1 | Khi tôi vừa quyết định đi Đà Nẵng cuối tuần này và chỉ còn 2 ngày để chuẩn bị | Nhanh chóng tìm được khách sạn view biển, gần trung tâm, dưới 800k/đêm mà không cần lọc tay hàng trăm kết quả | Chốt phòng trong 10 phút và tập trung vào việc khác | Friction cao nhất nằm ở bước lọc options — quá nhiều, quá chậm |
| JS2 | Khi tôi đặt phòng cho nhóm 4 người với nhu cầu khác nhau (1 người cần giường đôi riêng, 2 người muốn bao gồm bữa sáng, tất cả cần gần điểm tham quan X) | Nhận ngay 2–3 gợi ý phù hợp với toàn bộ yêu cầu để tôi có thể forward cho cả nhóm xem | Không mất thêm vòng hỏi-đáp với nhóm và chốt nhanh | Job có nhiều ràng buộc đồng thời — tools hiện tại không handle tốt |
| JS3 | Khi tôi đang ở Hội An và muốn ở lại thêm 1 đêm nhưng không biết phòng nào còn trống ngay hôm nay | Xác nhận ngay có phòng nào phù hợp và đặt được luôn mà không cần mở nhiều tab | Yên tâm nghỉ thêm mà không mất thời gian lên mạng tra trong lúc đang đi chơi | Pain ở bước execute khi user đang "on the go" — mobile friction rất cao |

### Tự kiểm nhanh

- [x] Mỗi story là một **tình huống thật**, không phải slogan chung chung
- [x] 3 story không trùng hệt nhau
- [x] Sau khi đọc 3 story, tôi hình dung được lúc nào product của mình đáng xuất hiện

---

## Bước 6 — Liệt kê `Current Alternatives`

Qua JTBD lens, đối thủ không chỉ là app cùng ngành.
Đối thủ là **bất kỳ thứ gì user đang "thuê" để làm job**:

- thao tác tay
- file Excel / Google Sheets
- intern / nhân viên
- agency
- ChatGPT / Claude / Gemini
- công cụ chuyên dụng khác
- hoặc thậm chí là **không làm gì cả**

### Bảng alternatives

| Alternative hiện tại | User đang thuê nó để làm gì? | Nó làm tốt gì? | Nó fail ở đâu? | Switching cost hiện tại cao hay thấp? |
|---|---|---|---|---|
| Booking.com / Agoda | Tìm + lọc + đặt phòng trong một nơi | Lọc theo giá, loại phòng, tiện nghi; thanh toán an toàn; có review | Cần tự lọc tay qua hàng trăm kết quả; không hiểu ngữ cảnh chuyến đi; review dài và mệt để đọc | Thấp — user có thể chuyển app khác ngay, không mất gì |
| ChatGPT / Claude | Hỏi gợi ý khách sạn theo nhu cầu tự nhiên | Hiểu ngữ cảnh tốt, trả lời nhanh, giải thích được lý do chọn | Không đặt được, thông tin có thể không còn chính xác (giá/availability), phải copy sang app khác để đặt | Thấp — chỉ là app chat, không có lock-in |
| Hỏi bạn bè / group Facebook du lịch | Nhận gợi ý từ người đã trải nghiệm thật | Tin cậy cao, có context cụ thể, peer recommendation | Chậm (phải chờ phản hồi), không phải lúc nào cũng có người trả lời, không đặt được | Cao hơn — dựa trên network xã hội, khó thay bằng tool |
| Travel agent / OTA agent | Để người khác lo toàn bộ | Không cần làm gì, được tư vấn tận tay | Tốn phí dịch vụ, chậm, không linh hoạt, không phù hợp với đặt phòng ngắn/gấp | Thấp nếu chỉ xét tiền, nhưng có switching friction về thói quen |

### Kết luận nhanh

**Nếu project của tôi biến mất hôm nay, user nhiều khả năng sẽ quay về:**  
> Kết hợp ChatGPT (để tư vấn) + Booking.com (để đặt) — đây là "workaround" hiện tại của hầu hết user. Switching cost rất thấp nên họ không cần sản phẩm của nhóm tốt hơn nhiều, nhưng phải làm được cả hai trong một luồng.

---

## Bước 7 — Điền `JTBD Lite Map`

Đây là bản rút gọn của `job map` trong playbook.

### Mục tiêu

Không phải để làm consultant workshop hoàn chỉnh.  
Mục tiêu là nhìn ra:

1. workflow hiện tại của user đi qua những bước nào
2. bước nào đang đau nhất
3. AI có nên chen vào đó không

### 8 bước tham chiếu từ playbook

1. `Define`
2. `Locate`
3. `Prepare`
4. `Confirm`
5. `Execute`
6. `Monitor`
7. `Modify`
8. `Conclude`

> Không nhất thiết bước nào cũng quan trọng như nhau trong dự án của bạn.  
> Nếu ít liên quan, ghi `N/A`, đừng để trống.

### Bảng JTBD Lite Map

| Step | Trong workflow này user đang cố làm gì? | Hôm nay họ đang dùng gì? | Friction / pain hiện tại | Mức đau |
|---|---|---|---|---|
| Define | Xác định rõ mình cần loại phòng gì, ngân sách bao nhiêu, ở khu nào | Tự nghĩ trong đầu, không có tool hỗ trợ structuring requirements | Nhu cầu thường mơ hồ ("phòng đẹp, giá ổn"), dễ bị options trên platform kéo lệch | Med |
| Locate | Tìm danh sách phòng/khách sạn phù hợp với tiêu chí đã có | Booking.com / Agoda filter, Google Search | Hàng trăm kết quả, filter kém linh hoạt, kết quả bị ảnh hưởng bởi quảng cáo/sponsored | **High** |
| Prepare | Đọc thông tin chi tiết, so sánh ưu nhược điểm giữa các options | Đọc reviews trên nhiều site, xem ảnh, tra Google Maps vị trí | Phải chuyển tab liên tục, review dài và khó tổng hợp nhanh, mất 30–60 phút cho bước này | **High** |
| Confirm | Kiểm tra còn phòng và giá chính xác cho ngày cụ thể | Check trực tiếp trên app, so sánh giá nhiều OTA | Giá có thể thay đổi, cần check nhiều trang để tìm giá tốt nhất | Med |
| Execute | Điền thông tin, chọn phòng và thanh toán | Booking.com / Agoda checkout flow | Form dài, phải nhập lại thông tin nhiều lần nếu đặt theo nhóm | Med |
| Monitor | Theo dõi xác nhận booking, nhận email/voucher | Email inbox, app notification | Thường ổn — ít friction ở bước này | Low |
| Modify | Thay đổi ngày, hủy phòng nếu kế hoạch thay đổi | Liên hệ CS của OTA, vào trang quản lý booking | Chính sách hủy phòng khác nhau, phí hủy bất ngờ, cần đọc kỹ fine print khi đặt | Med |
| Conclude | Check-in, đối chiếu phòng với kỳ vọng | N/A — tự làm khi đến nơi | Đôi khi phòng không đúng ảnh/mô tả — nhưng đây là vấn đề của OTA, không phải workflow tìm kiếm | Low |

### Chốt 2 bước đau nhất

**Bước đau nhất #1:** Prepare (đọc và so sánh thông tin giữa nhiều options)  
**Bước đau nhất #2:** Locate (tìm ra danh sách candidates phù hợp từ hàng trăm kết quả)

**Vì sao đây là nơi đáng chú ý nhất:**  
> Locate và Prepare cộng lại chiếm phần lớn thời gian của user — đây là nơi friction dồn nhất. Booking.com giải tốt bước Execute nhưng kém ở Locate/Prepare. ChatGPT giải khá bước Prepare nhưng không xong bước Execute. Đây là gap rõ nhất mà sản phẩm của nhóm có thể lấp.  
> Quan trọng hơn: nếu AI giải được Locate + Prepare tốt, user sẵn sàng để AI xử lý tiếp cả Execute — đây là chuỗi tự nhiên dẫn đến "đặt xong giúp tôi".

---

## Bước 8 — Chỉ ra `AI Leverage Point`

Sau khi map workflow, mới hỏi:
**AI nên vào đâu, với vai trò gì, và vì sao là ở đó?**

### Nhắc nhanh

- Đừng nhét AI vào chỉ vì "có AI thì nghe hay"
- Nếu pain lớn nhất không nằm ở chỗ AI giải tốt, hãy thành thật ghi ra
- Nếu current alternative đã đủ tốt, project cần xem lại

### Bảng leverage point

| Step | AI nên giúp bằng cách nào? | Vì sao AI hợp ở đây? | Rủi ro chính nếu dùng AI |
|---|---|---|---|
| Locate + Prepare | AI hiểu ngữ cảnh chuyến đi từ câu chat tự nhiên, lọc ra 3–5 gợi ý phù hợp kèm tóm tắt ưu nhược điểm ngắn gọn | LLM xử lý tốt multi-criteria filtering khi criteria được diễn đạt bằng ngôn ngữ thường (không cần filter form); tổng hợp review nhanh hơn người đọc thủ công | AI có thể bỏ sót tiêu chí ngầm của user; review tóm tắt có thể miss nuance quan trọng; data availability/price cần API real-time |
| Execute | AI hoàn thành booking trực tiếp sau khi user chọn option — không cần user rời khỏi chat | Đây là điểm khác biệt duy nhất so với ChatGPT: AI không chỉ tư vấn mà kết thúc được job | Phải tích hợp API OTA (phức tạp, có thể không available); user lo về bảo mật thanh toán; lỗi booking gây trust issue nghiêm trọng |

### Kết luận nhanh

**AI leverage point quan trọng nhất của dự án tôi là:**  
> Bước Locate + Prepare — AI hiểu nhu cầu từ ngôn ngữ tự nhiên và trả về 3–5 gợi ý phù hợp với tóm tắt rõ ràng, thay vì để user tự lọc hàng trăm kết quả. Đây là nơi tạo được giá trị rõ nhất và tạo đà để user muốn AI xử lý tiếp cả bước Execute.

**Vì sao không phải ở bước khác:**  
> Bước Define (mơ hồ nhưng không đau đủ), Monitor/Conclude (ít friction, Booking.com đã xử lý tốt), Modify (cần can thiệp vào OTA backend). Bước Execute quan trọng nhưng chỉ có giá trị khi đã giải được Locate/Prepare trước — không ai muốn AI đặt phòng nếu gợi ý ban đầu không đúng.

---

## Bước 9 — Viết `Product Hypothesis`

Bây giờ mới đến lúc viết hypothesis.

### Công thức gợi ý

```text
Nếu chúng ta giúp [job executor] làm [job / sub-job] tốt hơn ở bước [x],
bằng cách [AI leverage],
thì họ sẽ chuyển từ [current alternative] sang [hướng giải pháp của nhóm],
vì [giá trị rõ nhất].
```

### Bản hypothesis của tôi

> Nếu chúng ta giúp khách đặt phòng tự túc lọc và chọn được khách sạn phù hợp nhất ở bước Locate + Prepare, bằng cách AI hiểu yêu cầu chuyến đi từ chat tự nhiên và trả về 3–5 gợi ý kèm tóm tắt rõ ràng — rồi đặt được luôn trong cùng luồng hội thoại — thì họ sẽ chuyển từ combo ChatGPT (tư vấn) + Booking.com (tự đặt) sang sản phẩm của nhóm, vì tiết kiệm được >50% thời gian so sánh và không cần chuyển tab.

### Tín hiệu sớm nếu hypothesis này đúng

1. User hoàn thành booking trong cùng 1 session chat mà không cần mở thêm Booking.com hay ChatGPT
2. User quay lại dùng sản phẩm cho lần đặt phòng tiếp theo mà không phải được nhắc — tức là tự nhiên chọn đây thay vì Booking.com trước

---

## Bước 10 — Liệt kê `Assumptions to Validate`

Job story chưa có research vẫn chỉ là **giả thuyết tốt hơn**, chưa phải sự thật.

### 5 assumption thường đáng kiểm

- Tôi đã chọn đúng `job executor`
- Pain này thật sự đủ đau và xảy ra đủ thường xuyên
- User sẽ đổi khỏi alternative hiện tại nếu có giải pháp tốt hơn
- AI thực sự tạo giá trị ở step tôi chọn
- User đủ tin kết quả AI để đưa vào workflow thật

### Bảng assumptions

| Assumption | Vì sao assumption này rủi ro? | Tôi đang có bằng chứng gì? | Cần validate bằng cách nào tiếp theo? |
|---|---|---|---|
| A1: Người đặt phòng tự túc là đúng job executor | Có thể corporate traveler hoặc người đặt cho người khác có pain khác và nhiều hơn | Thấy nhiều user hỏi ChatGPT về khách sạn trong personal capacity; travel apps lớn nhất ở VN phục vụ self-serve | Phỏng vấn 5–10 người đã tự đặt phòng trong 3 tháng gần nhất; hỏi workflow thực tế |
| A2: Locate + Prepare là điểm đau lớn nhất, đủ để đổi tool | User có thể đã quen với Booking.com và chấp nhận friction — switching cost có thể cao hơn tôi nghĩ | JS1, JS2 trong bài này; anecdotal từ bạn bè trong nhóm | Quan sát user thật đặt phòng (session recording hoặc think-aloud), đo thời gian thực tế ở từng bước |
| A3: User sẽ tin và để AI đặt phòng thay mình (có liên quan đến thanh toán) | Người Việt có thể chưa tin AI xử lý thanh toán — trust rào cản cao với transaction liên quan tiền | Chưa có bằng chứng cụ thể — đây là assumption chưa được kiểm | Survey về mức độ sẵn sàng để AI xử lý booking; test với prototype "AI đề xuất, user bấm confirm" trước |
| A4: AI tổng hợp review đủ tốt để user không cần đọc thêm | LLM có thể miss nuance, hallucinate thông tin khách sạn, hoặc data review không cập nhật | Chưa test cụ thể với travel data | A/B test: user đọc tóm tắt AI vs. tự đọc review → đo quyết định cuối có khác không |
| A5: Tích hợp API đặt phòng từ OTA là khả thi với team hiện tại | Booking.com / Agoda API có thể không public hoặc tốn chi phí cao; tích hợp thanh toán phức tạp | Chưa research kỹ về OTA API access | Spike kỹ thuật: research API availability, thử affiliate/partner program của các OTA |

### Assumption nguy hiểm nhất nếu tôi đang sai

> **A3 — User chưa sẵn sàng để AI xử lý booking thay mình.** Nếu user muốn tư vấn AI nhưng vẫn muốn tự bấm đặt, thì sản phẩm của nhóm sẽ không khác ChatGPT + Booking.com là mấy — và lý do chính để user chuyển sang biến mất. Toàn bộ product hypothesis dựa trên giả định user muốn AI "đặt xong giúp tôi", không chỉ "tư vấn rồi tôi tự đặt".

---

## Bước 11 — Share trong bàn (3')

### Mỗi người / mỗi nhóm chỉ nói 4 thứ

1. **Job executor của bạn là ai**
2. **Core JTBD của bạn là gì**
3. **Step đau nhất đang nằm ở đâu**
4. **AI leverage point + assumption rủi ro nhất là gì**

### Nếu chưa biết hỏi ngược gì, dùng 4 câu này

1. **"Câu JTBD này có đang lỡ nhét solution vào không?"**
2. **"Alternative hiện tại của user là gì, và tại sao họ chưa bỏ nó?"**
3. **"Pain mạnh nhất nằm ở bước nào trong workflow, có chắc AI giải tốt được không?"**
4. **"Assumption nào nếu sai thì cả hypothesis sẽ sập?"**

### Ghi nhanh sau khi nghe bàn phản biện

| Ý phản biện tôi nghe được | Nó chạm vào phần nào? | Tôi sẽ giữ / sửa gì? |
|---|---|---|
| *(Điền sau khi share trong bàn)* | | |
| | | |
| | | |

---

## Bước 12 — Chốt version cuối sau thảo luận

### Sau khi nghe phản biện, tôi thay đổi gì?

- [x] Giữ nguyên `job executor`
- [ ] Sửa `job executor`
- [x] Giữ nguyên `core JTBD`
- [ ] Sửa `core JTBD`
- [x] Giữ nguyên `AI leverage point`
- [ ] Sửa `AI leverage point`
- [x] Giữ nguyên `product hypothesis`
- [ ] Sửa `product hypothesis`

### Vì sao tôi giữ / sửa?

> *(Điền sau khi share trong bàn — ghi cụ thể ý phản biện nào được nghe và tại sao giữ hoặc sửa)*  
> Bản nộp này là version trước khi nghe phản biện — sẽ cập nhật sau khi share trong bàn.

### Version cuối cùng tôi nộp

**Job executor:**  
> Khách đặt phòng tự túc — người trực tiếp tìm kiếm, so sánh và xác nhận chỗ ở cho chuyến đi cá nhân hoặc nhóm nhỏ, không qua tour/agent

**Core JTBD:**  
> Lựa chọn và xác nhận chỗ ở phù hợp với hành trình và ngân sách cụ thể, nhanh và tự tin, ngay khi có ý định đi

**2 bước đau nhất trong workflow:**  
> Locate (lọc ra candidates phù hợp từ hàng trăm kết quả) và Prepare (đọc, so sánh thông tin giữa nhiều options để ra quyết định) — hai bước này cộng lại chiếm hầu hết thời gian và friction của user

**AI leverage point chính:**  
> Locate + Prepare: AI hiểu nhu cầu từ ngôn ngữ tự nhiên, lọc và tóm tắt 3–5 gợi ý phù hợp — tạo đà để user muốn AI xử lý tiếp cả bước Execute (đặt phòng) trong cùng một luồng

**Product hypothesis:**  
> Nếu AI giúp user lọc + chọn phòng từ chat tự nhiên và đặt được luôn trong cùng luồng, user sẽ chuyển từ combo ChatGPT + Booking.com sang sản phẩm của nhóm vì tiết kiệm >50% thời gian và không cần chuyển tab

**Assumption cần validate đầu tiên:**  
> User có sẵn sàng để AI đặt phòng thay mình không (A3) — nếu không, toàn bộ hypothesis sập; cần test bằng prototype "AI đề xuất, user bấm confirm" với user thật trước khi build full booking integration

---

## Checklist trước khi nộp

- [x] Tôi đã khoanh đúng 1 lát cắt cụ thể của dự án.
- [x] Tôi đã phân biệt được `job executor` với buyer / influencer.
- [x] `Core JTBD` của tôi không nhét solution vào câu.
- [x] Tôi đã viết đủ 3 `job stories`.
- [x] Tôi đã điền `JTBD lite map` và khoanh ra 2 bước đau nhất.
- [x] Tôi đã chỉ ra `AI leverage point` thay vì nhảy thẳng vào feature list.
- [x] Tôi đã ghi rõ `assumptions to validate`.
- [ ] Tôi đã sửa version cuối sau khi share trong bàn. *(cần cập nhật sau khi share)*

---

## Nếu còn thời gian / làm về nhà

- Phỏng vấn nhanh 1 người dùng thật để kiểm xem `job story` nào là sát nhất.
- So sánh `current alternatives` với project của nhóm theo 3 tiêu chí: nhanh hơn, rẻ hơn, tin hơn.
- Tự hỏi lại một câu khó: **nếu không dùng AI, project này còn tạo giá trị không?**
- Nếu câu trả lời là "không", hãy xem lại liệu nhóm đang giải **job thật** hay chỉ đang tìm chỗ để nhét AI.
