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

![](Aspose.Words.863a019a-f0e6-4f16-aef0-7d9ecf59456d.001.png)

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

OSINT: Tesseract

FOCA: ( Tổ chức lấy dấu vân tay với kho lưu trữ được thu thập bở ElenventPaths) là công cụ tìm kiếm tài liệu

- FOCA PRO được gọi là phiên bản cuối cùng
- Phiên bản 3.4
- Chạy miễn phí trên windows
- EleventPaths đã tạo ra một dịch vụ có tên là”FaasT” với tư cách là phần mềm tiếp theo  của FOCA

FOCA có thể tìm kiếm tất cả tài liệu trong một miền

- Tải xuống và phân tích chúng
- Tạo danh sách metadata
- Metadata bao gồm: người dung, máy in, phần mềm, email, hệ điều hành, mật khẩu

Ngoài ra chúng ta có Maltengo, Spiderfoot, theHarvester,AutOSINT


The WEB: World Wide Web được thiết kế để tương đương với một máy chủ FTP ẩn danh

- Tất cả dữ liệu được công khai
- Không có chứng thực
- Không có mã hõa
- Mỗi lần tải xuống là 1 phiên
- 1 máy chủ = 1 máy chủ web không có máy chủ ảo

HTTP/0.9

Phiên bản đầu tiên của HTTP hỗ trợ một phương thức GET đơn giản 

- Giao thức này có tên trước đây là HTTP/0.9
- GET là phương thức được hỗ trợ duy nhất
- Client GET request là một dòng đơn được kết thúc bở CRFL
- Không có tiêu đề nào của máy client được hỗ trợ
- Không hỗ trợ virtual server
- Chỉ trả về HTML
- Một GET == một kết nối TCP
- Nhiều loại máy chủ web hiện đại( bao gồm cả Apache và Nginx) hỗ trợ HTTP/0.9 theo mặc định

HTTP/1.0

- RFC 1945 mô tả HTTP/1.0 được phát hành vào tháng 5 năm 1996
- Tiêu chuẩn HTTP chính thức đầu tiên
- Đã thêm các support bổ sung ngoài phương thức GET
- GET và HEAD được mô tả là phương phát an toàn( chúng không sửa đổi nội dung)
- POST, PUT, DELETE cũng mô tả 
- Phản hồi của máy chủ không phải HTML 
- Không hỗ trợ máy chủ ảo
- Một GET = 1 TCP

HTTP/1.1

- RFC 2616 mô tả HTTP/1.1 được phát hành vào tháng 6 năm 1999
- Được bổ sung bở các RFC HTTP/1.1 khác vào năm 2014
- Đã them hỗ trợ virtual server
- Tiêu đề host là bắt buộc với các yêu cầu máy client HTTP/1.1
- Cho phép kết nối liên tục
- Nhiều yêu cầu thông qua TCP/IP
- Đã thêm phương thức OPTIONS
- Hỗ trợ tốt hơn cho bộ nhớ đệm, proxy và nén

HTTP/2

- Trọng tâm chính của bản cập nhật HTTP/2 là đạt được hiệu suất nhanh hơn bằng cách cập nhật cách thức hoạt động của HTTP
- HTTP/2 mang đến thay đổi đáng kể cho HTTP
- Giao thức nhị phân
- Nén tốt hơn
- Giảm chi phí và độ phức tạp khi phân tích
- Push Promise – Máy chủ web có thể gửi nội dung máy client trước khi nó được yêu cầu
- Multiplexed not Pipelined – một kết nối TCP trên mỗi điểm gốc đồng thời thực hiện nhiều cầu/phản hồi
- HPACK – Giao thức được thiết kế cho nén tiêu đề HTTP/2
- HTTP/2 không yêu cầu mã hóa

QUIC-HTTP/3 

- Là một giao thức được thiết kế bởi google bảo đảm thông tin cung cấp qua HTTP/3 nhanh hơn đáng kể
- QUIC sử dụng port 80, 443 tương ứng với HTTP, HTTPS
- Cả hai đều được mã hóa nhưng cổng 80 không xác minh chứng chỉ máy chủ 
- QUIC là 1 phương thức truyền tải mới giúp giảm tốc độ so với TCP. QUIC rất giống với TCP+TLS+HTTP/2 được thực hiện trên UDP
- Chorm sẽ sử dụng QUIC cho các trang web hỗ trợ QUIC bảo gồm cả web của google
- ZAP và burpsuit đề không hỗ trợ QUIC

HTTP semantic

- Hiểu tất cả các khía cạnh khác nhau của HTTP
- Nội dung ban đầu tương tự với HTTP/0.9, HTTP/1.0, HTTP/1.1, HTTP/2, QUIC/HTTP/3
- Sự khác biệt cơ bản liên quan đến việc truyền dữ liệu qua mang
- Đọc các yêu cầu phù hợp và kiểm tra phản hồ từ CLI đến cURL hoặc qua proxy chặn của chúng tối, Burp hoặc ZAP là một nhiệm vụ thiết yếu trong quá trình thử nghiệm

Example HTTP request

![](Aspose.Words.863a019a-f0e6-4f16-aef0-7d9ecf59456d.002.png)

Example HTTP response

![](Aspose.Words.863a019a-f0e6-4f16-aef0-7d9ecf59456d.003.png)

HTTP request: Methods/ Verbs

- GET
- HEAD
- POST
- PUT
- DELETE
- CONNECT
- OPTIONS
- TRACE
- PATCH

HTTP request: Get the uri

- Việc sử dụng phần thân http có nghĩa là tất cả các trao đổi dữ liệu phải đươc giao tiếp trong HTTP
- HTTP GET sử dụng HTTP URI để truyền dữ liệu

