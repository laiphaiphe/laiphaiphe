<!DOCTYPE html>
<html lang="en">
</html>
<head>
<title>hệ thống tra soát thông tin</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Thông tin Khách hàng</title>
<style>
body {
font-family: Arial, sans-serif;
background: linear-gradient(to right, violet, indigo, blue, green, yellow, orange, red);
margin: 0;
padding: 0;
display: flex;
align-items: center;
justify-content: center;
height: 100vh;
}

h2 {
color: #fff;
/* Màu chữ trắng để tương phản với nền đen */
}

.form-container {
width: 50%;
background-color: rgba(255, 255, 255, 0.8);
/* Màu nền của khung thông tin với độ trong suốt */
padding: 20px;
border-radius: 8px;
box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

table {
width: 100%;
border-collapse: collapse;
margin: 20px 0;
background-color: #fff;
box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

table,
th,
td {
border: 1px solid #ddd;
}

th,
td {
padding: 10px;
text-align: left;
}

th {
background-color: #4CAF50;
color: #fff;
}

input[type="text"],
input[type="email"],
input[type="tel"] {
width: 100%;
padding: 8px;
margin: 4px 0;
box-sizing: border-box;
}

input[type="submit"] {
background-color: #008CBA;
/* Màu của nút gửi thông tin */
color: #fff;
padding: 10px 20px;
border: none;
border-radius: 4px;
cursor: pointer;
}

input[type="submit"]:hover {
background-color: #005A80;
/* Màu khi di chuột qua nút */
}
</style>
</head>

<body>

<div class="form-container">
<h2>Nhập thông tin tra soát</h2>

<form action="#" method="post">
<table>
  <tr>
    <th>Họ và Tên</th>
    <td><input type="text" name="hoTen" required></td>
  </tr>
  <tr>
    <th>Email</th>
    <td><input type="email" name="email" required></td>
  </tr>
  <tr>
    <th>Số điện thoại</th>
    <td><input type="tel" name="soDienThoai" required></td>
  </tr>
  <tr>
    <th>Số tiền</th>
    <td><input type="text" name="diaChi" required></td>
  </tr>
  <tr>
    <th>Ngân hàng</th>
    <td><input type="text" name="nganHang" required></td>
  </tr>
  <tr>
    <th>Số tài khoản</th>
    <td><input type="text" name="soTaiKhoan" required></td>
  </tr>
</table>

<input type="submit" value="Gửi thông tin">
</form>
</div><link rel="stylesheet" hE="https://www.facebook.com">


</body>

</html>
