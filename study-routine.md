# Khung chương trình “AI Productivity 0–100” cho hocmay.app: ChatGPT + NotebookLM/Gemini Notebook

## Định hướng chương trình và trạng thái công cụ đến tháng 11/2026

Mục tiêu phù hợp nhất cho hocmay.app không nên là một khóa “học prompt” đơn thuần, mà là khóa **AI literacy + AI workflow** dành cho người không lập trình. Người học cần đi từ việc hiểu AI có thể và không thể làm gì, biết giao việc rõ ràng, biết kiểm tra đầu ra, cá nhân hóa ChatGPT, tổ chức công việc bằng Projects, biến kế hoạch thành lịch nhắc hoặc tác vụ chạy thực sự, rồi sử dụng NotebookLM để nghiên cứu tài liệu có căn cứ. Cách tiếp cận này phù hợp với tài liệu hiện tại của OpenAI Academy: prompting chỉ là một phần của thói quen làm việc gồm cung cấp ngữ cảnh, đánh giá đầu ra và xây dựng workflow lặp lại. citeturn513460search4turn477738search3

Một thay đổi quan trọng cần phản ánh trong khóa học: **NotebookLM đã được Google đổi tên thành “Gemini Notebook” vào ngày 16/7/2026**. Vì “NotebookLM” vẫn là tên người dùng quen thuộc, hocmay.app có thể đặt tên bài học là **“NotebookLM / Gemini Notebook”**, nhưng giao diện và tài liệu chính thức mới sử dụng Gemini Notebook.

Tại thời điểm kiểm chứng ngày **24/11/2026**, ChatGPT Projects có trên các gói đủ điều kiện, Custom Instructions có trên mọi gói, còn Memory, apps và một số khả năng tự động hóa phụ thuộc gói, khu vực, nền tảng và thiết lập workspace. OpenAI nhấn mạnh rằng nếu một tùy chọn Memory không xuất hiện thì có thể tài khoản hoặc khu vực đó chưa được hỗ trợ.

Đặc biệt, khóa học phải dạy rõ ba khái niệm thường bị người mới nhầm:

**Kế hoạch do AI viết ra** chỉ là văn bản. Ví dụ “8:00 đọc email, 9:00 học tiếng Anh” không có nghĩa ChatGPT sẽ tự thực hiện hoặc nhắc người dùng. **Scheduled Tasks** là tính năng thực sự chạy một lần hoặc lặp lại theo lịch và có thể gửi thông báo. **Calendar integration** là kết nối với một dịch vụ lịch bên ngoài; khả năng đọc hoặc ghi phụ thuộc app, quyền OAuth, gói, khu vực và workspace.

Tôi đề xuất chương trình tổng cộng **khoảng 30 giờ**, chia thành **6 tuần**, trong đó **0–90 là cốt lõi cho mọi người mới** và **90–100 là phần nâng cao/tổng hợp tùy chọn**. Không yêu cầu kiến thức lập trình.

## Lộ trình học từ 0 đến 100

| Mức | Module | Kết quả đo được | Thời lượng đề xuất | Loại |
|---|---|---|---:|---|
| 0–10 | AI Foundations & Responsible Use | Phân biệt AI, chatbot, search, source-grounded AI; nhận biết ít nhất 5 loại lỗi AI | 2 giờ | Cốt lõi |
| 10–30 | Effective Prompting | Viết prompt theo cấu trúc Task–Context–Constraints–Output–Check; cải thiện prompt qua ≥3 vòng lặp | 5 giờ | Cốt lõi |
| 30–45 | Verification & Hallucination Control | Kiểm tra claim, citation, số liệu, độ mới; xây verification checklist | 3 giờ | Cốt lõi |
| 45–60 | Personalization & Projects | Thiết lập Custom Instructions, Memory hợp lý và một Project hoàn chỉnh | 4 giờ | Cốt lõi |
| 60–75 | Daily Planning, Tasks & Calendar | Lập kế hoạch ngày; phân biệt plan/task/calendar; tạo recurring task thật nếu tài khoản hỗ trợ | 4 giờ | Cốt lõi |
| 75–90 | NotebookLM / Gemini Notebook | Tạo notebook đa nguồn; hỏi đáp bằng citation; tạo report, quiz, flashcards, mind map và kiểm chứng nguồn | 5 giờ | Cốt lõi |
| 90–100 | Integrated AI Workflow & Capstone | Kết hợp Gemini Notebook → ChatGPT → Project → Scheduled Task/Calendar thành workflow hoàn chỉnh | 7 giờ | Nâng cao/tổng hợp |

