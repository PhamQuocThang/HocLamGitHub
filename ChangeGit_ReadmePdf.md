Readme.md (Cách cài Git trên Windows)
1. Đầu tiên Bạn phải _download_ phần cài đặt tại URL sau(chỉ với Windows):
[Visit Git Website](https://git-scm.com/download/win) 
Chạy chương trình cài đặt. Màn hình đầu tiên là màn hình về License bạn có thể đọc qua và tiếp tục bấm Next. 
2. Bạn sẽ đi dến màn hình **chọn các thành phần để cài đặt: Nên chọn default của màn hình.**
![Select Components](https://github.com/Dan470112/HocLamGitHub/blob/main/GitInstallDefault.png)
3. Kê tiếp **chọn cài đặt chương trình soan thạo văn bản**
   Bạn cũng có thể cài đặt chương trình sọan thảo khác ngoài vim default (nếu muốn).
![Default Editor](https://github.com/Dan470112/HocLamGitHub/blob/main/DefaultEditor.png)
4. Màn hình kế tiếp là **chọn môi trường cho biến PATH** như sau:
![AdjustingPath]https://github.com/PhamQuocThang/HocLamGitHub/blob/main/image3.png
Biến này giữ danh sách thư mục nơi mà chương trình được định vị. Mục đích để bạn không cần gõ con đường đầy đủ khi chạy chương trình tại console, bạn chỉ cần gõ tên chương trình là đủ.
5. Màn hình kế tiếp liên quan đến kết nối HPPTS:
https://github.com/PhamQuocThang/HocLamGitHub/blob/main/image4.png
Bạn sẽ phải chọn thư viện nào để sử dụng khi gửi số liệu với HTTPS bởi vì bạn phải kết nối với Server từ xa để chia xẻ commit của bạn với người khác, vì vậy tất cả các nối đó phải được mã hóa để đảm bảo an toàn cho số liệu của bạn không bị mất cắp.
 6. Bước kế tiếp là cách đối phó với kết thúc dòng văn bản.
https://github.com/PhamQuocThang/HocLamGitHub/blob/main/image5.png
Với các hệ điều hành khác nhau có cách xử lý kết thúc dòng văn bản khác nhau, do đó Git phải xử lý việc này trước khi chia xẻ các commits.
Lưu ý:
WINDOWS và MACOS sử dụng ‘\r\n’ cho kết thúc dòng. Còn LINUX chỉ dùng ‘\n’ cho kết thúc dòng mà thôi.
7. Bước kế tiếp là chọn cách giả lập Terminal default (hay console)
https://github.com/PhamQuocThang/HocLamGitHub/blob/main/image6.png
Git Bash cần bộ giả lập console để làm việc, cho nên bạn cần phải chọn hoặc là MinTTY hay console của Windows.
Nên chọn default bởi vì không những MinTTY có thể làm mọi thứ mà console của Windows có thể làm mà còn làm tốt hơn nữa.
   
- Trước khi sử dụng Git, bạn cần setup Git 1 chút (bạn cần cho Git biết về chính bạn). Bạn mở GitBash tại dấu nhắc lịnh gõ các lịnh sau:
$ git config --global user.name "tên của bạn"
$ git config --global user.email "Địa chỉ email của bạn@gmail.com"
Đối số “global” có nghĩa là setup cho tất cả các Git repositories sau này.
- Với lịnh config cũng cho phép bạn thay chương trình soạn văn bản default bằng chương trình
khác.
$ git config --global core.editor="nano"
Bạn có thể kiểm tra file gitconfig tại vị trí sau: “C:\Users\YourName\.gitconfig”
