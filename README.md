# Track1 · Day17 — Problem Interview Practice

## 1. Thông tin cá nhân và nhóm

| | |
|---|---|
| **MHV** | 2A202602619 |
| **Họ tên** | Hà Thị Mỹ Linh |
| **Tên nhóm** | The LDK |
| **Thành viên** | Nguyễn Thị Phương Duyên - 2A202603001<br>Nguyễn Hà Khuê - 2A202602938 |
| **Case** | B — AI Notes: Personal Learning Notes |

**Cấu trúc repo**

```
Track1_Day17_2A202602619_HaThiMyLinh/
├── README.md
└── interview/
    ├── notes.md          # Interview Record lượt mình làm interviewer
    └── recording-link.md # link Drive tới bản ghi (đã xin phép, quyền truy cập hạn chế)
```

---

## 2. Problem Hypothesis Brief (Chặng 1)

**Chuỗi Solution → Evidence**

| Bước | Nội dung |
|---|---|
| Solution directive | AI Notes — tổng hợp highlights, đánh dấu "Chưa hiểu" và nội dung bài thành ghi chú có cấu trúc |
| Capability trung tính | Gom các mảnh nội dung học viên lưu trong lúc học thành một thứ dùng lại được sau buổi học |
| Actor | Học viên học online (video/slide) có thói quen ghi chú, highlight, screenshot trong lúc học |
| Situation | Sau buổi học, khi cần ôn hoặc tìm lại một phần đã lưu |
| Pain giả định | Các mảnh lưu rời rạc, thiếu context → mất thời gian tìm lại nguồn, đọc lại, hoặc bỏ sót phần từng muốn xem lại |
| Evidence cần tìm | Lần gần nhất mở lại note để dùng; công sức ghi và tổng hợp; lần gần nhất tìm lại thông tin — mất bao lâu, có bỏ sót không (→ Big 3 ở mục 3) |

**Problem Hypothesis:**

> Học viên có thói quen lưu lại nội dung trong quá trình học có thể gặp khó khăn khi muốn sử dụng lại những thông tin đó sau buổi học, vì highlights, ghi chú, screenshot và câu hỏi được tạo nhanh theo từng thời điểm nên dễ rời rạc và thiếu context — khiến họ mất thời gian tìm lại nguồn, đọc lại nội dung hoặc bỏ sót những phần từng muốn xem lại.

**Điều phải đúng để giả thuyết đứng vững**
1. Học viên thực sự có nhu cầu xem lại nội dung sau khi học.
2. Học viên thực sự ghi chú, không chỉ xem lại bài.
3. Ghi chú thủ công gây khó khăn/lâu (≥ 15 phút hoặc dễ bỏ sót).
4. Highlight và đánh dấu "chưa hiểu" phản ánh đúng thứ học viên cần ôn.
5. Học viên muốn ôn tập, không bỏ qua.
6. Notes tạo ra được tin tưởng và mở lại dùng — nếu không, outcome không xảy ra.

**Điều có thể làm sửa hoặc bác bỏ giả thuyết**
1. Học viên không ghi chú — chỉ xem lại bài (không có demand).
2. User **không bao giờ** mở lại ghi chú cũ → pain thật nằm ở khâu tái sử dụng.
3. Phần họ muốn giữ là ý riêng/câu hỏi của chính họ, không phải nội dung bài → "tổng hợp nội dung bài" không trúng.
4. Notes dùng để chia sẻ cho nhóm học, không phải tự xem → job khác.
5. Học viên ít highlight/đánh dấu → không đủ dữ liệu đầu vào.

**Solution Parking Lot** (giữ lại, không dùng khi phỏng vấn)

| # | Hướng | AI? |
|---|---|---|
| 1 | Tổng hợp highlights + nội dung bài thành ghi chú có cấu trúc (directive gốc) | AI |
| 2 | Biến các điểm "Chưa hiểu" thành danh sách cần xem lại, kèm context | AI |
| 3 | Q&A tương tác: AI hỏi → học viên trả lời → sinh ghi chú | AI |
| 4 | Ghi chú gắn vào từng slide/mốc thời gian video | Không AI |
| 5 | Flashcard + lịch ôn ngắt quãng từ đoạn đã highlight | AI |
| 6 | Learner tự gắn tag (Quan trọng, Chưa hiểu, Ôn thi, Hỏi GV) | Không AI |

