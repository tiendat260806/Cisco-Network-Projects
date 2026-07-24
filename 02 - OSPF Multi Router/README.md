# OSPF Multi Router

## Giới thiệu

Đây là project mô phỏng hệ thống mạng doanh nghiệp có **3 chi nhánh** bằng Cisco Packet Tracer. Ba Router được kết nối với nhau theo mô hình tam giác và sử dụng giao thức định tuyến động **OSPF (Open Shortest Path First)** để trao đổi thông tin định tuyến. Đồng thời, Router cũng được cấu hình **DHCP** để tự động cấp phát địa chỉ IP cho các thiết bị trong từng mạng LAN.

## Mục tiêu

- Thiết kế mạng doanh nghiệp gồm 3 chi nhánh.
- Cấu hình địa chỉ IP cho Router.
- Cấu hình DHCP cấp phát IP tự động.
- Cấu hình OSPF trên nhiều Router.
- Quảng bá các mạng LAN và WAN bằng OSPF.
- Kiểm tra khả năng học route động.
- Đảm bảo các PC giữa các chi nhánh có thể liên lạc với nhau.

## Thiết bị sử dụng

- Router Cisco 2911 × 3
- Switch Cisco 2960 × 3
- PC × 6

## Địa chỉ IP

### LAN

| Chi nhánh | Network | Gateway |
|-----------|----------------|----------------|
| Branch 1 | 172.16.1.0/24 | 172.16.1.1 |
| Branch 2 | 172.16.2.0/24 | 172.16.2.1 |
| Branch 3 | 172.16.3.0/24 | 172.16.3.1 |

### WAN

| Kết nối | Network |
|----------|----------------|
| Router0 ↔ Router1 | 192.168.2.0/24 |
| Router1 ↔ Router2 | 192.168.3.0/24 |
| Router0 ↔ Router2 | 192.168.1.0/24 |

## Kiến thức áp dụng

- IPv4 Addressing
- DHCP
- OSPF Routing Protocol
- Multi Router Network
- Serial Connection
- LAN & WAN Design

## Kết quả đạt được

- ✅ Cấu hình DHCP cấp phát IP tự động cho các PC.
- ✅ Cấu hình thành công OSPF trên 3 Router.
- ✅ Các Router thiết lập OSPF Neighbor thành công.
- ✅ Các Router học route động thông qua OSPF.
- ✅ Toàn bộ PC ở 3 chi nhánh nhận IP tự động và ping được với nhau.
- ✅ Kiểm tra bảng định tuyến và quá trình định tuyến thành công.

Tác giả: Tiến Đạt