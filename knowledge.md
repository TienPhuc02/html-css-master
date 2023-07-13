- _div_ là thẻ block có độ rộng 100% phần tử chứa nó,lưu ý chưa nói tới vấn đề khi sử dụng CSS
- _div_ thường được dùng rất nhiều khi chia layout, gom 1 khối nào đó

- _img_ là thẻ inline , tự đóng dùng để hiển thị hình ảnh với 2 thuộc tính là src và alt

- _alt_ là alternate text nó dùng trong việc CEO, khi hình ảnh bị lỗi hoặc sai đường dẫn thì alt sẽ hiển thị
- _span_ là thẻ inline nó thường được dùng cho những đoạn chữ ngắn
- _class_ là thuộc tính dùng để sử dụng các class cho thẻ , sau đó dùng để styles cho CSS

- việc đặt tên class khá là nan giải,không nên đặt tên tiếng việt ,nên đặt tên tiếng anh dễ hiểu

- _Thẻ tiêu đề_ : h1,h2,h3,h4,h5,h6

- _h1_
  Mỗi trang chỉ có tối đa 1 thẻ h1 thôi, thẻ này dùng cho những tiêu đề lớn của trang

- _h2_:thường được dùng nhiều dùng cho những block to
- _h3_ :Dùng được nhiều , thường được dùng cho những block nhỏ

- _a_ : là thẻ inline chắc chắn là dùng cho liên kết nó có 3 thuộc tính hay dùng href ,target,rel

-khi dùng target có gì trị \_bank thì thẻ a nên thêm thuộc tính rel="noopener noreferrer"

- _font-weigth_: độ đậm nhạt của chữ 100-900 ,normal,bold,bolder,extra bold,thin ,regular,medium,semibold
- _font-family_: thiết lập font chữ, truyền vào là font name( tên của font chữ)
- _CSS Selectors_:tag,class,id, attribute
- _tags_:h1,h2,div,img,..
- _class_:.name,.container
- _id_ :#root,#id,..
- _attribute_: later \*
- cấu trúc 1 đoạn CSS
  cssSelector,cssSelector,cssSelector{
  propertity:value
  }
- _CSS reset_
- _san-serif_: là chữ có chân
- _serif_ : là chữ có chân

- _box-shizing_ :margin,padding,border,width,height,đơn vị px
- _color_: màu chữ
- _back-ground-color_: màu nền
  mã màu hexa #ccc,oragen,rgb(0,0,0),
  rgba(0,0,0,0.5) ,alpha:0->1

- **box-sizing**
- _content-box_:Độ rộng lúc này của 1 khối sẽ bằng width + padding(l+r) +border(l+r)
- _border-box_:Độ rộng lúc này của 1 khối sẽ bao gồm padding và border, nên áp dụng cho toàn bộ selector
- _padding_:có thể dùng số âm
- _margin_: có thể dùng số âm, có giá trị auto
- _width_: độ rộng
- _height_ : chiều cao
- _border_:viền
- _shorthand_ :viết rút gọn
- Đơn vị : px,em,rem,vw,vh,%
- khi set width và height cố định thì box sizing sẽ bao gồm cả padding và margin, không set thì nó sẽ cộng thêm dài ra với nội dung bên trong

- _text-decoration_:gạch dưới của thẻ a,`none`,`underline`,`overline`,`line-through`
- _border-radius_ : độ bo góc của khối , càng lớn thì càng bo góc, nếu hình vuông mà có bo góc thì -> hình tròn, nếu chữ nhật có bo góc lớp thì -> elipse
  top-left top-right bot-left bot-rigth
- _line-height_:khoảng cách giữa các dòng chữ

- khi những thẻ inline nằm cạnh nhau sẽ nằm trên 1 hàng ngược lại những thẻ block sẽ tạo ra hàng mới

- _display_:block,inline, inline-block,
  none,flex,grid

- `block` :Biến thành thẻ block
- `inline` :Biến thành thẻ inline, bị hạn chế CSS box-sizing, padding top bottom, margin bottom
- `inline-block` :Biến thành thẻ có thuộc tính inline và block luôn -> nằm trên 1 hàng độ rộng bằng nội dung nó chứa, không bị hạn chế CSS

- `flex`:
- `none`:không thấy không hành động được
- _min-width_:độ rộng tối thiểu -> >=
- _max-width_:độ rộng tối đa -> <=
- _flex-box_:Áp dụng thuộc tính display flexx vào phần tử mình muốn dàn layout
- _calc_: hàm để tính toán , lưu ý là phải có khoảng cách giữa các phép tính
- _flex-direction_: row; row-revese là ngược lại
- _align-items_: stretch; giá trị mặc định là stretch
- _stretch_ là các phần tử cao bằng nhau
- _align-items_: flex-start; căn các phần tử lên phía đỉnh
- _align-items_: flex-end; căn các phần tử lên phía đáy
- _align-items_: center; căn các phần tử ở giữa khối
- _align-items_: baseline; căn các phần tử theo đáy dòng chữ đầu tiên của các phần tử
- _flex-wrap_: nowrap; không cho phần tử xuống hàng mặc dù tổng các phần tử rộng hơn max width
- _flex-wrap_: wrap; cho phần tử xuống hàng
- _overflow_: hidden ;children bị tràn ra ngoài sẽ bị cut đi
- _object-fit_: cover; cho ảnh phủ hết width
- _justify-content: flex-start;_ giá trị mặc định là flex start là dồn các phần tử về bên trái :`center`,`space-beetween`,`space-around`,`space-evenly`
- _column-gap_:khoảng trống theo chiều dọc
- _row-gap_:khoảng trống theo chiều ngang
- _word-break_: break-word; nếu mà bị tràn chữ thì nó tự xuống dòng theo ý nghĩa chữ `break-all`
- _white-space_: nowrap; không cho chữ rơi xuống hàng
- _overflow_: hidden;
  _text-overflow_: ellipsis; ẩn phần bị tràn đi và có dấu ...
- snippit : text-truncate: text dài quá thì muốn 2 hoặc 3 hàng mới có dấu ...
- _component_ : mục đích tái sử dụng , có thể sử dụng ở nhiều nơi
- _position_:
- _pug_:
- _sass_:
- _javascript_:
