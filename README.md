<html lang="vi">
  <head>
    <meta charset = "UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  </head>
  <body>
     <!-- Banner -->
    <div class="banner">
        <h1 style="text-align:center;text-decorating: none; color: white; padding: 0 30px;">Bài 7: HTML VÀ CẤU TRÚC TRANG WEB</h1>
    </div>
  </body>
    <style>
      body {
    margin: 0;
    font-family: 'Times New Roman';
    background-color: #f2f2f2;
}
      /* Banner nền ảnh */
.banner {
    width: 100%;
    height: 300px;
    background-image: url('xinh.jpg');
    background-size: cover;
    background-position: center;
    display: flex;
    justify-content: center;
    align-items: center;
}
.banner h1 {
    color: white;
    font-size: 40px;
    letter-spacing: 5px;
    font-weight: bold;
}
</style>
   <div id="wp-products">
    <h1 style="text-align:center;text-decorating: none; color: #243b9a; padding: 0 30px;">LUYỆN TẬP</h1>
  </div>
  <div style="background-color: #FFFFFF; padding: 10px;">
  		<h2>Luyện tập 1: Tìm ví dụ về phần tử HTML không thể lồng, tức là không thể có quan hệ cha con trong cây thông tin của trang web.</h2> 
  </div>
  		  <p>_Các thẻ như h1, h2, h3, p,... không thể lồng </p>
        <p>_Các thẻ như b, u, i, em, strong,...cũng không thể lồng </p>
   <div style="background-color: #FFFFFF; padding: 10px;">
        <h2>Luyện tập 2: Chọn một văn bản đơn giản soạn thảo tệp HTML để hiển thị nội dung văn bản đó. Vẽ cây thông tin các phần tử HTML của trang web vừa soạn thảo.</h2>
   </div>
        <p>< !DOCTYPE html ></p>
        <p>< html></p>
        <p>  < head></p>
        <p>    < meta charset="utf-8"></p>
        <p>    < title>Luyện tập Bài 2< /title></p>
        <p>  < /head></p>
        <p>  < body></p>
        <p>    < h3 align="center">Ca dao Việt Nam< /h3></p>
        <p>    < p align="center"></p>
        <p>    Trong đầm gì đẹp bằng sen< br></p>
        <p>    Lá xanh bông trắng lại chen nhụy vàng< br></p>
        <p>    Nhụy vàng bông trắng lá< br></p>
        <p>    Gần bùn mà chẳng hôi tanh mùi bùn</p>
        <p>    < /p></p>
        <p>  < /body></p>
        <p>< /html></p>
        <img src="LT2.png">
        <div id="wp-products">
    <h1 style="text-align:center;text-decorating: none; color: #243b9a; padding: 0 30px;">VẬN DỤNG</h1>
  </div>
          <div style="background-color: #FFFFFF; padding: 10px;">
        <h2>Vận dụng 1: Em hãy tìm trên mạng các trang web hỗ trợ soạn thảo HTML trực tuyến.</h2>
          </div>
        <p>Một số trang web phổ biến cung cấp các công cụ soạn thảo HTML trực tuyến:</p>
        <p>JSFiddle (https://jsfiddle.net/).</p>
        <p>CodePen US Bin (https://jsbin.com/).</p>
        <p>Repl.it (https://replit.com/).</p>
          <div style="background-color: #FFFFFF; padding: 10px;">
        <h2>Vận dụng 2: Sử dụng phần mềm soạn thảo HTML và soạn thảo trang web có nội dung như Hình 7.7. Lưu ý rằng thẻ < img> với tính tăng thể hiện ảnh trên trang web có cú pháp: < img src = "tên tệp ảnh">,trong đó “tên tệp ảnh” chính là đường dẫn của tệp hình ảnh cần đưa lên trang.</h2>
          </div>
        <p>< !DOCTYPE html></p>
        <p>< html></p>
        <p>  < head></p>
        <p>    < meta charset="utf-8"></p>
        <p>    < title>Lịch sử phát triển HTML< /title></p>
        <p>  < /head></p>
        <p>  < body></p>
        <p>     < h1>< strong>Lịch sử phát triển HTML</ strong>< /h1></p>
        <p>     < p>Các chuẩn HTML của trang web hiện nay được nhà vật lý Tim Berners-Lee đưa ra lần đầu tiên vào những năm 1990 của thế kỷ XX tại trung tâm vật lý hạt nhân CERN.< /p></p>
        <p>     < p>Ý tưởng ban đầu của Berners-Lee là muốn thiết lập một chuẩn chung để thể hiện và chia sẻ các văn bản có thể trao đổi bên trong cơ quan CERN.< /p></p>
        <p>     < p>Hình ảnh sau là sơ đồ thông tin mà Tim Berners-Lee đưa ra lần đầu tiên để minh họa cho ý tưởng của mình. Trong sơ đồ này lần đầu tiên xuất hiện cụm từ “hypertext” (siêu văn bản).< /p></p>
        <p>     <!-- Bạn cần thay thế 'đường_dẫn_đến_hình_ảnh_của_bạn' bằng đường dẫn thực tế hoặc URL của hình ảnh mà bạn muốn chèn -->
        <p>     < img src="đường_dẫn_đến_hình_ảnh" alt="Sơ đồ Hypertext của Tim Berners-Lee" style="max-width: 100%; height: auto;"></p>
        <p>     < p>Phiên bản đầu tiên của HTML được thiết lập vào cuối năm 1991 mang tên “các thẻ HTML” văn bản này do chính Tim Berners-Lee biên soạn.</ p></p>
        <p>     < p>Từ đó các phiên bản tiếp theo của HTML lần lượt ra đời cùng với sự phát triển của công nghệ internet.< /p></p>
        <p>     < p>Phiên bản hiện tại là HTML5, ra đời năm 2014.< /p></p>
        <p>  < /body></p>
        <p>< /html></p>
    </div>
  </body>
</html>
