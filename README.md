# Lession-15-Ham-2

[Bài tập] Hàm kiểm tra số nguyên tố
Mục tiêu
Luyện tập tạo và gọi hàm.

Mô tả
Xây dựng phương thức:

boolean isPrime(int number)
để kiểm tra xem một số nguyên bất kỳ có phải là số nguyên tố hay không. Sử dụng phương thức này để tìm tất cả các số nguyên tố nhỏ hơn 10000. 

Số nguyên tố là số tự nhiên khác 0 chỉ có hai ước số dương phân biệt là 1 và chính nó.

Do số 1 chỉ có một ước số dương là chính nó, nên số 1 không phải là số nguyên tố.

Ví dụ, các số sau đây là số nguyên tố:

2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47, 53, 59, 61, 67, 71, 73, 79, 83, 89, 97...

[Bài tập] Chuyển đổi giữa feet và meters
Mục tiêu
Luyện tập tạo và sử dụng hàm

Mô tả
Xây dựng hai phương thức sau:

Chuyển đổi từ feet sang meters:

public static double footToMeter(double foot)
Chuyển đổi từ meters sang feet:

public static double meterToFoot(double meter)
Công thức chuyển đổi như sau:

      meter = 0.305 * foot
      foot = 3.279 * meter 
Sử dụng các giá trị trong bảng sau để kiểm tra tính chính xác của các hàm:



Để hoàn thành bài thực hành, học viên cần:

Đưa mã nguồn lên GitHub
Dán link của repository lên phần nộp bài trên CodeGymX

[*Bài tập] Ứng dụng quản lý sản phẩm sử dụng hàm
Mục tiêu
Luyện tập sử dụng mảng, hàm. Làm quen với khái niệm "Ứng dụng quản lý".

Mô tả
Ứng dụng quản lý sản phẩm có các chức năng sau:

Hiển thị danh sách sản phẩm
Có thể thêm một sản phẩm mới vào danh sách
Có thể sửa tên của sản phẩm trong danh sách
Có thể xoá một sản phẩm khỏi danh sách
Để hoàn thành bài thực hành, học viên cần:

Đưa mã nguồn lên GitHub
Dán link của repository lên phần nộp bài trên CodeGymX
Hướng dẫn
Bước 1: Tạo một trang HTML với các thẻ cơ bản

Bước 2: Tạo một mảng chứa danh sách sản phẩm

Bước 3: Xây dựng các hàm hiển  thị danh sách sản phẩm, thêm một sản phẩm vào danh sách, sửa tên sản phẩm, xoá sản phẩm.

Bước 4: Gọi hàm hiển thị danh sách sản phẩm

Tạo một mảng lưu trữ tên của sản phẩm
Sử dụng vòng lặp để hiển thị danh sách sản phẩm trên một bảng. Bảng này có 3 cột, cột đầu tiên là số thứ tự, cột thứ 2 là tên của sản phẩm, cột thứ 3 chứa nút để xoá sản phẩm.
Bước 5: Gọi hàm thêm một sản phẩm vào danh sách

Tạo một form với một ô nhập tên sản phẩm và một nút "Thêm"
Khi nhấn nút "Thêm" thì lấy tên mới nhập và đưa vào mảng.
Hiển thị thông báo.
Bước 6: Gọi hàm sửa một sản phẩm trong danh sách

Tạo một form với một ô để hiển thị tên danh sách và một nút "Sửa"
Khi nhấn vào một tên của sản phẩm trong danh sách thì hiển thị tên của nó ở trong ô tên danh sách
Sau khi sửa tên và nhấn nút "Sửa" thì cập nhật lại tên của sản phẩm đó ở trong mảng
Bước 7: Gọi hàm xoá một sản phẩm trong danh sách

Khi nhấn vào nút "xoá" ở một sản phẩm, hãy tìm vị trí của sản phẩm đó trong danh sách
Xoá sản phẩm đó trong danh sách
Hiển thị lại bảng
Ứng dụng có giao diện tham khảo như sau:



[*Bài tập] Kiểm tra từ đối xứng
Mục đích
Luyện tập sử dụng phương thức đệ quy.

Mô tả bài toán
Xây dựng chương trình sử dụng đệ quy để kiểm tra một từ có phải là từ đối xứng không. Phương thức kiểm tra chuỗi đối xứng có nguyên mẫu như sau:

function isPalindrome(s) ;
Phương thức isPalindrome() trả về true nếu chuỗi truyền vào là chuỗi đối xứng. Còn lại trả về false.

Để hoàn thành bài thực hành, học viên cần:

Đưa mã nguồn lên GitHub
Dán link của repository lên phần nộp bài trên CodeGymX
Hướng dẫn
Một chuỗi palindrome là một từ được đọc theo thứ tự xuôi, ngược đều giống nhau. Ví dụ, rotor và redder là các chuỗi palindrome, nhưng motor thì không phải.

Kiểm tra một chuỗi là một palindrome được chia thành hai bài toán con

(1) Kiểm tra xem ký tự đầu tiên và ký tự cuối cùng của chuỗi có bằng nhau.

(2) Bỏ qua hai ký tự đầu và cuối, kiểm tra xem phần còn lại của chuỗi con là một palindrome.

Bài toán con thứ hai (2) giống như vấn đề ban đầu nhưng nhỏ hơn về kích thước.