HTTP request methods: POST

- HTTP POST phương thức yêu cầu HTTP phổ biến thứ 2 không giống như GET, các yêu cầu HTTP POST sử dụng dữ liệu trong nội dung thông báo HTTP cho trao đổi dữ liệu
- Tuy đơn giản nhưng điều này thể hiện sử khác biệt đáng kể giữa GET và POST 

HTTP request methods: HEAD

- PHương thức yêu cầu HTTP an toàn tạo ra phần hồi của máy chủ
- Chỉ các tiêu đề HTTP sẽ được trả về một yêu cầu HEAD

HTTP request methods: TRACE

- Phương thức được thiết kế để khắc phục sự cố không kích hoạt được trong quá trình làm việc
- Hỗ trợ trace được coi là một phát hiện trong bất kì đánh giá nào

HTTP request methods: Option

HTTP request: Cookie and set cookie

- Ứng dụng thiết lập follow người dung qua các phiên bằng cách sử dụng cookie

HTTP request: Status code

1xx: information

2xx: success

3xx: redirection

4xx: client error

5xx: server error

HTTP response: Cacheable and cache-control

- Vì 1 số mục đích một số nội dung HTTP có thể được lưu vào bô nhớ cache cục bộ
- Nếu được lưu vào bộ nhớ cache thành công, trình duyệt sẽ không gửi request lại
- Nội dung có thể được lưu vào bộ nhớ đệm hay không phụ thuộc vào phương thức yêu cầu- chỉ phản hồi cho GET và HEAD thường có thể lưu vào bộ nhớ cache mã trạng thái – 200,203,204,206,300,404,405,410,412,5012

HTTP response: Server

- Máy chủ cung cấp phản hồi tương đương với head của user agent
- Cho biết máy chủ web gần nhất với người dung cuối
- Server có thể được định cấu hình

HTTPS: Transmisson security for http

- HTTP trình bày là một giao thức chủ yếu văn bản rõ rang
- Các phiên bản gần đây của HTTP có bao gồm các phần tử nhị phân nhưng về tính bảo mật dữ liệu thì không
- SSL/TLS được sử dụng để mang lại bảo mật truyền tới HTTP
- Phiên bản SSL cuối cung 3.0 được phát hành vào năm 1996
- Phiên bản phổ biến nhất TLS 1.2 ra mắt trong 2008
- RFC cho TLS 1.3 phát hành năm 2018

HTTPS: SSL/TLS Handshake 

- Tuân theo quá trình bắt tay 3 bước

HTTP: Confidnetiality ++

Mặc dù SSL/TLS chủ yếu được coi là cung cấp bảo mật nhưng nó thực sự làm được nhiều hơn thế

Bộ mật mã bao gồm

- ` `Một thuật toán đối xứng mã hóa/ bảo mật dữ liệu hang loạt
- ` `Một thuật toán bất đối xứng để tìm khóa và xác thưc
- ` `Một thuật toán băm để đảm bảo tính toàn vẹn

Việc triển khai các mật mã riêng lẻ có thể có các lỗi bảo mật

HTTPS: Public keys/ Certificates and Certificate Authorities

- Phần thuật toán bất đối xứng của mật mã phụ thuộc vào khóa công khai cho vai trò của nó trong hoạt dộng của TLS
- Mặc dù ai cũng có thể dễ dàng tạo khóa công khai nhưng khách hang cần phải đảm bảo khóa công khai sẽ được chia sẻ
- Các chứng chỉ có thể xác minh là phương tiện đáng tin cây
- Chứng chỉ phải được kí điện tử bở một tổ chức
- Tổ chức phát hành chứng chỉ CA là những thức thể đáng tin cậy sẽ tạo và kí chứng chỉ

HTTPS testing: Version and cipher suites

- Chỉ các bộ mật mã TLS 1.3 mới nhất tốt nhất sẽ là lí tưởng

HTTPS testing: Using Nmap to evaluate HTTPS support

- Các lệnh Nmap NSE sẽ đánh giá các mật mã được hỗ trợ bởi máy chủ HTTPS
- Phân loại độ mạnh của mật mã với các cấp từ A đến F
- Các cấp lớn có thể vượt quá với kiến thức hiện tại

![](Aspose.Words.863a019a-f0e6-4f16-aef0-7d9ecf59456d.004.png)

HTTPS: Testing: Qualys SSL Labs


Interception Proxies

- Chỉ đứng sau trình duyệt về tầm quan trọng đối với ứng dụng web: Proxy đánh chăn

Interception proxies: OWASP zed attack proxy

- OWASP là một công cụ mở đầy tính năng proxy chặn mã nguồn
- Phiên bản ZAP 2.4 đã có số lượng đáng kể cải tiến hiện nãy đã có phiên banr2.10
- Giao diện đã gọn hơn

- ![](Aspose.Words.863a019a-f0e6-4f16-aef0-7d9ecf59456d.005.png)

ZAP: interface

ZAP: Attack menu

- Phiên bản 2.4+ đã hợp nhất một số chức năng vào menu tấn công
- Quét chủ động: Chủ động tìm kiếm 1 trang web tìm kiếm các lỗ hỏng
- Forced browsing
- Spider và Ajax Spider
- Fuzzing

**Phần burp suit em chưa hiểu lắm nên em sẽ tìm hiểu thêm ạ**



Heartbleed 

- Lỗ hổng heartbleed open SSL được phát hiện vào tháng 4 năm 2014
- Các phiên bản open ssl bị ảnh hưởng 1.0.1- 1.0.1f và 1.0.2 beta1
- Lỗ hồng bảo mật chưa được vá từ tháng 3 năm 2012 đến tháng 4 năm 2014
- CVE 2014-0160

