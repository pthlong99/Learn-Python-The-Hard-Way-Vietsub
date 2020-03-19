# Thiết kế và sửa lỗi #

Bây giờ bạn đã biết về các câu lệnh điều kiện if, else, elif. Tôi sẽ cung cấp cho bạn một số quy tắc để giúp bạn tránh xa khỏi những rắc rối. Tôi cũng sẽ cung cấp cho bạn một số mẹo để sửa lỗi cho chương trình khi nó sảy ra vấn đề. Cuối cùng bạn sẽ thiết kế một trò chơi nhỏ tương tự ví dụ của bài hôm trước với một chút thay đổi.

**Các quy tắc khi sử dụng câu lệnh if**

- Tất cả các câu lệnh if phải có vế else.

- Nếu vế else cảu câu lệnh if không bao giờ cần dùng đến thì hãy để vào vế đó hàm die, tương tự hàm dead trong ví dụ cảu bài trước để in ra một thông báo lỗi. Điều này giúp chúng ta phát hiện ra lỗi dễ dàng hơn.

- Không bao giờ lồng nhiều hơn hai hàm if vào nhau, bằng mọi cách hãy làm chúng đơn giản nhất có thể.

- Hãy làm như mỗi câu lệnh if là một đoạn văn, đặt dòng trống trước và sau.

- Phần điều kiện của hàm if phải thật đơn giản, nếu chúng phức tạp hãy tạo riêng một hàm để làm việc đó và trả về true hoặc false.

Nếu bạn tuân thủ các quy tắc trên thì bạn có thể viêt code một cách đơn giản hơn và ít khi mắc lỗi hơn.

**Các quy tắc khi sử dụng câu lệnh for**

- Chỉ sử dụng vòng lặp while để lặp mãi mãi, và điều nãy có nghĩa là không bao giờ. Nó chỉ được cho phép trên python, còn các ngôn ngữ khác thì điều này sẽ là khác.

- Dùng vòng lặp for cho mọi vòng lặp khác, đặc biệt là vòng lặp biết trước số lượng vòng lặp cố định, hoặc có giới hạn kết thúc.


**Các mẹo sửa lỗi**

- Không nên quá lạm dụng trình gỡ lỗi "Debugger". Bởi vì nó giống như quét toàn bộ cơ thể người bệnh. Bạn sẽ không nhận được thông tin nào hữu ích, cụ thể cho việc sửa lỗi, nó chỉ làm cho bạn nhầm lẫn.

- Hãy sử dụng câu lệnh print() để in ra giá trị cảu biến tại các thời điểm trong chương trình, từ đó có thể biết được cách chương trình hoạt động như thế nào, biết dược sai ở chỗ nào.

- Hãy chắc chắn rằng các phần nhỏ của chương trình hoặt động tốt, không cố gắng viết các phần lớn, phức tạp trước, hãy bắt đầu từ những phần nhỏ nhất.

Đến đây bạn đã biết được các quy tắc sử dụng if và for trong python, cũng như đã biết cách sửa lỗi cho một chương trình. Hãy tự tao cho mình một trò chơi nhé.
