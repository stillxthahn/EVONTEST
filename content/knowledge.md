# HTML

- attributes: thuộc tính
- _div_: là thẻ `block`, thường dùng để bao 1 khối chưa nhiều phần tử, đây là thẻ thông dụng nhất và được dùng nhiều nhất
- _p_: là thẻ `block`, thường dùng để hiển thị văn bản, có nhiều chữ và thường là các chữ nhỏ
- _a_: là thẻ `inline`, thường dùng để cho mục đích là liên kết, có `href` là thuộc tính để điền vào đường dẫn, muốn nhấn vào mở tab mới thì thêm thuộc tính `target="\_blank"`, nếu sử dụng target là \_blank thì nên thêm thuộc tính `rel="noopener norefferer"`
- _header_: thường dùng cho các khối ở trên
- _footer_: thường dùng cho khối dưới cùng của trang
- _main_: là phần chính của trang
- _article_: thẻ block, thường dùng cho các giao diện dạng bài viết
- _aside_: thẻ block, thường dùng cho các giao diện sidebar
- _span_: là thẻ inline, thường dùng cho các đoạn chữ ngắn
- _strong_, _b_: là thẻ inline, chức năng tương tự thẻ span, nhưng nó khác ở chỗ là làm cho chữ in đậm
- _em_, _i_: là thẻ inline, chức năng tương tự span, nhưng làm cho chữ in nghiêng
- h1->h6: thẻ block, nó dùng cho các tiêu đề từ lớn đến nhỏ
- _h1_: trong 1 trang chỉ có tối đa 1 thẻ h1 mà thôi vì nó liên quan tới SEO
- _h2_: thường đại diện cho 1 khối lớn
- _h3_: đại diện cho khối nhỏ hơn
- _h4_: tiêu đề nhỏ
- _img_: là thẻ inline, dùng để hiển thị hình ảnh, `src` là để truyền vào đường dẫn hình ảnh, đường dẫn hình có thể lấy từ thư mục đang làm hoặc là hình ảnh online, `alt`(alternate text) mô tả tên tấm ảnh(liên quan tới SEO), là thẻ tự đóng
- _br_: xuống hàng mới, là thẻ tự đóng
- _hr_: sẽ tạo ra đường kẻ ngang, là thẻ tự đóng
- _ul_: thường dùng để hiển thị danh sách không có thứ tự(ko có đánh số)
- _ol_: thường hiển thị danh sách có đánh số
- thẻ đóng mở có thể chứa các thẻ khác,
- thẻ div có thể chứa thẻ div, thẻ div chứa hầu hết các thẻ khác đều được
- thẻ a không nên chứa thẻ a
- thẻ tự đóng là thẻ không có children(con): img, br, hr
- thẻ p không chứa được thẻ div, thẻ p(chính nó)
- _class_ là thuộc tính dùng cho các thẻ, mục đích của nó là để styling trong CSS, hoặc truy vấn trong Javascript, class có thể trùng nhau, class có nhiều cách đặt tên, thông thường hay gặp là BEM(Block\_\_Element--Modifier)
- _id_ là thuộc tính dùng cho các thẻ, id là duy nhất cho nên ko được trùng nhau, cũng dùng cho truy vấn trong Javascript
- vấn đề đặt tên không được tốt là do thiếu vốn từ tiếng Anh
- Naming convention: tên ngắn gọn, dễ hiểu, không dấu, không có khoảng trắng. 1 ví dụ tốt: header, header-item, button, button--primary
- 2 dấu -- gọi là modifier nghĩa là tùy biến của một thành phần
- Block\_\_Element--modifier
- Block: header
- Element: search, user, noti, message, button
- Modifier: header big, header small, search long, search gray, user rounded, user round, noti small, message active, message unactive, button big, button primary, button secondary
- BEM: header--big, header--small, search--gray, buttoon--primary, button--secondary, header\_\_button--primary
- evondev way: buton--primary, button, header-button
- Từ tiếng Anh hay gặp: danh sách(list)
- phần tử(item)
- tiêu đề(title
- heading)
- nội dung(content)
- chữ(text)
- hình ảnh(image
- img
- avatar)
- liên kết(link
- url)
- đường dẫn(url
- src)
- thông tin(info)
- thời gian(time)
- khối(box
- boxed)
- viền(border
- line)
- trạng thái(status)
- kích hoạt(active/unactive)
- xóa(delete
- remove)
- cập nhật(update) thêm(new
- create)
- sửa(edit
- change)
- biểu tượng(icon)
- đánh giá(review
- rating)
- thích(like
- love)
- đánh dấu(saved
- bookmark)
- tab
- slider
- progress
- slider bullet
- tìm kiếm(search)
- dropdown(danh sách sổ xuống)
- lớp phủ(overlay)
- ...

