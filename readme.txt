----English----
- Here is introduction for the program named "Real time chat app".
- This guide is written in both Vietnamese and English.

- Before using this app you need to download, install, setting enviroment and some neccesary library, if you have got anything that I would say down here please check and do the next one.

1. Firstly, you need to download NodeJS on browser and install it.
2. Next, open your terminal/powershell window/linux shell (in Desktop) depends on the type of computer/laptop you are using and follow these introduction, I highly recommend you should download and use VSCode IDE because of it's convenience and you also can use VSCode's terminal to do all these thing:
    - Check your NodeJS is installed or not: node -v
    - Check "NPM" (the default library manager in the Node.js environment): npm -v
    - Install "yarn" ("yarn" is a software packaging system developed for the Node.js JavaScript runtime environment): npm install -g yarn
    - Change the path to the directory of this app where you saved (to make it more easier, you can open the folder of this file and then open terminal/powershell window/linux shell again if you don't know how to change the path by using terminal):
        - Add "ws" library to the folder: yarn add ws
3. Run server, we will use terminal as well:
    - Open file "server.js" and run server: yarn start
4. Run the program, there are two ways you can to do it:
    + The first way: you can open file "index.html" with one browser (this is the first tab also represents for the first person in chat app) and copy the path of the web page (it's also the path where you save the file) then open one more tab in incognito mode (the browser which is opened) and paste the path to that one or you can open the second tab with the different browser from the first one (this tab represents for the second person in chat app).
    + Another way - this would be applied for someone who used VSCode IDE that I have mentioned before:
        + Add extension: Live Server.
        + Now you can run the file with Live Server extension then open one more tab in incognito mode (the browser which is opened) and paste the path to that one or you can open the second tab with the different browser from the first one (this tab represents for the second person in chat app).
5. Now you can text something from each tab to see the result.
----Vietnamese----
- Đây là hướng dẫn cho chương trình tên "Ứng dụng trò chuyện thời gian thực".
- Hướng dẫn này được viết bằng cả Tiếng Việt và Tiếng Anh.

- Trước khi sử dụng chương trình này bạn cần tải, cài đặt môi trường và một số thư viện cần thiết, nếu bạn đã có bất kì những gì tôi sẽ đề cập dưới đây, hãy kiểm tra và làm cái tiếp theo.

1. Đầu tiên, bạn cần tải NodeJS trên trình duyệt và cài đặt nó.
2. Tiếp theo, mở terminal/powershell window/linux shell (tại Desktop) tùy thuộc vào loại máy tính/laptop bạn đang sử dụng và làm theo những hướng dẫn sau đây, tôi khuyến khích bạn nên tải và sử dụng VSCode - môi trường tích hợp dùng để viết code - bởi vì sự tiện lợi của nó và bạn cũng có thể sử dụng terminal của VSCode để làm những thứ sau:
    - Kiểm tra NodeJS đã được cài đặt hay chưa: node -v
    - Kiểm tra "NPM" (thư viện quản lí mặc định trong môi trường Node.js): npm -v
    - Cài đặt "yarn" ("yarn" là một hệ thống đóng gói phần mềm được phát triển cho môi trường thời gian chạy JavaScript Node.js.): npm install -g yarn
    - Chuyển đường dẫn tới thư mục của chương trình nơi mà bạn đã lưu, 
//hỏi thầy gửi thư mục có gửi node_module hay kh (để có cần tải ws hay kh) 