542.1 

Giới thiệu và thu thập thông tin\

Day1: Introduction and information gathering

SANS security 504: Hacker techniques, Exploits, and incident handling: Ở phần này , các khóa học của sans tập trung chủ yếu và cách ứng phó với các cuộc tấn công máy tính bắng cách sử dụng giải pháp ứng phó sự cố bằng phương pháp luận

SANS security 542: Web app pentesting and ethical hacking: nếu bạn đang tập trung vào web, kiểm tra thâm nhập ứng dụng, khóa học này cung cấp các kĩ năng để bạn phân tích kĩ các ứng dụng web

SANS security 550: Active defense,  Offensive Countermeasures, and Cyber Deception: Cung cấp tư duy để bảo vệ môi trường của bạn một cách an toàn và hiệu quả

SANS security 560: Network penetration testing and ethical hacking: Bao gồm các công cụ, công nghê và các phương pháp pháp luận quan trọng nhất mà tổ chức cần để tiến hành kiểm thử mang lại mô hình lợi nhuận giá trị 

SANS security 561: Intese Hands-On Skill Development for Penetration Tester: Khóa học này cung cấp cho bạn 80% các kĩ năng để giúp bạn có thể xây dựng được kĩ năng kiểm thử nhanh chóng

SANS security 562: CyberCity Hands-On Kinetic Cyber Range: Khóa học này 80% là thực hành với các nhiêm vụ quan trọng

SANS security 573: Automating Information Security with Python: Phương pháp bảo mật này dành cho các chuyên gia thành thao python, và nó cho phép người dung chỉnh sửa cung cụ như thế nào để có thêm nhiều chức năng hơn

SANS security 575: Mobile Device Security và Ethical Hacking: Khóa học cung cấp các kiến thức để thiết kế, triển khai vận hành đánh giá môi trường di động bao gồm điện thoại thông minh và máy tính bảng

SANS security 617: Wireless Ethical Hacking, Pentesting and defenses: Cung cấp các kĩ năng bảo mật thông tin chuyên sâu và bảo vệ mạng Lan không dây thiết bị blutooth, vv

SANS security 642: Advanced web app pen testing and ethical hacking: Khóa học bảo mật web nâng cao

SANS security 660: Advanced penetration testing, exploits and ethical hacking: Giúp người kiểm tra khả năng nâng cao kĩ năng thâm nhập lên cấp độ tiếp theo và bao gồm các chủ đề NAC bypass, route injection

SANS security 760: Advanced exploit development for penetration Tester: Đây là kĩ thuật chuyên sâu nhất của chúng tôi cung cấp với tác nhân của windows sửa lỗi khác và nhiều cuộc tấn công và khai thác khác



Why are you here?

Web applications

- Có mặt trên mọi nơi với mọi quy mô và loại hình kinh doanh
- Chức năng quan trọng với doanh nghiệp
- Cung cấp quyền truy cập vào dữ liệu nhạy cảm và quan trọng

Hầu hết các tổ chức không nhấn mạng đến việc bảo vệ ứng dụng

- Thường gặp với nhà phát triển kém thành thạo về bảo mật ứng dụng
- Điển hình cho việc các chuyên gia bảo mật thiếu kiến thức và kĩ năng trong lĩnh vực này

Lí do khác do tất công web thú vui ^^

Nhiều doanh nghiệp chỉ kiểm tra chức năng  kinh doanh và ứng dụng triển khai trên web

Kiểm tra đánh giá thậm nhập vị trí bảo mật của ứng dụng

Phương thức này sẽ là trọng tâm của lớp này nhưng nhiều cách tiếp cận khả thi khác nhau để đánh giá tính bảo mật của ứng dụng

Hiểu cách kiểm tra ứng dụng web để chứng minh sự quan trọng

Có thể không phải là công cụ phù hợp hoặc tốt nhất cho một ứng dụng nhất định

Có thể cần được bổ sung tiếp cận bằng các cách tiếp cận khác


Asessensing application security

Các mô hình mối đe dọa

Code review

Các phương pháp kiểm tra bảo mật

SAST

DAST

IAST2

OAST3

Đánh giá kiểm tra grayscale

Black/white/grey box testing

Black box 

- Không có hiểu biết, không điển hình
- Không cung cấp quyền truy cập mã nguồn, tài khoản người dung, quyền truy cập cho admin

White box

- Kiểm tra bảo mật kiến thức với đầy đủ quyền truy cập vào mã nguồn ứng dụng tài khoản kiến thức về ứng dụng và quyền truy cập vào các nhà phát triển

