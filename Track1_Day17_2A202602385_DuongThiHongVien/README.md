# Track 1 — Day 17: Finding and Validating Pain Points

## 1. Thông tin cá nhân và nhóm

- Họ tên: Dương Thị Hồng Viên
- MHV: 2A202602385
- Tên nhóm: Học Có Dấu
- Thành viên: Dương Thị Hồng Viên (làm cá nhân)
- Case lựa chọn: B — AI Notes: Personal Learning Notes

Mình chọn B vì gần với việc học của mình và có thể tìm học viên đã lưu nội dung trong bảy ngày gần đây để nói chuyện. Mình muốn tìm hiểu phần ghi chú được dùng thế nào sau lúc học. Có ghi chú chưa chắc có nhu cầu dùng lại, và có nhu cầu dùng lại chưa chắc gặp khó khăn.

Các nhận định về học viên bên dưới đều là giả thuyết trước phỏng vấn.

## 2. Problem Hypothesis Brief — Chặng 1

### Solution

Directive nguyên văn:

> Trong khi học, học viên có thể highlight một đoạn nội dung, đánh dấu “Chưa hiểu”, hoặc viết một câu hỏi hay ghi chú ngắn. Khi bài học kết thúc, AI Notes kết hợp những dấu vết này với nội dung bài để tạo một bản ghi chú có cấu trúc. Học viên có thể chỉnh sửa và xác nhận trước khi lưu.

Capability trung tính: giúp học viên tập hợp, sắp xếp và kiểm tra phần nội dung muốn giữ lại từ bài học để dùng về sau.

### Change

Tập hợp nội dung đã đánh dấu → học viên kiểm tra, bổ sung phần còn thiếu → học viên mở lại khi cần và tìm đúng nội dung → tiếp tục ôn tập hoặc làm bài với ít công sức tra cứu hơn.

Ba thay đổi được kỳ vọng:

1. Học viên dành thời gian kiểm tra phần đã lưu sau bài học.
2. Học viên quay lại dùng phần đó khi có nhu cầu.
3. Nội dung đã lưu đủ dễ tìm và đủ ngữ cảnh để sử dụng.

Output là bản ghi chú được lưu. Outcome kỳ vọng là việc dùng lại kiến thức thuận lợi hơn. Nếu học viên không mở lại hoặc vẫn phải tìm từ đầu, output chưa tạo được outcome này.

### Actor

| Actor | Họ đang làm gì? | Pain hoặc hậu quả có thể có | Lợi ích có thể có |
| --- | --- | --- | --- |
| Học viên | Theo dõi bài, lưu và dùng lại kiến thức | Mất nhịp khi ghi; khó tìm hoặc áp dụng nội dung khi xem lại | Giữ và dùng lại nội dung thuận lợi hơn |
| Bạn cùng nhóm | Trao đổi kiến thức để làm bài chung | Phải tìm tài liệu hoặc giải thích lại cho nhau | Có nội dung và ngữ cảnh để trao đổi |
| Coach/giảng viên | Hỗ trợ học viên học và làm bài | Phải giải thích lại; khó biết học viên vướng ở đâu | Có thể nhận câu hỏi cụ thể hơn từ học viên |

Mình ưu tiên học viên, ở thời điểm cần dùng lại nội dung để làm bài. Đây là người trực tiếp thực hiện hành vi đang được giả định và có thể tiếp cận trong giờ lab. Các actor khác được giữ lại nhưng chưa điều tra trước. Khó khăn lúc đang ghi chú cũng là nhánh khác, chưa loại bỏ.

### Situation & Job

Tình huống giả định: gặp yêu cầu trong bài thực hành → cần kiến thức từ bài trước → tìm trong phần đã lưu hoặc mở bài gốc → có thể vướng ở bước tìm đúng đoạn hay hiểu cách áp dụng.

Khi làm bài thực hành cần kiến thức từ bài trước, học viên đang cố tìm và sử dụng đúng nội dung để làm tiếp bằng cách xem phần đã lưu hoặc tra lại bài học. Các cách hiện tại này cần được kiểm tra, chưa phải hành vi đã quan sát.

