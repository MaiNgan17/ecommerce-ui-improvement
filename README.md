# ecommerce-ui-improvement
BT Cá Nhân Chương 1 môn Phát triển ứng dụng TMĐT
1. Giới thiệu
Dự án thực hiện cải tiến giao diện trang giỏ hàng của website thương mại điện tử Hasaki.vn, tập trung vào việc hiển thị minh bạch các khoản chi phí (tạm tính, phí vận chuyển ước tính và tổng thanh toán dự kiến) ngay từ bước giỏ hàng trước khi khách hàng tiến hành đặt hàng.

2. Website tham khảo
Tên website: Hasaki (Hasaki Beauty & Clinic)

URL: https://hasaki.vn/

Khu vực đã khảo sát: Trang chủ, Danh mục sản phẩm, Chi tiết sản phẩm, Tìm kiếm, Giỏ hàng.

3. Chức năng
Hiển thị danh sách sản phẩm mẫu (bao gồm hình ảnh minh họa, tên sản phẩm, phân loại, đơn giá, số lượng và thành tiền).

Hiển thị khung tóm tắt đơn hàng minh bạch chi phí với thông tin tạm tính, phí vận chuyển ước tính và tổng thanh toán dự kiến.

Tích hợp nút tiếp tục đặt hàng và các ghi chú hỗ trợ người dùng kiểm tra thông tin.

Bố cục linh hoạt hỗ trợ nhiều kích thước màn hình từ máy tính đến điện thoại di động.

4. Công nghệ
HTML5

CSS3

5. Cách chạy
Mở file index.html bằng trình duyệt web.

6. Cải tiến đã thực hiện
Vấn đề ban đầu: Ở trang giỏ hàng thông thường, thông tin về phí vận chuyển hoặc các khoản chi phí phát sinh thường chưa được hiển thị đầy đủ ngay từ bước giỏ hàng, khiến khách hàng có thể bất ngờ khi chuyển sang trang thanh toán.

Thay đổi đã thực hiện: Thiết kế lại khung tóm tắt đơn hàng tại trang giỏ hàng với bố cục hai cột trực quan trên máy tính và tự động co giãn thành một cột dọc trên điện thoại bằng Media Queries, giúp người dùng dễ dàng theo dõi chi tiết sản phẩm và tổng chi phí song song mà không cần cuộn trang hay chuyển đổi qua lại giữa nhiều màn hình.

7. Hỗ trợ từ AI
Tóm tắt những phần AI hỗ trợ: AI hỗ trợ phân tích nghiệp vụ 5 khu vực của website Hasaki.vn, đề xuất phương án thiết kế giao diện (bố cục, cấu trúc thẻ HTML5, tổ chức CSS theo nhóm và nguyên tắc responsive), đồng thời cung cấp mã nguồn HTML/CSS mẫu cho trang giỏ hàng cải tiến.

Phần tôi đã kiểm tra: Bản thân đã trực tiếp kiểm tra website thực tế Hasaki.vn để đối chiếu các nhận định, tự tay kiểm tra khả năng hiển thị của trang web trên cả máy tính lẫn thiết bị di động, đồng thời tự điều chỉnh lại tên thương hiệu (Hasaki), tiêu đề trang (<title>), định danh logo và các thông tin chi tiết trong mã nguồn để đảm bảo phù hợp hoàn hảo với yêu cầu bài tập cá nhân.

---

# BUỔI 2 – HOÀN THIỆN GIAO DIỆN HTML5/CSS3

## 1. Giới thiệu bài tập

Bài tập Buổi 2 tiếp tục phát triển giao diện website thương mại điện tử từ Buổi 1, tập trung thực hành HTML5, CSS Selector, Box Model, Flexbox và CSS Grid để cải thiện bố cục và cách trình bày giao diện.

- Website tham khảo: Hasaki
- Khu vực thực hiện: Trang giỏ hàng (Cart Page)
- Công nghệ sử dụng: HTML5, CSS3

## 2. Website tham khảo và khu vực cải tiến

**Website tham khảo:** https://hasaki.vn/

**Khu vực cải tiến:** Trang giỏ hàng.

Em tiếp tục hoàn thiện giao diện giỏ hàng mô phỏng website Hasaki, bao gồm danh sách sản phẩm, hình ảnh, tên sản phẩm, phân loại, đơn giá, số lượng và thành tiền.