---

## 3. Conversation Guide — phiên bản cuối (sau luyện)

> Các chỗ sửa so với bản trước khi luyện (Chặng 2) được đánh dấu **[SỬA]**; bản cũ và lý do sửa nằm ở bảng "Đã sửa gì" cuối mục.

**Tiêu chí tuyển:** người đã ghi chú, highlight hoặc lưu lại nội dung học tập để xem sau trong **7 ngày** gần đây.

**Recruitment check:** "Lần gần nhất bạn lưu lại hoặc highlight một đoạn nội dung khi học là khi nào — bạn lưu nó ở đâu?"
**[SỬA]** Thêm: "Bạn đã nghe/thấy gì về sản phẩm hay đề bài của nhóm mình chưa?" → nếu đã biết solution, ghi chú lại và cân nhắc đổi người.

**Lời mở đầu + xin phép ghi âm:** "Bọn mình đang tìm hiểu cách mọi người ghi chú và xem lại nội dung khi học, và muốn học từ trải nghiệm thật của bạn — không có đáp án đúng sai. Mình xin ghi âm chỉ để nghe lại, bóc transcript và phục vụ bài học, không chia sẻ công khai. Bạn đồng ý nhé?"
**[SỬA]** **Dừng lại, chờ user nói rõ "đồng ý"** rồi mới bấm record; nếu record đã chạy, xin user nhắc lại "Mình đồng ý ghi âm" trong bản ghi.

**Story opener:** "Kể mình nghe về **lần gần nhất** bạn ghi chú, highlight hoặc lưu một đoạn nội dung trong lúc học — lúc đó bạn đang học gì, lưu lại để làm gì?"

**Big 3** — **[SỬA]** mỗi lượt chỉ hỏi **một** câu, chờ user trả lời hết rồi mới hỏi câu kế

| # | Điều cần học | Câu hỏi (hỏi lần lượt từng câu) | Điều gì khiến xem lại giả thuyết |
|---|---|---|---|
| 1 | **(Đáng sợ)** Notes cũ có được mở lại để dùng không? | ① "Lần gần nhất bạn mở lại những gì mình đã lưu là khi nào?" ② "Lúc đó bạn mở ra để làm gì?" ③ "Bạn dùng được phần nào, phần nào không?" | Hiếm khi/không bao giờ mở lại → "AI tự sinh notes" không trúng job |
| 2 | Ghi chú tốn bao nhiêu công — **[SỬA]** cả lúc học **và sau buổi học** | ① "Lúc đó bạn đã làm gì để lưu lại?" ② "Sau buổi học, bạn làm gì tiếp với những note đó?" ③ "Lần gần nhất việc đó mất bao lâu, với khoảng bao nhiêu note?" | Ghi chú và tổng hợp nhẹ nhàng, ít phút → phần "tốn công" yếu đi |
| 3 | Có bỏ sót / không tìm lại được không? | ① "Lần gần nhất bạn cần lại một thông tin đã lưu, bạn tìm ở đâu?" ② "Mất bao lâu, có tìm ra không?" ③ "Có lần nào bạn không tìm ra hoặc quên mất một chỗ đã đánh dấu không? Khi đó bạn làm gì?" | Tìm lại được ngay, không bỏ sót → phần "rời rạc" không đứng |

**Probe bank:** "Chuyện gì xảy ra tiếp theo?" · "Bạn đã làm gì?" · "Vì sao chọn cách đó?" · "Phần nào khó nhất?" · "Đã thử cách nào khác chưa?" · "Việc đó kéo theo hậu quả gì?" · "Lần gần nhất trước đó là khi nào?"
**[SỬA]** Probe **bắt buộc** khi user nhắc tới chi phí ("mất thời gian", "thủ công", "khó"): *"Lần gần nhất mất bao lâu? Cụ thể bạn đã làm những bước nào?"*

**Ba phản xạ khi data lệch**

