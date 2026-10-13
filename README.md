# 🧭 Unit 5 — Where Are You Going? · 你去哪儿？(Nǐ qù nǎr?) · Lesson 1

Trang web học đa ngữ (Anh – Trung) cho trẻ **4–10 tuổi**. Trẻ chọn từng hoạt động và **được dán ⭐ khi hoàn thành**. Tiến trình lưu tự động trên máy của trẻ.

## 📚 6 hoạt động

1. 🧠 **Vocabulary** (Wordwall)
2. ✏️ **Quiz** (Wordwall)
3. 🀄 **Chinese vs Pinyin** (Wordwall)
4. 📝 **Complete the Sentences** (Wordwall)
5. 🧩 **Unjumble** (Wordwall)
6. ✍️ **Let's Write!** (app tập viết chữ Hán, nằm ngay trong repo này — file `letswrite.html`)

Có **nút Trang chủ**, thanh **tab trượt ngang**, **tự đánh dấu hoàn thành** (✓/✅), thanh **tiến trình ⭐**, màn **ăn mừng 🏆** khi đủ 6 mục, nút **Đặt lại tiến trình**. Thân thiện điện thoại & iPad.

> **Mới:** App Tập viết (Let's Write) đã được gộp thẳng vào trang này — không còn phụ thuộc repo `canopyu5l1` riêng. Tab Let's Write nhúng file `letswrite.html` cùng thư mục. Chỉ cần quản lý **một repo duy nhất**.

## 🚀 Đưa lên GitHub Pages

1. Tạo repository mới (ví dụ `unit5-lesson1`).
2. **Add file → Upload files**, kéo **cả hai file** `index.html` **và** `letswrite.html` (và `README.md` nếu muốn) vào, **Commit changes**.
3. **Settings → Pages → Source**: **Deploy from a branch**, nhánh `main`, thư mục `/ (root)`, **Save**.
4. Đợi 1–2 phút, mở `https://<tài-khoản>.github.io/unit5-lesson1/`.

> ⚠️ Phải có **cả `letswrite.html`** trong repo thì tab Let's Write mới hiện. Thiếu file này tab sẽ trống.

## 🔗 Nội dung nhúng

| Hoạt động | Nguồn |
|-----------|-------|
| Vocabulary | Wordwall `856857fc…` |
| Quiz | Wordwall `167df860…` |
| Chinese vs Pinyin | Wordwall `6bd7a540…` |
| Complete the Sentences | Wordwall `ba0504df…` |
| Unjumble | Wordwall `e1193c72…` |
| Let's Write! | `letswrite.html` (cùng repo) |

## ✏️ Đổi nội dung / sửa app Tập viết

- Thay hoạt động khác: mở `index.html`, tìm `const CATS = [ ... ]` gần cuối, sửa dòng tương ứng (`type:'wordwall'` dán link nhúng; `type:'external'` là trang/app nội bộ, dán tên file như `letswrite.html`).
- Sửa app Tập viết (cỡ hình ở tab Nhận diện, độ mờ, nội dung chữ…): sửa trực tiếp trong `letswrite.html`.

## 📌 Ghi chú

- Tiến trình lưu bằng `localStorage`, khóa riêng `progress_u5_lesson1_v1`.
- Mở qua **link https** của GitHub Pages thì Wordwall và tab Let's Write mới hiển thị (mở file `file://` trực tiếp sẽ bị chặn).
- App Tập viết cần Internet để tải dữ liệu nét chữ (Hanzi Writer qua CDN).
