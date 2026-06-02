#TCP/IP Model
##TCP/IP model (Transmission Control Protocol/Internet Protocol) =  is the foundational networking framework that dictates how data is packetized, addressed, transmitted, and received across the Internet (รากฐานโมเดลต้นแบบที่ใช้ในโลกความจริง ระบบอินเทอร์เน็ตและเครื่อข่ายที่ใช้กันอยู่ทุกวัน) It organizes all network communication into 4 distinct abstraction layers

### Application Layer 
The topmost layer interacts directly with software applications (it combines the funtions of the Application , Presentations , Session from OSI Model)
**Funtions : Formats data so the receiving software understands it, manages secure connections, and starts the data transmission.** 
(จัดรูปแบบข้อมูลเพื่อให้ซอฟต์แวร์ที่รับข้อมูลเข้าใจ จัดการการเชื่อมต่อที่ปลอดภัย และเริ่มต้นการส่งข้อมูล) *EX: HTTP/HTTPS, FTP , DNS , SSH*

###Transport Layer
Sits between the Application and Internet layer, handling data segmentation, flow control, and end-to-end communication(like Transport layer from OSI Model)
**Function: Ensures data packets arrive intact and in the correct order** EX: TCP(Slow but gurantees reliable(ความน่าเชื่อถือ)) , UDP(Fast but does not gurantees delivery)

###Internet Layer
This layer is responsible for addressing, packaging, and routing data across different networks.(กำหนดที่อยู่ บรรจุและกำหนดเส้นทางส่งข้อมูลข้ามเครือข่าย)
**Function: Determines the best path for data to travel from the source to its final destination.** EX: IP , ICMP , APR

###Network Interface
The lowest layer acts as the physical. It oversees how data is physically transmitted through hardware like cables, switches, and wireless connections.
(รวมหน้าที่การจัดการฮาร์ดแวร์และการเชื่อมต่อของชั้น Datalink และ Physical ใน OSI Model เข้าด้วยกัน)
**Function: Converts digital data packets into electrical, optical, or radio signals and manages the hardware framing.** EX:  Ethernet, Wi-Fi, MAC addressing.
(แปลงแพ็กเก็ตข้อมูลดิจิทัลเป็นสัญญาณไฟฟ้า แสง หรือคลื่นวิทยุ และจัดการการจัดเฟรมฮาร์ดแวร์)
