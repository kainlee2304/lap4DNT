# BÁO CÁO  
## LAB 4: Magic 8 Ball 🎱  
**Họ và tên**:
**Mã số sinh viên**:
**Email**: 

### 1. Giới thiệu  
- **Mục đích**:  
  Bài báo cáo này nhằm trình bày quá trình xây dựng ứng dụng Magic 8 Ball bằng Flutter. Ứng dụng này giúp người dùng nhận được câu trả lời cho những câu hỏi khó bằng cách nhấn vào quả bóng. Đây là một cơ hội để củng cố những kiến thức đã học từ bài hướng dẫn Dicee, đồng thời áp dụng các khái niệm về Stateful và Stateless widgets trong Flutter.

- **Thông tin nền tảng**:  
  Magic 8 Ball là ứng dụng đơn giản, được xây dựng trên nền tảng Flutter, sử dụng ngôn ngữ Dart. Ứng dụng này cho phép người dùng tương tác với quả bóng ảo và hiển thị những câu trả lời ngẫu nhiên khi nhấn vào bóng. Flutter là framework mạnh mẽ cho phát triển ứng dụng đa nền tảng (cross-platform), giúp phát triển nhanh chóng trên cả Android và iOS với cùng một mã nguồn.

### 2. Mục tiêu  
- Xây dựng ứng dụng Magic 8 Ball với khả năng thay đổi hình ảnh quả bóng khi nhấn vào, hiển thị ngẫu nhiên một trong các hình ảnh đã định sẵn.  
- Củng cố kiến thức về Flutter, đặc biệt là các loại widget trong Flutter, như `StatelessWidget` và `StatefulWidget`.  
- Sử dụng thư viện `dart:math` để tạo ra các số ngẫu nhiên trong phạm vi xác định.  

### 3. Phương pháp  
- **Phương pháp**: Ứng dụng Magic 8 Ball được phát triển dựa trên các bước như sau:
  - Sử dụng `StatelessWidget` để xây dựng giao diện chính của ứng dụng với thanh `AppBar` và màu nền xanh.
  - Sử dụng `StatefulWidget` cho quả bóng Magic 8 Ball, cho phép thay đổi trạng thái khi nhấn vào.
  - Sử dụng hàm `setState()` để cập nhật hình ảnh bóng ngẫu nhiên khi người dùng tương tác.
  - Thư viện `dart:math` được sử dụng để sinh số ngẫu nhiên từ 1 đến 5, tương ứng với 5 hình ảnh quả bóng khác nhau.
  - Mỗi lần người dùng nhấn vào bóng, một số ngẫu nhiên sẽ được chọn và in ra màn hình console cùng với hình ảnh mới.

### 4. Kết quả  
- Ứng dụng được phát triển thành công, khi nhấn vào quả bóng, ứng dụng sẽ hiển thị hình ảnh ngẫu nhiên tương ứng từ 1 đến 5.
- Kết quả được hiển thị trên console với số ngẫu nhiên tương ứng với mỗi lần nhấn vào bóng.
- Giao diện hiển thị đơn giản, màu sắc hài hòa với màu nền xanh, tạo cảm giác nhẹ nhàng cho người dùng.

**Ảnh chụp kết quả**:


### 5. Thảo luận  
- **Kết quả đạt được**: Ứng dụng hoạt động chính xác theo mong đợi. Hình ảnh quả bóng thay đổi mỗi khi người dùng nhấn vào nút, và kết quả ngẫu nhiên được in ra console. Giao diện của ứng dụng thân thiện và dễ sử dụng.

- **Ưu và nhược điểm của phát triển ứng dụng cross-platform**:
  - **Ưu điểm**:  
    - Phát triển đồng thời trên nhiều nền tảng (Android, iOS) chỉ với một bộ mã nguồn duy nhất, giúp tiết kiệm thời gian và công sức.
    - Flutter cung cấp giao diện đẹp mắt và hiệu suất cao trên cả hai hệ điều hành.
  - **Nhược điểm**:  
    - Một số thành phần riêng của từng hệ điều hành có thể không dễ dàng tích hợp hoặc yêu cầu tùy chỉnh riêng.
    - Cộng đồng Flutter tuy đang phát triển nhưng vẫn chưa lớn mạnh bằng các nền tảng khác như Native Android hoặc iOS.

### 6. Kết luận  
- Ứng dụng Magic 8 Ball đã được xây dựng thành công với đầy đủ tính năng yêu cầu.
- Sử dụng Flutter và Dart giúp phát triển ứng dụng nhanh chóng và hiệu quả.
- Trong tương lai, có thể bổ sung thêm các tính năng như âm thanh khi nhấn bóng, hoặc hiển thị thêm nhiều câu trả lời thú vị hơn.
