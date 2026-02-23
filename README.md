# BasicKnowledgeForH4ck1ng

Chào mừng bạn đến với **"Hacker's Cookbook: The Ultimate Core"**! 

---

### 🧠 MODULE 0: THE MINDSET, METHODOLOGY & OPSEC

Đây là lời tựa cho Cookbook. Không bắt đầu bằng code, bắt đầu bằng tư duy của một kẻ săn mồi (Bug Hunter) và sự cẩn trọng của một bóng ma (OpSec).

* **Lõi lý thuyết:** * *Getting Started Becoming a Master Hacker:* Đọc Prelude & Chương 1 (Bản chất của Hacking).
* *Bug Bounty Bootcamp:* Chương 1 (Luật chơi của Bug Bounty, HackerOne, Bugcrowd).


* **Kiến thức note chính:** * Tam giác bảo mật CIA (Confidentiality, Integrity, Availability).
* Phương pháp luận: Cyber Kill Chain & PTES (Penetration Testing Execution Standard).
* Tư duy Bug Bounty: Đừng report rác, hãy tập trung vào Impact (Hậu quả).
* OpSec: Cách thiết lập Proxychains, Tor, VPN để ẩn danh an toàn.


* **Thực hành / Local Lab:** Cài đặt máy ảo Kali Linux, thiết lập kết nối VPN, snapshot lại trạng thái "Clean" của máy ảo.
* **Nền tảng / Khóa học:** * *Course TCM:* Ghi chú lại tư duy tiếp cận một dự án Pentest thực tế từ những video đầu tiên.

---

### 🐧 MODULE 1: OS & LINUX CORE

Vũ khí đầu tiên và quan trọng nhất. Một Hacker không hiểu sâu về Linux giống như một đầu bếp không biết dùng dao.

* **Lõi lý thuyết:** * *Linux Basics for Hackers:* Chương 1 đến Chương 10.
* **Kiến thức note chính:** * Cấu trúc File System của Linux (`/etc`, `/var`, `/bin`...).
* Hệ thống phân quyền (Permissions: `chmod`, `chown`, SUID, SGID).
* Quản lý Process (`ps`, `top`, `kill`) và Service (`systemctl`).
* Các lệnh thao tác text thần thánh: `grep`, `awk`, `sed`.


* **Thực hành / Local Lab:** Tự tay mount ổ đĩa, phân quyền cho thư mục ẩn, cấu hình SSH server trên máy ảo.
* **Nền tảng / Khóa học:** * *pwn.college:* **Bắt buộc** cày nát khóa "Linux Luminarium". Đây là nơi tôi luyện sinh viên CS thành trùm OS.
* *HTB Writeups:* Thêm writeups của các máy Starting Point (Meow, Fawn, Dancing).
* *Course TCM:* Hoàn thành phần "Linux Refresher".


---

### 🌐 MODULE 2: NETWORKING FOR HACKERS

Không có mạng, không có Hacking. Hiểu cách dữ liệu di chuyển để biết cách chặn bắt và thao túng nó.

* **Lõi lý thuyết:** * *Network Basics for Hackers:* Chương 1 đến Chương 8.
* **Kiến thức note chính:** * So sánh mô hình TCP/IP và OSI.
* Subnetting, CIDR (Kỹ năng bắt buộc để khoanh vùng mục tiêu).
* Cách hoạt động của ARP, DNS, DHCP.
* Phân tích cấu trúc gói tin IPv4/IPv6.


* **Thực hành / Local Lab:** Cài đặt Cisco Packet Tracer, tự vẽ một mạng LAN. Dùng Wireshark và tcpdump bắt gói tin ping/HTTP giữa máy Host và máy ảo.
* **Nền tảng / Khóa học:** * *TryHackMe:* Hoàn thành path "Network Fundamentals".
* *Course TCM:* Hoàn thành phần "Networking Refresher".



---

### 🐍 MODULE 3: PROGRAMMING & TOOL DEVELOPMENT

Chuyển hóa từ "người dùng tool" sang "người tạo tool". Python và Bash là hai cánh tay đắc lực.

* **Lõi lý thuyết:** * *Black Hat Python (2nd Ed):* Chương 2, 3, 4 (Networking, Sniffer).
* *Linux Basics for Hackers:* Chương 17 (Bash Scripting).