Gray box

- Hầu hết các thử nghiệm để rơi vào vùng màu xám giữa màu đen và màu trắng một cách hợp pháp


SAST

SAST liên quan đến việc xem xét kĩ lưỡng các mã nguồn ứng dụng đang tìm kiếm các thiếu sót bảo bật

Sử dụng các công cụ thay vì chỉ dựa vào việc xem xét mã thủ công

- Tuy nhiên, SAST có thể xem là một đánh giá mã tự động và hiệu quả
- Được đánh giá như một kĩ thuật kiểm tra hộp trắng do quyền truy cập mã nguồn được yêu cầu cho loại thử nghiệm này

Điểm mạnh: Xác định các thiếu sót bảo mật không dễ thấy trong ứng dụng triển khai

Điểm yếu:      Yêu cầu quyền truy cập vào mã nguồn, có thể bỏ qua các API hoặc các thư viện được tận dụng, bỏ qua các phần hoạt động động của ứng dụng


DAST

sác định các lỗi bảo mật thông qua tương tác với ứng dụng đã triển khai

Điểm mạnh: Có thể coi là một hình thức kiểm tra hộp đen do thiếu mã nguồn

Các công cụ DAST Không yêu cầu quyền truy cập mã nguồn, nhất thiết phải có tài khoản cho phía hoạt động của ứng dụng, có thể được tự động hóa, quy mô tốt cho các ứng dụng lớn

Điểm yếu: Chỉ tốt như công cụ, cấu hình của nó và người dung sử dụng nó

Công cụ DAST đóng vai trò quan trọng trong ứng dụng web kiểm thử

Sử dụng các công cụ DAST một cách hiệu quả

- ĐỊnh cấu hình cho ứng dụng đích
- Hướng dẫn quét để đảm bảo xem xét toàn diện
- Theo dõi kết quả để giảm những phát hiện không chính xác
- Đánh giá những mặt tích cực để hiểu được tác động tiềm ẩn
- Hiểu và khắc phục những khiếm khuyết về năng lực


Tools Dast

Free/Open Source

- ZAP active scan
- SQL map( SQL injection specific)
- W3AF
- Metasploit WMAP
- WPScan

Comercial 

- Acunetix 
- Burp Scanner
- IBM appscan
- Qualys WAS
- Rapid 7 Appspider
- Veracode dynamic analysis
- ZAP scan


Chuẩn bị thiết bị

Máy ảo VMware workstation 15

USB port

CPU 2.0+hz

Ram >=8GB

Full quyền admin và ngắt kết nối firewall antivirus

Lập kế hoạch cẩn thận khi đi vào xây dựng web

Bộ công cụ của người kiểm tra

Môi trường tấn công

Các công cụ scan và phân tích web động

Trình duyệt

Các proxy đánh chặn

WHOIS và DNS

WHOIS là giao thức cung cấp cho máy khách và máy chủ quyền truy cập thông tin về các miền IPv4 và IPv6 netblocks

Sử dụng port 43

Được mô tả bở RFC3912

Các công ty đăng kí chạy WHOIS server cũng như nhiều công ty đăng kí ISP

Sử dụng Whois ta có thể nhận được

- Tên và số điện thoại
- Địa chỉ vật lý
- DNS

Ta nhận được địa chỉ IP của máy chủ DNS cho web kiểm tra thâm nhập

DNS là hệ thống phân giải địa chỉ tên miền, một dữ liệu được phân cấp

- Sử dụng UDP cho port 53 nếu lương thông tin <= 512 byte
- Sử dụng TCP cho port 53 nếu lương thông tin > 512 byte

Tính đến năm 2016 đã có 1500 DNS 

DNS có thể cung cấp nhiều thông tin và đặc biệt hữu ích để khám phá máy ảo

Reverse DNS scan: Dịch ngược DNS

Brute Force DNS: Cung cấp một từ điển các DNS tiềm năng < Tấn công vét cạn>

Sử dụng các công cụ do thám DNS

- Nslookup, Nmap, DNSRecon, Meta

Nslookup: Công cụ để scan DNS

- Tính khả dụng hầu như phổ biến bao gồm UNIX, LINUX, MACos và window
- Hữu ích để xác định được các lỗ
- 1 số tính năng đã được xóa khỏi các phiên bản mới hơn

Dig: Là một DNS client đầy đủ tính năng

- Có sẵn trên macOS và các phiên bản có nhân UNIX/Linux
- Nó không được cài đặt trên windows 

DNSRecon của carlos perez: Thực hiện nhiều chức năng trinh sát DNS