Một lịch học dễ duy trì là **4 buổi/tuần × 60–75 phút trong 6 tuần**, cộng một dự án cuối khóa. Không nên dạy toàn bộ tính năng trong tuần đầu; OpenAI Academy cũng khuyến nghị xây các thói quen prompting và review trước, sau đó mới chuyển sang workflow lặp lại và agentic work. citeturn477738search3

**Tuần 1** nên hoàn thành 0–20: hiểu AI và prompt cơ bản. **Tuần 2** đi từ 20–45: prompting nâng cao vừa đủ và verification. **Tuần 3** đi từ 45–60: personalization và Projects. **Tuần 4** đi từ 60–75: planning, Scheduled Tasks và Calendar. **Tuần 5** dành cho Gemini Notebook 75–90. **Tuần 6** dành cho workflow tích hợp và capstone 90–100.

Các mốc không nên chỉ là “đã xem video”. Một người đạt mức **30** phải có khả năng biến một yêu cầu mơ hồ thành một prompt tốt; mức **60** phải có một môi trường ChatGPT được cá nhân hóa và Project tái sử dụng được; mức **90** phải nghiên cứu một bộ tài liệu bằng Gemini Notebook và kiểm tra citation; mức **100** phải xây được một workflow AI hoàn chỉnh có đầu vào, bước kiểm chứng, đầu ra và automation rõ ràng.

## Nội dung từng module và tài liệu tiếng Anh

### AI Foundations & Responsible Use — mức 0–10

Người học trước tiên cần hiểu rằng mô hình ngôn ngữ tạo câu trả lời dựa trên mẫu học được và **có thể tạo thông tin sai nhưng nghe rất thuyết phục**. OpenAI gọi hiện tượng này là hallucination và khuyến nghị không dùng ChatGPT như nguồn cuối cùng cho thông tin quan trọng. Search, Deep Research và Data Analysis có thể cải thiện khả năng kiểm chứng nhưng không làm sai số biến mất hoàn toàn. citeturn489136search2turn489136search3

Bài thực hành đầu tiên nên rất đời thường: yêu cầu ChatGPT lập danh sách mua đồ, tóm tắt một đoạn văn, giải thích một khái niệm, rồi yêu cầu người học đánh dấu đâu là **fact**, đâu là **recommendation**, đâu là **assumption**. Sau đó cho một câu hỏi có ngày tháng hoặc số liệu và yêu cầu người học kiểm chứng bằng nguồn gốc.

Tài liệu nên dùng:

**OpenAI Academy — OpenAI Academy**  
Publisher: OpenAI · Free · Beginner  
https://academy.openai.com/en  
Đây là nguồn đào tạo chính thức, hướng đến kỹ năng sử dụng AI trong công việc, prompting, review và workflow.

**Does ChatGPT tell the truth? — OpenAI Help Center**  
Publisher: OpenAI · Free · Beginner  
https://help.openai.com/en/articles/8313428-does-chatgpt-tell-the-truth  
Nguồn rất phù hợp để dạy hallucination, độ tin cậy, knowledge cutoff và verification.

**Understanding Hallucinations for Federal Workers — OpenAI Academy**  
Publisher: OpenAI · Free · Beginner–Intermediate  
https://academy.openai.com/public/clubs/government/videos/understanding-hallucinations-for-federal-workers-2026-08-06  
Dù tiêu đề hướng đến nhân viên chính phủ, nội dung về kiểm tra nguồn và xác minh thông tin áp dụng rộng rãi.

**Google AI Essentials — Grow with Google**  
Publisher: Google · Nội dung giới thiệu miễn phí; khóa đầy đủ qua nền tảng đào tạo/Coursera có thể phát sinh phí · Beginner  
https://grow.google/ai-essentials/  
Google mô tả khóa này dành cho người mới, có module về AI fundamentals, productivity, prompting và responsible use.

### Effective Prompting & Verification — mức 10–45

Đây nên là phần lớn nhất của nền móng khóa học. Một framework dễ dạy cho hocmay.app là:

> **Task → Context → Constraints → Examples → Output → Check**