# Gõ nhanh HTML trong VSCode

- Settings: Trigger expandsion on Tab: checked
- class: dấu chấm(.)
- dấu + tạo nhiều thành phần liền kề nhau
- dấu > để tạo ra thành phần là thành phần con
- dấu \* để tạo ra số lượng mà mình muốn
- dấu {item $} nó sẽ tạo ra chữ đánh số nếu mình dùng dấu \* ở trên
- Khi gõ emmet HTML thì không nên có khoảng trắng
- dấu ^ nghĩa là cùng cấp, dùng trong trường hợp đã đi sâu vào phần tử của phần tử trước đó
- dấu [] dành cho việc các thuộc tính khác ngoài class và id

# CSS

- Thẻ block: là thẻ có độ rộng 100% thằng chứa nó( chưa áp dụng CSS), khi các thẻ block nằm với nhau thì nó sẽ rớt xuống và tạo hàng mới
- Thẻ inline: là thẻ có độ rộng bằng với nội dung nó chứa, khi các thẻ inline nằm với nhau thì nó sẽ nằm cạnh nhau, hạn chế 1 vài thuộc tính CSS
- Thẻ inline-block: nó sẽ có độ rộng bằng với nội dung nó chứa, nó không bị hạn chế về CSS, khi nằm với nhau thì không bị rớt xuống hàng, có 1 khoảng trống tầm 4px ở giữa
- display: inline, block, inline-block
- ./: cùng cấp
- ../: truy xuất ở trong ra ngoài
- user agent stylesheet: CSS mặc định của trình duyệt
- \*: là selector chọn toàn bộ các thẻ trong HTML
- _selectors_:
- tags(h1, header, div, p, span, a, img..)
- class: .heading, .button, .section--primary
- id: #header, #main, #container, #footer
- attributes: href, src, rel, target, arial-label, placeholder, type, name, disabled, alt...
- đối với các thuộc tính ngoài class và id thì dùng dấu []
- [alt="evondev-image"] -> chọn toàn bộ các thẻ có thuộc tính alt là "evondev-image"
- img[alt="evondev-image"] -> chọn toàn bộ thẻ `img` có thuộc tính alt là "evondev-image"
- dấu = nghĩa là chính xác tuyệt đối
- dấu ^ nghĩa là bắt đầu với
- a[href^="https"] -> chọn toàn bộ các thẻ a có thuộc tính href `bắt đầu` bằng chữ https
- a[href$=".com"] -> chọn toàn bộ các thẻ a có thuộc tính href `kết thúc` bằng chữ .com
- a[href*="com"] -> chọn toàn bộ các thẻ a có thuộc tính href `có chứa` chữ .com
- a[lang|="en"] -> chọn toàn bộ các thẻ a có thuộc tính lang là chữ `en` hoặc bắt đầu với chữ `en-`

# CSS cơ bản

