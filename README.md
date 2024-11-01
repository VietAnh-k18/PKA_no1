1.Giới thiệu về hệ điều hành Linux

* Tại sao chọn Linux trong phát triển và học tập công nghệ thông tin.

2.Lịch sử phát triển Linux và Unix

* Unix: Phát triển bởi Dennis Ritchie và Ken Thompson (1969, Bell Labs).
* Linux: Linus Torvalds phát triển vào 1992, là nền tảng của nhiều hệ điều hành hiện nay.

3.Các bản phân phối Linux

* Dòng Debian: Debian, Ubuntu, Linux Mint, Kali Linux, Tails OS, Knoppix.
   + Quản lý phần mềm: Sử dụng dpkg (.deb), -apt.
 * Dòng Red Hat: RHEL, Fedora, CentOS, Scientific Linux.
   +Quản lý phần mềm: Sử dụng .rpm, yum.

4.Nơi học và thực hành

* Tài nguyên học online: Labex.io, Vietjack.
* Thực hành tại phòng lab hoặc dùng Jupyter Hub (Phenikaa) với tài khoản PU.

5.Hệ thống tệp Linux

* Cấu trúc hệ thống tệp, các đường dẫn tương đối và tuyệt đối.

6.Shell

* Trình giao tiếp dòng lệnh giúp thực hiện các tác vụ phức tạp, làm việc từ xa, tùy biến, lập trình.
* Terminal: Gnome-terminal, Kconsole, xTerm, Powershell (Windows).

7.Cấu trúc dòng lệnh và lệnh cơ bản trong Shell

* Lệnh hệ thống
* Lệnh thư mục: ls (liệt kê thư mục), pwd (in thư mục hiện tại), cd (chuyển thư mục), mkdir (tạo thư mục), rm -r (xóa thư mục).
* Lệnh tệp: cat (xem nội dung tệp), cp (sao chép), rm (xóa), mv (di chuyển/đổi tên).

8.Quyền truy cập tệp và thư mục

* Các quyền: Đọc (r), Ghi (w), Thực thi (x), được thiết lập cho chủ sở hữu, nhóm, và người khác.
* Cách thiết lập quyền: Dùng lệnh chmod với các ký hiệu +, -, =.
* Ví dụ: chmod o-r file, chmod u+x,o+r file.

9.Chmod bằng số

* Quyền đọc = 4, ghi = 2, thực thi = 1.
* Ví dụ thiết lập quyền: chmod 555 file, chmod 775 file.
