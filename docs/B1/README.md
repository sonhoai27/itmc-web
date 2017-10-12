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
- > Các file .html
- > Thư mục style
    - > thư mục js (chứa các file javascript)
    - > thư mục css (chứa các file css)
    - > thư mục font (chứa các font, font-icon)
- > Thư mục chứa hình
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
- Với `<ul>`
```html
<ul type="circle">
    <li>A</li>
    <li>B</li>
    <li>C</li>
</ul>
```
<ul type="circle">
    <li>A</li>
    <li>B</li>
    <li>C</li>
</ul>

- với `<ol>`
```html
<ol type="a">
    <li>A</li>
    <li>B</li>
    <li>C</li>
</ol>
```
<ol type="a">
    <li>A</li>
    <li>B</li>
    <li>C</li>
</ol>

- > Một số thẻ html có thể dùng trong `<li>`:
    - `<a>`: đường dẫn, liên kết, `<target>`.
    - `<span>` và `<p>`: phân biệt.
    - Các thẻ `<h>`.
    - `<iframe>`.
    
#### Bài tập 1: Dùng `<ul>`, `<li>`, `<iframe>` và `<a>` để tạo một liên kết tới một trang khác trong cùng một cửa sổ mà không phải chạy, load tới trang có địa chỉ gì đó.
#### Bài tập 2: Sử dụng `list` để làm bài sau:
<ul>
    <li>A
        <ol type="I">
            <li>1</li>
            <li>2</li>
            <li>
                <ul>
                    <li>AA</li>
                    <li>BB</li>
                </ul>
            </li>
        </ol>
    </li>
    <li>B</li>
    <li>C</li>
</ul>



## 3. Table
Ví dụ về `<table>`

```html
<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th> 
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
  <tr>
    <td>John</td>
    <td>Doe</td>
    <td>80</td>
  </tr>
</table>
```
<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th> 
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
  <tr>
    <td>John</td>
    <td>Doe</td>
    <td>80</td>
  </tr>
</table>

- `<tr>`: là dòng.
- `<td>`: là cột.

- `<rowspan>`: <b>gộp dòng</b>.

Ví dụ:
```html
<table style="width:100%">
    <tr>
        <td rowspan="2">A</td>
        <td>B</td>
        <td>C</td>
        <td>C</td>
    </tr>
    <tr>
        <td>2</td>
        <td>3</td>
        <td>4</td>
    </tr>
</table>
```


<table style="width:100%">
    <tr>
        <td rowspan="2">A</td>
        <td>B</td>
        <td>C</td>
        <td>C</td>
    </tr>
    <tr>
        <td>2</td>
        <td>3</td>
        <td>4</td>
    </tr>
</table>


- `<colspan>`: <b>gộp cột</b>.

Ví dụ:
```html
<table style="width:100%">
    <tr>
        <td colspan="2">A</td>
        <td>C</td>
        <td>C</td>
    </tr>
    <tr>
        <td>1</td>
        <td>2</td>
        <td>3</td>
        <td>4</td>
    </tr>
</table>
```


<table style="width:100%">
    <tr>
        <td colspan="2">A</td>
        <td>C</td>
        <td>C</td>
    </tr>
    <tr>
        <td>1</td>
        <td>2</td>
        <td>3</td>
        <td>4</td>
    </tr>
</table>
