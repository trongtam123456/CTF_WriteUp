## Đề :
> There's nothing I love more than oreos, lions, and winning. https://mega.nz/#!DC5F2KgR!P8UotyST_6n2iW5BS1yYnum8KnU0-2Amw2nq3UoMq0Y Have Fun :)
- Tải file về thứ đầu tiên đập vào mắt là 1 chiếc bánh oreo. Dùng `strings` để xem thử nó có gì không. `This is not the flag you are looking for.Q"t` =))).
- Có nghĩa là flag nó không nằm ở đây. Có thể là nó có 1 tệp ẩn nữa.
- `binwalk -e oreo.jpg` quả nhiên có 1 tệp ẩn thật 
- Truy cập vào em thấy có 3 file 
- Mở lần lượt các file đến file b.jpg thì lệnh `strings b.jpg` có tác dụng
- Flag là : `flag{eat_more_oreos}`