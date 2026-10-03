# Physics: Phép đo, sai số và độ không đảm bảo đo

## Mục lục

- [1.Phép đo và các đại lượng đo lường](#1phép-đo-và-các-đại-lượng-đo-lường)
	- [1.1.Khái niệm phép đo](#11khái-niệm-phép-đo)
	  - [1.1.1.Phép đo trực tiếp](#111phép-đo-trực-tiếp)
	  - [1.1.2.Phép đo gián tiếp](#112phép-đo-gián-tiếp)
	- [1.2.Đại lượng vật lý và đơn vị đo](#12đại-lượng-vật-lý-và-đơn-vị-đo)
	  - [1.2.1.Đại lượng cơ bản và đại lượng dẫn xuất](#121đại-lượng-cơ-bản-và-đại-lượng-dẫn-xuất)
	  - [1.2.2.Hệ đơn vị SI và chuyển đổi đơn vị](#122hệ-đơn-vị-si-và-chuyển-đổi-đơn-vị)
	  - [1.2.2.1.Bảy đơn vị cơ bản của hệ SI](#1221bảy-đơn-vị-cơ-bản-của-hệ-si)
	  - [1.2.2.2.Đơn vị dẫn xuất](#1222đơn-vị-dẫn-xuất)
	  - [1.2.2.3.Tiền tố SI](#1223tiền-tố-si)
	  - [1.2.2.4.Chuyển đổi đơn vị](#1224chuyển-đổi-đơn-vị)
	  - [1.2.2.4.1.Chuyển đổi giữa các đơn vị cùng loại](#12241chuyển-đổi-giữa-các-đơn-vị-cùng-loại)
	  - [1.2.2.4.2.Chuyển đổi thông qua tiền tố SI](#12242chuyển-đổi-thông-qua-tiền-tố-si)
	  - [1.2.2.4.3.Chuyển đổi đơn vị có lũy thừa](#12243chuyển-đổi-đơn-vị-có-lũy-thừa)
	  - 1.2.2.5.Chuyển đổi đơn vị dẫn xuất
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

Cái này đơn giản là dùng các biểu thức toán học suy ra các đại lượng chưa biết của vật sau khi đã biết các đại lượng khác từ phép đo trực tiếp, ví dụ một tam giác vuông ta biết hai cạnh góc vuông vì đo bằng thước, ta dùng định lý pythagoras để tính ra cạnh huyền, gọi là phép đo gián tiếp

## 1.2.Đại lượng vật lý và đơn vị đo

Đại lượng vật lý là một thuộc tính định lượng của một vật thể, hiện tượng hoặc hệ vật lý, có thể được biểu diễn bằng một giá trị số kèm theo đơn vị đo thích hợp. **Ví dụ**, Chiều dài của một dây dẫn, khối lượng của một linh kiện, nhiệt độ của CPU, điện áp giữa hai điểm trong mạch điện, thời gian thực thi một chương trình. Mỗi đại lượng mô tả một thuộc tính khác nhau, chiều dài không phải khối lượng, điện áp không phải dòng điện, và thời gian không phải tần số. Một đại lượng vật lý thường được biểu diễn bằng công thức $$\large\text{X} = x.u$$ như trên

Đơn vị đo là một đại lượng cùng loại được chọn làm chuẩn để biểu diễn và so sánh các giá trị của đại lượng cần đo. **Ví dụ**, mét là đơn vị đo chiều dài, giây là đơn vị đo thời gian, volt là đơn vị đo hiệu điện thế.

### 1.2.1.Đại lượng cơ bản và đại lượng dẫn xuất

Đại lượng cơ bản là những đại lượng được chọn làm cơ sở độc lập trong một hệ đơn vị. **Ví dụ**, độ dài, khối lượng và thời gian. Đại lượng dẫn xuất được xác định thông qua các đại lượng khác bằng một quan hệ toán học. **Ví dụ**, vận tốc được xác định bằng quãng đường chia cho thời gian $$\Large v = \frac{s}{t}$$ Gia tốc được xác định bằng độ biến thiên vận tốc chia cho thời gian $$\Large a = \frac{\Delta v}{\Delta t}$$.

### 1.2.2.Hệ đơn vị SI và chuyển đổi đơn vị

Hệ đơn vị SI (International System of Units) là hệ thống đơn vị đo lường quốc tế được sử dụng rộng rãi trong khoa học, kỹ thuật và đo lường. SI cung cấp một hệ thống thống nhất để biểu diễn các đại lượng vật lý, trong đó có 7 đơn vị cơ bản làm nền tảng để xây dựng các đơn vị dẫn xuất. Bảng đơn vị cơ bản SI định nghĩa 7 đại lượng cơ bản, mỗi đại lượng có một đơn vị cơ bản tương ứng :

#### 1.2.2.1.Bảy đơn vị cơ bản của hệ SI

<div align="center">

| Đại lượng cơ bản            | Ký hiệu đại lượng | Đơn vị SI            | Ký hiệu đơn vị |
| --------------------------- | ----------------: | -------------------- | -------------: |
| Thời gian                   |             $$\large t$$ | giây (*second*)      |              s |
| Độ dài                      |             $$\large l$$ | mét (*metre*)        |              m |
| Khối lượng                  |             $$\large m$$ | kilôgam (*kilogram*) |             kg |
| Dòng điện                   |             $$\large I$$ | ampe (*ampere*)      |              A |
| Nhiệt độ nhiệt động lực học |             $$\large T$$ | kelvin               |              K |
| Lượng chất                  |             $$\large n$$ | mol (*mole*)         |            mol |
| Cường độ sáng               |             $$\large I_{v}$$ | candela              |             cd |

</div>

> [!IMPORTANT]
> Cần phân biệt giữa Đại lượng dẫn xuất $$\large\neq$$ Đơn vị dẫn xuất $$\large\neq$$ giá trị số , đại lượng là thứ cần xác định còn đơn vị là cách biểu diễn giá trị của nó, còn giá trị bằng số là phần số cho biết độ lớn của đại lượng khi đại lượng được biểu diễn bằng một đơn vị đã chọn. Giá trị này có thể là số nguyên, số thập phân, phân số, số âm, số mũ, căn thức,.... **Ví dụ:** `I = 4.2A`, trong đó `4.2` là biễu diễn số còn `A` là đơn vị ampere, `4.2A` là giá trị của đại lượng được biểu diễn dưới dạng số + đơn vị

#### 1.2.2.2.Đơn vị dẫn xuất

Đơn vị dẫn xuất được hình thành từ các đơn vị cơ bản thông qua các phép nhân, chia và lũy thừa. Cho **ví dụ**, vận tốc ta biết :

<div align="center">

$$\Large v=\frac{s}{t}$$

</div>

Nhưng trong SI thì nó lại biễu diễn như sau:

<div align="center">

$$\Large v=\frac{m}{s} = m/s$$

</div>

Ta thấy sự khác biệt của nó sau khi biểu diễn SI. Cho thêm vài ví dụ ta có:

<div align="center">

$$\Large\text{tính gia tốc: } a = \frac{\Delta v}{\Delta t}$$

$$\Large\Rightarrow a = \frac{m/s}{s} = m/s^{2}$$

$$\Large\text{Tính lực: } F = ma$$

$$\Large\Rightarrow F = kg . m/s^{2}$$

</div>

Như thế, ta có một số đơn vị dẫn xuất thường gặp:

<div align="center">

| Đại lượng       | Quan hệ                 | Đơn vị SI          |
| --------------- | ----------------------- | ------------------ |
| Diện tích       | $$\large A=l^{2}$$               | $$\large\mathrm{m^2}$$   |
| Thể tích        | $$\large V=l^{3}$$               | $$\large\mathrm{m^3}$$   |
| Vận tốc         | $$\large v=s/t$$               | $$\large\mathrm{m/s}$$  |
| Gia tốc         | $$\large a=\frac{\Delta v}{\Delta t}$$ | $$\large\mathrm{m/s^2}$$ |
| Lực             | $$\large F=ma$$                | N                  |
| Công/năng lượng | $$\large W=Fs$$                | J                  |
| Công suất       | $$\large P=W/t$$               | W                  |
| Điện áp         | $$\large U=W/Q$$               | V                  |
| Điện trở        | $$\large R=U/I$$               | Ω                  |
| Tần số          | $$\large f=1/T$$               | Hz                 |

</div>

Ví dụ : 

<div align="center">

$$\Large1J=1Nm=1kg.m^{2}/s^{2}$$

</div>

Như vậy, Joule (J) là một đơn vị dẫn xuất có tên riêng, nhưng về cấu tạo vẫn có thể phân tích thành các đơn vị cơ bản.

#### 1.2.2.3.Tiền tố SI

Trong thực tế, các đại lượng có thể lớn hoặc nhỏ hơn đơn vị cơ bản rất nhiều. SI cung cấp các tiền tố để biểu diễn các bội số hoặc phần của đơn vị. Một số tiền tố quan trọng:

<div align="center">

| Tiền tố | Ký hiệu |        Hệ số |
| ------- | ------: | -----------: |
| kilo    |       k |     $$\large10^{3}$$ |
| mega    |       M |     $$\large10^{6}$$ |
| giga    |       G |     $$\large10^{9}$$ |
| tera    |       T |  $$\large10^{12}$$ |
| milli   |       m |  $$\large10^{-3}$$ |
| micro   | $$\large\mu$$ |  $$\large10^{-6}$$ |
| nano    |       n |  $$\large10^{-9}$$ |
| pico    |       p | $$\large10^{-12}$$ |

</div>

#### 1.2.2.4.Chuyển đổi đơn vị

Chuyển đổi đơn vị là quá trình biểu diễn cùng một đại lượng vật lý bằng một đơn vị khác mà không làm thay đổi giá trị của đại lượng đó. **Ví dụ**, chuyển đổi đơn vị `m` sang `cm` ta có `1m = 100cm`. Điều kiện của chuyển đổi đơn vị là, đại lượng vật lý không đổi, giá trị bằng số thay đổi theo đơn vị​

#### 1.2.2.4.1.Chuyển đổi giữa các đơn vị cùng loại

Muốn chuyển đổi giữa hai đơn vị cùng loại, cần xác định hệ số chuyển đổi giữa chúng. **Ví dụ**, 1km = 1000m do đó 3.5km = 3.5 x 1000 = 3500m ngược lại chuyển `km -> m` ta thay đổi phép nhân thành phép chia (nguyên lý toán học căn bản được vận dụng nhiều ở giải phương trình) cho ví dụ chuyển 1232m sang km ta xét $$\Large1232m = \frac{1232}{1000} = 1.232km$$

Một cách tổng quát, nếu $$\large1A = kB$$ thì :
<div align="center">

$$\Large xA = xkB$$ 

</div>

và 

<div align="center">

$$\Large yB = \frac{y}{k}A$$

</div>

Trong đó $$\large A$$ và $$\large B$$ là hai đơn vị của cùng một đại lượng.

#### 1.2.2.4.2.Chuyển đổi thông qua tiền tố SI

Các tiền tố SI cho biết bội số hoặc ước số của đơn vị. **Ví dụ** $$\large1km = 10^{3}m$$ thì $$\large2.4km = 2.4 \times 10^{3}m$$ = 2400m, tương tự với việc chuyển đổi `mm -> m` và ta biết $$\large1mm = 10^{-3}m$$ nên ta có $$\large8mm = 8 \times10^{-3}m$$ = 0.008m. Tuy nhiên, ta có thể viết trực tiếp bằng hệ số chuyển đổi như sau :

<div align="center">

$$\Large8mm \times \frac{10^{-3}m}{1mm} = 8\times10^{-3}m$$

</div>

Đơn vị $$\large\mathrm{mm}$$ triệt tiêu, còn lại $$\large\mathrm{m}$$. Đây là cách đặc biệt hữu ích khi thực hiện các phép tính có nhiều đơn vị.

#### 1.2.2.4.3.Chuyển đổi đơn vị có lũy thừa

Khi đơn vị xuất hiện trong một đại lượng có lũy thừa, hệ số chuyển đổi cũng phải được nâng lên cùng lũy thừa. **Ví dụ**, ta có $$\large1m = 100cm = 10^{2}cm$$,