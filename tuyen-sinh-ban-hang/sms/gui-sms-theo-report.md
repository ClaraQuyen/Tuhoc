# 📳 Gửi SMS theo Report

> **Bước 1:** Ở màn hình danh sách của module Report, chúng ta chọn báo cáo "Payment List Report".

<figure><img src="../../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

> **Bước 2:** Tại màn hình báo cáo chi tiết những khoản thu với trạng thái thanh toán là **"Unpaid"**, chọn **Export Excel** khi đi Apply (xem báo cáo trước khi xuất báo cáo ra file).

<figure><img src="../../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
:woman\_gesturing\_ok: **Ghi chú** :

1. Thông tin filter để xuất báo cáo
2. Nhấn **Apply** để xem báo cáo&#x20;
3. Xuất report dạng **Excel**
{% endhint %}

> **Bước 3:**&#x20;> Chọn Apply xem báo cáo, tiếp theo chọn **Export Excel**, tải file Excel về máy, sau đó bỏ những filed không cần thiết chỉ giữ lại 2 filed **Tên** và **Số điện thoại** (filed số điện thoại phải có format là **Text**)

![](../../.gitbook/assets/SMS\_report4.png)

> **Bước 4:**> &#x20;Vào module Student, chọn **Send SMS** (bạn có thể chọn 1 trong 2).

![](../../.gitbook/assets/SMS\_report5.png)

> **Bước 5:** Tại màn hình Send SMS, chọn tải **Template SMS List** theo mẫu hệ thống và đưa danh sách học viên vào Template SMS List.

![](<../../.gitbook/assets/SMS\_report6 (1).png>)

> Mẫu template sms

![](../../.gitbook/assets/SMS\_report7.png)

&#x20;                                                                          <img src="../../.gitbook/assets/down-arrow (1).png" alt="" data-size="original">&#x20;

![](../../.gitbook/assets/SMS\_report8.png)

> **Bước 6:**> &#x20;Sau khi có được file dữ liệu như mẫu, tiến hành import vào hệ thống. Cuối cùng click **Send** để gửi tin nhắn.

> Sau khi Upload file lên hệ thống, click **Submit** hệ thống sẽ hiện thị danh sách học viên nhận được tin nhắn của trung tâm.

![](../../.gitbook/assets/SMS\_repport9.png)

{% hint style="info" %}
**Ghi chú:**

1. Danh sách học viên nhận tin nhắn (bạn có thể nhập thêm số điện thoại)
2. Nội dung gửi tin nhắn đến học viên (chọn theo **Template** hoặc bạn có thể soạn nội dung ngẫu nhiên, để chèn tên học viên thì bạn gõ **$name**).&#x20;
3. Kết quả: Thống kê số lượng bạn học viên nào đã nhận được tin nhắn, chưa nhận được tin nhắn, tổng số lượng tin nhắn đã gửi)
{% endhint %}