- color: đổi màu chữ
- line-height: khoảng cách giữa các dòng chữ
- word-break: phù hợp cho những đoạn chữ dài dính nhau, làm cho nó tự ngắt xuống dòng
- white-space: nowrap làm cho chữ luôn nằm trên 1 hàng
- letter-spacing: khoảng cách giữa các kí tự
- word-spacing: khoảng cách giữa các từ
- text-align: căn lề cho chữ
- text-decoration: gạch cho chữ, giữa, trên và dưới
- text-indent: di chuyển chữ vào trong hoặc ra ngoài
- serif: chữ có gạch chân
- sans-serif: chữ không có gạch chân
- baseline: đáy chữ
- overflow: hidden -> nếu nội dung bị tràn thì sẽ bị cắt mất đi
- text-overflow: ellipse -> nếu kết hợp overflow hidden thì nó sẽ hiển thị dấu 3 chấm ...
- cắt chữ 1 dòng thì kết hợp thêm white-space: nowrap
- cắt chữ nhiều dòng thì kết hợp thêm display: -webkit-box; -webkit-box-orient: vertical -webkit-line-clamp: 3; ko nên dùng white-space: nowrap
- font-weight: độ đậm nhạt của chữ
- font-style: in thường hoặc in nghiêng
- font-family: tên font
- font-size: kích thước chữ px rem em ch vw vh %
- background-color -> màu nền
- object-fit: cover(phủ), contain(theo tỉ lệ tấm ảnh gốc)
- object-position: căn chỉnh trên dưới hoặc trung tâm
- cursor: con trỏ
- border-radius: bo góc, giá trị càng lớn thì bo càng lớn, muốn bo góc hình tròn thì khối nên là hình vuông
- `border-radius: 1px` nghĩa top=right=bottom=left = 1px
- `border-radius: 2px 4px` nghĩa top-left-radius=bottom-right-radius = 2px, top-right-radius=bottom-left-radius = 4px
- `border-radius: 2px 4px 6px` nghĩa top-left-radius = 2px, top-right-radius=bottom-left-radius = 4px, bottom-right-radius: 6px
- `border-radius: 2px 4px 6px 8px` nghĩa top-left-radius = 2px, top-right-radius = 4px, bottom-right-radius: 6px, bottom-left-radius=8px;
- list-style: hiển thị phía trước thẻ li khi dùng trong ol hoặc ul

## Box-sizing

- _content-box_:
- độ rộng = độ rộng(trong css) + padding-left + padding-right + border-left + border-right
- chiều cao = chiều cao(trong css) + padding-top + padding-bottom + border-top + border-bottom
- _border-box_:
- độ rộng = độ rộng(đã trừ padding-left, padding-right, border-left, border-right) + padding-left + padding-right + border-left + border-right
- chiều cao = chiều cao(đã trừ padding-top, padding-bottom, border-top, border-bottom) + padding-top + padding-bottom + border-top + border-bottom

## Margin

- `margin`: có 4 hướng top right bottom và left, giá trị của margin có thể là số âm, số dương và auto
- margin-left và margin-right auto không cho ra giữa đối với inline
- `margin: 1px` nghĩa là top=right=bottom=left = 1px
- `margin: 1px 2px` nghĩa top=bottom = 1px, right=left = 2px
- `margin: 1px 2px 3px` nghĩa là top= 1px right=left = 2px và bottom = 3px
- `margin: 1px 2px 3px 4px` top = 1px, right = 2px, bottom = 3px, left = 4px
- `margin: 0 auto` nghĩa là làm khối chạy ra giữa(chỉ có tác dụng với block hoặc flex)
- `margin-inline: auto` tương đương margin-left: auto và margin-right: auto
- `margin-block: auto` tương đương margin-top: auto và margin-bottom: auto
- _margin-collapse_: trường hợp phần tử dùng margin-bottom và margin-top đứng trên dưới, thì giá trị nào lớn hơn nó sẽ lấy giá trị đó, nếu bằng nhau thì lấy 1 trong 2
- có thể khắc phục bằng cách dùng inline-block
- dùng `text-align: center` cho thằng cha chứa inline-block nếu muốn inline-block ra giữa(center)

## Padding

- padding ko dùng được số âm(>=0)
- khi để độ rộng hoặc chiều cao là auto, thì nếu tăng padding lên thì kích thước cũng sẽ tăng theo
- khi để độ rộng hoặc chiều cao là cố định, khi dùng padding nên lưu ý cẩn thận chiếm hết diện tích của width height
- nếu không sử dụng padding thì nên thiết lập width và height cố định
- khi sử dụng padding và không thiết lập width height cố định: tăng font-size, line-height thì width và height sẽ tăng theo
- nên thiết lập padding left và padding right để không bị dính chữ hai bên(UI)

## Border, outline

- border thuộc về box-sizing, còn outline thì không
- border: border-width border-style border-color
- border-width: 2px, 3px
- border-style: solid, dashed, double, dotted
- border-color: red, #ff6bcb, rgb, rgba, hsl

# CSS

- `currentColor`: nó sẽ lấy giá trị của thuộc tính color
- `opacity: 0` nghĩa là không thấy, nhưng vẫn chiếm diện tích và có thể rê chuột vào được(con trỏ)
- `visibility: hidden` là không thấy, vẫn chiếm diện tích nhưng không rê chuột vào được(con trỏ)
- `display: none` là ko thấy, ko chiếm diện tích, ko còn gì cả
