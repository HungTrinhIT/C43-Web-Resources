# Bài kiểm tra: HTML - CSS

## Tổng quan: bài làm gồm 2 phần
- **Phần 1:** Trắc nghiệm 10 câu / 10 phút.
- **Phần 2:** Dàn lại layout như mẫu.

## Cách nộp bài
- **Bài 1:** các bạn làm trên trực tiếp trên link mình gửi.
- **Bài 2:** Đóng gói file html , css và folder chứa hình ảnh vào 1 thư mục với định dạng như sau:
```
Ví dụ: học viên: Lê Văn A
Thì định dạng tên folder sẽ là: Lê_Văn_A_HTML_CSS.rar
```
- Bài làm phải được nén trước khi nộp trên classroom

## Yêu cầu:
- **Bài 1:** thực hiện trực tiếp bài làm trên link sau: [Quiz test HTML - CSS](https://forms.gle/hG4fanQSm9VkAJraA)

- **Bài 2:**
    - Dàn 1 layouts như sau: [layouts](https://preview.uideck.com/items/unfold/#work)
    - Folder mẫu bao gồm **1 file html**, **1 file css** và **1 folder images** được chuẩn bị sẵn cho các bạn thực hiện **layouts** như trên: [Click here to download template](https://drive.google.com/file/d/1sNLfQ5HDczGhEIB7YWVfvFLvoEogNpFC/view?usp=sharing)
    - Không cần thực hiện các **animation** quá phức tạp như trong **layouts mẫu**. Chỉ cần các bạn dàn đúng layouts về vị trí các **components** như trong mẫu. Còn các hiệu ứng thì chỉ làm 1 số hiệu ứng cơ bản như đã học.

## Gợi ý:
- Tổng thể trang web gồm các màu chính sau đây: do đó mình có define sẵn các màu này, để dễ sử dụng lại, trong file css các bạn sẽ khai báo như sau:
```js
*{
    box-sizing:border-box;
    padding: 0;
    margin:0;
}
:root{
    
    --purple-color: #754ef9;
    --black-color: #000;
    --gray-color: #8a8fa3;
    --white-color: #ffffff;
    
    --bg-color-gray: #fbfbfb;
    --bg-color-white: #ffffff;
    
}

body{
    font-size:16px;
    color: var(--gray-color);
}

```
- Đọc kĩ đề, phân tích kỹ layouts, trước khi bắt tay vào code. Chỗ nào khó bí idea => skip làm component khác sau đó quay lại chỗ chưa làm được sau.

