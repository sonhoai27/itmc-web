# Buổi 2: CSS

### Học các phần sau:
- `<div>`.
- Phân biệt giữa `id` và `class`, độ ưu tiên giữa `class` và  `id`.
- `Color`, `font-size`, `font-weight`, `width`, `height`...
- Phân biệt giữa `padding`, `margin`.
- Display - bài tập làm menu ngang, dọc.
- Hover một đối tượng, thẻ...
- Sử dụng ">" để định dạng một thẻ, đối tượng nào đó.
- Position - bài tập chèn chữ lên hình.
- Bài tập về nhà sử dụng các cái đã học làm bài sau: 
<img src="http://bashooka.com/wp-content/uploads/2015/08/card-ui-designs-15.jpg">

## DIV
- Dịch là "Khu", được sử dụng để tạo ra một khu vực nào đó trong website ở dụng Block. Gom nhóm các thành phần nhỏ lại tạo thành  một thành phần lớn.
- Ví dụ Khu vực sidebar bên phải của website, những thành phần như ô tìm kiếm, bài viết mới... được đặt, gom nhóm lại trong thẻ `<div>`.
<br>
Hình minh họa
<img src="https://thachpham.com/wp-content/uploads/2015/04/html-div-sample.png">
<br>
- Phân biệt `class` và `id`.
  + id được ưu tiên hơn class
  + trong class có thể đặt được, chứa nhiều tên class, id thì chỉ được chứa 1 tên.
  + class, id được đặt trong thẻ `<div>`.
  Ví dụ
  
```html
<div class="menu top-menu">
  
</div>
<div class="menu">
  
</div>
```
