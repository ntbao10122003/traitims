# 💖 Hiệu Ứng Mở Quà Trái Tim - Ngọc Châm

Dự án chuyển đổi chính xác **100% logic thuật toán và hệ thống hạt** từ file Python Tkinter (`heartpython.py`) sang chuẩn web **HTML5 Canvas & JavaScript thuần**.

---

## 🌟 Trải Nghiệm & Tính Năng

1. **Hộp thoại mở quà bất ngờ**:
   - Khi vừa vào trang, hiển thị câu hỏi: *"Bạn có muốn mở món quà này không? ✨"*.
   - Có 2 nút: **"Mở quà 💕"** và **"Không mở 🥺"**.
   - Nếu bấm **"Không mở"**: Nút **"Mở quà"** sẽ tự động **to dần lên** sau mỗi lần click, kèm theo các câu năn nỉ dễ thương.
   - Chỉ khi bấm **"Mở quà"**: Hộp thoại mới mờ dần đi và hiệu ứng trái tim cùng chữ **Ngọc Châm** mới bắt đầu xuất hiện và đập theo nhịp.

2. **Bảo toàn 100% logic code gốc**:
   - Phương trình trái tim parametric, thuật toán tán xạ hạt bên trong (`scatter_inside`), co giãn hào quang viền (`shrink`), đường cong co bóp nhịp đập (`curve`), và tham số lực biến dạng ma thuật (`0.520`).
   - Tốc độ nhịp đập chuẩn: 160ms/frame (~20 frame) của Tkinter gốc.

3. **Căn giữa và tương thích mọi thiết bị**:
   - Tự động co giãn phù hợp trên cả điện thoại (màn hình dọc), máy tính bảng và PC.

---

## 🚀 Hướng Dẫn Deploy Lên Netlify

### Cách nhanh nhất: Netlify Drop (Chỉ 10 giây) ⭐ Khuyên dùng

1. Truy cập vào trang: [https://app.netlify.com/drop](https://app.netlify.com/drop) (đăng nhập tài khoản Netlify của bạn).
2. Kéo thả toàn bộ thư mục **`traitim`** vào khung tải lên của Netlify.
3. Đợi vài giây, Netlify sẽ tạo ngay link web trực tiếp (ví dụ: `https://ten-ngau-nhien.netlify.app`).
4. Bạn có thể vào mục **Site configuration > Change site name** để đổi tên link theo ý thích (ví dụ: `https://ngoc-cham.netlify.app`).
