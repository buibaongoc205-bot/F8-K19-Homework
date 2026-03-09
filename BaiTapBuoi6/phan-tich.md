<!-- 
Câu 1: Selector nào có độ ưu tiên cao nhất trong CSS?
Trả lời: inline style

Câu 2: Nếu một phần tử HTML có cả h1, .title, và #main cùng set color — selector nào thắng? Tại sao?
Trả lời: #main
Vì: độ mạnh trong 3 selector trên sẽ là: id > class > tag

Câu 3: Nếu bạn thêm style="color: pink" trực tiếp vào phần tử ở Câu 2, kết quả thay đổi như thế nào?
Trả lời: color sẽ là màu: pink
Vì: inline style còn mạnh hơn cả 3 cái cái trên nữa

Câu 4: Tại sao theme.css có thể override style từ base.css? Điều kiện để override thành công là gì?
Trả lời: Vì nó được link ở dưới
Rule là css nào đứng dưới thì nó thắng

Câu 5: Trong project của bạn, có hai phần tử đều dùng class .title nhưng hiển thị màu khác nhau. Giải thích tại sao.
Trả lời: nó còn phụ thuộc vào những yếu tố selector khác nữa, những selector mạnh hơn để có thể ghi đè class là: 
- link css đứng dưới (ví dụ như thêm.css đứng dưới base.css)
- id cũng mạnh hơn
- inline style cũng mạnh hơn
- internal style cũng mạnh hơn

Câu 6: Phần tử nào trong project của bạn có CSS phức tạp nhất? Liệt kê các selector tác động lên nó và giải thích selector nào thắng cuối cùng. 
Trả lời:
<h1 class="title" id="special" style="color: red">DASHBOARD</h1>

  Phan tu nay co: tag(h1) + class(.title) + id(#special) + internal(style="color:black;") + inline (style="color: red;")
  Selector thang: inline style vi css trực tiếp trên cùng dòng code của html
  Mau hien thi: red

-->