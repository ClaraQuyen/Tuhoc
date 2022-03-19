---
description: >-
  Tính năng này sẽ linh động hơn tính năng hiện tại, cho phép ng dùng có thể add
  học viên trực tiếp vào lớp qua cách thức tạo Payment - Cashholder.
---

# New - Enrollment

:tada:**Điều kiện Kích hoạt Auto-Enrollment khi tạo Payment:**&#x20;

:point\_right:<mark style="color:red;">**Số giờ học viên đăng kí học trong lớp phải >= 10 giờ và Payment type : Cashholder**</mark>

> Bước 1: Đưa chuột vào module **Payment** chọn **Create Payment**.

![](../.gitbook/assets/payment1.jpg)

> Bước 2:&#x20;> Tại màn hình tạo mới thanh toán nhập đầy đủ các thông tin mà học viên mua khóa học như discount, số giờ mua,... và lưu ý chọn Payment Type là **Cashholder**. Sau đó check vào ô Auto - Enroll để chọn Lớp, Ngày bắt đầu học của học viên, hệ thống sẽ tự động Enroll đưa học viên vào lớp, sau khi đã thu tiền. Cuối cùng click **Save** để hoàn tất.

![](../.gitbook/assets/New\_Auto1.png)

{% hint style="info" %}
****:woman\_gesturing\_ok: **Ghi chú:**

1.Lựa chọn học viên.&#x20;Click vào biểu tượng ![](../.gitbook/assets/Enroll4.png) , một popup xuất hiện, tìm kiếm và lựa chọn Học viên.

2: Lựa chọn **Payment** type là **Cashholder**.

3: Lựa chọn khoá học viên mua.

4: Nhập số giờ học viên mua khóa học (có thể nhập tổng số giờ nếu 2 hoặc 3 khóa cùng KOC)**.**

5: Lựa chọn các Discount/Sponsor (Nếu có).

6.Lựa chọn khoảng tiền đã đặt cọc trước đó để sử dụng.

7: Lựa chọn số lần thanh toán

8\. **Check** chọn <mark style="color:green;">**Auto-Enroll**</mark> : Chọn lớp, ngày bắt đầu học của học viên. Hệ thống sẽ tự động add học viên vào lớp, sau khi đã thực hiện thu tiền.
{% endhint %}

> Bước 3: Sau khi Save thành công, hệ thống hiện thị thông tin Payment như bên dưới. Cuối cùng thực hiện Thu Tiền học viên.

![](../.gitbook/assets/New\_Auto2.png)

{% hint style="info" %}
****:tada:**Ghi chú:**

**1.Phương thức thu tiền có thể xem** [<mark style="color:blue;">**>>Tại Đây<<**</mark>](https://help.dotb.vn/quan-li-dang-ki-hoc-va-thu-tien/quan-li-thanh-toan#thanh-toan-cho-payment)<mark style="color:blue;">****</mark>

2.Khi chưa thanh toán -> có thể chỉnh sửa ngày bắt đầu học của học viên trong lớp bằng tính năng <mark style="color:red;">**Edit trên Payment (Auto - Enroll).**</mark>:point\_down:<mark style="color:red;">****</mark>
{% endhint %}

![](../.gitbook/assets/newauto\_3.png)

{% hint style="success" %}
<mark style="color:blue;">****</mark>:person\_raising\_hand:<mark style="color:blue;">**Lưu ý :**</mark>&#x20;

Sau khi **đã thánh toán học phí** -> **hệ thống sẽ tự động đưa học viên vào lớp** với thông tin bạn đã chọn. Tuy nhiên để chỉnh sửa lại một số thông tin:

<mark style="color:red;">****</mark>:clap:<mark style="color:red;">**Chỉnh sủa lại số tiền thu**</mark><mark style="color:red;">:</mark>&#x20;

1.Remove học viên ra khỏi lớp bằng tính năng :point\_right: [<mark style="color:blue;">**Delay**</mark>](bao-luu-xoa-hoc-vien.md),&#x20;

2.Quay lại **Payment **<mark style="color:orange;">**Void Phiếu thu**</mark>, thực hiện thu tiền lại.

<mark style="color:red;">****</mark>:clap:<mark style="color:red;">**Chỉnh sửa lại ngày bắt đầu học**</mark> của học viên bằng tình năng Edit trên Payment (Auto- Enroll),&#x20;

1.Remove học viên ra khỏi lớp bằng tính năng :point\_right: [<mark style="color:blue;">**Delay**</mark>](bao-luu-xoa-hoc-vien.md).

2.Dùng tính năng <mark style="color:green;">**Edit**</mark> trên **Payment **<mark style="color:green;">**(Auto- Enroll)**</mark> chọn lại ngày bắt đầu.
{% endhint %}

![](../.gitbook/assets/newauto\_3.png)

{% hint style="warning" %}
**Lưu ý**:&#x20;

**(\*) : **<mark style="color:red;">**Deactive Auto- Enroll**</mark>** :** Hệ thống sẽ không tự động Enroll học viên ở những lần học nợ tiếp theo, khi thực hiện Thu Tiền.

Nếu muốn hệ thống tự động Enroll ở những lần thu tiền sau, người dùng cần **active Auto - Enroll** lại bằng cách bấm vào button **Auto - Enroll trên Payment.**
{% endhint %}

![](../.gitbook/assets/eidt\_auto.png)
