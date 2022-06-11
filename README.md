<p align="center"><img src="https://avatars.githubusercontent.com/u/91626055?v=4" width="128" /></p>

<div align="center">

# AikoAir-Universe
Air-Universe AikoCute Projects

[![](https://img.shields.io/badge/Telegram-group-green?style=flat-square)](https://t.me/aikocutehotme)
[![](https://img.shields.io/badge/Telegram-channel-blue?style=flat-square)](https://t.me/AikoCute_Support)
[![](https://img.shields.io/github/downloads/AikoAir-Universe/Air-Universe/total.svg?style=flat-square)](https://github.com/AikoAir-Univeverse/Air-Universe/releases)
[![](https://img.shields.io/github/v/release/AikoAir-Universe/Air-Universe?style=flat-square)](https://github.com/AikoAir-Univeverse/Air-Universe/releases)
[![docker](https://img.shields.io/docker/v/aikocute/airu?label=Docker%20image&sort=semver)](https://hub.docker.com/r/aikocute/airu)
[![Build and Release](https://github.com/AikoAir-Universe/Air-Universe/actions/workflows/release.yml/badge.svg)](https://github.com/AikoAir-Universe/Air-Universe/actions/workflows/release.yml)
<img alt="visited" src="https://badges.pufler.dev/visits/AikoAir-Universe/Air-Universe"/>
</div>


# Backend Air-Universe

Aiko đa chức năng mã nguồn mở , Giao thức hỗ trợ V2Ray (VMess), Trojan, Shadowsocks (một cổng đa người dùng) ; bảng điều khiển hỗ trợ SSPanel, v2board.

> Nhóm TG phản hồi: https://t.me/Aikocutehotme <br>
> Thích dự án này, cho chúng tôi Star⭐

## Tài liệu

- Không có

## Giới thiệu chức năng

> √: Để sử dụng chức năng này, bạn chỉ cần sử dụng tập lệnh một cú nhấp chuột mà không cần sự can thiệp của người dùng <br>
> Thủ công : Việc sử dụng chức năng này yêu cầu người dùng tự định cấu hình và người dùng cần sửa đổi thủ công tệp cấu hình Xray hoặc cập nhật chương trình Xray <br>
> ×: Chức năng này hiện không được hỗ trợ



| Chức năng                          | VMess | Trojan | Shadowsocks | Vless |
| ---------------------------------- | ----- | ------ | ----------- | ----- |
| Tự động định cấu hình các nút      |  √    |  √     |  √          |   ×   |
| Nhận thông tin người dùng          |  √    |  √     |  √          |   √   |
| Thống kê lưu lượng người dùng      |  √    |  √     |  √          |   √   |
| Báo cáo thông tin máy chủ          |  √    |  √     |  √          |   √   |
| Tự động đăng ký chứng chỉ TLS      |  √    |  √     |  √          |   √   |
| Tự động gia hạn chứng chỉ tls      |  √    |  √     |  √          |   √   |
| Đếm số người trực tuyến            |  √    |  √     |  √          |   √   |
| Hạn chế Người dùng Trực tuyến      |  ×    |  ×     |  ×          |   ×   |
| Quy tắc kiểm tra                   | HDSD  | HDSD   |     HDSD    |  HDSD |
| Báo cáo kiểm toán                  |  ×    |  ×     |  ×          |   ×   |
| Giới hạn tốc độ cổng nút           | HDSD  | HDSD   |     HDSD    |  HDSD |
| Theo giới hạn tốc độ của người dùng| HDSD  | HDSD   |     HDSD    |  HDSD |
| DNS tùy chỉnh                      | HDSD  | HDSD   |     HDSD    |  HDSD |


- Cấu hình Xray hoàn toàn có thể tùy chỉnh
- Shadowsocks một cổng đa người dùng Không cần giao thức và hỗ trợ plug-in làm xáo trộn , sử dụng cổng đơn mã hóa AEAD (có sẵn Clash gốc)
- Hỗ trợ đa nút khởi động đơn, đa nút máy chủ đơn không cần mở nhiều chương trình, nhiều đầu vào với ID đa nút, thống kê lưu lượng truy cập riêng
- Các quy tắc kiểm tra chặn BT và IP mạng nội bộ theo mặc định, bạn có thể tự thêm các quy tắc này nhưng không hỗ trợ kéo từ bảng điều khiển
- Các loại nút cho cấu hình được tạo tự động
    - Tất bóng
    -VMess (V2ray)
      - Phương thức truyền : TCP, Websocket, KCP, HTTP
      - Mã hóa lớp truyền tải : TLS
    - Trojan (TCP + TLS)


## Hỗ trợ giao diện người dùng

| Bảng điều khiển     | v2ray | trojan | shadowsocks |
| ------------------- | ----- | ------ | ----------- |
| sspanel-uim         | √     | √      | √           |
| v2board             | √     | √      | √           |


