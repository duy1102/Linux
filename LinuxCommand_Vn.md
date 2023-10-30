# Getting Started with Linux Command Line

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

### To change to a specific directory 
- You can use the ***cd*** command  followed by the path to the directory you want to navigate to (get into). 

```bash
cd /path/to/directory

```

### To change to  to the Home Directory
-  You can use cd without any arguments to quickly return to your home directory. 

```bash
cd 

```

### Navigating within the directory using the relative path

- When your directories or files are located within the same directory, you can use **relative paths**tree to efficiently navigate up or down the directory tree from your current location.
- `cd ..` moves up one level back (towards the parent directory).
- `cd foldername` moves into a directory named "foldername" in your current location.

### Using Tilde (~) Shortcut

You can also use the tilde (~) as a shortcut to represent your home directory. 

```bash
cd ~
```

### Navigating between directories using the absolute path
Learn to navigate between directories using the absolute path.

## Creating a new Directory (MKDIR)

You task is to create a couple of directories in your home folder. 

### Creating Multiple Directories with MKDIR
Your task is to create multiple directories at least 3 with a single mkdir command.

### Creating a text file with a nano text editor. 

Your task is to create 3 text files using a text editor. You can write something in your text file. You can create these text files into any of the directory that you have created above. Remember how to save the file using nano. 
## Understanding the path (absolute & relative)
What do you understand by absolute and relative path? Discuss with each other with examples. 

## Creating Files with Redirection
Learn to use pipe sign as mentioned in the video tutorial.

## Some examples of using wildcard characters in Ubuntu
Use some wild characters with ls commands and get familiar with wildcard characters. 

## Manipulating Files & Folders


### Removing an empty directory

Your task is remove one of the empty director which you have created above.

### Removing a non-empty directory
Your task is remove the directory that has files which you have created above with nano text editor. 

## Copying a file/directory (use relative path)

Create 3 text files in one of your directory and copy them to different directory.

## Moving a file/directory (use absolute path)
Create 3 text files in one of your directory and move them to different directory.

## Renaming Files & Directories
Rename a few of your files and directories. 


## Data Manipulation

- Create a text file called data.txt using nano text editor. Copy some text from wikipedia ( atleast a couple of pages). 

- Use cat command to view the file's content. 

- Use less command to display one page at a time. 

    - Use spacebar to go to the new page. 

    - Type q to quit viewing the file.

- Use head command to view the head of the file. 

- Use tail command to view into the end of the file.

- Use grep command to search something within your file

## Pipe | 

Learn to use pipe sign as mentioned in the video tutorial.

## Root user

Discuss what is a root user ?

## Hidden Files

How can you hide a file in Ubuntu? 

***After you have done all the above tasks, you will run the following command and create linux1.txt file in your home directory.*** 

```bash
history >linux1.txt
```

**Type explorer.exe . in your terminal and you will see the file linux1.txt**
