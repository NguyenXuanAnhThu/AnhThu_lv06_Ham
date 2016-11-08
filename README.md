#HÀM

[1. Khái niệm](khainiem)

[2. Quy tắc xây dựng một hàm](quytac)

[3. Các tham số của hàm](thamso)

[4. Hàm đối con trỏ](hamdoi)

<a name"khainiem"></a>
###1. Khái niệm:

  *a. Chương trình:*
    Một chương trình C bao gồm một hay nhiều hàm. Hàm **main()** là thành phần bắt buộc của chương trình. Chương trình được bắt đầu thực hiện bằng câu lệnh đầu tiên của hàm **main()** cho đến khi gặp dấu **}** cuối cùng của hàm này.
    
  *b. Hàm:*
    Là một đoạn chương trình độc lập thực hiện trọn vẹn một công việc nhất định, rồi trả về một giá trị tương ứng cho chương trình đã gọi nó.
    
    Đặc điểm của Hàm:
    
     - Là một đơn vị độc lập của chương trình.
  
     - Không cho phép xây dựng một hàm khác bên trong hàm.
<a name"quytac"></a>
###2. Quy tắc xây dựng một hàm:
   Một hàm gồm có các thành phần sau:
   
   **-Nguyên mẫu của hàm:** bao gồm
   
      <Kiểu_dữ_liệu_của_hàm><tên_hàm(danh_sách_các_tham_số)>
      Có thể không khai báo nguyên mẫu của hàm. Tất cả các nguyên mẫu của hàm phải đặt trước hàm main()
   
   **-Kiểu giá trị của hàm:** Khai báo không có giá trị trả về thì dùng hàm **Void**. Còn có giá trị trả về thì dựa vào mục đích của hàm.
   
   **-Tên hàm:** Đặt khi khai báo và trong nguyên mẫu phải giống nhau. Đặt tên theo quy định đối với danh định.
   
   **-Tham số của hàm:** Cần xác định hàm có bao nhiêu tham số (khi viết).
   
   **-Nội dung của hàm:**
   
   *Cấu trúc của một hàm:*
    
      <Kiểu trả về><Tên hàm>(<ds tham số hình thức hay đối số>)
        {		
         <Khai báo biến cục bộ>;
		     <Các câu lệnh trong thân hàm>;
		     [return<bt trả về giá trị hàm>];
	     };
<a name"thamso"></a>
###3.Các tham số của hàm:
  
  **3.1 Phân loại tham số của hàm theo cách sử dụng:**
  
  *Tham số hình thức*
  
  *Tham số thực*
  
  *Tham chiếu*
  
  *Tham trị*
  
  **3.2 Phân loại theo công dụng:** có hai loại công dụng:
  
  
   `
     Cung cấp các giá trị cho hàm khi ta gọi nó thực hiện .
   
    Lưu các kết quả tính toán được trong quá trình hàm hoạt động
    
    Tương ứng với công dụng ta có các loại tham số:
    
    Tham số vào: Cung cấp giá trị cho hàm.
    
    Tham số ra: Lưu kết quả tính toán được trong hàm. 
    
    Tham số vừa vào, vừa ra: vừa cung cấp giá trị cho hàm, vừa lưu kết quả tính toán được trong hàm.`

  