JTBD Hypothesis:

> Khi làm bài thực hành cần dùng kiến thức đã học, tôi muốn tìm lại đúng phần liên quan và hiểu cách áp dụng, để có thể tiếp tục hoàn thành bài.

### Pain — Hai cách giải thích cạnh tranh

**A — Khó tìm lại:** Khi làm bài thực hành cần kiến thức từ bài trước, học viên khó tìm đúng nội dung đã lưu vì nội dung nằm ở nhiều nơi hoặc khó nhận biết, dẫn đến phải tìm qua nhiều nguồn và gián đoạn việc làm bài.

**B — Tìm thấy nhưng chưa dùng được:** Trong cùng tình huống, học viên khó áp dụng phần đã lưu vì thiếu ví dụ hoặc ngữ cảnh giải thích, dẫn đến phải đọc lại bài gốc hoặc nhờ người khác giải thích.

Mình chọn A để điều tra trước vì có thể hỏi rõ trình tự tìm kiếm. B là cách giải thích cạnh tranh cho cùng hành vi mở lại bài. Một khả năng nữa là cách hiện tại đã đáp ứng tốt và không có pain đáng kể.

### Evidence Map

| Cần kiểm tra | Evidence làm mình tin hơn | Evidence làm mình nghi ngờ hoặc bác bỏ |
| --- | --- | --- |
| Situation có thật | Kể được lần gần đây cần nội dung đã học để làm bài, có trình tự cụ thể | Chưa cần dùng lại; chỉ nói chung |
| Pain có ý nghĩa | Đã tìm nhiều nơi, không tìm ra và phải đổi cách làm | Tìm đúng ngay; tra cứu thuận tiện |
| Workaround tồn tại | Đã đặt tên, gom file, tạo mục lục hoặc hỏi bạn để tìm lại | Cách lưu hiện tại đủ dùng, không cần xử lý thêm |
| Consequence tồn tại | Phải dừng bài, làm thêm bước hoặc nhờ người khác do tìm không ra | Việc tìm kiếm không ảnh hưởng đáng kể |
| Pattern có lặp | Kể được lần khác có khó khăn tương tự | Sự cố riêng lẻ, chẳng hạn quên lưu một lần |

Problem Hypothesis mang sang Chặng 2:

> Khi làm bài thực hành cần dùng lại kiến thức từ bài trước, một số học viên VLearn khó tìm đúng nội dung đã lưu vì cách lưu và sắp xếp khiến việc tra cứu mất công, dẫn đến gián đoạn việc hoàn thành bài.

Giả thuyết cần bốn điều đúng: có nhu cầu dùng lại; khó khăn nằm ở bước tìm; cách lưu có liên quan; việc tìm kiếm gây ảnh hưởng đủ đáng kể. Mình sẽ sửa hoặc bỏ giả thuyết nếu người học tìm dễ dàng, ít cần mở lại, chủ động dùng bài gốc hiệu quả, hoặc khó khăn chính nằm ở hiểu kiến thức.

### Solution Parking Lot

| Hướng giải quyết có thể có | AI / Không AI |
| --- | --- |
| Mẫu ghi chú có nội dung chính, ví dụ và câu hỏi còn lại | Không AI |
| Gắn ghi chú với đúng bài và slide gốc | Không AI |
| Tìm kiếm từ khóa trong ghi chú cá nhân | Không AI |
| Học viên tự đặt nhãn và gom ghi chú | Không AI |
| Gợi ý nhóm phần đã lưu theo chủ đề để học viên kiểm tra | AI |
| Gợi ý phần đã lưu liên quan đến câu hỏi đang làm | AI |

Các hướng này được park lại, chưa chọn triển khai.

## 3. Conversation Guide — Chặng 2

Phiên bản: v2, chỉnh theo kịch bản mô phỏng trong interview/simulation.md. Chưa phải bản cuối sau phỏng vấn thực tế.

### Big 3

