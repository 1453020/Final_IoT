# Final_IoT
#Cửa thông minh
#Chức năng:
#Xác nhận người vào có phải là thành viên trong gia đình hay không
#Gửi thông tin khi có người vào nhà
#Phát tín hiệu báo động khi có người ngoài đột nhập
#Hoạt động
#Khi một thành viên trong gia đình muốn mở cửa, trước tiên họ sẽ cho cảm biến hình ảnh nhận được hình ảnh mã QR của mình
#Hệ thống sẽ gửi mã QR tương ứng đó về server và trích xuất ID tương ứng của thành viên đó trong gia đình và ghi nhận lại, đồng thời thông báo cho người quản trị trong gia đình tên và thời gian của thành viên đó khi mở cửa.
#Nếu có người lạ đột nhập không có mã QR thì khi cửa mở sẽ kích hoạt cảm biến chuyển động đặt gần bậc cửa, hệ thống sẽ nhận chuyển động mở cửa mà không nhận được ID đó là đột nhập và kích hoạt cảm biến âm thanh để báo động người lạ đột nhập, đồng thời gửi thông tin đột nhập đén quản trị viên.
#Trường hợp một thành viên trong gia đình có mã QR nhưng quên cho cảm biến hình ảnh nhận đc hình ảnh mã QR, hệ thống cũng sẽ thông báo là có người lạ đột nhập cho tới khi thành viên đó cho cảm biến nhận được mã QR của mình
#Yêu cầu
#Cảm biến hình ảnh
#Cảm biến chuyển động
#Cảm biến âm thanh
#Vi điều khiển để phối hợp vận hành các cảm biến
#Module wifi để kết nối với server và gửi thông tin tới quản trị viên
#Kiến thức lập trình để gửi nhận dữ liệu giữa local và server
