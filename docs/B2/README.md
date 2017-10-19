# Buổi 2: CSS - Lý thuyết - Bài tập làm trên máy.

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

## ID VÀ CLASS
- Phân biệt `class` và `id`.
  + id được ưu tiên hơn class.
  + trong class có thể đặt được, chứa nhiều tên class, id thì chỉ được chứa 1 tên.
  + class, id được đặt trong thẻ DIV.
  Ví dụ
  
```html
<div class="menu top-menu">
  
</div>
<div class="menu">
  
</div>
```
### Bài tập phân biệt độ ưu tiên giữa id và class.
  - Nói về các các cách chèn css.
  - Định dạng màu chữ, kích thước.
  - border và các con của border: border-radius, border-width, border-color.
  - Nói padding và margin, sử dụng border để ví dụ.
## DISPLAY
- Các Giá trị thông dụng của display
- Block, Flex, Inline-block
- Ví dụ: làm một menu dọc + css....
- Ví dụ menu ngang + css

### Flex: có thể dùng để chia layout, dùng để canh chỉnh một phần tử....
- Ví dụ về sử dụng flex để canh chỉnh
- Muốn sử dụng flex, thì phải có <b>height</b>
- Các dạng flexbox...
- justify-content
- align-items

## POSITION
- Fixed, relative, absolute
- Ví dụ về 3 cái trên
- Làm một bài tập chèn chữ lên hình - z-index.
- Muốn sử dụng z-index thì phải có position: relative.
