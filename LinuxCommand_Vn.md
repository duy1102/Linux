# Khởi động với các dòng lệnh trên Linux (Linux Command Line)

## Làm thế nào để khởi động WSL của bạn?

Mở Ubuntu bằng cách đơn giản là tìm kiếm 'Ubuntu' trong thanh tìm kiếm Windows của bạn và nhấp vào ứng dụng Ubuntu. Khi mở, bạn sẽ có quyền truy cập vào terminal nơi bạn có thể nhập các lệnh của mình.

# Thư mục Home của bạn trong Ubuntu


Trong Ubuntu và nhiều hệ điều hành khác dựa trên Linux, thư mục "Home folder" hay "home directory" là một vị trí trung tâm trên hệ thống của bạn, nơi mỗi người dùng có không gian lưu trữ riêng biệt cho các tệp cá nhân, tài liệu, tệp cấu hình và cài đặt

**Bạn có thể truy cập thư mục home của mình bằng cách sử dụng ký hiệu "~" (dấu ngã).**

### Thực hiện lệnh để in ra thư mục home của bạn. 



## Lệnh **CD** là gì? 
- Lệnh "cd" (rút gọn của "change directory") là một công cụ cơ bản trong giao diện dòng lệnh như terminal Linux và Windows Command Prompt.
- Chức năng chính của nó là hỗ trợ điều hướng mượt mà giữa các thư mục hoặc thư mục trong hệ thống tệp.
- Lệnh cd cho phép bạn thay đổi thư mục làm việc hiện tại sang một thư mục được chỉ định. 
- Bạn luôn cần chú ý đến thư mục làm việc của mình

### Thực hiện lệnh để in ra thư mục home của bạn 
- Bạn có thể sử dụng lệnh cd theo sau là đường dẫn đến thư mục bạn muốn di chuyển đến.

```bash
cd /path/to/directory

```

### Để chuyển đến Thư mục Home
-  Bạn có thể sử dụng cd mà không có bất kỳ đối số nào để nhanh chóng quay lại thư mục home của bạn. 

```bash
cd 

```

### Điều hướng trong thư mục bằng đường dẫn tương đối

- Khi các thư mục hoặc tệp của bạn nằm trong cùng một thư mục, bạn có thể sử dụng **đường dẫn tương đối** để di chuyển lên hoặc xuống cây thư mục từ vị trí hiện tại của bạn
- `cd ..` di chuyển lên một cấp (tới thư mục cha)..
- `cd foldername` di chuyển vào một thư mục có tên "tên_thư_mục" ở vị trí hiện tại của bạn.

### Sử dụng dấu ngã - Tilde (~) Shortcut

Bạn cũng có thể sử dụng dấu ngã (~) như một phím tắt để đại diện cho thư mục home của bạn. 

```bash
cd ~
```

### Di chuyển giữa các thư mục bằng đường dẫn tuyệt đối

Học cách di chuyển giữa các thư mục bằng đường dẫn tuyệt đối.

## Tạo một Thư mục mới (MKDIR)

Nhiệm vụ của bạn là tạo một vài thư mục trong thư mục home của bạn. 

----------------------------------------------------------------------
## Bài thực hành 

### Tạo Nhiều Thư mục với MKDIR
Nhiệm vụ của bạn là tạo nhiều thư mục ít nhất là 3 với một lệnh mkdir duy nhất.

### Tạo một tệp văn bản với trình soạn thảo nano 

Nhiệm vụ của bạn là tạo 3 tệp văn bản bằng trình soạn thảo văn bản. Bạn có thể viết gì đó trong tệp văn bản của mình. Bạn có thể tạo các tệp văn bản này trong bất kỳ thư mục nào bạn đã tạo ở trên. Nhớ cách lưu tệp bằng nano.

## Hiểu về đường dẫn (tuyệt đối và tương đối)
Bạn hiểu gì về đường dẫn tuyệt đối và tương đối? Thảo luận với nhau và có ví dụ. 

## Tạo tệp với Điều hướng
Học cách sử dụng dấu cống / dấu gạch đứng | như đã đề cập trong video hướng dẫn.

## Một số ví dụ về việc sử dụng ký tự đại diện trong Ubuntu
Sử dụng một số ký tự đại diện với lệnh ls và làm quen với ký tự đại diện.

## Thao tác với Tệp và Thư mục


### Xóa một thư mục trống
Nhiệm vụ của bạn là xóa một trong những thư mục trống bạn đã tạo ở trên.

### Xóa một thư mục không trống
Nhiệm vụ của bạn là xóa thư mục có tệp mà bạn đã tạo ở trên với trình soạn thảo nano. 

## Sao chép một tệp/thư mục (sử dụng đường dẫn tương đối)

Tạo 3 tệp văn bản trong một trong thư mục của bạn và sao chép chúng vào các thư mục khác nhau.

## Di chuyển một tệp/thư mục (sử dụng đường dẫn tuyệt đối)Di chuyển một tệp/thư mục (sử dụng đường dẫn tuyệt đối)
Tạo 3 tệp văn bản trong một trong thư mục của bạn và di chuyển chúng vào các thư mục khác nhau.

## Đổi tên Tệp & Thư mục
Đổi tên một số tệp và thư mục của bạn.


## Sửa đổi Dữ liệu

- CTạo một tệp văn bản có tên là data.txt bằng trình soạn thảo văn bản nano. Sao chép một số văn bản từ Wikipedia (ít nhất là một vài trang).

- Sử dụng lệnh cat để xem nội dung của tệp.

- Sử dụng lệnh less để hiển thị từng trang một.

 - Sử dụng phím cách để chuyển đến trang mới.

 - Gõ q để thoát xem tệp.

- Sử dụng lệnh head để xem phần đầu của tệp.

- Sử dụng lệnh tail để xem vào cuối tệp.

- Sử dụng lệnh grep để tìm kiếm một cái gì đó trong tệp của bạn.

## Dấu cống / Gạch đứng (pipe) | 

Học cách sử dụng dấu cống / gạch đứng như đã đề cập trong video hướng dẫn.

## Người dùng Root (root user)

Thảo luận về người dùng root là gì?

## Tệp Ẩn

Làm thế nào bạn có thể ẩn một tệp trong Ubuntu?

***Sau khi bạn đã hoàn thành tất cả các nhiệm vụ trên, bạn sẽ chạy lệnh sau và tạo tệp linux1.txt trong thư mục home của bạn.*** 

```bash
history >linux1.txt
```

**Gõ "explorer.exe ." trong terminal và bạn sẽ thấy tệp linux1.txt**
