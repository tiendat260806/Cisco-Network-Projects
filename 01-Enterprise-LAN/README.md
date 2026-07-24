# Enterprise LAN
## Giới thiệu
Đây là project mô phỏng mạng doanh nghiệp bằng Cisco Packet Tracer với 3 phòng ban. Mạng được chia thành các VLAN riêng biệt, sử dụng Router-on-a-Stick để định tuyến giữa các VLAN và triển khai các dịch vụ DHCP, DNS, Web Server.
## Mục tiêu
- Thiết kế mạng doanh nghiệp cơ bản.
- Chia mạng bằng VLAN.
- Cấu hình Trunk giữa các Switch.
- Cấu hình Inter-VLAN Routing.
- Cấp phát IP động bằng DHCP.
- Cấu hình DNS.
- Triển khai Web Server.
## Thiết bị sử dụng
- Router Cisco 2911 × 1
- Switch Cisco 2960 × 4
- PC × 9
- Server × 1
## Địa chỉ IP

| VLAN | Phòng ban | Network | Gateway |
|------|-----------|----------------|----------------|
| VLAN 10 | HR | 192.168.10.0/24 | 192.168.10.1 |
| VLAN 20 | IT | 192.168.20.0/24 | 192.168.20.1 |
| VLAN 30 | Sales | 192.168.30.0/24 | 192.168.30.1 |
## Kiến thức áp dụng
- VLAN
- Trunk
- Router-on-a-Stick
- Inter-VLAN Routing
- DHCP
- DNS
- Web Server
## Kết quả đạt được
- ✅ Chia mạng thành 3 VLAN.
- ✅ Cấu hình Trunk giữa Core Switch và Access Switch.
- ✅ Các VLAN giao tiếp được với nhau.
- ✅ PC nhận IP tự động từ DHCP.
- ✅ Phân giải tên miền bằng DNS.
- ✅ Truy cập Web Server thành công.
## File trong project
- `Network.pkt`: File Packet Tracer.
- `Topology.png`: Sơ đồ mạng.
- `Screenshots/`: Ảnh cấu hình và kết quả kiểm tra.

Tác giả: Tiến Đạt