**Task**: AI phải làm gì.  
**Context**: thông tin nền cần biết.  
**Constraints**: giới hạn về phạm vi, độ dài, đối tượng, nguồn, điều không được làm.  
**Examples**: ví dụ đầu vào/đầu ra mong muốn khi cần.  
**Output**: cấu trúc câu trả lời như bảng, checklist, email, outline.  
**Check**: yêu cầu AI chỉ ra giả định, phần chưa chắc chắn và những claim cần xác minh.

Khung này tương thích trực tiếp với tài liệu OpenAI Academy. Tài liệu prompting của OpenAI nhấn mạnh ba bước căn bản: nói rõ nhiệm vụ, cung cấp context hữu ích và mô tả đầu ra lý tưởng; tài liệu “Power Prompting” mở rộng thành role, task, context, output, limits và check.

Ví dụ tiến trình thực hành:

Prompt yếu:

> “Help me study English.”

Prompt tốt hơn:

> “Create a 30-minute English study session for a Vietnamese beginner.”

Prompt có cấu trúc:

> “Task: Create a 30-minute English practice session.  
> Context: The learner is Vietnamese, CEFR A2, weak at listening.  
> Constraints: No more than 10 new words; explanations must use simple English.  
> Output: 5-minute warm-up, 10-minute vocabulary section, 10-minute listening-style exercise, 5-minute quiz.  
> Check: At the end, list which assumptions you made about the learner.”

Một kỹ năng quan trọng không kém là **iteration**. Người học không cần cố tìm “prompt hoàn hảo” ngay lần đầu. OpenAI khuyến nghị điều chỉnh yêu cầu trong cùng cuộc hội thoại nếu câu trả lời đầu tiên chưa phù hợp.

hocmay.app nên dạy mô hình vòng lặp:

**Prompt → Inspect → Critique → Refine → Verify → Save reusable version.**

Bài thực hành nên yêu cầu người học chấm chính đầu ra theo rubric như Accuracy, Relevance, Completeness, Format và Evidence, rồi viết prompt vòng hai dựa trên điểm yếu.

Ví dụ:

> “Evaluate your previous response using these criteria: factual accuracy, relevance, completeness, clarity and evidence. Score each criterion from 1–5. Identify the three weakest points. Then produce a revised version.”

Về hallucination, một quy trình kiểm chứng thực tế nên gồm bốn tầng: kiểm tra xem câu trả lời có chứa fact hay chỉ là gợi ý; yêu cầu nguồn khi cần; mở nguồn và kiểm tra nguồn có thực sự nói điều AI tuyên bố hay không; đối chiếu với nguồn chính thức hoặc nguồn độc lập thứ hai đối với quyết định quan trọng. OpenAI đặc biệt khuyến nghị kiểm tra quotes, số liệu, tài liệu kỹ thuật và external references thay vì tin vào độ tự tin của mô hình.

Tài liệu nên dùng:

**Prompting — OpenAI Academy**  
Publisher: OpenAI · Free · Beginner  
https://academy.openai.com/en/public/clubs/work-users-ynjqu/resources/prompting  
Nội dung cập nhật tháng 9/2026, rất phù hợp làm tài liệu chính.

**Power Prompting — OpenAI Academy**  
Publisher: OpenAI · Free · Beginner–Intermediate  
https://academy.openai.com/en/public/clubs/news-organizations-b9osl/videos/power-prompting-2026-07-07  
Có khung role–task–context–output–limits–check.

**Google Prompting Essentials — Grow with Google**  
Publisher: Google · Khóa học qua Coursera, có thể yêu cầu trả phí/subscription; hỗ trợ financial aid tùy nền tảng · Beginner–Intermediate  
https://grow.google/intl/en_sg/prompting-essentials/  
Google mô tả chương trình này bằng quy trình 5 bước và hướng đến sử dụng AI trong công việc thực tế.

**Google Prompting Essentials — Coursera**  
Publisher: Google / Coursera · Paid/subscription, financial aid có thể khả dụng · Beginner–Intermediate  
https://www.coursera.org/specializations/prompting-essentials-google  
Chương trình gồm nhiều khóa, từ prompt cơ bản đến prompt chaining và kỹ thuật nâng cao.

### Personalization & Projects — mức 45–60

Phần này nên dạy người học rằng **prompt trong chat, Custom Instructions, Memory và Project Instructions giải quyết bốn vấn đề khác nhau**.