| Điều cần học | Evidence cần tìm | Điều khiến mình xem lại giả thuyết |
| --- | --- | --- |
| 1. Lưu để làm gì và có dùng lại không? | Một lần lưu, mục đích lúc lưu và hành vi dùng lại | Ghi chú chỉ giúp nhớ lúc học; không có nhu cầu xem lại |
| 2. Khi cần dùng, tìm và xử lý thế nào? | Trình tự tìm, nơi đã mở, bước phát sinh, workaround | Tìm được ngay; vướng ở hiểu hoặc áp dụng |
| 3. Cách hiện tại ảnh hưởng gì đến việc đang làm? | Kết quả công việc, bước phải làm thêm và hậu quả thực tế | Cách hiện tại đáp ứng tốt; chỉ là bất tiện nhỏ |

Điều 3 là câu hỏi “đáng sợ”: câu trả lời có thể cho thấy pain mình chọn không đáng giải.

### Recruitment check

Cần nói chuyện với học viên ngoài nhóm đã ghi chú, highlight hoặc lưu nội dung để xem sau trong bảy ngày gần đây. Không yêu cầu họ phải gặp khó khăn hay đã dùng lại.

“Trong bảy ngày vừa rồi, bạn có ghi chú, highlight hoặc lưu phần nào của bài học để xem sau không? Đó là bài nào?”

Câu tuyển người không được tính là evidence chính. Nếu không phù hợp, báo giảng viên để đổi cặp.

### Mở đầu và xin phép ghi âm

“Mình là Viên. Mình đang làm bài thực hành tìm hiểu cách học viên ghi lại và dùng lại nội dung trên VLearn. Mình muốn nghe một lần bạn đã trải qua gần đây, khoảng 15 phút. Mình xin phép ghi âm để nghe lại, bóc transcript nếu cần và phục vụ bài học; bản ghi chỉ dùng cho việc đó, không chia sẻ công khai. Bạn có đồng ý không?”

Chỉ bắt đầu ghi sau khi được đồng ý.

### Story opener

“Kể mình nghe lần gần nhất bạn ghi chú hoặc lưu một phần bài học để xem sau nhé. Lúc đó bạn đang học bài gì?”

### Ba câu hỏi chính

| Điều cần học | Câu hỏi |
| --- | --- |
| 1. Mục đích và việc dùng lại | “Lúc đó bạn lưu phần này để làm gì?” Sau khi nghe: “Từ lúc lưu đến giờ, bạn đã mở lại phần đó chưa?” |
| 2. Cách tìm và xử lý | Nếu có dùng lại: “Kể mình nghe lần gần nhất bạn dùng phần đó, từ lúc cần đến lúc sử dụng. Bạn làm gì đầu tiên?” |
| 3. Ảnh hưởng thực tế | “Sau khi xem lại phần đó, việc bạn đang làm tiếp tục như thế nào?” Nếu có bước phát sinh: “Bước đó ảnh hưởng gì đến việc bạn đang làm?” |

Nếu chưa dùng lại: “Từ lúc lưu đến giờ, đã có lúc nào bạn cần nội dung đó chưa?” Nếu có nhưng dùng cách khác: “Lần đó bạn làm thế nào?” Nếu chưa có nhu cầu, ghi nhận và tìm hiểu tiếp việc lưu; không ép có câu chuyện về khó khăn.

### Probe bank

- “Lúc đó chuyện gì xảy ra tiếp theo?”
- “Bạn đã làm gì?”
- “Bạn đã mở hoặc tìm ở đâu?”
- “Vì sao lúc đó bạn chọn cách này?”
- “Bạn nói ‘mất công’, cụ thể bạn đã phải làm thêm gì?”
- “Bạn đã thử cách nào khác trong lần đó?”
- “Bạn có nhớ khoảng bao lâu không?” — chỉ hỏi khi có bước cụ thể, không ép ước lượng.
- “Bạn có thể cho mình xem phần đã lưu không, nếu tiện?”
- “Lần gần nhất trước đó là khi nào?”

### Khi câu trả lời lệch

