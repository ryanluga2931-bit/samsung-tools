# Samsung Flash Tools

Công cụ flash lại điện thoại Samsung bằng Odin + app cầu nối remote. Tải trực tiếp về máy Windows để cài lại.

## Công cụ flash

| File | Dùng để |
|---|---|
| `Odin3_v3.14.4.zip` | Odin bản mới nhất — flash firmware (khuyên dùng) |
| `Odin3_v3.13.1.zip` | Odin bản cũ hơn — dùng nếu 3.14 lỗi với máy cũ |
| `USB_Drivers_1.5.27.0.rar` | Driver USB Samsung — cài TRƯỚC khi cắm máy vào Odin |
| `ADB_Fastboot.zip` | ADB & Fastboot (platform-tools) |

## App cầu nối remote (cài trên máy Windows ở nơi khác)

| File | Dùng để |
|---|---|
| `AnyDesk.exe` | Điều khiển màn hình từ xa (cài + chạy, đọc mã 9 số cho người kia vào) |
| `tailscale-setup-1.90.9-amd64.msi` | VPN mesh — làm cầu để SSH tới máy xử lý flash |

## Tải nhanh (link raw — dán vào trình duyệt máy Windows)

- Odin 3.14.4: `https://github.com/ryanluga2931-bit/samsung-tools/raw/main/Odin3_v3.14.4.zip`
- USB Drivers: `https://github.com/ryanluga2931-bit/samsung-tools/raw/main/USB_Drivers_1.5.27.0.rar`
- ADB/Fastboot: `https://github.com/ryanluga2931-bit/samsung-tools/raw/main/ADB_Fastboot.zip`
- AnyDesk: `https://github.com/ryanluga2931-bit/samsung-tools/raw/main/AnyDesk.exe`
- Tailscale: `https://github.com/ryanluga2931-bit/samsung-tools/raw/main/tailscale-setup-1.90.9-amd64.msi`

## Thứ tự cài trên máy Windows mới
1. USB Drivers Samsung (cài trước)
2. AnyDesk (mở, đọc mã cho người điều khiển)
3. Tailscale (cài + đăng nhập để làm cầu SSH)
4. Odin (giải nén, chạy — không cần cài)

## Firmware
Firmware (bản `_fac.zip` mỗi máy 5-7GB) KHÔNG để ở đây — tải trực tiếp online từ samfw.com / sammobile theo đúng model (SM-A175F, SM-A235F, SM-A256E, SM-A166P, SM-A245F, SM-A165F...).