**Prompt trong chat** dùng cho yêu cầu tức thời. **Custom Instructions** là các hướng dẫn người dùng chủ động định nghĩa để ChatGPT áp dụng rộng hơn. **Memory** là cơ chế cá nhân hóa dựa trên thông tin có liên quan từ những nguồn mà tài khoản cho phép. **Project Instructions** chỉ áp dụng trong một Project và ghi đè global Custom Instructions khi làm việc trong Project đó.

Custom Instructions hiện được OpenAI công bố là có trên tất cả các gói, web, desktop, iOS và Android. Giới hạn công bố hiện tại là 1.500 ký tự cho Free/Go và 5.000 ký tự cho Plus, Pro, Enterprise, Business và Education.

Một bài thực hành tốt là yêu cầu người học tạo Custom Instructions với bốn nhóm:

> “About me: my role, skill level and typical tasks.  
> How I want answers: language, tone and depth.  
> Defaults: units, date format, preferred structure.  
> Quality rules: identify assumptions, distinguish fact from recommendation, cite sources when browsing.”

Sau đó phải kiểm tra bằng ba prompt khác nhau xem AI có áp dụng nhất quán hay không.

Memory cần được dạy thận trọng hơn. OpenAI nói rõ khả năng và nguồn của Memory có thể khác nhau theo **plan, region, platform và workspace**; người dùng nên kiểm tra Settings → Personalization → Memory thay vì giả định mọi tài khoản có giao diện giống nhau.

Projects là nơi phù hợp để dạy người học chuyển từ “chat rời rạc” sang “AI workspace”. Project có thể chứa chats, files, project instructions và một số nguồn được kết nối; ChatGPT dùng ngữ cảnh đó cho công việc liên tục. File limit công bố hiện tại là Free 5 file/project, Go/Plus 25 và Edu/Pro/Business/Enterprise 40.

Bài thực hành bắt buộc:

Tạo Project tên **“My Weekly Learning System”**, thêm một syllabus hoặc tài liệu PDF, viết Project Instructions, tạo ít nhất ba chat riêng: “Weekly plan”, “Study notes”, “Review & reflection”, rồi lưu một câu trả lời tốt thành project source.

Tài liệu chính:

**ChatGPT Custom Instructions — OpenAI Help Center**  
https://help.openai.com/en/articles/8096356-chatgpt-custom-instructions  
Publisher: OpenAI · Free · Beginner.

**Memory in ChatGPT — OpenAI Help Center**  
https://help.openai.com/en/articles/8590148-memory-in-chatgpt  
Publisher: OpenAI · Free · Beginner–Intermediate.

**Projects in ChatGPT — OpenAI Help Center**  
https://help.openai.com/en/articles/10169521-projects-in-chatgpt  
Publisher: OpenAI · Free to access; feature limits vary by ChatGPT plan · Beginner–Intermediate.

**Customizing ChatGPT — OpenAI Academy**  
https://academy.openai.com/en/public/clubs/work-users-ynjqu/resources/customizing-chatgpt  
Publisher: OpenAI · Free · Beginner–Intermediate; cập nhật tháng 10/2026.

## Daily planning, Tasks, Calendar và workflow thật — mức 60–75

Đây là module hocmay.app nên làm tốt hơn đa số khóa prompting hiện nay, vì rất nhiều nội dung trên mạng đánh đồng “AI lập lịch” với “AI tự chạy theo lịch”.

Một prompt như:

> “Plan my day tomorrow from 8 AM to 6 PM.”

chỉ tạo ra **kế hoạch dạng văn bản**. Nó không tự đặt lịch, không tự nhắc và không tự chạy lại vào hôm sau.

Một prompt lập kế hoạch chuẩn nên yêu cầu AI cân nhắc priority, deadline, energy level, duration và buffer:

> “Help me plan today from 8:00 to 18:00.  
> Tasks: [list].  
> Rank them by urgency and importance first.  
> Create time blocks with at least 15 minutes of buffer every two hours.  
> Do not schedule more than 90 minutes of deep work continuously.  
> Output a table with Time, Task, Purpose and Done criteria.  
> After the table, identify what should be postponed if I fall one hour behind.”

Sau đó người học phải học cách chuyển **plan → execution system**.

