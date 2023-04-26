# Table Structure

Thẻ **<table>** là một phần tử block-level mặc định, nghĩa là nó sẽ chiếm toàn bộ chiều rộng của phần tử cha và bắt đầu từ một dòng mới. Nó được sử dụng để tạo ra một bảng chứa các dữ liệu được sắp xếp thành các hàng và cột. Cấu trúc của một thẻ <table> bao gồm các phần tử sau:

-Thẻ **<table>**: Là phần tử cha bao bọc toàn bộ bảng.

-Thẻ **<caption>**: Được sử dụng để đặt tiêu đề cho bảng.

-Thẻ **<thead>**: Chứa các thẻ <tr> đại diện cho phần đầu bảng.

-Thẻ **<tbody>**: Chứa các thẻ <tr> đại diện cho phần thân bảng.

-Thẻ **<tfoot>**: Chứa các thẻ <tr> đại diện cho phần chân bảng.

-Thẻ **<tr>**: Đại diện cho một hàng trong bảng.

-Thẻ **<th>**: Đại diện cho một ô tiêu đề trong bảng.

-Thẻ **<td>**: Đại diện cho một ô dữ liệu trong bảng.

Một số lưu ý khi chia các cell trong **<table></table>** ta sử dụng thuộc tính border-collapse, đây là một thuộc tính CSS được sử dụng để xác định cách thức mà các đường viền của các ô (cell) trong bảng (table) sẽ được xử lý khi chúng gặp nhau.
Thuộc tính "border-collapse" có hai giá trị:

- "collapse": các đường viền của các ô trong bảng sẽ được xem như là một đường viền duy nhất khi chúng gặp nhau. Điều này có nghĩa là các đường viền không được phân cách bằng khoảng trắng hoặc bất kỳ khoảng cách nào khác.

- "separate": mỗi đường viền của các ô trong bảng được xử lý riêng lẻ và được phân cách bằng khoảng trắng hoặc khoảng cách khác.

Có thể CSS cho thẻ **<caption>** của table với một vài thuộc tính như **caption-side** , font-weight , color , ...

# Sticky Table

Sticky table là một thuật ngữ để chỉ một bảng (table) trong thiết kế web, được cố định (fixed) trên một vị trí cụ thể trên trang web và không bị mất đi khi người dùng cuộn (scroll) trang web. Khi người dùng cuộn trang, nội dung khác của trang web sẽ di chuyển qua lại nhưng bảng sticky table sẽ luôn hiển thị ở cùng một vị trí trên trang web, giúp cho người dùng dễ dàng theo dõi các thông tin quan trọng trong bảng.

Sticky table được sử dụng rộng rãi trong thiết kế web để hiển thị các bảng dữ liệu, đặc biệt là trên các trang web có tính tương tác cao như các trang thương mại điện tử, trang quản lý dữ liệu, trang quản trị hệ thống và nhiều ứng dụng web khác.
