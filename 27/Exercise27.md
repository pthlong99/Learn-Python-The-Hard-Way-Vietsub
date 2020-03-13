# Giới thiệu logic trong python #

Tính đến thời điểm hiện tại, bạn đã học được cách đọc, ghi file, và cũng học được khá nhiều về khả năng toán học của python.

Bắt đầu từ bài này bạn sẽ không phải học về những lý thuyết tẻ nhạt mà chỉ những nhà toán học nghiên cứu nữa. Bài hôm nay chúng ta sẽ bắt đầu học về logic trong python.

Trong python sẽ có những toán tử và cụm từ để xác định xem thứ gì đó là đúng hay sai. Nó bao gồm:

- and
- or
- not
- != (không bằng nhau)
- == (bằng nhau)
- \>= (lớn hơn bằng)
- <= (nhỏ hơn bằng)
- true (đúng)
- false (sai)

Và để kết hợp những thứ này lại với nhau mà không sảy ra nhầm lẫn thì người ta đã tạo ra bảng sự thật hay bảng chân lý để ghi nhớ chúng.

**Bảng sự thật**

|Not|True?|
|:-:|:-:|
|not False|True|
|not True|False|


|Or|True?|
|:-:|:-:|
|True or False|True|
|True or True|True|
|False or True|True|
|False or False|False|


|And|True?|
|:-:|:-:|
|True and False|False|
|True and True|True|
|False and True|False|
|False and False|False|


|Not Or|True?|
|:-:|:-:|
|not (True or False)|False|
|not (True or True)|False|
|not (False or True)|False|
|not (False or False)|True|


|Not And|True?|
|:-:|:-:|
|not (True and False)|True|
|not (True and True)|False|
|not (False and True)|True|
|not (False and False)|True|


|!=|True?|
|:-:|:-:|
|1 != 0|True|
|1 != 1|False|
|0 != 1|True|
|0 != 0|False|


|==|True?|
|:-:|:-:|
|1 == 1|True|
|1 == 0|False|
|0 == 0|True|
|0 == 1|False|


Hãy cố gắng ghi nhớ chúng nhé, những bài tập sau sẽ phải dùng đến chúng rất nhiều.


### Thắc mắc bạn đọc ###

**1. Tôi có thể chỉ cần học đại số boolean mà không cần nhớ điều này không?**

  Chắc chắn, bạn có thể làm điều đó nhưng đến khi bạn viết chương trình nếu bạn không nhớ nó bạn sẽ tốn rất nhiều thời gian để xem lại.