* **Kiến thức note chính:** * Tương tác Socket bằng Python.
* Viết clone của Netcat (Netcat thay thế).
* Sử dụng thư viện Scapy để thao túng gói tin.
* Cấu trúc vòng lặp, điều kiện trong Bash để tự động hóa.


* **Thực hành / Local Lab:** * Viết script `ping_sweep.sh` quét IP mạng LAN.
* Viết script `port_scanner.py` quét cổng siêu tốc đa luồng (threading).


* **Nền tảng / Khóa học:** * *Course TCM:* Học "Python 101" và "Intro to Scripting". Push các tool bạn code được trong khóa này lên Repo.

---

### 🕵️‍♂️ MODULE 4: RECONNAISSANCE & OSINT

Thắng bại tại Recon. Bạn không thể hack thứ mà bạn không nhìn thấy.

* **Lõi lý thuyết:** * *Web Application Security:* Pillar 1 (Reconnaissance).
* *Bug Bounty Bootcamp:* Chương 2, 3, 4.


* **Kiến thức note chính:** * Subdomain Enumeration (Chủ động & Thụ động).
* Content Discovery (Dò tìm thư mục, file ẩn, API endpoints).
* Công nghệ Fingerprinting (Wappalyzer, WhatWeb).
* GitHub Recon & Google Dorking.


* **Thực hành / Local Lab:** Gom tool từ Module 3, kết hợp với các tool xịn (`Amass`, `httpx`, `ffuf`) để viết một Bash Script tự động hóa toàn bộ quy trình Recon (Recon Pipeline).
* **Nền tảng / Khóa học:** * *Course TCM:* Cày kỹ "Information Gathering".
* *HTB Writeups:* Đưa các máy đòi hỏi kỹ năng tìm kiếm tốt (Cronos, OpenAdmin) vào đây.



---

### 🕸️ MODULE 5: WEB APPLICATION HACKING & BUG BOUNTY

Trái tim của cuốn Cookbook. Hướng dẫn khai thác mọi lỗ hổng Web hiện đại.

* **Lõi lý thuyết:** * *Bug Bounty Bootcamp:* Chương 5 đến Chương 20 (Cực kỳ chi tiết).
* *Web Application Security:* Pillar 2 (Offense) và Pillar 3 (Defense).


* **Kiến thức note chính:** * Cơ chế bảo mật Web: SOP, CORS, CSP.
* Top lỗ hổng: XSS, SQLi, SSRF, CSRF, IDOR, XXE, Command Injection.
* Cách bypass WAF/Filter cho từng loại lỗ hổng.


* **Thực hành / Local Lab:** Cấu hình Burp Suite Professional/Community. Dựng Docker lab OWASP Juice Shop.
* **Nền tảng / Khóa học:** * *PortSwigger Web Security Academy:* **Tài nguyên VÔ GIÁ**. Cày 100% các lab liên quan đến các lỗ hổng đã note ở trên. Đưa lời giải (Lab Solutions) vào Repo.
* *Course TCM:* "Web Application Enumeration" & "Web Vulnerabilities".
* *HTB Writeups:* Toàn bộ các máy Web-based (Juce, Jerry, Blocky, Node, Cap).



---

### 🔌 MODULE 6: API HACKING

Biên giới mới của Hacking. Các ứng dụng Mobile và Web hiện đại đều chạy trên API.

* **Lõi lý thuyết:** * *Hacking APIs:* Đọc và thấm nhuần toàn bộ sách.
* *Bug Bounty Bootcamp:* Ôn tập chương API Testing.


* **Kiến thức note chính:** * Phân biệt kiến trúc REST, SOAP, GraphQL.
* Top 10 OWASP API: BOLA (IDOR API), BFLA, Mass Assignment.
* Phân tích JWT Token và các lỗi Implement (None algorithm, weak secret).


* **Thực hành / Local Lab:** Dựng **crAPI** (Completely Ridiculous API) và **vAPI** bằng Docker. Thực hành test BOLA và Mass Assignment bằng Postman.
* **Nền tảng / Khóa học:** * Sử dụng Postman kết hợp (Proxy qua) Burp Suite để thao tác.
* *HTB Writeups:* Các máy API kinh điển (Postman, Crapi).