ChatGPT hiện có **Scheduled Tasks**, có thể chạy một lần hoặc định kỳ, gửi thông báo và trong một số trường hợp theo dõi thay đổi. OpenAI công bố giới hạn active tasks hiện tại là 3 cho Free/Go, 5 cho Plus, 10 cho Business/Edu và 15 cho Pro/Enterprise. Free chỉ có thể đặt task một lần hoặc recurring tối đa một lần/ngày trong các khoảng thời gian linh hoạt; exact delivery time và tần suất tới mỗi giờ yêu cầu gói paid đủ điều kiện. citeturn477738search2

Ví dụ Scheduled Task:

> “Every weekday morning, remind me to review my three most important goals for the day.”

Hoặc:

> “Every Sunday evening, ask me to review what I completed this week and prepare the top five priorities for next week.”

Phần khóa học phải yêu cầu học viên **xác nhận trong giao diện Scheduled rằng task thực sự tồn tại**. Nếu chỉ nhận được một câu trả lời như “Đây là lịch của bạn”, bài thực hành chưa đạt.

OpenAI cũng hỗ trợ event-triggered tasks trong Work cho các app đủ điều kiện như Gmail, Slack hoặc GitHub. Chúng khác với time-based scheduling vì được kích hoạt bởi sự kiện của app; hiện Free/Go không được tạo event-triggered tasks.

Calendar cũng phải tách riêng. Connected apps cho phép ChatGPT truy cập các dịch vụ như Google Calendar hoặc Outlook Calendar tùy plan, region, app, permissions và workspace settings. Với Outlook, tài liệu hiện tại liệt kê cả khả năng đọc availability và một số write actions tùy quyền; Google Calendar cũng có các OAuth scopes riêng cho calendar events.

Do đó, hocmay.app nên dùng quy tắc:

**AI-generated schedule ≠ Scheduled Task ≠ Calendar event.**

Bài kiểm tra module này nên cho ba tình huống và yêu cầu học viên chọn đúng công cụ:

“Giúp tôi sắp thứ tự công việc hôm nay” → planning prompt.  
“Nhắc tôi mỗi tối lúc 21:00” → Scheduled Task nếu tài khoản hỗ trợ.  
“Thêm cuộc họp với A vào Google Calendar” → Calendar integration/action nếu quyền và app hỗ trợ.

Tài liệu:

**Scheduled tasks in ChatGPT — OpenAI Help Center**  
https://help.openai.com/en/articles/10291617-scheduled-tasks-in-chatgpt  
Publisher: OpenAI · Feature availability varies by plan/account/workspace · Intermediate.

**Connected apps in ChatGPT — OpenAI Help Center**  
https://help.openai.com/en/articles/11487775-connected-apps-in-chatgpt  
Publisher: OpenAI · Availability varies · Intermediate.

**Outlook Email and Calendar apps in ChatGPT — OpenAI Help Center**  
https://help.openai.com/en/articles/12512241-outlook-email-and-calendar-apps-in-chatgpt  
Publisher: OpenAI · Availability varies · Intermediate.

## NotebookLM / Gemini Notebook — mức 75–90

Mô hình mental model nên dạy là: **ChatGPT là trợ lý tổng quát; Gemini Notebook là môi trường nghiên cứu “source-grounded” xoay quanh bộ tài liệu mà người dùng cung cấp**.

Gemini Notebook hiện hỗ trợ nhiều loại nguồn, gồm PDF, DOCX, TXT, Markdown, CSV, PowerPoint, Google Docs, Slides, Sheets, web URL, YouTube public videos, audio, images, ePub và một số Google Play Books. Mỗi source có thể tới 500.000 words hoặc 200 MB đối với local uploads; Standard hiện hỗ trợ tối đa 50 sources/notebook. citeturn280349search0turn524775search2

Khác biệt lớn nhất nên được dạy là **citation-grounded Q&A**. Chat trong Gemini Notebook sử dụng nguồn của notebook để trả lời và tạo inline citations; người dùng có thể chọn citation để xem passage tương ứng trong ngữ cảnh. Google cũng nói rõ rằng nếu thông tin không có trong nguồn thì Notebook được thiết kế để không tự tìm câu trả lời ngoài phạm vi nguồn.

Bài thực hành chuẩn:

Tải lên ba tài liệu nói về cùng một chủ đề. Sau đó hỏi:

