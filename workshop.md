# Buổi học thử

---

## Buổi 1: Giới thiệu và Làm CV

### Lời chào

Xin chào mọi người, đầu tiên anh xin phép tự giới thiệu chút ít về bản thân mình. anh tên đầy đủ là Diệp Mỹ Dương, là một senior developer đã có 7 năm kinh nghiệm trong ngành lập trình. Với kinh nghiệm và kỹ năng đã từng tham gia và phát triển nhiều dự án thực tế, anh rất hân hạnh được Chủ tịch của tập đoạn Hitek Group, anh Khôi, mời tham gia phụ trách chia sẻ và hướng dẫn các bạn trong buổi học thử ngày hôm nay.

> Slide chứa hình ảnh, năm kinh nghiệm, vị trí, vai trò

Giờ chúng ta quay lại nội dung buổi học nhé. Trước khi bắt đầu lớp học, cho anh hỏi trong lớp học ngày hôm nay, bạn nào không có học từ chuyên ngành công nghệ thông tin không?

> Chờ đợi học viên giơ tay tương tác.

Và có bao nhiêu bạn đã có kiến thức cơ bản nhất định về lập trình web chưa ? Cụ thể là biết về HTML và CSS ?

> Chờ đợi học viên tương tác

Cám ơn các bạn. Chác hẳn các bạn trước khi tham gia vào buổi học thử này cũng đã có tham khảo qua thông tin lớp học trước rồi. Và anh cũng muốn nhắc lại mục địch của lớp học cũng như giá trị mà các bạn nhận được sau lớp học này. Lớp học của chúng ta sẽ chia làm 2 buổi học, ở buổi học đầu tiên, các bạn sẽ được học sử dụng các công cụ cần thiết để bắt đầu lập trình web, biết được cơ bản HTML và CSS là gì. Đặc biết là anh sẽ chỉ cho mọi người cách làm sao để làm được một website CV đẹp chuẩn chỉnh chỉ với những kiến thức cơ bản này. Các bạn có thích không?

> Slide chứa nội dung outline về buổi học đầu tiên

Còn buổi học tiếp theo, vói thời gian ngắn ngủi 2 buổi học, sự thật là chúng ta sẽ không thể so sánh được với các lớp học chính quy từ đại học rồi. Nên anh sẽ chia sẻ nhiều giá trị nhất để các bạn có một hướng đi cụ thể cho con đường lập trình frontend sau này. Các bạn sẽ học được cách tự tạo hosting đưa website của chúng ta ra ngoài thế giới internet, sẽ ấn tượng nếu nhà tuyển dụng xem trực tiếp dự án của chúng ta trên mạng đúng không? Anh cũng sẽ chia sẽ thêm về lộ trình để các bạn phát triển những kỹ năng gì cần thiết cho lập trình viên front-end cũng như các vị trí mà các bạn có thể nhắm tới khi quyết định bước chân vào ngành IT. Và sẽ có một món quà đặc biệt dành cho các bạn kiên trì hoàn thành đủ 2 buổi học. Các bạn muốn biết đó là gì không?

> Slide chứa nội dung outline về buổi học thứ 2

### Yêu cầu khoá học

Không làm mất nhiều thời gian nữa, chúng ta bắt đầu buổi học ngay thôi.
Đầu tiên anh muốn các bạn hãy cài đặt một số công cụ không thể thiếu để lập trình nhé.

#### VSCode

