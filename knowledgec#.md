_Console.Write();_ xuất dữ liệu trên cùng 1 dòng (nôm na chỗ này xuất dữ liệu ra thì dữ liệu xuất ra sẽ nằm yên trên 1 dòng và không xuống dòng).
_Console.WriteLine();_ xuất dữ liệu trên các dòng khác nhau (chỗ có lệnh này khi xuất ra dữ liệu bên trong () thì nó sẽ xuống dòng).

_Console.ReadLine();_ : 
tác dụng 1:khi _Console.Write_ 1 cái gì đó thì khi chạy chương trình thì phải thêm _Console.ReadLine_ để ngăn chương trình tự đóng lại.
tác dụng 2: dùng để nhập dữ liệu từ bàn phím(giống Scanner bên java) rồi sau đó nhấn enter.

_Console.OutputEncoding = Encoding.UTF8;_ để in ra tiếng việt ko bị lỗi thì ghi dòng này trước tất cả các dòng _Console.Write_

_int.Parse_ chuyển đổi sang kiểu int (khá giống ép kiểu). Sử dụng trong trường hợp như là nhập một số nào đó từ bàn phím bằng Console.ReadLine(); nhưng khi nhập thì nó sẽ hiểu số đó là kiểu chuỗi (String). Vậy nên lệnh này để chuyển String sang int "5" => 5