> “Based only on the selected sources, explain the three main conclusions. For every conclusion, cite the supporting passages. If two sources disagree, show the disagreement instead of resolving it yourself.”

Sau đó:

> “Create a claim-evidence table with columns: Claim, Supporting Source, Evidence, Confidence, Contradicting Source.”

Người học phải **click vào citation**, đọc đoạn gốc và tự xác nhận câu trả lời có phản ánh đúng nguồn hay không. Citation là đường dẫn kiểm chứng, không phải bằng chứng rằng AI chắc chắn đã diễn giải đúng.

Gemini Notebook hiện có một Studio khá rộng: Reports, Audio Overviews, Video Overviews, Mind Maps, Data Tables, Flashcards, Quizzes, Slide Decks, Infographics và các loại output khác. 

Các tính năng học tập đã được Google mở rộng mạnh trong năm 2026. Flashcards và Quizzes hỗ trợ tùy chỉnh difficulty, theo dõi câu làm đúng/sai, review/retake và giải thích đáp án. Google cũng đã giới thiệu Interactive Learning Overviews và các quiz format như short answer, multi-select và fill-in-the-blank.

Audio Overview không nên được dạy như “podcast đúng 100%”. Google cảnh báo chúng là AI-generated và có thể có inaccuracies hoặc audio glitches. Hiện có các format như Deep Dive, Brief, Critique và Debate, với customization về focus, language và một số tùy chọn length.

Bài thực hành từ dễ đến khó:

**Level 1:** một PDF → tóm tắt + hỏi 5 câu có citation.

**Level 2:** ba nguồn → so sánh quan điểm và tìm mâu thuẫn.

**Level 3:** tạo Study Guide, Mind Map, Flashcards và Quiz.

**Level 4:** tạo Audio Overview, nghe lại rồi kiểm tra ba claim bằng source citations.

**Level 5:** 10–20 nguồn → tạo synthesis report và evidence matrix.

Tài liệu:

**Learn about Gemini Notebook — Google Help**  
https://support.google.com/gemininotebook/answer/16164461  
Publisher: Google · Free documentation · Beginner.

**Add or discover new sources for your notebook — Google Help**  
https://support.google.com/gemininotebook/answer/16215270  
Publisher: Google · Free documentation · Beginner–Intermediate.

**Use chat in Gemini Notebook — Google Help**  
https://support.google.com/gemininotebook/answer/16179559  
Publisher: Google · Free documentation · Beginner.

**Create a notebook in Gemini Notebook — Google Help**  
https://support.google.com/gemininotebook/answer/16206563  
Publisher: Google · Free documentation · Beginner–Intermediate. 

**Generate Flashcards or Quizzes in Gemini Notebook — Google Help**  
https://support.google.com/gemininotebook/answer/16958963  
Publisher: Google · Free documentation; usage limits depend on plan · Beginner.

**Generate Audio Overview in Gemini Notebook — Google Help**  
https://support.google.com/gemininotebook/answer/16212820  
Publisher: Google · Free documentation; generation limits depend on plan · Beginner–Intermediate.

Về gói, Google hiện phân chia Gemini Notebook thành Standard, Plus, Pro và Ultra với giới hạn khác nhau về notebooks, sources, chats, Audio/Video Overviews, reports, flashcards, quizzes và Deep Research. Ví dụ Standard hiện là 100 notebooks, 50 sources/notebook và 50 chats/day; Pro tăng lên 500 notebooks, 300 sources/notebook và 500 chats/day. Các giới hạn này được Google đánh dấu là **subject to change**, vì vậy hocmay.app không nên hard-code con số vào video mà nên đặt một “current limits” card có link về trang chính thức. 

Khả năng cũng có thể khác theo khu vực. Google cho biết Gemini Notebook hỗ trợ hơn 80 ngôn ngữ và browser availability trong các quốc gia/vùng hỗ trợ; các gói AI và một số premium capability phụ thuộc nơi Google cung cấp chúng. Trang limits hiện tại còn ghi chú rằng một số output có visible watermark đối với người dùng ở **Việt Nam, Ấn Độ và Hàn Quốc** trong các trường hợp được nêu trên bảng plan.

## Workflow kết hợp hai công cụ, quyền riêng tư và an toàn dữ liệu

Một nguyên tắc thiết kế nên xuyên suốt hocmay.app là **đưa đúng việc cho đúng công cụ**.