---

### ⚔️ MODULE 7: NETWORK PENTESTING & EXPLOITATION

Bắt đầu dấn thân vào Red Team. Tấn công trực diện vào các dịch vụ hạ tầng mạng.

* **Lõi lý thuyết:** * *Getting Started Becoming a Master Hacker:* Phần Exploitation, Password Cracking.
* *Network Basics for Hackers:* Chương 9, 10, 11 (SMB, SMTP, SNMP).


* **Kiến thức note chính:** * Quy trình sử dụng Metasploit Framework (Search, Use, Set Payload, Exploit).
* Tấn công dịch vụ tệp tin: SMB, FTP nặc danh.
* Vulnerability Scanning: Cấu hình và đọc report từ Nessus.
* Crack Hash: Cơ chế của Hashcat và John The Ripper (Đưa kiến thức Crypto của bạn vào đây).


* **Thực hành / Local Lab:** Dựng Metasploitable 2 & 3. Dùng Nmap dò quét và Metasploit bắn Exploit lấy shell (Ví dụ: vsftpd backdoor, ms08_067).
* **Nền tảng / Khóa học:** * *Course TCM:* "Scanning & Enumeration", "Vulnerability Scanning", "Exploitation Basics".
* *HTB Writeups:* Các máy đòi hỏi rà quét cổng và khai thác CVE mạng (Lame, Legacy, Blue, Devel, Optimum).



---

### 🏢 MODULE 8: ACTIVE DIRECTORY (AD) HACKING

End-game của mạng doanh nghiệp. Đánh sập Domain Controller.

* **Lõi lý thuyết (Lấy 100% từ khóa học):** * Sách của bạn không đi sâu vào AD. Module này sẽ lấy kiến thức hoàn toàn từ khóa *TCM Practical Ethical Hacking*.
* **Kiến thức note chính:** * AD Architecture (Domain Controller, Forests, Trusts).
* Tấn công mạng nội bộ: LLMNR/NBT-NS Poisoning (Responder), SMB Relay.
* Tấn công Identity: Pass the Hash, Kerberoasting, AS-REP Roasting.
* Sử dụng BloodHound/Sharphound để vẽ bản đồ đường đi lên Domain Admin.


* **Thực hành / Local Lab (BẮT BUỘC):** Build Local AD Lab y hệt Heath Adams hướng dẫn (1 Windows Server DC, 2 Windows 10 Client). Tự thiết lập cấu hình lỗi và tự Hack.
* **Nền tảng / Khóa học:** * *Course TCM:* Học đi học lại phần "Active Directory".
* *HTB Writeups:* Kéo toàn bộ writeup AD (Active, Forest, Mantis, Sauna, Resolute) vào mục này.



---

### 👑 MODULE 9: PRIVILEGE ESCALATION & POST-EXPLOITATION

Đã vào được hệ thống, giờ là lúc trở thành Chúa tể (Root/SYSTEM) và cướp dữ liệu.

* **Lõi lý thuyết:** * *Black Hat Python:* Chương 8, 9, 10 (Khai thác Windows COM, Process Control, Exfiltration).
* *Getting Started Becoming a Master Hacker:* Phần Post-Exploitation.


* **Kiến thức note chính:** * Linux PrivEsc: SUID/SGID, Sudo misconfigurations, Cron jobs, Kernel Exploits.
* Windows PrivEsc: Unquoted Service Paths, Token Impersonation (Potato attacks), Registry Autoruns.
* Pivoting (Dùng máy đã hack làm bàn đạp đánh sâu vào mạng trong).


* **Thực hành / Local Lab:** Chạy thử nghiệm các tool tự động quét lỗi leo quyền: `LinPEAS` (Linux) và `WinPEAS` (Windows) để đọc hiểu output.
* **Nền tảng / Khóa học:** * *Course TCM:* "Linux Privilege Escalation" & "Windows Privilege Escalation".
* *TryHackMe:* Cày 2 room "Linux PrivEsc" và "Windows PrivEsc" (của Tib3rius).
* *HTB Writeups:* Các máy nặng về kỹ năng leo quyền (Bounty, Jeeves, Bastard, Granny).


