# Physics: Phép đo, sai số

## Mục lục

- [1.Phép đo và các đại lượng đo lường](#1phép-đo-và-các-đại-lượng-đo-lường)

	- 1.1.Khái niệm phép đo

	  - 1.1.1.Phép đo trực tiếp

	  - 1.1.2.Phép đo gián tiếp

	- 1.2.Đại lượng vật lý và đơn vị đo

	  - 1.2.1.Đại lượng cơ bản và đại lượng dẫn xuất

	  - 1.2.2.Hệ đơn vị SI và chuyển đổi đơn vị

	- 1.3.Giá trị thực, giá trị đo và giá trị tham chiếu

	- 1.4.Độ chính xác, độ chụm và độ phân giải

- 2.Sai số và độ không đảm bảo đo

	- 2.1.Khái niệm sai số phép đo

	- 2.2.Sai số hệ thống

	  - 2.2.1.Sai số do dụng cụ đo

	  - 2.2.2.Sai số do phương pháp đo

	  - 2.2.3.Sai số do môi trường và người đo

	- 2.3.Sai số ngẫu nhiên

	- 2.4.Độ không đảm bảo đo

	  - 2.4.1.Phân biệt sai số và độ không đảm bảo đo

	  - 2.4.2.Độ không đảm bảo loại A và loại B

	- 2.5.Hiệu chuẩn và kiểm định dụng cụ đo

- 3.Xác định sai số và xử lý kết quả đo

	- 3.1.Giá trị trung bình của nhiều lần đo

	- 3.2.Sai số tuyệt đối của từng lần đo

	- 3.3.Sai số tuyệt đối trung bình

	- 3.4.Sai số tuyệt đối của phép đo

	- 3.5.Sai số tỉ đối và sai số phần trăm

	- 3.6.Độ lệch chuẩn và phương sai

	- 3.7.Chữ số có nghĩa và quy tắc làm tròn

	- 3.8.Ghi kết quả đo và biểu diễn độ không đảm bảo

- 4.Sai số của phép đo gián tiếp và truyền sai số

	- 4.1.Sai số của tổng và hiệu

	- 4.2.Sai số của tích và thương

	- 4.3.Sai số của lũy thừa và căn bậc hai

	- 4.4.Truyền sai số qua hàm số

	  - 4.4.1.Vi phân và đạo hàm trong đo lường

	  - 4.4.2.Truyền độ không đảm bảo theo căn tổng bình phương

	- 4.5.Sai số tương quan giữa các đại lượng đo

	- 4.6.Sai số giới hạn và trường hợp xấu nhất

- 5.Cơ sở toán học của đo lường

	- 5.1.Tỉ lệ, tỉ số và phần trăm

	- 5.2.Trị tuyệt đối và độ lớn của sai lệch

	- 5.3.Hàm số và sự phụ thuộc giữa các đại lượng

	- 5.4.Cấp số cộng và độ biến thiên đều

	- 5.5.Đạo hàm và độ nhạy của phép đo

	- 5.6.Xác suất và phân phối dữ liệu

	- 5.7.Thống kê mô tả và phân tích ngoại lệ

---

# 1.Phép đo và các đại lượng đo lường

## 1.1.Khái niệm phép đo

Phép đo là quá trình so sánh một đại lượng cần đo với một đại lượng cùng loại được chọn làm đơn vị đo, nhằm xác định giá trị của đại lượng đó. Nói đơn giản thế này, muốn biết một vật dài bao nhiêu, ta so sánh chiều dài của nó với một đơn vị chiều dài, chẳng hạn mét. Các thuật ngữ của vật lý cơ bản như sau:

- **dụng cụ đo :** chỉ một vật có thể đo đại lượng của một vật, ví dụ thước đo đại lượng chiều dài cm truyền thống, hay đồng hồ bấm giờ để đo thời gian, thậm chí dùng lệnh `perf`, `time` để đo thời gian thực thi một chương trình cũng được xem là dụng cụ đo dù đó là software

- **Đơn vị đo :** Chi một ký hiệu đơn vị ví dụ như `(cm, kg, ns (nanosecon : nano_giây), ms (milisecon : mili-giây), s (second : giây), h (hour : giờ), v.v..)`

- **Đại lượng cần đo :** là mình cần đo cái gì của vật, ví dụ đo chiều dài, chiều rộng, cân nặng, thời gian

- **Kết quả đo :** là kết quả sau khi thực nghiệm quá trình đo đạc

**Ví dụ**, ta có một cây thước và bút chì, thước là dụng cụ đo, ta muốn đo chiều dài thì gọi đó là đại lượng cần đo, thước chỉ có `cm` là thước truyền thống ta gọi đó là đơn vị đo (cm), kết quả sau khi đo một cây bút chì là `10cm`. Dựa vào đó ta suy ra bản chất toán học của phép đo là:

<div align="center">

$$\Large\text{X} = x . u$$

</div>

**Trong đó :**

- X : là đại lượng cần đo

- $$\large x$$ : là giá trị bằng số của đại lượng đó

- $$\large u$$ : là đơn vị đo cùng loại

cho ví dụ, từ kết quả trên đo cây bút chì ta được `10cm` bây giờ ta đổi sang `cm` thì ta dùng, $$\large X_{\text{cm}} = 10 . 1 = 10$$, nhưng nếu muốn đổi sang `mm` thì ta dùng $$\large X_{\text{mm}} = 10 . 10 = 100$$

> [!IMPORTANT]
> **Lưu ý:** Giá trị bằng số phụ thuộc vào đơn vị đo được chọn. Chẳng hạn, chiều dài `10 cm` cũng bằng `100 mm`. Đại lượng vật lý không thay đổi, chỉ cách biểu diễn thay đổi.