# Router and Switch

## Network Devices for Routing and Switching

---

## Keyword

**Router, Switch**

---

## Definition

### Router — English Definition

> A router is a network device that connects two or more different networks and forwards data packets to their destinations by using IP addresses and routing information.

### Switch — English Definition

> A switch is a network device that connects computers, servers, printers, wireless access points, and other devices within a Local Area Network (LAN). It forwards data to the correct destination by using MAC addresses.

### คำจำกัดความภาษาไทย

**Router (เราเตอร์)** คืออุปกรณ์เครือข่ายที่ทำหน้าที่เชื่อมต่อเครือข่ายตั้งแต่สองเครือข่ายขึ้นไป เช่น การเชื่อมต่อเครือข่ายภายในองค์กรเข้ากับอินเทอร์เน็ต โดย Router จะพิจารณา IP Address และข้อมูลใน Routing Table เพื่อเลือกเส้นทางในการส่งข้อมูล

**Switch (สวิตช์)** คืออุปกรณ์เครือข่ายที่ทำหน้าที่เชื่อมต่ออุปกรณ์หลายเครื่องภายในเครือข่าย LAN เดียวกัน เช่น คอมพิวเตอร์ เครื่องพิมพ์ เซิร์ฟเวอร์ และ Wireless Access Point โดย Switch จะพิจารณา MAC Address เพื่อส่งข้อมูลไปยังอุปกรณ์ปลายทาง

---

## Explanation

## Router คืออะไร?

Router เป็นอุปกรณ์ที่ทำหน้าที่เลือกเส้นทางในการส่งข้อมูลระหว่างเครือข่าย

เมื่อ Router ได้รับข้อมูลเข้ามา จะตรวจสอบ IP Address ปลายทางและค้นหาเส้นทางที่เหมาะสมจาก Routing Table ก่อนส่งข้อมูลออกไปยังเครือข่ายปลายทาง

Router มักติดตั้งอยู่ระหว่างเครือข่ายภายในกับเครือข่ายภายนอก เช่น อินเทอร์เน็ต หรือใช้เชื่อมต่อเครือข่ายหลายสาขาขององค์กรเข้าด้วยกัน

### ความสามารถหลักของ Router

| ความสามารถ | รายละเอียด |
|---|---|
| **Routing** | เลือกเส้นทางและส่งข้อมูลระหว่างเครือข่าย |
| **Default Gateway** | เป็นทางออกของอุปกรณ์ภายใน LAN ไปยังเครือข่ายอื่น |
| **NAT** | แปลง Private IP Address เป็น Public IP Address |
| **Firewall** | กรองและควบคุมการรับส่งข้อมูล |
| **DHCP Server** | แจก IP Address ให้กับอุปกรณ์ภายในเครือข่าย |
| **VPN** | สร้างการเชื่อมต่อเครือข่ายแบบเข้ารหัส |
| **Bandwidth Control** | ควบคุมหรือจำกัดความเร็วในการใช้งานเครือข่าย |
| **Dynamic Routing** | รองรับ Routing Protocol เช่น RIP, OSPF และ BGP |

---

## Switch คืออะไร?

Switch เป็นอุปกรณ์ที่ใช้เชื่อมต่ออุปกรณ์หลายเครื่องภายในเครือข่าย LAN

เมื่อ Switch ได้รับข้อมูลเข้ามา จะตรวจสอบ MAC Address ปลายทางและส่งข้อมูลออกไปยังพอร์ตที่เชื่อมต่อกับอุปกรณ์ปลายทาง

Switch ช่วยให้การสื่อสารภายในเครือข่ายมีประสิทธิภาพมากกว่าการใช้ Hub เนื่องจาก Switch ไม่จำเป็นต้องส่งข้อมูลออกไปทุกพอร์ต

### ความสามารถหลักของ Switch

| ความสามารถ | รายละเอียด |
|---|---|
| **Device Connectivity** | เชื่อมต่ออุปกรณ์หลายเครื่องภายในเครือข่าย LAN |
| **MAC Address Learning** | เรียนรู้ว่า MAC Address แต่ละหมายเลขอยู่ที่พอร์ตใด |
| **Frame Forwarding** | ส่ง Ethernet Frame ไปยังพอร์ตของอุปกรณ์ปลายทาง |
| **VLAN** | แบ่งเครือข่ายภายในออกเป็นหลายเครือข่ายเสมือน |
| **Trunking** | ส่งข้อมูลของหลาย VLAN ผ่านสายเชื่อมต่อเส้นเดียว |
| **STP** | ป้องกันปัญหา Loop ในเครือข่าย |
| **Link Aggregation** | รวมสายเชื่อมต่อหลายเส้นเพื่อเพิ่มความเร็ว |
| **Port Security** | จำกัดอุปกรณ์ที่ได้รับอนุญาตให้เชื่อมต่อแต่ละพอร์ต |

---

## Router และ Switch แตกต่างกันอย่างไร?

| เกณฑ์เปรียบเทียบ | Router | Switch |
|---|---|---|
| **หน้าที่หลัก** | เชื่อมต่อเครือข่ายหลายเครือข่าย | เชื่อมต่ออุปกรณ์ภายในเครือข่าย LAN |
| **ข้อมูลที่ใช้ตัดสินใจ** | IP Address | MAC Address |
| **OSI Layer** | Layer 3 — Network Layer | Layer 2 — Data Link Layer |
| **ข้อมูลที่ส่งต่อ** | Packet | Frame |
| **ตารางที่ใช้งาน** | Routing Table | MAC Address Table |
| **การเชื่อมต่ออินเทอร์เน็ต** | ใช้เป็นทางออกไปยังอินเทอร์เน็ต | เชื่อมต่อกับ Router เพื่อออกอินเทอร์เน็ต |
| **Broadcast Domain** | แต่ละ Interface แยก Broadcast Domain | แต่ละ VLAN เป็นหนึ่ง Broadcast Domain |
| **ตัวอย่างการใช้งาน** | เชื่อมต่อ LAN กับ Internet | เชื่อมต่อ PC, Server, Printer และ Access Point |

> **หมายเหตุ:** Layer 3 Switch สามารถทำ Routing ระหว่าง VLAN ได้ แต่โดยทั่วไป Router จะมีความสามารถด้าน WAN, NAT, VPN และ Firewall ที่ครอบคลุมกว่า

---


*[← Back to Profile](https://jittraporn928262-bit.github.io)*