![Image](https://i.imgur.com/lFX4NBq.png)

    https://code.visualstudio.com/Download

#### Extension Live Server

![Image](https://i.imgur.com/U5xsoYK.png)

#### Tool Wget

##### Linux

    apt-get install wget

##### Mac

Cài đặt Homebrew

    /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

Cài đặt Wget

    brew install wget

##### Window

Truy cập

    https://gnuwin32.sourceforge.net/packages/wget.htm

![Image](https://i.imgur.com/HsoyQX8.png)

---

Anh sẽ giới thiệu sơ qua các công cụ này cũng như mục đích sử dụng của từng công cụ:

- VSCode: Đây là công cụ chính cho chúng ta viết code, đây là công cụ phổ biến nhất và mạnh mẽ được đông đảo lập trình viên sử dụng dùng để code web, backend và cả các ứng dụng di động. Nó có một kho ứng dụng tích hợp extension giúp ta làm được nhiều thứ hơn ngoài code như vẽ biểu đồ, chỉnh sửa hình ảnh, v.v...
- Extension Live Server: Là một ứng dụng tích hợp vào vscode, giúp cho các bạn lập trình front-end tạo một máy chủ cục bộ trên máy tính. Các bạn có thể vừa chỉnh sủa code vừa xem thay đổi trên giao diện realtime mà không cần load trang lại, rất tiện nha.
- Wget: Là một thư viện hỗ trợ tính năng tải file trên internet, không dừng lại ở đó, nó còn có một công dụng đặc biết mà chưa ai chỉ các bạn và anh sẽ bật mí cho các bạn sau trong buổi học này, các bạn sẽ phải wow với công cụ này.

> Slide chứa hình ảnh và hướng dẫn cài đặt các công cụ trên

### HTML Cơ bản

Vậy là chúng ta đã chuẩn bị đủ vũ khí nhập môn rồi. Tiếp theo thì học một chút nhập môn công pháp. Bắt đầu từ HTML trước.

![Image](https://i.imgur.com/4WTkONs.png)

    https://wiki.matbao.net/html-la-gi-nen-tang-lap-trinh-web-cho-nguoi-moi-bat-dau/

> HTML viết tắt của Hypertext Markup Language là ngôn ngữ lập trình dùng để xây dựng và cấu trúc lại các thành phần có trong Website.

![Image](https://i.imgur.com/EH32qLk.jpg)

> HTML được tạo ra bởi Tim Berners-Lee, tại Thụy Sĩ

![Image](https://i.imgur.com/Tw6EeUv.jpg)

> Phiên bản đầu tiên của HTML xuất hiện năm 1991, gồm 18 tag HTML

![Image](https://i.imgur.com/MMa01UX.png)
![Image](https://i.imgur.com/cUL08RJ.png)
![Image](https://i.imgur.com/DTAbbdd.png)

> HTML đã có một quá trình hình thành và phát triển cho tói năm 2008 với phiên bản HTML5 có hơn 140 tag khác nhau dùng để thể hiện các loại nội dung cụ thể

![Image](https://i.imgur.com/v9RH5xv.png)

![Image](https://i.imgur.com/gf0c0si.png)

#### Một số từ khoá trong HTML

1. innerText

![Image](https://i.imgur.com/7Oi7old.png)

2.  innerHTML

![Image](https://i.imgur.com/ZukZI2K.png)

3. attribute

![Image](https://i.imgur.com/2PDM6vW.png)

4. DOM: Document Object Model

![Image](https://i.imgur.com/3mKEiG6.png)

5. File HTML: đuôi file .html
6. Tag `<html>, <head>, <body>`
   ![Image](https://i.imgur.com/QOhNwnd.png)
   ![Image](https://i.imgur.com/d9lTzCp.png)
   ![Image](https://i.imgur.com/tW2O6Ju.png)
7. Tag `<h1>, <p>, <img>, <a>, <div>`

### CSS Cơ bản

![Image](https://i.imgur.com/AD0Fd6Y.png)

    https://topdev.vn/blog/css-la-gi/

> Hãy tưởng tượng coi HTML như là bộ xương người vậy. Nó đủ tính năng nhưng xấu xí, ai cũng như ai

![Image](https://i.imgur.com/Ec6fx0V.png)

> Lúc này CSS như một lớp da và bộ áo cho bộ xương HTML vậy. Bằng cách thiết kế viết CSS mỗi website sẽ có bộ mặt khác nhau, như màu sắc, kích cỡ, font chữ, bố cục, v.v...

![Image](https://i.imgur.com/waoseJg.jpg)

#### Một số từ khoá cần nắm

1. Rule: Selector, Declaration Block, Properties
   ![Image](https://i.imgur.com/py3Fn1K.png)
   ![Image](https://i.imgur.com/Sdsdlaf.png)

2. Stylesheets CASCADE
   ![Image](https://i.imgur.com/gB5MxL5.png)

### Xây dựng và chỉnh sửa CV

---

## Buổi 2: Lộ trình và cơ hội lập trình Front end

### Tạo Hosting Website

### Chia sẻ mục tiêu

### Lộ trình phát triển kỹ năng

### Lộ trình phát triển vị trí

### Cơ hội việc làm tại Hitek

### Khoá học chuyên sâu
