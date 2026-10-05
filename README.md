# Bài 4 - Quản lý tệp tin bỏ qua (.gitignore) và Sửa lịch sử (Amend)

## 1. Mục tiêu

Bài thực hành thực hiện các nội dung:

- Tạo file `.gitignore` để bỏ qua các file không cần thiết.
- Bỏ qua file chứa thông tin nhạy cảm `credentials.txt`.
- Gỡ file `credentials.txt` khỏi Git bằng `git rm --cached`.
- Giữ nguyên file `credentials.txt` trên máy tính.
- Sửa thông điệp của commit gần nhất bằng `git commit --amend`.
- Kiểm tra trạng thái Git bằng `git status`.
- Kiểm tra commit gần nhất bằng `git log -n 1`.

---

## 2. Tạo file credentials.txt

Tạo file:

```text
credentials.txt