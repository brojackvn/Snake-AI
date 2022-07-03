# SNAKE AI

### FINAL PROJECT

*Tham khảo từ UI/UX và game Snake tutorial từ link:
 https://www.youtube.com/watch?v=CD4qAhfFuLo&t=1734s&ab_channel=freeCodeCamp.org*
 
 ### Mục đích:
 Tạo game Snake có thể chơi một cách tự động bằng cách sử dụng các thuật toán tìm kiếm khác nhau. Tạo metric đánh giá hiệu quả giữa các thuật toán<br>
 **Các thuật toán được đưa ra đánh giá**
 1. Depth First Search (DFS)
 2. Breadth First Search (BFS)
 3. A Star Search (A*)
 4. Uniform Cost Search (UCS) 

### Results:
Sau khi chạy, thì BFS cho kết quả tốt nhất. Thông qua metric đánh giá của chúng tôi
> performance = (score / actions) * 100
>> trong đó: score là số thức ăn mà con rắn ăn được và actions là tổng tất cả bước di chuyển của con rắn cho đến khi chết.
Ở đây chúng tôi vẫn ưu tiên score hơn là actions

### Cài đặt:
Clone code từ repo. Cài thêm pygame (pip i pygame) nếu bạn chưa có

1. Chạy main()
    - Để chơi game thủ công
2. Run showExample()
    - Chạy tất cả các thuật toán tìm kiếm với tốc độ chậm để bạn có thể quan sát. Thứ tự chạy: BFS, A*, UCS, DFS
3. runSearch(times)
    - Chạy mỗi thuật toán tìm kiếm với vòng lặp 400 hoặc cho đến khi con rắn chết
    - Tính kết quả đánh giá
    - Viết ra file result.txt
    - Đưa ra kết quả đánh giá performance -> Bar chart
    - Tạo line chart thể hiện mối liên hệ giữa scores và actions
4. Run runMultiple(times) 
    - Chạy runSearch với times lần
    - Tính trung bình và đưa ra kết quả đánh giá performance -> Bar chart
    - Viết ra file result.txt

    


