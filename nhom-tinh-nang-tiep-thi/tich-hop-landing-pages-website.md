---
description: >-
  Chú ý: Người dùng nên cấu hình lưu trữ dữ liệu từ form về ít nhất 2 nơi. Có
  thể là Google Sheet + API DotB
---

# Tích hợp Landing Pages /Website

## :writing\_hand: Giới thiệu Landing page

> Tích hợp landing page website này làm gì ?

:point\_right: Landing page còn gọi là trang đích, là một trang web độc lập, được tạo riêng cho chiến dịch tiếp thị hoặc quảng cáo, nhằm mục đích thu thập thông tin khách hàng hoặc bán hàng.

:point\_right: Landing page có nhiều mục đích, tuỳ vào doanh nghiệp hoặc mục tiêu quảng cáo của bạn mà nó có nhiều chức năng. Tuy nhiên, nhìn chung thì Landing page có những mục đích sau.

:star2: Thu thập thông tin khách hàng

:star2: Giới thiệu sản phẩm

:star2: Giới thiệu doanh nghiệp

> API là gì ?

&#x20;**API** là các phương thức, giao thức kết nối với các thư viện và ứng dụng khác. Nó là viết tắt của **Application Programming Interface** – giao diện lập trình ứng dụng.

&#x20;**Web API** là một phương thức dùng để cho phép các ứng dụng khác nhau có thể giao tiếp, trao đổi dữ liệu qua lại. Dữ liệu được Web API trả lại thường ở dạng [JSON](https://topdev.vn/blog/json-la-gi/) hoặc XML thông qua giao thức HTTP hoặc HTTPS.

## :zap: Tích hợp với Ladipage.vn

> Bước 1 : Chọn **Lưu Data.**

![](../.gitbook/assets/ladi1.jpg)

> Bước 2: Chọn **Thêm Mới**

![](../.gitbook/assets/ladi2.jpg)

> Bước 3: Đặt tên cấu hình .. Sau đó click chọn Thêm tài khoản liên kết mới.

![](../.gitbook/assets/ladi3.jpg)

{% hint style="info" %}
****:woman\_gesturing\_ok: **Ghi chú**:

&#x20;**Tên cấu hình** : Lưu ý: tên cấu hình nên đặt tên dễ nhớ.
{% endhint %}

> Bước 4: Chọn option là API và sau đó click vào **Thêm Mới.**

![](../.gitbook/assets/ladi4.jpg)

> Bước 5: Maping các trường dữ liệu từ form về API. Sau đó click **Xong.**

![](../.gitbook/assets/ladi5.jpg)

{% hint style="info" %}
****:woman\_gesturing\_ok: **Ghi chú**:

1: Tên lưu trữ: Lưu ý: nên đặt tên dễ nhớ

2: API URL: [**https://api.dotb.cloud/**](https://api.dotb.cloud)&#x20;

VD: ví dụ KH **ABC** English có tên miền sử dụng EMS là **abc.dotb.cloud** thì ==> URL API là: [**https://api.dotb.cloud/abc.dotb.clou**d](https://api.dotb.cloud/abc.dotb.cloud)

3: API Content Type: chọn **application/json.**

4: Mapping các trường dữ liệu từ form về API theo mẫu bên dưới.
{% endhint %}

![](../.gitbook/assets/ladi8.PNG)

> Bước 6: Nếu thêm tài khoản liên kết là google sheet thì click vào thêm tài khoản liên kết và chọn google sheet. Nếu không thì có thể bỏ qua bước này.

![](../.gitbook/assets/ladi6.jpg)

{% hint style="info" %}
****:woman\_gesturing\_ok: **Ghi chú**:

1: Chỉnh sữa

2: Xóa

3: Thêm tài khoản liên kết mới như google sheet, mail,...

![](../.gitbook/assets/ladi6.1.jpg)&#x20;
{% endhint %}

> Bước 7: Cấu hình API đã được set up và nếu có lời nhắn, cảm ơn đến khách hàng chúng ta có thể chọn ở mục số 2. Cuối cùng click **Cập Nhật.**

![](<../.gitbook/assets/ladi7 (1).jpg>)

## :zap: Tích hợp với Wordpress - Contact Form 7

> Bước 1: Vào module **Plugins** chọn **Add New.**

![](../.gitbook/assets/contact1.jpg)

> Bước 2 : Chọn **Tags** cần tìm là **Contact form 7 TO API**, sau đó click chọn **Install Now.**

![](../.gitbook/assets/contact2.jpg)

> Bước 3: Sau đó tiếp tục vào module **Plugins** chọn **Installed Plugins** và chọn phần vừa cài đặt xong click chọn **Active.**

![](../.gitbook/assets/contact6.jpg)

> Bước 4: Tiếp đến vào module Contact click chọn Contact Forms và chọn form cần cấu hình.

![](../.gitbook/assets/contact3.jpg)

> Bước 4: Tại trang Contact Form click chọn **API Integration**.

![](../.gitbook/assets/contact4.jpg)

> Bước 5: Maping các trường dữ liệu từ form về API. Cuối cùng click **Save**.

![](../.gitbook/assets/contact5.jpg)

{% hint style="info" %}
****:woman\_gesturing\_ok: **Ghi chú:**

1: API URL: [**https://api.dotb.cloud/**](https://api.dotb.cloud)&#x20;

VD: ví dụ KH **ABC** English có tên miền sử dụng EMS là **abc.dotb.cloud** thì ==> URL API là: [**https://api.dotb.cloud/abc.dotb.clou**d](https://api.dotb.cloud/abc.dotb.cloud).

2: Input type chọn : **Parameters-GET/POST**  như ảnh.

3: Method: Chọn **GET**.

4: Mapping các trường dữ liệu từ form về API theo mẫu bên dưới.
{% endhint %}

![](../.gitbook/assets/ladi8.PNG)

{% hint style="success" %}
Tương tự cho các Plug-in khác của Wordpress như: WFrom, Gravity .... và các CMS khác như Joomla, Druple.
{% endhint %}
