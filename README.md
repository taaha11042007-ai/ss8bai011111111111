# DEBUG REPORT - SAAS SUBSCRIPTION

## 1. Mô tả lỗi

Chương trình có lỗi trong quá trình duyệt mảng struct `user_list`.

Vòng lặp sử dụng biến `i` để duyệt từ phần tử 0 đến phần tử 3:

```c
for (i = 0; i < 4; i++)
