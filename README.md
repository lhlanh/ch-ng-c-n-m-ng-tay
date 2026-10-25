# 🖐️ Chống Cắn Móng Tay

Trang web dùng camera máy tính để phát hiện khi bạn đưa tay lên miệng (cắn móng tay) và phát còi báo động. Bỏ tay xuống thì còi tắt.

## Cách chạy

1. Tải về: bấm **Code → Download ZIP**, rồi giải nén.
2. Mở file `index.html` bằng **Chrome** hoặc **Edge**.
3. Bấm **▶ Bắt đầu**, rồi bấm **Cho phép** khi trình duyệt hỏi quyền camera.

Không cần cài gì thêm. Máy cần có **Internet** để tải mô hình AI (vài MB, chỉ tải lần đầu).

## Tùy chỉnh

- **Độ nhạy**: kéo lên thì dễ báo động hơn, kéo xuống nếu bị báo nhầm (ví dụ khi chống cằm).
- **Âm lượng**: chỉnh độ to của còi.
- **Âm thanh báo động**: bấm **📁 Chọn file âm thanh** để dùng file mp3/wav của bạn (được nhớ cho lần sau), hoặc đặt file tên `alarm.mp3` cạnh `index.html`. Không có file thì dùng còi hú mặc định.
- **Hiện điểm nhận diện**: hiện vòng tròn quanh miệng và các điểm trên tay.

## Quyền riêng tư

Hình ảnh camera chỉ được xử lý ngay trên máy bạn (dùng [MediaPipe](https://ai.google.dev/edge/mediapipe)), không gửi đi đâu cả.