| User đưa ra | Phản xạ | Cách quay lại câu chuyện |
| --- | --- | --- |
| Lời khen | Deflect | “Cảm ơn bạn. Quay lại lần đó nhé, sau khi lưu bạn làm gì tiếp?” |
| Nhận xét chung hoặc lời hứa | Anchor | “Lần gần nhất chuyện đó xảy ra là khi nào?” |
| Ý tưởng hoặc feature request | Dig | “Bạn đang nghĩ đến lần nào cần làm việc đó? Lần ấy bạn đã xử lý ra sao?” |

### Tự rà soát và phân công

Guide hỏi sự kiện gần đây, nối với Big 3, cho phép evidence trái giả thuyết và không nhắc solution với interviewee. Tiêu chí tuyển không mặc định phải có pain.

| Interviewer | Người ngoài nhóm được phỏng vấn | Đáp ứng tiêu chí |
| --- | --- | --- |
| Dương Thị Hồng Viên | Chưa xác nhận | Chưa xác nhận |

### Revision Log sau luyện

Chưa có bản ghi để xác định sửa đổi sau luyện. Việc rà câu hỏi trên giấy không được coi là revision dựa trên phỏng vấn.

| Câu trước luyện | Sự kiện trong bản ghi và mốc thời gian | Câu sửa và lý do |
| --- | --- | --- |
| “Ghi chú ở nhiều nơi làm bạn tìm khá mất thời gian đúng không?” | Trong mô phỏng, P01 nói tìm Docs nhanh, khó ở áp dụng. | “Sau khi tìm được đoạn đó, bạn làm gì tiếp?” Bỏ gợi ý nguyên nhân và cho user kể hành vi. |
| “Bạn có nhớ khoảng bao lâu không?” | Nhân vật gộp thời gian xem lại với hỏi bạn. | Hỏi rõ từng bước trước; chỉ giữ thời lượng như ước lượng của người trả lời, không quy toàn bộ cho tìm kiếm. |

## 4. Practice Reflection — Chặng 4

Phân tích luyện tập dưới đây dựa trên hội thoại mô phỏng, không phải reflection từ việc mình tự nghe lại một cuộc phỏng vấn thật.

1. Trong kịch bản, câu “Bạn kể từ lúc cần dùng đến lúc dùng được nhé. Bạn làm gì đầu tiên?” mở được trình tự từ tìm Docs đến nhờ bạn kiểm tra. Nhờ vậy phân biệt được tìm lại và áp dụng.
2. Câu “Ghi chú ở nhiều nơi làm bạn tìm khá mất thời gian đúng không?” gán sẵn nguyên nhân. Điểm cần luyện là chờ user kể hết bước tiếp theo, không suy ra pain chỉ từ việc họ lưu ở nhiều nơi.
3. Guide bỏ câu xác nhận có sẵn kết luận, thay bằng “Sau khi tìm được đoạn đó, bạn làm gì tiếp?”. Bổ sung probe “Bước nào giúp bạn làm tiếp được?” để làm rõ điều thực sự giải quyết vướng mắc.

Đây là bài luyện kỹ năng; chưa có kết luận validated.

## 5. AI Support Log

Mình dùng ChatGPT để hỗ trợ soạn bản nháp giả thuyết, Conversation Guide, rà câu hỏi dẫn dắt và tổ chức file bài làm.

Các điểm bản AI ban đầu cần xem lại: dễ mặc định người ghi chú gặp khó khăn khi dùng lại; đề xuất thời lượng 10–12 phút thay vì 15 phút; dễ nhầm bản rà trên giấy với guide cuối sau luyện. Bản hiện tại đã sửa thời lượng và bổ sung nhánh chưa dùng lại, tìm dễ dàng, hoặc khó khăn nằm ở áp dụng. Đây là các sửa đổi trong quá trình hỗ trợ bằng AI, chưa phải sửa đổi do mình tự nghe bản ghi.

AI đã tạo thêm hội thoại mô phỏng, notes và phân tích cách hỏi để luyện tập. P01, hành vi và lời thoại đều giả định. Phần mô phỏng không thay thế Interview Record, consent, bản ghi và Practice Reflection từ lượt phỏng vấn thật.
