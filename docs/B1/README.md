# Ghi Chú:

-	16h30h -> 17h điểm danh.
-	17h bắt đầu học.
-	Học chăm chỉ sẽ có những phần thưởng có giá trị.
-	Bài tập có * là bài tập về nhà, bắt buộc nộp, buổi sau sẽ lên làm và sửa trước khi học bài mới – thời gian sửa 16h30 -> 16h50.
-	Link bài học – tài liệu sẽ up vào cuối buổi học trên Github + link video Youtube +  link codepen.io.
-	Link code  + preview: codepen.io
-	Video của buổi học sẽ up vào cuối buổi trên Youtube.

## 1.Cấu trúc file html

Dưới đây là một ví dụ cơ bản về cấu trúc cơ bản của một html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```
- `<head></head>`: thêm title, link css, javascript, meta...
- `<body></body>`: nơi đặt các thẻ html, định dạng style cũng là nơi đặt javascript

## 2. Tạo một project web cơ bản
Project gồm 3 phần:
- > file index.html
- > thư mục style
    - > thư mục js (chứa các file javascript)
    - > thư mục css (chứa các file css)
    - > thư mục font (chứa các font, font-icon)
- > thư mục chứa hình
## 3. List

`List` dùng để tạo ra các danh sách, dùng để tạo ra các menu...
Có 2 loại `list` chính, thường sử dụng:
- `<ul>` - dạng danh sách không theo thứ tự như là A, B, C hay 1, 2, 3
- `<ol>` - dạng danh sách có theo thứ tự như là A, B, C hay 1, 2, 3

### Ví dụ về `<li>`:
```html
<ul>
    <li>A</li>
    <li>B</li>
    <li>C</li>
</ul>
```
<ul>
    <li>A</li>
    <li>B</li>
    <li>C</li>
</ul>

### Ví dụ về `<ol>`:
```html
    <ol>
        <li>A</li>
        <li>B</li>
        <li>C</li>
    </ol>
```
<ol>
    <li>A</li>
    <li>B</li>
    <li>C</li>
</ol>

### Custom type-style
- Với `<ul>'
    <ul type="circle">
        <li>A</li>
        <li>B</li>
        <li>C</li>
    </ul>

- với `<ol>`
    
 <ol type="a">
    <li>A</li>
    <li>B</li>
    <li>C</li>
</ol>   
    
