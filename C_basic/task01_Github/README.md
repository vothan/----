
**BÁO CÁO TASK 1**

***1.cách thức hoạt động của Github***

Hãy tưởng tượng Git là server của game online còn client(lap,pc...) là những con nghiện khi client chơi game thì sẽ có những thay đổi về stats,skill tree của nhân vật +nếu như ta không đồng tình với stat hay skill tree thì game sẽ cho ta reset lại nó để ta có thể set theo ý muốn cá nhân(tùy game nữa) -->Cũng như Git ghi lại tất cả những thay đổi về source code mỗi khi ta chỉnh sửa nó vào lúc nào, sửa đổi code như thế nào +khi player của client chết thì sẽ như thế nào? về thành là điều tất nhiên.giống như 1 vài game off có hệ thống checkpoint game sẽ lưu lại tất cả trạng thái của player ở 1 thời điểm nào đó để chúng ta có thể bắt đầu lại khi player die(ai đã từng chơi Dark Soul sẽ hiểu cái (cảm giác) này) -->Git cũng vậy, khi lưu tất cả changes đã nói ở trên về source codes thì Git cũng có thể phục hồi nó

*Đi cùng với Git là Github
Github như một blog cá nhân, nó lưu trữ tất cả những thay đổi của cái dòng code mọi lúc.Nhờ điều đó ta có thể khôi phục lại những dữ liệu đã mất khi ta gặp sự cố không mong muốn.Github kết hợp với Git sẽ là thế giới "Hello World" của riêng chúng ta.

***2.các khái niệm***

Add :như tên gọi thì Add là thêm vào(thêm file)

Commit :
lệnh này ở đây ta có thể hiểu là thừa nhận, đồng ý. Vậy nếu hiểu theo Git thì commit sẽ ghi nhận những thay đổi từ file đang làm việc lưu tại máy cục bộ

Push :
Push có nghĩa là đẩy, mà dùng Git thì đẩy cái quái gì? thay vì hiểu đẩy ta hãy hiểu nó theo nghĩa synchronization(đồng bộ hóa) thì chuẩn xác hơn, push là lệnh dùng để đồng bộ các thay đổi ở client lưu vào repository của Github

Pull :
Pull là kéo, hiểu đúng hơn thì cũng như push nhưng theo nghĩa ngược lại, ta đồng bộ hóa từ server xuống máy local sau đó merge với source code ở local repo

Remote :
remote có nghĩa là (điều khiển) từ xa, có thể push source codes từ local repo của chúng ta để mọi người access vào hoặc ngược lại có thể pull source codes của người khác từ remote repo.

Fetch :
tương tự như pull nhưng không merge

Clone :
clone có nghĩa là nhân bản, clone sẽ sao chép 1 repo về repo cá nhân tạo thành 1 directory mới(thường được tự động đặt tên là "origin")

Star :
khá giống núi like ở fb, khi like thì ta sẽ follow chủ sở hữu của status nên star giống như bookmark của browser để đánh dấu repo mà mình thích hay có việc cần đến repo đó ###fork copy repo của 1 người về repo của cá nhân để có thể thoải mái chỉnh sửa mà không làm ảnh hưởng đến repo nguyên gốc hay chỉ đơn giản là lấy ý tưởng của repo đó để làm khởi đầu cho repo của mình ###watch giống như notice của fb, dùng để nhận thông báo về 1 câu trả lời của ai đó hay những thay đổi của repo mà ta watching

***3.SSH key***

thay vì ta dùng username và password để vào repo thì có thể thay thế được = SSH key tạo thuận tiện cho việc vào repo cũng như độ an toàn của nó khi ta để lộ usr và pwd