| User đưa ra | Phản xạ | Cách quay lại |
|---|---|---|
| Lời khen | Deflect | Cảm ơn ngắn rồi quay lại việc họ đang làm |
| Câu chung chung / hứa hẹn tương lai | Anchor | "Lần gần nhất chuyện đó xảy ra là khi nào?" |
| Ý tưởng / feature request | Dig | "Điều đó giúp bạn làm được gì? **Lần gần nhất gặp chuyện đó, bạn đã xử lý ra sao?**" — **[SỬA]** phải Dig trước khi kết thúc, không cảm ơn rồi dừng |

**Câu kết** — **[SỬA]** thay "Bạn còn cần điều gì nữa không?" bằng: *"Còn chuyện nào gần đây về việc ghi chú hay ôn lại bài mà mình chưa hỏi không?"*

**[SỬA] Cấm tuyệt đối:** "Nếu có một công cụ/tính năng… bạn có muốn không?" · "Bạn có muốn một công cụ nào khác…?" · nhắc AI Notes, tag "Chưa hiểu", ghi chú có cấu trúc.

**Đã sửa gì sau khi luyện**

| Chỗ sửa | Trước | Sau | Vì sao (dựa trên buổi luyện) |
|---|---|---|---|
| Big 3 #2 | Gộp 3 câu "đã làm gì / vì sao / phần nào khó" trong một lượt | Tách từng câu, hỏi lần lượt | [00:55–01:06] user phải hỏi lại "Chị có thể hỏi em kỹ hơn được không?" |
| Big 3 #2 | Chỉ hỏi chi phí **lúc ghi** | Thêm "Sau buổi học bạn làm gì với note?" + "mất bao lâu, bao nhiêu note" | Pain thật nằm ở **khâu gom note sau buổi học** [02:38], guide cũ không có câu nào chạm tới |
| Probe bank | Không có probe bắt buộc về chi phí | Probe bắt buộc "Lần gần nhất mất bao lâu?" | User nhắc "tốn thời gian" nhiều lần nhưng không đo được bao lâu |
| Cấm hỏi | Chỉ là checklist tự rà soát | Thành mục "Cấm tuyệt đối" ngay trong guide | [02:52–03:04] và [03:26–03:36] mình đã pitch công cụ và hỏi "bạn có muốn…" → câu trả lời không dùng được làm evidence |
| Câu kết + Dig | Kết bằng "còn điều gì quan trọng không" | Câu kết hỏi về quá khứ; phải Dig feature request trước khi dừng | [04:19–04:59] câu kết kéo ra feature request ("hỏi ngay tại chỗ note"), mình không Dig mà cảm ơn và kết thúc |
| Xin phép ghi âm | Hỏi "Bạn đồng ý nhé?" rồi đi tiếp | Chờ câu "đồng ý" rõ ràng | [00:29–00:31] user không nói rõ đồng ý |
| Recruitment | Chỉ check hành vi 7 ngày | Thêm check user đã biết solution chưa | [00:31–00:47] user nhắc "note line này", "tính năng này" → đã biết trước solution |

---

## 4. Practice Reflection

1. **Câu hỏi nào đã giúp user kể một tình huống cụ thể?**
   Story opener *"Kể mình nghe về lần gần nhất bạn ghi chú, highlight hoặc lưu một đoạn nội dung trong lúc học — lúc đó bạn đang học gì, lưu lại để làm gì?"* Nhờ neo vào "lần gần nhất", user kể được việc **hôm qua** học bài Product Discovery, ghi note theo từng slide cho thuật ngữ quan trọng và chỗ chưa hiểu, rồi sau buổi phải gom note từng slide vào một file chung — phần evidence rõ nhất của buổi.

2. **Chỗ nào mình cần làm tốt hơn ở lần phỏng vấn thật?**
   Lỗi lớn nhất: ở [02:52–03:04] mình **pitch solution và hỏi "bạn muốn có một cái công cụ để làm việc đấy không?"**, lặp lại ở [03:26–03:36] — nên các câu "em sẽ rất muốn/rất cần một công cụ" không dùng được làm evidence. Đáng lẽ khi user nói khâu gom note tốn thời gian, mình phải đào tiếp *"Lần gần nhất mất bao lâu? Sau đó bạn mở file tổng hợp lần nào chưa?"* — vì bỏ lỡ chỗ này nên Big 3 #1 (câu đáng sợ) vẫn chưa có câu trả lời. Ngoài ra mình gộp 3 câu hỏi vào một lượt khiến user phải hỏi lại, không chờ user nói rõ "đồng ý" ghi âm, và không Dig feature request cuối buổi.