- Có sẵn trong /opt/dnsrecon/dnsrecon.py in the Sec542 Linux VM
- Bao gồm 1 số danh sách được sử dụng để quét DNS brute force
- Các tính năng nâng cao bao gồm hỗ trợ DNSSEC và mDNS
- Carlos cũng đã chuyển nhiều chức năng DNSRecon sang Metasploit module phụ

Metasploit có 1 số công cụ hỗ trợ thu thập thông tin DNS hữu ích

DNS523 WORKBOOK: DNS Harvesting

OTG: Thu thập thông tin

OTG-INFO-001: Tiến hành do thám và khám phá các công cụ tìm kiếm

OTG-INFO-002: Máy chủ web vân tay

OTG-INFO-003: Xem lại các tệp tin máy chủ trang web về rò rỉ thông tin

OTG-INFO-004: Liệt kê các ứng dụng sử dụng trang web

OTG-INFO-005: Đánh giá trang web

OTG-INFO-006: Xác định điểm đầu vào ứng dụng

OTG-INFO-007: Định hướng cách thực thi qua ứng dụng

OTG-INFO-008: Ứng dụng của môi trường web vân tay

OTG-INFO-009: Ứng dụng web vân tay

OTG-INFO-010: Kiến trúc sư ứng dụng

` `OSINT là 1 cụm viêt tắt cho Open Source Intelligency . Trong đó OS là Open Source hay còn gọi là những nguồn mở được public trên internet và Intelligency là Tình báo (sự thu thập các tin tức). Từ đó ta có thể hiểu được là đây chính là những phương thức, cách thức khai thác lấy những thông tin từ video,hình ảnh, văn bản,.. từ những gì liên quan đến mục tiêu có sẵn và đang public trên internet. Những nguồn đó có thể ở bất cứ đâu : trên forum, trên các trang báo,trong 1 cuốn sách, video hay là những thư viện mở,các báo cáo và lịch sử từ trước đó.

Công cụ rõ ràng nhất của OSINT là đơn giản là tìm kiếm

Hầu hết mọi người chỉ tận dụng công cụ tìm kiếm yêu thích của họ và không suy nghĩ nhiều. Đối với tìm kiếm cơ bản thì điều này có vẻ ổn, còn với tìm kiếm nâng cao điều này nên có chút thay đổ

OSINT: Các từ khóa để search

Site:,Cache:,Filetype:,Intitle:,Inurl:,Contain:,OSINT: google docks,

GHDB( google hacking database): Nơi những lỗ hồng được update lên hằng ngày

OSINT: Cache content

Wayback machine: Search các phiên bản cũ hơn của web

Shodan.io: Là công cụ tìm kiếm đầu tiên trên thế giới dành cho các thiết bị kết nối Internet

Có tại: <http://www.shodan.io>. Công cụ này cho phép tìm kiếm máy tính, thiết bị Internet (IOT). Ví dụ như webcam, bộ định tuyến, điện thoại, voiIP

![](Aspose.Words.4e57c6fa-88d4-44e6-a76e-a951f6ed3efd.001.png)

Khi ta đi đến IP mà shodan tìm thế ta sẽ truy cập được vào máy chủ nhưng 1 số sẽ yêu cầu tính năng xác thực. Ở đây ta sẽ gặp 1 số trường hợp khi và ta login vào với username: admin và pass: admin thì hệ thống báo login success nhưng trường hợp đó thì thường rất ít khi xảy ra

Shodan có thể tiết lộ các hệ thống nằm trong phạm vi nào nhưng đây không phải là vị trí chính xác hiện tại. Có thể ở đây bao gồm cả hệ thống do bên thứ 3 quản lý thay cho client. Khi tìm kiếm tên của client ở trên shodan ta phải chú ý đến thiết bị bên ngoài IP của client

Ngoài ra hay thảo luận về các loại hệ thống của client

OSINT: Social Media – Linkedln

Phương tiên tuyền thông xã hội chứa 1 lương lớn thông tin mà chúng ta cần khai thác

OSINT: Metadata 

Nhiều loại file chứa dữ liệu bổ sung ngoài nội dung mà chúng ta cần tìm hiểu

OSINT: exiftool

Exiftool siêu dữ liệu ở nhiều định dạng tệp khác nhau ngoài những hình ảnh

Tài liệu: DOC/XLS/PPT/PDF

Tệp nén: Gz, RAR, ZIP

Hình ảnh: BMP,GIF,JPEG,PNG, TIFF

Âm thanh: MOV,MP3,MP4,WM


