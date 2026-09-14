# Physics: Phép đo, sai số và độ không đảm bảo đo

## Mục lục

- [1.Phép đo và các đại lượng đo lường](#1phép-đo-và-các-đại-lượng-đo-lường)

	- [1.1.Khái niệm phép đo](#11khái-niệm-phép-đo)

	  - [1.1.1.Phép đo trực tiếp](#111phép-đo-trực-tiếp)

	  - [1.1.2.Phép đo gián tiếp](#112phép-đo-gián-tiếp)

	- [1.2.Đại lượng vật lý và đơn vị đo](#12đại-lượng-vật-lý-và-đơn-vị-đo)

	  - [1.2.1.Đại lượng cơ bản và đại lượng dẫn xuất](#121đại-lượng-cơ-bản-và-đại-lượng-dẫn-xuất)

	  - [1.2.2.Hệ đơn vị SI và chuyển đổi đơn vị](#122hệ-đơn-vị-si-và-chuyển-đổi-đơn-vị)

	  - 1.2.3.Phân tích thứ nguyên và đơn vị

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

- **dụng cụ hoặc công cụ đo:** chỉ một vật có thể đo đại lượng của một vật, ví dụ thước đo đại lượng chiều dài cm truyền thống, hay đồng hồ bấm giờ để đo thời gian, thậm chí dùng lệnh `perf`, `time` để đo thời gian thực thi một chương trình cũng được xem là dụng cụ đo dù đó là software

- **Đơn vị đo :** Chi một ký hiệu đơn vị ví dụ như `(cm, kg, ns (nanosecond : nano_giây), ms (milisecond : mili-giây), s (second : giây), h (hour : giờ), v.v..)`

- **Đại lượng cần đo :** là mình cần đo cái gì của vật, ví dụ đo chiều dài, chiều rộng, khối lượng, thời gian

- **Kết quả đo :** là kết quả sau khi thực nghiệm quá trình đo đạc

**Ví dụ**, ta có một cây thước và bút chì, thước là dụng cụ đo, ta muốn đo chiều dài thì gọi đó là đại lượng cần đo, thước chỉ có `cm` là thước truyền thống ta gọi đó là đơn vị đo (cm), kết quả sau khi đo một cây bút chì là `10cm`. Dựa vào đó ta suy ra bản chất toán học của phép đo là:

<div align="center">

$$\Large\text{X} = x . u$$

</div>

**Trong đó :**

- X : là đại lượng cần đo

- $$\large x$$ : là giá trị bằng số của đại lượng đó

- $$\large u$$ : là đơn vị đo cùng loại

cho ví dụ, từ kết quả trên đo cây bút chì ta được `10cm` bây giờ ta đổi sang `cm` thì ta dùng, $$\large X = 10 . 1 = 10\text{ cm}$$, nhưng nếu muốn đổi sang `mm` thì ta dùng $$\large X = 10 . 10 = 100\text{ mm}$$

> [!IMPORTANT]
> **Lưu ý:** Giá trị bằng số phụ thuộc vào đơn vị đo được chọn. Chẳng hạn, chiều dài `10 cm` cũng bằng `100 mm`. Đại lượng vật lý không thay đổi, chỉ cách biểu diễn thay đổi.

### 1.1.1.Phép đo trực tiếp

Cái này đơn giản là xác định đại lượng cần đo bằng cách đọc kết quả từ dụng cụ hoặc hệ thống đo đã được thiết lập để đo đại lượng đó, ví dụ dùng thước đo bút chì biết ngay `10cm`, hay dùng đồng hồ đo diện đo được điện trở là `300ohm` hoặc dùng `perf` để đo thời gian thực thi của chương trình

> [!WARNING]
> Đo trực tiếp chỉ mô tả cách xác định đại lượng, không bảo đảm kết quả chính xác tuyệt đối. **Ví dụ**, đồng hồ vạn năng có thể hiển thị `5,00 V` nhưng giá trị thực của điện áp vẫn có thể khác `5,00 V`. Phần này sẽ được giải thích đầy đủ trong chương [sai số và độ không đảm bảo đo](#2sai-số-và-độ-không-đảm-bảo-đo).

### 1.1.2.Phép đo gián tiếp

Cái này đơn giản là dùng các biểu thức toán học suy ra các đại lượng chưa biết của vật sau khi đã biết các đại lượng khác từ phép đo trực tiếp, ví dụ một tam giác vuông ta biết hai cạnh đối và kề vì đo bằng thước, ta dùng định lý pythagoras để tính ra cạnh huyền, gọi là phép đo gián tiếp

## 1.2.Đại lượng vật lý và đơn vị đo

Đại lượng vật lý là một thuộc tính của vật thể, hiện tượng hoặc hệ vật lý có thể xác định bằng phép đo và biểu diễn bằng một giá trị cùng đơn vị đo. **Ví dụ**, Chiều dài của một dây dẫn, khối lượng của một linh kiện, nhiệt độ của CPU, điện áp giữa hai điểm trong mạch điện, thời gian thực thi một chương trình. Mỗi đại lượng mô tả một thuộc tính khác nhau, chiều dài không phải khối lượng, điện áp không phải dòng điện, và thời gian không phải tần số. Một đại lượng vật lý thường được biểu diễn bằng công thức $$\large\text{X} = x.u$$ như trên

Đơn vị đo là một đại lượng cùng loại được chọn làm chuẩn để biểu diễn và so sánh các giá trị của đại lượng cần đo. **Ví dụ**, mét là đơn vị đo chiều dài, giây là đơn vị đo thời gian, volt là đơn vị đo hiệu điện thế.

### 1.2.1.Đại lượng cơ bản và đại lượng dẫn xuất

Đại lượng cơ bản là những đại lượng được chọn làm cơ sở độc lập trong một hệ đơn vị. **Ví dụ**, độ dài, khối lượng và thời gian.

Đại lượng dẫn xuất được xác định thông qua các đại lượng khác bằng một quan hệ toán học. **Ví dụ**, vận tốc được xác định bằng quãng đường chia cho thời gian $$\large v = \frac{s}{t}$$ Gia tốc được xác định bằng độ biến thiên vận tốc chia cho thời gian $$\large a = \frac{\Delta v}{\Delta t}$$.

### 1.2.2.Hệ đơn vị SI và chuyển đổi đơn vị

> [IMPORTANT]
> Đại lượng dẫn xuất $$\large\neq$$ Đơn vị dẫn xuất, đại lượng là thứ cần xác định còn đơn vị là cách biểu diễn giá trị của nó.