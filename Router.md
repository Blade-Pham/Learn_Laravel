<ul>
<li>
<h3> Basic Router</h3>
<p><strong>Xác định tuyến dựa trên URl tương vào hàm controller(có thể đi thẳng đến View)</strong></p>
<p>Router::get('url','usercontroller@controller');</p>
</li>
<li>
  <h3> Parameter Router</h3>
  <p> Cho phép định tuyến các URL có tham số động </p>
  <p>Router::get('/url/{id}','usercontroller@controller');</p>
</li>
<li>
  <h3> Named Router</h3>
  <p> Đặt tên cho Router, giúp tham chiếu đến router dễ dàng</p>
  <p> Router::get('/url','usercontroller@controller')->name['yourname'];</p>
</li>
</ul>
