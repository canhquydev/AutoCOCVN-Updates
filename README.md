# AutoCOCVN Official OTA Update Repository

- **Latest Version**: `v6.0.39`
- **Updated At**: `2026-11-17 10:46:41`

### Nội dung cập nhật (VI)
Tối ưu hóa cơ chế zoom_out (u2) cho đa giả lập: tái sử dụng worker thread chống kẹt khi timeout, tự phục hồi uiautomator và thử lại khi lỗi kết nối.

### Update Notes (EN)
Optimized u2 zoom_out for multi-emulator stability: reused worker thread to prevent hang lockouts, auto-reset uiautomator and retry on transient RPC errors.