3. **Sau khi luyện, nhóm đã sửa Conversation Guide ở đâu và vì sao?**
   - Tách Big 3 thành câu đơn, hỏi lần lượt — vì user bị rối khi nghe 3 câu gộp.
   - Mở rộng Big 3 #2 sang **khâu sau buổi học** và thêm probe bắt buộc về thời gian — vì pain thật user kể là gom note từng slide thành một file chung, guide cũ không có câu nào chạm tới.
   - Đưa các câu "bạn có muốn…/nếu có công cụ…" thành mục **cấm tuyệt đối** ngay trong guide — vì dù checklist đã có, lúc nói mình vẫn buột ra.
   - Thay câu kết bằng câu hỏi quá khứ và bắt buộc Dig feature request; chờ consent rõ ràng; check user đã biết solution chưa.

---

## 5. AI Support Log

| Chặng | AI đã giúp gì | Điểm sai / hời hợt | Mình đã tự sửa thế nào |
|---|---|---|---|
| 1 | Gợi ý cách reverse directive AI Notes thành capability trung tính; liệt kê các điều phải đúng / điều có thể bác bỏ giả thuyết; brainstorm Solution Parking Lot | Bản nháp đầu còn gắn với solution: các giả định như "highlight + unclear marks phản ánh đúng thứ cần ôn", "ghi chú AI tạo không đủ chất lượng" là giả định về **sản phẩm**, không phải về **problem**; Parking Lot ban đầu gần như toàn hướng AI | Tách các giả định về solution ra khỏi Problem Hypothesis, giữ pain ở dạng hành vi (tìm lại nguồn, đọc lại, bỏ sót) và không chứa tên feature; bổ sung các điều có thể bác bỏ dựa trên người dùng thật (không bao giờ mở lại notes, notes để chia sẻ cho nhóm); thêm 2 hướng không dùng AI vào Parking Lot |
| 2 | Gợi ý Big 3, story opener, probe bank và bảng ba phản xạ (Deflect / Anchor / Dig) | Câu hỏi AI gợi ý gộp nhiều ý trong một câu (vd Big 3 #2: "đã làm gì / vì sao / phần nào khó"); có câu hỏi ý kiến chung chung chưa neo vào "lần gần nhất"; một số câu vô tình nhắc tới highlight "Chưa hiểu" — lộ solution | Neo story opener và cả ba câu Big 3 vào "lần gần nhất"; bỏ mọi câu nhắc AI Notes / tag "Chưa hiểu" / ghi chú có cấu trúc; thêm câu hỏi "đáng sợ" (Big 3 #1) có thể làm giả thuyết yếu đi; câu gộp nhiều ý chỉ phát hiện ra sau buổi luyện → sửa ở bản cuối |
| 3 | Soạn kit phỏng vấn: kịch bản xin phép ghi âm, phân bổ 15 phút, cheat sheet probe/phản xạ, khung Interview Record; liệt kê kịch bản câu hỏi theo thứ tự | Phân bổ phút theo thứ tự Big 3 dễ khiến đọc bảng máy móc; giữ nguyên câu Big 3 #2 gộp 3 ý từ Chặng 2, không cảnh báo sẽ làm user rối | Phát hiện qua buổi luyện (user hỏi lại) → tách câu trong guide cuối |
| 4 | Chuyển bản ghi thành transcript (Whisper chạy local); điền `interview/notes.md` có mốc thời gian; chỉ ra câu dẫn dắt, consent chưa rõ; nháp Reflection và đề xuất sửa guide | Transcript tự động sai nhiều từ ("hy trú" = ghi chú, "bóp transcript" = bóc transcript…); quote đã được AI sửa theo ngữ cảnh nên có thể lệch lời gốc; đề xuất sửa guide là của AI, chưa phải quyết định nhóm | Nghe lại bản ghi để đối chiếu các quote chính trong `notes.md` với lời gốc; loại khỏi evidence các câu trả lời cho câu hỏi dẫn dắt; đối chiếu bảng "Đã sửa gì" với những gì nhóm chốt khi chia sẻ ở Chặng 4 |
