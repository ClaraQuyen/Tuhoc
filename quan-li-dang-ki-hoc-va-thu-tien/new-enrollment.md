---
description: >-
  Tính năng này cho phép người dùng sử dụng các khoản dư hiện có của học viên để
  mua khóa học mới để Enroll và cho phép add học viên trực tiếp vào lớp qua cách
  thức tạo Payment - Cashholder.
---

# 🆕 New - Enrollment

{% hint style="info" %}
**Điều kiện Kích hoạt Auto-Enrollment khi tạo Payment:** &#x20;

1. **Số giờ học viên đăng kí học trong lớp phải >= 10 giờ**&#x20;
2. **Payment type: Cashholder**
{% endhint %}

> **Bước 1:** Ở màn hình danh sách của module **Payments**, ta nhấn vào button **Create Payment** để mở ra màn hình thêm mới Payment.

![](../.gitbook/assets/payment1.jpg)

> **Bước 2:**&#x20;> Tại màn hình tạo mới **Payments**, nhập đầy đủ các thông tin cần thiết, người dùng lưu ý rằng các trường (field) có chữ **Required** bắt buộc phải nhập thông tin vào, những field khác có thể bỏ qua và lưu ý chọn Payment Type là **Cashholder.** Sau đó nhấn chọn button **Save** để hoàn tất việc tạo ra một **Payments** mới

![](../.gitbook/assets/New\_Auto1.png)

{% hint style="info" %}
****:woman\_gesturing\_ok: **Ghi chú:**

1. Lựa chọn học viên.&#x20;   Nhấn vào biểu tượng <img src="../.gitbook/assets/Enroll4.png" alt="" data-size="line">, một popup xuất hiện, tìm kiếm và lựa chọn Học viên.
2. Lựa chọn **Payment Type** là **Cashholder**.
3. Lựa chọn khoá học viên mua.
4. Nhập số giờ học viên mua khóa học (có thể nhập tổng số giờ nếu 2 hoặc 3 khóa cùng KOC)**.**
5. Lựa chọn các Discount/Sponsor (Nếu có).
6. Lựa chọn khoảng tiền còn dư học viên (bao gồm đặt cọc, các khoản phí học viên chưa sử dụng) trước đó để khấu trừ vào Payment tiếp theo (Nếu có).
7. Lựa chọn số lần thanh toán
8. Check **** chọn <mark style="color:green;">**Auto-Enroll**</mark>: Chọn lớp, ngày bắt đầu học của học viên. Hệ thống sẽ tự động add học viên vào lớp, sau khi đã thực hiện thu tiền.
{% endhint %}

> **Bước 3:** Sau khi Save thành công, hệ thống hiển thị thông tin Payment như bên dưới. Cuối cùng thực hiện Thu tiền học viên.

![](../.gitbook/assets/New\_Auto2.png)

{% hint style="info" %}
****:tada:**Ghi chú:**

1. Phương thức thu tiền có thể xem **** [<mark style="color:blue;">**>>Tại Đây<<**</mark>](https://help.dotb.vn/quan-li-dang-ki-hoc-va-thu-tien/quan-li-thanh-toan#thanh-toan-cho-payment)
2. Khi chưa thanh toán -> có thể chỉnh sửa ngày bắt đầu học của học viên trong lớp bằng tính năng <mark style="color:red;">**Edit trên Payment (Auto - Enroll).**</mark>:point\_down:<mark style="color:red;">****</mark>
{% endhint %}

![](../.gitbook/assets/newauto\_3.png)

{% hint style="success" %}
<mark style="color:blue;">****</mark>:person\_raising\_hand: <mark style="color:blue;">**Lưu ý :**</mark>&#x20;

Sau khi **đã thánh toán học phí** -> **hệ thống sẽ tự động đưa học viên vào lớp** với thông tin bạn đã chọn. Tuy nhiên để chỉnh sửa lại một số thông tin:

<mark style="color:red;">****</mark>:clap:<mark style="color:red;">**Chỉnh sửa lại số tiền thu**</mark><mark style="color:red;">:</mark>&#x20;

1. Remove học viên ra khỏi lớp bằng tính năng :point\_right: [<mark style="color:blue;">**Delay**</mark>](bao-luu-xoa-hoc-vien.md)<mark style="color:blue;">**.**</mark>
2. Quay lại **Payment **<mark style="color:orange;">**Void Phiếu thu**</mark>, thực hiện thu tiền lại.

<mark style="color:red;">****</mark>:clap:<mark style="color:red;">**Chỉnh sửa lại ngày bắt đầu học**</mark> của học viên bằng tình năng Edit trên Payment (Auto- Enroll)

1. Remove học viên ra khỏi lớp bằng tính năng :point\_right: [<mark style="color:blue;">**Delay**</mark>](bao-luu-xoa-hoc-vien.md).
2. Dùng tính năng <mark style="color:green;">**Edit**</mark> trên **Payment **<mark style="color:green;">**(Auto- Enroll)**</mark> chọn lại ngày bắt đầu.
{% endhint %}

![](../.gitbook/assets/newauto\_3.png)

{% hint style="warning" %}
**Lưu ý**:&#x20;

**(\*): **<mark style="color:red;">**Deactive Auto- Enroll**</mark>**:** Hệ thống sẽ không tự động Enroll học viên ở những lần học nợ tiếp theo, khi thực hiện Thu Tiền.

Nếu muốn hệ thống tự động Enroll ở những lần thu tiền sau, người dùng cần **active Auto - Enroll** lại bằng cách bấm vào button **Auto - Enroll trên Payment.**
{% endhint %}

![](../.gitbook/assets/eidt\_auto.png)
