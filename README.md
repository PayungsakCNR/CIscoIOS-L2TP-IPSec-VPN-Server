# CIscoIOS-L2TP-IPSec-VPN-Server
CIscoIOS-L2TP-IPSec-VPN-Server

อันนี้เป็นตัวอย่าง Config สำหรับการทำ L2TP/IPSec VPN Server บน Cisco IOS นะครับ

ในตัวอย่างจะเป็นการ VPN แบบ เข้ามาทาง WAN Interface เเล้วถ้าจะออกเน็ตก็จะโดน NAT Overload ออกไปทาง WAN Interfrace ที่เข้ามา
ส่วนการเข้าถึง Private Network ก็ตาม Static Route เลย (แต่อาจใช้ OSPF,EIGRP สำหรับใช้ Route ภายในได้เช่นกัน ขึ้นกับการออกแบบเลย)
