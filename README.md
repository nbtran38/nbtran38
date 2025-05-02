<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trang cá nhân</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        .navbar {
            background-color: #333;
            padding: 10px;
            display: flex;
            justify-content: center;
            gap: 20px;
        }
        .navbar button {
            background-color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            font-size: 16px;
        }
        .navbar button:hover {
            background-color: #ddd;
        }
        .content {
            padding: 20px;
            display: none;
        }
        .active {
            display: block;
        }
        .profile-img {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            object-fit: cover;
            margin-top: 20px;
        }
        .music-img {
            width: 300px;
            height: auto;
            margin-top: 20px;
        }
        .music-video {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="navbar">
        <button onclick="showPage('gioithieu')">Giới thiệu</button>
        <button onclick="showPage('sach')">Sách</button>
        <button onclick="showPage('amnhac')">Âm nhạc</button>
        <button onclick="showPage('phim')">Phim</button>
    </div>

    <div id="gioithieu" class="content active">
        <h2>Giới thiệu bản thân</h2>
        <p>Chào mừng bạn đến với trang cá nhân của tôi!</p>
        <img src="https://i.imgur.com/ZF0lqdN.jpeg" alt="Ảnh cá nhân" class="profile-img">
    </div>
    <div id="sach" class="content">
        <h2>Sách yêu thích</h2>
        <div class="container">
                        <div class="book-info">
                <div class="book-cover">
                    <img src="https://product.hstatic.net/1000237375/product/vap-nga-900x900_4_c65e8c029fa5422a81385572827595b2.png" alt="Mỗi Lần Vấp Ngã Là Một Lần Trưởng Thành">
                </div>
                <div class="book-details">
                    <table>
                        <tr>
                            <th>Tác giả:</th>
                            <td>Liêu Trí Phong</td>
                        </tr>
                        <tr>
                            <th>Dịch giả:</th>
                            <td>Trần Yến</td>
                        </tr>
                        <tr>
                            <th>NXB:</th>
                            <td>Thanh niên</td>
                        </tr>
                        <tr>
                            <th>Kích thước:</th>
                            <td>14.5 x 14.5 cm</td>
                        </tr>
                        <tr>
                            <th>Số trang:</th>
                            <td>376</td>
                        </tr>
                        <tr>
                            <th>Năm xuất bản:</th>
                            <td>2022</td>
                        </tr>
                    </table>
                </div>
            </div>
            <div class="book-description">
                <p>Cuốn sách này giúp bạn hiểu rõ hơn về thất bại và cách vươn lên trong cuộc sống. Nó chứa đựng nhiều câu chuyện ý nghĩa, khuyến khích sự trưởng thành qua mỗi lần vấp ngã.</p>
            </div>
<p>&nbsp;&nbsp;&nbsp;&nbsp;Liêu Trí Phong là một tác giả sống tại Mỹ. Có rất nhiều bài viết được đăng trên tạp chí, sách báo, mỗi bài viết đều sưởi ấm trái tim hàng ngàn độc giả. Với cuốn sách “Mỗi lần vấp ngã là một lần trưởng thành” này cũng vậy. Những quan điểm của tác giả về thất bại để giúp những người trẻ hiểu rằng không có gì là đáng sợ, nó là điều hiển nhiên trong cuộc sống.

     <br>&nbsp;&nbsp;&nbsp;&nbsp;“Mỗi lần vấp ngã là một lần trưởng thành” với nội dung theo kiểu kể chuyện và phân tích. Nhưng câu chuyện này như một dẫn chứng cụ thể và sống động trong cuộc sống hàng ngày của mỗi chúng ta, trong đó có tôi và bạn đấy.

    Tác giả Liêu Trí Phong đã dẫn dụ những câu nói, nhưng câu chuyện thực về đối nhân xử thế, về đạo đức về kinh doanh… Để rồi phân tích rõ nét để chúng ta hiểu sâu sắc hơn về cuộc sống của mỗi người đang sống hoặc trong tương lai sẽ cần đến.

       <br>&nbsp;&nbsp;&nbsp;&nbsp;Người ta vẫn thường hay nói mỗi lần vấp ngã là một lần đau và sau lần ngã ấy, chúng ta sẽ trở nên mạnh mẽ và trưởng thành hơn bao giờ hết. Thế nhưng, khi sự vấp ngã trở thành thói quên với một thân mình chằng chịch vết trầy xước, đó chính là khi tâm hồn dần dần hình thành sự vô cảm chai sạn trước những nổi đau.

       <br>&nbsp;&nbsp;&nbsp;&nbsp;Sống ở đời phải biết thất bại là gì các bạn ạ. Có thất bại có mệt mỏi thì mới biết quý cái giá thành công, mới thấy thành công nó đánh giá thế nào. Có hạnh phúc nào mà không trải qua đau đớn cơ chứ.

       <br>&nbsp;&nbsp;&nbsp;&nbsp;Từng chương, từng mục nhỏ trong quyển sách “Mỗi lần vấp ngã là một lần trưởng thành” như là một bài học tuy giản dị mà ý nghĩa biết bao nhiêu : cuộc đời vốn là những bước chân mỏi, có bước tiến lên, cũng có lúc phải lùi xuống, đôi khi phải vấp ngã một lần.

       <br>Chính khi thất bại, bạn luôn phải nhớ vì sao bạn phải khởi đầu nhé! Hãy bước tiếp để tận hưởng từng khoảnh khắc tuyệt vời mà cuộc sống này ban tặng, bằng tâm hồn trong trẻo, hồn nhiên như bước đầu chập chững bước ra thế giới rộng lớn.

<br>&nbsp;&nbsp;&nbsp;&nbsp;Có lẽ cuốn sách “Mỗi lần vấp ngã là một lần trưởng thành” đã đi vào lòng khán giả biết bao cảm xúc đẹp. Đây thật sự là một cuốn sách đầy ý nghĩa.</p>

                </div>
             <div class="review">
                “Sóng yên biển lặng không làm nên một thủy thủ xuất sắc. Chỉ khi dám vượt qua muôn trùng phong ba bão táp bạn mới có thể trở thành thủy thủ tài ba nhất!”<br>
                &mdash; Liêu Chí Phong
            </div>
        </div>
    </div>
    <div id="amnhac" class="content">
        <h2>Âm nhạc yêu thích</h2>
                <img src="https://i.ytimg.com/vi/_IWn_lo_42M/mqdefault.jpg" alt="Hình ảnh âm nhạc" class="music-img">
        <div class="music-video">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/sj_UDyfoo-A?si=15YT8MaXB-axp33m" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        </div>
    </div>
    <div id="phim" class="content">
 <h2>Phim yêu thích</h2>
     
                    <section class="movie-section">
            <div class="movie-card">
                 <iframe width="560" height="335" src="https://www.youtube.com/embed/rEBdY6OHJVI?si=YEWP28k25uBM12Jc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <h3>Trailer</h3>
                <p>2024, Korea, Romantic Comedy, Fantasy</p>
            </div>
            <div class="movie-card">
                <img src="https://phunuso.mediacdn.vn/603486343963435008/2024/4/21/photo-1-17136977863301501993265-1713698363139-1713698364221227383619.jpg" alt="Girl in a jacket" width="700" height="400">
                <h3>Lovely Runner</h3>
                <p>2024, Korea, Romantic Comedy, Fantasy</p>
            </div>
        </section>
    </div>

    <script>
        function showPage(pageId) {
            var pages = document.querySelectorAll('.content');
            pages.forEach(page => page.classList.remove('active'));
            document.getElementById(pageId).classList.add('active');
        }
    </script>
</body>
</html>