Bên cạnh đó, giao diện có khu vực tóm tắt đơn hàng, phí vận chuyển ước tính và tổng thanh toán dự kiến.

Các cải tiến trong Buổi 2 tập trung vào việc điều chỉnh khoảng cách, màu sắc, đường viền, bố cục sản phẩm và khả năng hiển thị trên nhiều kích thước màn hình.

## 3. Những kỹ thuật HTML5/CSS3 đã thực hành

### 3.1. HTML5

- Sử dụng các thẻ ngữ nghĩa như `header`, `main`, `nav`, `section`, `article`, `aside` và `footer` để tổ chức nội dung.
- Sử dụng thẻ `img` kết hợp thuộc tính `alt` để mô tả hình ảnh sản phẩm.
- Sử dụng `input type="number"` để tạo ô nhập số lượng sản phẩm.

### 3.2. CSS3

- **CSS Selector:** Sử dụng class selector, descendant selector và pseudo-class như `:hover`, `:focus-visible`.
- **Box Model:** Sử dụng `margin`, `padding`, `border` để điều chỉnh khoảng cách và đường viền.
- **Flexbox:** Căn chỉnh hình ảnh, thông tin sản phẩm, số lượng và thành tiền.
- **CSS Grid:** Chia giao diện giỏ hàng thành hai cột và tổ chức bố cục Footer.
- **Responsive:** Sử dụng Media Queries để điều chỉnh giao diện trên tablet và mobile.

## 4. Hướng dẫn chạy website

1. Tải mã nguồn từ GitHub về máy.
2. Mở thư mục dự án bằng Visual Studio Code.
3. Mở file `index.html` bằng trình duyệt hoặc sử dụng Live Server.
4. Thay đổi kích thước cửa sổ trình duyệt để kiểm tra khả năng responsive.

**Các file chính:**

- `index.html`: Cấu trúc HTML của trang giỏ hàng.
- `style.css`: Định dạng giao diện và responsive.

Website hiện được xây dựng ở mức giao diện HTML5/CSS3, chưa triển khai chức năng đặt hàng thực tế.

## 5. Những thay đổi đã thực hiện trong Buổi 2

- Điều chỉnh cách trình bày các thẻ sản phẩm bằng Box Model, bao gồm khoảng cách, đường viền và màu nền.
- Sử dụng Flexbox để căn chỉnh hình ảnh và thông tin trong từng thẻ sản phẩm.
- Hoàn thiện bố cục hai cột giữa danh sách sản phẩm và phần tóm tắt đơn hàng bằng CSS Grid.
- Điều chỉnh giao diện Header và Footer để tăng tính thống nhất.
- Sử dụng Media Queries để cải thiện khả năng hiển thị trên thiết bị di động.
- Kiểm tra các thuộc tính CSS và đánh giá mức độ phù hợp của những phương án điều chỉnh giao diện.

## 6. Công cụ AI đã sử dụng và cách kiểm tra kết quả

**Công cụ AI:** ChatGPT.

Trong quá trình thực hiện, em sử dụng ChatGPT để tham khảo cách tổ chức CSS, phân tích nguyên nhân có thể gây lỗi giao diện và đề xuất các phương án cải thiện bố cục.

**Ví dụ về đề xuất AI đã kiểm tra:**

AI đề xuất thay đổi thuộc tính `grid-template-columns` của Footer từ `1fr 1fr` thành `1.2fr 1fr` để điều chỉnh tỷ lệ chiều rộng giữa hai cột.

Tuy nhiên, sau khi áp dụng và quan sát giao diện thực tế, em nhận thấy bố cục chưa cân đối như mong muốn. Vì vậy, em quyết định giữ nguyên thiết kế ban đầu với hai cột có chiều rộng bằng nhau.

Qua đó, em nhận thấy cần chủ động kiểm tra và đánh giá các đề xuất của AI thay vì áp dụng hoàn toàn mà không xem xét mức độ phù hợp với giao diện thực tế.

## 7. Đường dẫn dự án

- **GitHub Repository:** https://github.com/MaiNgan17/ecommerce-ui-improvement
- **Website đã triển khai: https://maingan17.github.io/ecommerce-ui-improvement/



---

**Ghi chú:** Đây là giao diện mô phỏng phục vụ mục đích học tập, không phải website chính thức của Hasaki.
