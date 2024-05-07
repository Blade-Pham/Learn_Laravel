# Learn_Laravel
<table>
  <tr>
    <th>File</th>
    <th>Mô tả</th>
  </tr>
  
  <tr>
    <td>User</td>
    <td>User gửi yêu cầu</td>
  </tr>
  
  <tr>
    <td>Routing</td>
    <td>Yêu cầu từ User đến Routing điều hướng<br>
      <ul>
        <li>Tới controller để xử lý yêu cầu</li>
        <li>Tới MiddleWare để kiểm tra điều hướng cần thiết</li>
        <li>Tới View nếu không cần xử </li>
      </ul>
    </td>
  </tr>
  
  <tr>
    <td>MiddleWare</td>
    <td>bộ lọc http từ request, ví dụ kiểm tra thông tin xác thực người dùng sau đó chuyển về controller để tiếp tục điều hướng</td>
  </tr>
  
  <tr>
    <td>Controller</td>
    <td>Trung tâm điều khiển của hệ thống
    <ul>
      <li>Controller kết nối với Database thông qua Model hoặc có thể kết nối trực tiếp thông qua các câu lệnh </li>
      <li>Kết quả xử lý sẽ trả về View</li>
    </ul>
    </td>
  </tr>
  
  <tr>
    <td>Model</td>
    <td>Khi có yêu cầu từ Controller, Model sẽ tương tác với Database trả kết quả về Controller, 1 số trường hợp có thể trả thẳng về View </td>
  </tr>
  
  <tr>
    <td></td>
    <td></td>
  </tr>
  
  <tr>
    <td></td>
    <td></td>
  </tr>
  
  <tr>
    <td></td>
    <td></td>
  </tr>
  
  <tr>
    <td></td>
    <td></td>
  </tr>
</table>
