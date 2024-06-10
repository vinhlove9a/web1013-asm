<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trang chủ</title>
    <link rel="stylesheet" href="trangchu.css">
</head>
<script>
    function showMessage() {
        alert('Vinh chưa làm xong cái này');
    }
    function showMessage1(){
        alert('Chào mừng đến với trang chủ trường cao đẳng FPT Polytechnic');
    }
    function showMessage2(){
        alert('Chào mừng đến với trang giới thiệu về trường cao đẳng FPT Polytechnic');
    }
    function showMessage3(){
        alert('Chào mừng đến với trang liên hệ của trường cao đẳng FPT Polytechnic\nhãy liên hệ với chúng tôi qua các địa chỉ dưới đây tại cơ sở Hà Nội');
    }
    function showMessage4(){
        alert('Hỗ trợ về các chức năng dành cho sinh viên theo học tại cao đẳng FPT Polytechnic');
    }
    function showMessage5(){
        alert('Góp ý cho chúng tôi ở cuối trang để góp phần tạo ra môi trường học tập chuyên nghiệp nhất');
    }
    </script>
<body>
    <div class="container">
        <header>
            <div class="logo">
                <a href="trangchu.html">    
                    <img src="../lab1/img/1.1/FptPoly Logo.png" alt="" width="200px">
                </a>
            </div>
        </header>
        <nav>
            <a href="trangchu.html" onclick=showMessage1()>Trang chủ</a>
            <a href="gioithieu.html" onclick=showMessage2()>Giới thiệu</a>
            <a href="lienhe.html" onclick=showMessage3()>Liên hệ</a>
            <a href="hotro.html" onclick=showMessage4()>Hỗ trợ</a>
            <a href="feedback.html" onclick=showMessage5()>Feedback</a>
            <div class="search">
                <form action="">
                    <input type="text" >
                    <button onclick="showMessage()">Tìm kiếm</button>
                </form>
            </div>
        </nav>
        <div class="banner">
            <img src="img/banner.gif" alt="" width="100%">
        </div>
        <article>
            <img src="img/article1.webp" alt=""width="100%">
                <h2 align="center">Vấn đề chọn việc làm trong năm 2024 </h2>
                <p>
                Chọn lựa việc làm luôn là vấn đề “đau đầu” của mọi người, đặc biệt là những học sinh đứng trước ngưỡng
                cửa tìm ngành nghề phù hợp cho mình. Đừng lo, FPT Polytechnic sẽ giúp bạn chọn ra những ngành nghề
                hot nhất trong 5 năm tới của trường, gợi ý các công việc có thể giúp các bạn có mức lương cao và phù hợp
                với xu hướng hiện đại.
                </p>
        </article>
        <aside>
            <div class="DangKiTuyenSinh">
                <form action="" class="form_mau">
                    <div class="formchung">
                        <label class="form_label" for="">Họ và tên:</label> <br>
                        <input class="form_input" type="text" name="" id="" minlength="5" required>
                    </div>
                    <div class="formchung">
                        <label class="form_label" for="">Email:</label> <br>
                        <input class="form_input" type="text" name="" id="" minlength="5" required>
                    </div>
                    <fieldset class="form_input">
                        <legend>Giới tính</legend>
                        <input type="radio" name="GT" id="">Nam
                        <input type="radio" name="GT" id="">Nữ
                    </fieldset> <br>
                    <div class="formchung">
                        <label class="form_label" for="">Ngày sinh</label><br>
                        <input class="form_input" type="date" name="" id="" required><br>
                    </div>
                    <div class="formchung">
                        <label class="form_label" for="">Điểm thi tốt nghiệp THPT</label>
                        <input class="form_input" type="number" name="" id="" step="0.25" min="0" max="30" required><br>
                    </div>
                    <div class="formchung">
                        <label class="form_label" for="">Nghành học muốn đăng kí</label>
                        <select class="form_input" name="" id="">
                            <option value="">Phát triển phần mềm</option>
                            <option value="">Kiểm thử phần mềm</option>
                            <option value="">Thiết kế đồ họa</option>
                            <option value="">Marketing</option>
                            <option value="">Cơ khí</option>
                            <option value="">Lập trình web</option>
                            <option value="">Ứng dụng phần mềm</option>
                            <option value="">Lập trình game</option>
                        </select> <br>
                    </div>

                    <div class="formchung">
                        <label class="form_label" for="">Ghi chú</label>
                        <textarea class="form_input" name="" id="" required></textarea>
                    </div>
                    <hr>
                    <div class="form_button">
                        <button type="submit">Đăng kí</button>
                        <button type="reset">Nhập lại</button>
                        <button type="reset" disabled>Xóa</button>
                        <button type="submit">Tìm kiếm</button>
                    </div>
                </form>
            </div>
        </aside>
        <footer>
            <div class="footer1">
                <img src="img/logo2.png" alt="" width="200px">
                <div class="LienHe">
                    <a href="https://www.facebook.com/fpt.poly"><img src="img/fb.png" alt=""></a>
                    <a href="https://www.youtube.com/channel/UCHXm-vzOfAuLucVBKDUfhvQ"><img src="img/youtube.png"
                            alt=""></a>
                    <a href="https://www.tiktok.com/@fpt.polytechnic.official"><img src="img/tiktok.png" alt=""></a>
                    <a
                        href="https://vi.wikipedia.org/wiki/Tr%C6%B0%E1%BB%9Dng_Cao_%C4%91%E1%BA%B3ng_Th%E1%BB%B1c_h%C3%A0nh_FPT"><img
                            src="img/wiki.png" alt=""></a>
                </div>
                <div class="ThongTinLienHe">
                    <h2>THÔNG TIN LIÊN HỆ</h2> <br>
                    Điện thoại: (024) 7300 1955 <br> <br>
                    Email: caodang@fpt.edu.vn
                </div>
            </div>
            <div class="footer2">
                <h2>HỆ THỐNG VĂN PHÒNG TUYỂN SINH</h2>
                <div class="ThongTinTuyenSinh">
                    Cơ sở Hà Nội <br>
                    Cổng số 1, Tòa nhà FPT Polytechnic, 13 phố Trịnh Văn Bô, phường Phương Canh, quận Nam Từ Liêm, TP Hà
                    <br>
                    Nội <br>
                    <br>
                    <br>
                    Km12 Cầu Diễn, Phường Phúc Diễn, Quận Bắc Từ Liêm, Hà Nội <br>
                    (024) 8582 0808 <br>
                    <br> <br>
                    Cơ sở Thái Nguyên <br>
                    Tòa nhà FPT Polytechnic, đường đê Mỏ Bạch, tổ 10, phường Quyết Thắng, TP Thái Nguyên, tỉnh Thái <br>
                    Nguyên <br>
                    091 532 9213 <br>
                    <br> <br>
                    Cơ sở Hải Phòng <br>
                    271 Lê Thánh Tông, phường Máy Chai, quận Ngô Quyền, TP Hải Phòng <br>
                    0915431313 <br>
                    <br> <br>
                    Cơ sở Hà Nam <br>
                    Tổ hợp Giáo dục FPT, Unischool, Khu Đại học Nam Cao, Phường Hoàng Đông, Thị xã Duy Tiên, Hà Nam <br>
                    0911 968 213 <br>

                    <br>
                </div>
            </div>
        </footer>
    </div>
</body>

</html>
