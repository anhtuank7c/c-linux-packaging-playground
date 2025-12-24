# C Linux Packaging Playground

Dự án này ra đời với mục tiêu thực thành đóng gói, phân phối dự án code bằng ngôn ngữ C tới hàng loạt các distro Linux.

## Dẫn chuyện

Một ngày đẹp trời nọ tôi nảy ra một ý tưởng khá đơn giản, đó là lập trình một agent theo dõi SSH Session trên linux để gửi cảnh báo đăng nhập về các kênh như Telegram, Slack và custom webhook, có nhiều cách để triển khai ý tưởng nhưng vì tôi muốn mình thực hành C nhiều hơn nên tôi chọn phương án này.

Tạm bỏ qua việc tôi lập trình agent đó như thế nào vì đó không phải trọng tâm của bài viết này, đơn giản output của đám code trên là một file thực thi (executable file) đơn giản.

Chà, nếu chỉ dùng ở mức độ thử nghiệm, proof of concept, quy mô nhỏ thì mọi chuyện cũng không có gì đáng nói.

Vấn đề chỉ bắt đầu khi tôi mong muốn có thể phân phối agent này tới mọi người, điều mà tôi quả thật đã không lường trước đã xuất hiện, và tôi coi đây là một điểm cộng khi tôi bước ra khỏi vùng hiểu biết của mình.

Một comment xuất hiện, tôi xin được dẫn lại nguyên văn nội dung như sau: "*Thực tình, với tư cách là người dùng Linux chính hiệu, có quản lý server, có viết phần mềm cho Linux, mình không đề cao bộ source này lắm và cũng **không khuyến khích** ae Linux dùng.*"

Việc bạn đề cao bộ source hay không thì tôi cũng không quan tâm lắm, có sao thì tôi share vậy, không hoa mỹ, không làm màu, nhưng có một vài từ khóa chính mà tôi cảm thấy mình cần quan tâm đó là "*người dùng Linux, quản lý server, viết phần mềm cho Linux, không khuyến khích dùng*".

Lúc này trong đầu tôi bắt đầu xuất hiện những câu hỏi như:

- Mình đã làm sai điều gì nhỉ?
- Lý do gì mà bạn không khuyến khích dùng?

Với tinh thần ham học hỏi, cầu tiến. Tôi không ngần ngại trao đổi thêm với bạn để làm rõ vấn đề. 

Có một trích đoạn khá hài hước mà các bạn nếu xem được các thể loại video reup chủ đề "tổng tài" trên mxh thì sẽ thấy pattern xuất hiện như sau "*Bạn không cải thiện được đâu, bạn không làm được đâu*", đoạn này mình thấy kịch bản nó giống quá nên thực sự thấy khá giải trí :smile:

Quay lại chủ đề chính, hóa ra vấn đề nằm ở cách tôi **đóng gói** và **phân phối** ứng dụng Linux.

Tôi bắt đầu tìm hiểu và so sánh cách tôi phân phối ứng dụng với cách mà Debian, một distro khá phổ biến để triển khai trước.

**Dưới đây là bảng so sánh ưu/nhược**

To be continue...