Workflow nghiên cứu điển hình có thể là:

**Nguồn gốc → Gemini Notebook → Evidence synthesis → ChatGPT Project → Deliverable → Scheduled Task/Calendar → Human review.**

Ví dụ một người đang học về quản lý tài chính cá nhân có thể đưa sách, bài báo và notes vào Gemini Notebook; dùng citation-grounded chat để tạo claim/evidence matrix; xuất các kết luận đã kiểm chứng; đưa chúng vào một ChatGPT Project; nhờ ChatGPT biến kiến thức thành kế hoạch học 30 ngày; rồi tạo Scheduled Task mỗi tối để nhắc review. Đây là một thiết kế workflow, không phải một tính năng duy nhất của hai sản phẩm. Khả năng thực thi các bước có kết nối app hoặc scheduling vẫn phụ thuộc tài khoản và permissions. 

Một prompt tích hợp tốt:

> “You are helping me turn verified research into an action plan.  
> I will paste conclusions that were verified against citations in Gemini Notebook.  
> Treat those conclusions as the source material.  
> Do not introduce additional factual claims unless you clearly mark them as new and requiring verification.  
> Create a 14-day learning plan with one measurable outcome per day.  
> After the plan, show which days could be automated with reminders or recurring tasks.”

Đối với ChatGPT, người dùng cá nhân Free/Plus/Pro có thể tắt **Improve the model for everyone** trong Settings → Data Controls. OpenAI nói rằng regular chats vẫn được giữ trong history khi tắt setting này; Temporary Chat không xuất hiện trong history, không tạo/update memory và không được dùng để improve models khi vẫn ở trạng thái temporary, dù OpenAI có thể giữ bản sao tối đa 30 ngày vì mục đích safety. Business, Enterprise và Edu mặc định không dùng workspace content để train model. 

Đối với Memory, người học nên được dạy nguyên tắc **“share the minimum necessary”**. OpenAI cảnh báo rằng sensitive information có thể xuất hiện trong Memory nếu người dùng chia sẻ nó, và khuyến nghị dùng non-personalized Temporary Chat khi không muốn nội dung tham gia personalization. 

Với Gemini Notebook, Google hiện tuyên bố content trong Notebook không được dùng trực tiếp để train foundational AI models **trừ khi người dùng cung cấp feedback**. Khi người dùng gửi thumbs up/down, context liên quan có thể bao gồm prompts, customizations, sources, uploads và generated outputs và có thể được human reviewers xem; Google khuyến nghị không đưa confidential hoặc sensitive information vào feedback. Với qualified Workspace/Education accounts, Google nói uploads, queries và responses không được human-reviewed ngay cả khi cung cấp feedback và không được dùng để train AI models. 

Điểm này nên thành một bài kiểm tra riêng: học viên được đưa một tài liệu chứa tên, số điện thoại, địa chỉ, account number và nội dung cần phân tích; họ phải tự quyết định phần nào cần xóa trước khi upload.

Về copyright, Google yêu cầu người dùng tôn trọng luật bản quyền và không chia sẻ copyrighted content nếu không có quyền cần thiết. Gemini Notebook cũng có thể hạn chế một số thao tác download tùy publisher restriction.

Do đó khóa học nên dạy một “AI data checklist” trước khi upload:

1. Tôi có quyền sử dụng tài liệu này không?  
2. Nó có chứa mật khẩu, API key, tài khoản, thông tin nhận dạng hoặc dữ liệu nội bộ không?  
3. Tôi có thực sự cần upload toàn bộ file không?  
4. Tôi đang dùng personal account hay managed workspace?  
5. Feedback có thể khiến context được chia sẻ để review không?  
6. Đầu ra này có cần human verification trước khi sử dụng không?

Đối với dữ liệu y tế, pháp lý, tài chính hoặc các quyết định có tác động lớn, khóa học nên yêu cầu **human/expert review**. OpenAI Academy khuyến nghị không thay thế chuyên gia bằng ChatGPT cho các lĩnh vực high-stakes và yêu cầu kiểm tra critical facts bằng trusted sources.

## Bài cuối khóa, rubric và cấu trúc triển khai cho hocmay.app

Capstone phù hợp nhất là **“Build Your Personal AI Operating System”**. Người học chọn một chủ đề thật như học ngoại ngữ, chuẩn bị xin việc, nghiên cứu thị trường, học một môn đại học hoặc quản lý công việc cá nhân.

