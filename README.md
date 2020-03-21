# LinkNeverDie.github.io
 
## Danh mục:
- [URLredirect](#urlredirect)
---
## URLredirect:

- __Vấn đề:__ Facebook thường nhận diện một số url là spam và xoá đi, dồng thời ra thông báo "cảnh cáo" người dùng khi các url đó được chia sẻ quá nhiều

- __Chức năng:__ Chuyển hướng gián tiếp đến url đích

* __Định dạng:__ 
```
https://linkneverdie.github.io/html/URLredirect.html?___<url>___
```

- __Ví dụ:__ Chuyển hướng đến trang chủ Link Never Die

```
https://linkneverdie.github.io/html/URLredirect.html?___https://linkneverdie.com/___
```

- __Tạo nhanh:__ Sử dụng bookmark (dấu trang) để tạo nhanh URLredirect sử dụng url hiện tại
```
javascript:(function(){var dummy = document.createElement('input'),toclip = 'https://linkneverdie.github.io/html/URLredirect.html?___'+window.location.href+'___';document.body.appendChild(dummy);dummy.value = toclip;dummy.select();document.execCommand('copy');document.body.removeChild(dummy);alert('Generated url to clipboard');})();
```
---
### About me:
Mình là Rika - cựu admin Link Never Die. Mình tạo ra tài khoản github này để viết vài thứ tiện ích có thể sẽ dùng ở cộng đồng LND.

Vì không chuyên (nói trắng ra là thiếu hiểu biết) nên có thể không tối ưu và kém chất lượng; mình cũng không rành github nốt. Hãy đóng góp ý kiến giúp mình cải thiện bằng cách gửi tin nhắn đến [trang Facebook cá nhân của mình](https://www.facebook.com/NguyenThaoRi "Rika Nguyễn").

__Lưu ý:__ Mình không còn hoạt động ở Link Never Die nữa.
