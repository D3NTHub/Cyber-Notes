# OSI Model 
## OSI Model = A Standard Model that describes how communication in a network works in a sequnetial manner (โมเดลมาตราฐานอธิบาย การสื่อสารในเครือข่ายทำงานเป็นลำดับขั้นอย่างไร)
## Divided into 7 layers.

### Application (Layer 7) 
The layer closest to the user *EX Web browser , Email , HTTP*

### Presentation (Layer 6)
The layer ensures(ช่วยให้มั่นใจ) data from the application layer is readable. It handles translation, encryption, and compression 

### Session (Layer 5)
The layer handles communication sessions between applications. It handles dialog control and session checkpoints. (จัดการ "การเชื่อมต่อ" เปิด/ปิด session)

### Transport (Layer 4)
The layer manages end-to-end communication between devices. It break data into segment ensures reliable delivery. *EX Protocol : TCP,UDP*

### Network (Layer 3)
The layer handles logical addressing, determining(การกำหนด) the best physical path for data packets to travel across different networks *EX IP Address , CMP*
(ทำหน้าที่จัดการการกำหนดแอดเดรส โดยพิจารณาเส้นทางทางกายภาพที่ดีที่สุดสำหรับแพ็กเก็ตข้อมูลที่จะเดินทางข้ามเครือข่ายต่างๆ)

### Data link (Layer 2)
The layer package raw data from Network layer into "frames" and uses **MAC address** for node-to-node delivery and hardware identification

### Physical (Layer 1)
The foundational hardware layer. It's transmits the raw, unstructured data bits over physical mediums (Transmitting electrical signals / Lan cable)