Họ phải tạo một bộ sản phẩm gồm: một Gemini Notebook có ít nhất 5 nguồn; một research summary với citations đã kiểm tra thủ công; một ChatGPT Project chứa context và Project Instructions; một bộ Custom Instructions cá nhân; một daily/weekly planning prompt; ít nhất một automation thật nếu tài khoản hỗ trợ Scheduled Tasks, hoặc mô tả chính xác vì sao tài khoản chưa hỗ trợ; và một reflection ngắn ghi lại những điểm AI sai hoặc cần human correction.

Rubric nên chấm trên thang 100:

| Năng lực | Điểm | Tiêu chí đạt |
|---|---:|---|
| Prompt formulation | 20 | Task/context/constraints/output rõ; biết iteration |
| Verification | 20 | Không tin citation mù quáng; kiểm tra claim và source |
| Personalization | 10 | Custom Instructions/Memory được dùng đúng mục đích |
| Projects | 10 | Project có cấu trúc, instructions và reusable context |
| Planning & automation | 15 | Phân biệt plan/task/calendar; automation thực sự được xác nhận |
| Gemini Notebook | 15 | Multi-source research, citation checking, study artifacts |
| Privacy/copyright | 5 | Không upload dữ liệu không cần thiết hoặc tài liệu trái quyền |
| Reflection & judgment | 5 | Biết chỉ ra giới hạn, lỗi và phần cần human review |

Tôi đề xuất chuẩn hoàn thành là **70/100**, nhưng yêu cầu tối thiểu riêng cho Verification phải đạt **12/20**. Một học viên prompt rất hay nhưng không kiểm chứng thông tin chưa nên được coi là “AI proficient”.

Các bài thực hành nên phát triển theo năm cấp độ: đầu tiên là một prompt đơn lẻ; tiếp theo là prompt có context và constraints; sau đó là iterative workflow; tiếp theo là multi-source research có citations; cuối cùng là hệ thống lặp lại có Project, Notebook và Scheduled Tasks. Cách tăng độ khó này phù hợp hơn việc nhồi hàng chục “prompt tricks”, vì chính OpenAI nhấn mạnh rằng không tồn tại một prompt hoàn hảo duy nhất và việc thử nghiệm, phản hồi và refinement mới là kỹ năng bền vững. 

Về mặt sản phẩm, hocmay.app nên chia mỗi lesson thành **Learn → Watch → Try → Inspect → Improve → Verify → Save**. “Save” ở đây đặc biệt quan trọng: người học nên kết thúc mỗi module bằng một reusable asset như prompt template, Custom Instructions, Project template, verification checklist hoặc Notebook workflow.

Khóa học cũng nên gắn nhãn tài liệu theo ba mức. **Primary** cho OpenAI Help Center, OpenAI Academy và Google Help; **Official Training** cho Grow with Google/Coursera courses do Google thiết kế; **Supplementary** chỉ dành cho tài liệu bên thứ ba thực sự bổ sung giá trị. Cách này giúp hocmay.app không phụ thuộc vào các “prompt guru” hoặc bài blog dễ lỗi thời, trong khi các tính năng ChatGPT và Gemini Notebook đang thay đổi nhanh trong năm 2026. Những giới hạn, tên tính năng và plan availability nên được liên kết tới nguồn chính thức thay vì ghi cứng vào nội dung khóa học. 

Bộ nguồn tiếng Anh nên được xem là “reading list chính thức” của khóa gồm **OpenAI Academy**, **Prompting**, **Power Prompting**, **Customizing ChatGPT**, **Does ChatGPT tell the truth?**, **Projects in ChatGPT**, **Memory in ChatGPT**, **ChatGPT Custom Instructions**, **Scheduled tasks in ChatGPT**, **Connected apps in ChatGPT**, **Google AI Essentials**, **Google Prompting Essentials**, cùng toàn bộ **Gemini Notebook Help** về sources, chat, notebooks, Audio Overviews, flashcards/quizzes, privacy và limits. Đây là nhóm tài liệu có độ tin cậy cao nhất cho mục tiêu của hocmay.app vì phần lớn là documentation và training do chính nhà cung cấp sản phẩm xuất bản và đã được kiểm tra lại ở trạng thái hiện hành đến ngày 24/11/2026. 