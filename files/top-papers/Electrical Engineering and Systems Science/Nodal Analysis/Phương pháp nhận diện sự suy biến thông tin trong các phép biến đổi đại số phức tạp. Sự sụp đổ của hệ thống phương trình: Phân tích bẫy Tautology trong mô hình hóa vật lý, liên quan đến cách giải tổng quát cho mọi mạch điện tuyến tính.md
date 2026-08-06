# =================================

# Vấn đề

"Cái bẫy Tautology" (Sự đồng nhất thức giả tạo). 

Nó là "Ảo giác của sự tiến triển".

Hiện tượng: Khi một phương trình trông có vẻ chứa đựng thông tin mới nhưng thực chất chỉ là một phép biến đổi tương đương của các dữ kiện đã biết (Đồng nhất thức).


# Vì sao nó xảy ra?

**Các nguyên nhân chính :**

1. Linear Dependency : Bạn đang dùng 2 phương trình nhưng thực chất phương trình này được rút ra từ phương trình kia qua các bước biến đổi trung gian.

2. Circular Substitution : Bạn rút x từ phương trình A, rồi lại thế x vào chính một biến thể của phương trình A thay vì thế vào phương trình B độc lập.

3. Information-related issues : Trong vật lý, nhiều khái niệm không tồn tại độc lập mà được định nghĩa thông qua nhau.

# Phương pháp luận

**I. Hình ảnh của 2 phương trình trên mặt phẳng tọa độ (2D)**

(Điều này không phải là đối với mọi dạng phương trình)

**1:** Khi đặt 2 phương trình có : (vế 1) và (vế 2), và (vế 1) và (vế 2) đều bao gồm đầu vào là biến x. và nếu đặt x là 1 số, và lúc đó (vế 1) trở thành y, tương tự với (vế 2). Thì nếu coi như 2 đường thẳng, tức là dạng hàm số này nè : f(x) = ax + b. 

Nếu chúng **cắt nhau** tại 1 điểm, y của 2 đường thẳng và x bắt buộc phải bằng nhau, hay (vế 1) = (vế 2) và x thì là biến đầu vào (duy nhất) của cả 2 vế, dĩ nhiên là bằng nhau, hay nó là một. Và vì là 2 đường thẳng, và cắt nhau (không trùng nhau) nên chỉ có duy nhất **1 nghiệm x**.

Nếu chúng **song song** với nhau, chứng tỏ **vô nghiệm**.

Nếu chúng **trùng nhau** (hay còn gọi là Đồng Nhất Thức, tức là nó thỏa mãn "Điều kiện 1", mà tôi sẽ miêu tả ở bên dưới), vậy tức là có **vô số nghiệm**.

**2:** Ví dụ (thật ra cái này là phương trình bậc 2) :

(x + 6)(36 - x) = 8(36 - x) + 12(x + 6)

"(x + 6)(36 - x)" **cắt nhau** với "8(36 - x) + 12(x + 6)", tại điểm có tọa độ (x;y), và x chính là nghiệm của phương trình trên (**ừ 2 nghiệm, vì là phương trình bậc 2**).

**II. Áp dụng công thức Vật lý và vấn đề**

**ĐIỀU KIỆN 1 :** (Lưu ý rằng điều kiện này do tôi tự suy luận ra, nên có thể có các vấn đề...)

"

Nếu (vế 1) = (vế 2).

Ta phải đảm bảo (vế 1) hoặc (vế 2) không thể bị biến đổi đại số toán học làm nó trở thành vế còn lại, mà không cần đến thông tin từ vế còn lại. Ví dụ như :

36 - x = 36 - x; 36x = 36x; 36 = 36 (sau khi biến x đã bị triệt tiêu); xy = yx (có thể bạn đã từng gặp sai sót liên quan đến điều này trong hệ phương trình).

Điều này hoàn toàn có thể xảy ra với những thứ phức tạp hơn nhiều (làm khó nhận dạng hơn bằng mắt thường?), ví dụ :

Coi "*" là phép nhân :

{(36 - x)/6 * 6} + { x/{(x^2)/51.84} + (x^2)/51.84 } = 36

(Tương đương với 36 = 36)

Thêm 1 số ví dụ khác nữa :

x + y = 10

2x + 2y = 20

Cái đó cũng là bẫy :), nhưng mà nó là trong việc lập hệ phương trình tức là phương trình vốn dĩ không phải đồng nhất thức, nhưng khi kết hợp 2 phương trình nhìn tưởng khác nhưng thật ra lại là một.

"



Được rồi, hãy cùng xem 1 ví dụ cơ bản:

F = m . a (Định luật II Newton, coi "." là phép nhân)

m = F/a (Coi "/" là phép chia)

Thấy gì chứ? 2 cái công thức đó chính xác là 1 công thức.

Vậy nếu làm như vầy:

Giả sử ta sau khi đo đạc thực nghiệm thì có F = 10, và ta muốn biết a là bao nhiêu (lưu ý rằng a chắc chắn chỉ có 1 giá trị duy nhất ở ngoài thực tế).

F = (F/a) . a => 10 = ((10/a) . a) => a có **vô số nghiệm**.


Vấn đề? Rõ ràng công thức trên là hoàn toàn đúng, tuy nhiên vì đầu vào là F, a, m. Tuy nhiên chỉ có đầu vào F là có số đo. Nhìn nó trông đơn giản và dễ "tránh", hay như điều hiển nhiên ?

Vậy cùng đến với bài toán này :

Giả sử cho điện trở R_1 và R_2 nối tiếp với nhau. Và hiệu điện thế U_AC của 2 đầu mạch là 36 (V). Với dòng điện I là 9 (A).

Tôi đặt điểm có vôn thế giữa 2 điện trở R_1 và R_2 là V_x. Hay ta có U_Ax + U_xC = U_AC = 36 (V).

Và nó trông như này :

Bước 1 : (36 - x) + (x - 0) = 36 => x = 1

Bước 2 : R_1 = (36 - 1)/9 = 35/9 (Ohm)

....

Được rồi, thực tế thì **Bước 1**, x phải có **vô số nghiệm**. Đơn giản vì học sinh cấp 2 (Trung Học Cơ Sở) thường hay sử dụng CASIO fx-580VN X Classwiz, và nó chỉ đưa đại ra 1 nghiệm bất kỳ (thật ra còn dựa trên bộ nhớ, thuật toán Newton-Raphson của casio...) trong vô số nghiệm thôi (SHIFT + SOLVE) :), dẫn đến nhầm lẫn này. Vấn đề là điều này rất dễ xảy ra sai sót, học sinh vốn dĩ đã áp dụng đúng công thức ở **Bước 1**, nhưng tại sao lại thành ra như vầy? Đơn giản vì đã vi phạm **Điều kiện 1**, khi mà (vế 1) hoàn toàn có thể bị biến thẳng thành 36 bằng biến đổi đại số như này, mà không cần đến thông tin từ (vế 2) :

(36 - x) + (x - 0) = 36 - x + x = 36

Hay phương trình sẽ thành như này : 36 = 36; (vế 1 sau khi rút gọn) = (vế 2) = (vế 1);

Mà "x" hay V_x buộc phải có 1 nghiệm duy nhất, vì đó là **Môi trường Vật lý** mà tôi đã "Giả sử" ở trên. 


Thật ra cái ví dụ F = m . a không phải là kiểu dạng ví dụ thực tế, nó kiểu như tối giản thôi, chứ chỉ có mấy đứa điên mới làm 10 = (10/a) . a rồi ngồi giải (thật ra tôi đã làm vậy, có vẻ tôi bị điên, omg). Nhưng khi vào một mạch điện có 5 nút, 3 nguồn, 10 điện trở, việc bạn "thế ngược" (Circular Substitution) một biểu thức dòng điện vào một vòng KVL mà bạn vừa rút ra chính biểu thức đó là cực kỳ dễ xảy ra. Kiểu kiểu vậy :3.

Hoặc là đang xài định luật Ohm kiểu như : I_x = (V_A - V_B)/R_x, sau đó bạn hì hục viết KCL cho nút A, rồi KVL cho vòng chứa R_x gì đó... Trong lúc biến đổi đại số cực kỳ mệt mỏi với đống phân số, bạn vô tình thế biểu thức V_A - V_B = I_x . R_x vào chính cái phương trình bạn vừa rút ra từ định luật Ohm. Sau đó bạn sẽ nhận **cái kết** : Bạn biến đổi mất 15 phút và ra được phương trình R_x = R_x hoặc 0 = 0 gì đó :)).

Lúc này, trong phòng thi, bạn không thấy mình "ngu" hay "điên", mà bạn thấy tuyệt vọng vì tưởng mình làm sai ở đâu đó và bắt đầu cuống cuồng đi tìm lỗi sai trong đống đại số. Đó mới là cái giá đắt nhất của "Cái bẫy Tautology" (chắc thế).



# Cách phòng ngừa, liên quan đến cách giải tổng quát

**1. Cách để xác định đâu là phương trình vi phạm Điều kiện 1**

Đây là 1 cách đơn giản, chỉ cần thay 1 số bất kỳ, vào biến (ví dụ như x, và giả sử chỉ có 1 biến duy nhất là biến x) (vế 1) của phương trình đó, tiếp tục đến (vế 2), rồi tính ra số. Nếu như cả 2 vế bằng nhau, thì tiếp tục thay x thành 1 con số khác, làm lại nhiều lần... Bạn có thể tự suy luận ra chuyện gì đang xảy ra mà?

**2. Đây là cách biến đổi đại số**

Thường thì sẽ biến đổi bằng tay, cơ bản nhưng có thể chậm?

**3. Cách để phòng tránh việc tự khiến mình làm ra phương trình vi phạm Điều kiện 1, và làm ra phương trình có vô số nghiệm, và hợp lý cho việc sử dụng phổ biến trong Môi Trường Vật lý (Điện), hay bằng cách chỉ cần nhìn vào bài toán vật lý từ thực nghiệm/đề bài, chúng ta có thể phát hiện sớm, và nhanh nhất, đồng thời tự xác định được đâu mới là phương trình đạt yêu cầu để dẫn đến kết quả ta cần tìm, hay đúng hơn là chuyển từ cách tư duy pattern recognition + memory sang "general algorithm"**

Thật ra nó chưa hoàn thiện, nhưng cứ đọc đi :

**Điều 0 : 1 số thứ cần học nhưng có thể chưa biết btw**

Nodal Analysis. Hiệu điện thế là điện thế - điện thế. Và hãy biết CÁCH VẼ LẠI MẠCH, hiểu hết về mạch điện, nếu không, bạn sẽ rất có khả năng không áp dụng/áp dụng sai những điều bên dưới.

**Điều 1 : Degrees of Freedom**

Nếu có n ẩn số, để giải ra 1 nghiệm duy nhất, cần đúng n phương trình ĐỘC LẬP.

Thế nào là độc lập? Phương trình mới phải mang đến một "ràng buộc" (constraint) mà các phương trình trước chưa có.

Hiếm : Trong vật lý, đôi khi số phương trình < số ẩn nhưng vẫn giải được nhờ các điều kiện biên hoặc giá trị cực trị (bất đẳng thức).

**Điều 2 : Mapping Laws** 

Gán mỗi phương trình với 1 định luật hoặc tính chất riêng biệt


**Điều 3 : Thuật toán lập phương trình "Độc lập thông tin"**

Để tránh rơi vào bẫy kiểu như 36 = 36, phải lấy phương trình từ các "túi chứa thông tin" khác nhau và không được lấy quá số lượng cho phép ở mỗi túi.

1 số túi thông tin phổ biến :

Túi Ohm (Định Luật Ohm), Túi KCL (Kirchhoff 1, Định luật bảo toàn điện tích), Túi KVL (Kirchhoff 2, Bảo toàn năng lượng),..

Bây giờ cùng quay lại cái bẫy ở trên :

Nếu viết (36 - V_x) + (V_x - 0) = 36, đây đơn giản là túi KVL, nhưng thiếu thông tin từ túi Ohm. Nó chỉ là phép cộng độ dài thế năng.

Thuật toán đúng: Cần trộn thông tin :). Lấy Ohm + KVL, hoặc điện thế nút.

Được rồi đây là 1 số đúc kết của tôi :

Dùng KVL để giải V_x mà không dùng Ohm -> Tautology.

Dùng Ohm để tìm U mà không dùng KCL để biết dòng qua nó -> Loay hoay.


Và theo tôi, nên RẤT ưu tiên lập phương trình ở những nơi có "ẩn cần thiết để giải bài toán".

1 thứ tôi thấy khá đúng, dĩ nhiên vẫn có "edge case", mà nhiều khi là thế thật : Đa số các bài toán xài Ohm và KCL/KVL là chủ yếu, thì nếu như chỉ xài Ohm mà ko giải được, thì phải xài thêm KCL/KVL (nếu là dạng bài "phức tạp", đặt ẩn tùm lum,.. ko đc xài mỗi KCL/KVL, phải xài KCL/KVL + Ohm).

**Điều 4:** Mỗi phương trình mới lập ra phải chứa ít nhất một thông tin về cấu trúc (Nút/Vòng) chưa được khai thác, hoặc một thông tin về linh kiện (Ohm) chưa được kết nối.

**Điều 5:** Đếm ẩn, nó như kiểu điều hiển nhiên trong lập trình, khi ta xem "input"/"output", rồi bạn sẽ tận dụng thông tin này để kiểm tra xem mình làm hệ phương trình hay phương trình... chưa, nó là 1 phần. Trong nhiều bài toán, việc này cần thiết : chọn gốc thế năng là = 0V.

**Điều 6:** Để không bị rơi vào Tautology, số phương trình KCL lập được tối đa là (n-1) với n là số nút. Số phương trình KVL cần lập là (m - n + 1) với m là số nhánh. Nếu tuân thủ quy tắc này, hệ phương trình chắc chắn độc lập và có nghiệm duy nhất. Sự sụp đổ của nút: Trong lý thuyết mạch, khi hai nút được nối bằng dây dẫn không có điện trở (hoặc ko đáng kể, hoặc ampe kế lý tưởng gì đó), chúng nhập lại làm một nút duy nhất (gọi là siêu nút - Supernode).

**LƯU Ý :** Nếu mạch có $n$ nút, bạn chỉ có đúng $(n-1)$ (phương trình) KCL có giá trị. Cái thứ n chắc chắn là vi phạm Điều Kiện 1, và gần như chắc chắn dẫn đến bẫy Tautology. Điều này là **chắc chắn 100%** và không phải mẹo hay kinh nghiệm vì nó là **Graph theory**. Còn KVL thì là (m - n + 1), như ở trên đã nói.

**Thực tế thì một nút được hiểu là đứng giữa 2 điện trở (đáng kể); Đơn giản vậy thôi, cho dù là mạch chỉ toàn nối tiếp, hay toàn song song, cũng thế, dù là mạch cầu,etc,..v.v ; Điều thực sự rất quan trọng trong việc xác định đâu mới là nút thật sự; Và 2 nút có điện thế bằng nhau, có thể coi là một, ý tôi là chập 2 nút đó lại ấy, cho dù giữa 2 nút đó có điện trở;**



Tôi đoán đây là thuộc trường hợp khi "bắt buộc" phải đếm (n - 1) để "bảo hiểm" cho bộ não, dĩ nhiên là trừ khi bạn có thể làm bằng cách khác và cách đó tối ưu hơn... :) :

1. Mạch không thể phân tích nối tiếp/song song, tôi thấy điều này là khá đúng vì chúng ta chỉ còn nước KVL/KCL,.. thôi, chứ tính điện trở tương đương khá căng, vì không phải cái nào cũng xài được Star Delta Transformation hay gì đó...

2. Mạch có 5-7 nút trở lên hoặc mạch có nhiều nguồn lồng nhau, nói chung là kiểu thật sự "PHỨC TẠP"

3. Hệ phương trình bị "vòng vo": Khi bạn giải ra và thấy vi phạm Điều kiện 1 ở trên, và đáp án kiểu như có số nghiệm hữu hạn ví dụ như 1, 2 nghiệm.

Nhìn chung theo tôi thì, nếu giải được bằng định luật Ohm mà bản thây thấy ổn, thì cứ giải kiểu đó. Nhưng nếu định luật Ohm cồng kềnh, thì xài thêm KVL/KCL. Còn mấy cái như cực trị, bất đẳng thức, max/min thì xài ở đoạn cuối.

**Điều 7 :** Nếu bỏ các dạng bài kiểu như phải sử dụng thêm AM-GM Inequality, tìm Max/Min nâng cao, Hàm bậc 2, Cực trị gì đó...,Thì việc sử dụng Nodal Analysis, KCL, **chắc chắn** giải được 100% các bài toán mạch điện **tuyến tính** (linear) - (mạch chỉ gồm nguồn điện và điện trở thuần), tôi thấy ở trình độ lớp 9-10 chuyên lý, chắc chắn chỉ tồn tại dạng này, tính tới năm 2026, còn tương lai tôi thì tôi chưa biết. Vậy nên, tôi thật sự khuyên bạn sử dụng nó, đừng chỉ dùng mỗi Định Luật Ohm. Bạn sẽ gặp rủi ro theo tôi đánh giá là LỚN NHẤT đó là "Cái bẫy Tautology", còn 1 số bẫy khác liên quan đến vẽ lại mạch... và tôi đã nêu ra cách né ở trên :). À tất nhiên, nếu ở mấy dạng song song / nối tiếp cơ bản thì đừng có dại mà đi xài Nodal Analysis :)).


**Điều 8 :** Nâng cấp Nodal Analysis + KCL lên :

Thay vì phải biết rằng nút bạn đang xét (giả định là nút X), nút X có các dây dẫn nối vào, và bạn thông thường phải biết dòng nào đi vào, dòng nào đi ra để áp dụng Nodal Analysis + KCL. Nhưng thay vào đó, chúng ta giả định dòng điện đi ra khỏi nút X, lan truyền vào mọi dây dẫn nối với nút X.

**Vậy ta có (Nếu nút đang xét là nút x, và có 3 điện trở trên 3 nhánh khác nhau, và có điện thế khác nhau) :**

I_1out + I_2out + I_3out = 0

Vậy nên suy ra :

(V_x - V_1)/R_1 + (V_x - V_2)/R_2 + (V_x - V_3)/R_3 = 0

Vậy, bạn chỉ cần nhìn vào nút, rồi áp dụng ngay, và bạn cần đảm bảo rằng bạn đã vẽ lại mạch chuẩn, hoặc không cần vẽ lại mạch nhưng phải đảm bảo bạn đã chập các nút lại (nếu có), và đặt thế năng = 0V,... nhìn chung là chuẩn hóa xong mạch điện. Và cách bá đạo này giúp ta tránh được "Cái bẫy Tautology" một cách tự nhiên, tôi cảm thấy như bạn sẽ không bao giờ gặp bẫy Tautology nếu xài thứ bá đạo này :).

**À phải rồi, nên trình bày nếu bạn tính dùng nó để đi thi kỳ thi tuyển sinh học sinh lớp 9 lên lớp 10 chuyên lý, THPT Chuyên ấy, thì nên trình bày như này nhé, tôi đã tính toán kỹ để người chấm bài không trừ điểm rồi, tôi nghĩ gần như ko thể trừ điểm được :**

Chọn nút (Tự chọn đi) làm mốc điện thế, V_(nút đã chọn) = 0. Giả sử mọi dòng điện trong các nhánh nối với nút X đều hướng ra khỏi nút. Theo tính chất mạch điện: Tổng các cường độ dòng điện đi đến nút bằng tổng các cường độ dòng điện đi ra khỏi nút, ta có:

I_1out + I_2out + I_3out = 0

=> (V_x - V_1)/R_1 + (V_x - V_2)/R_2 + (V_x - V_3)/R_3 = 0

Còn nếu bạn muốn biết chiều dòng điện thì chỉ cần nhìn "âm" hay "dương" của I bạn đang xét là biết.


**Điều 9 :** Quy tắc độc lập thông tin 

Khi lập 1 phương trình mới bằng cách kết hợp các phương trình cũ, phương trình mới đó CHỈ CÓ NGHĨA nếu nạp thêm một dữ kiện mà chưa từng dùng ở bước trước.


**Điều 10 :**

Bạn không cần vẽ lại bất kỳ đoạn mạch tuyến tính nào về dạng nối tiếp / song song vì nỗi sợ "nếu không vẽ lại thành song song / nối tiếp, sẽ không giải được. hoặc là phải vẽ lại thành song song / nối tiếp thì mới có đủ thông tin để xài Nodal Analysis + Kirchhoff 1", chỉ cần sử dụng Kirchhoff 1 + Nodal Analysis là giải được toàn bộ mạch tuyến tính. Nếu không giải được, bạn chắc chắn đang làm thiếu ở bước pre-processing mạch, hoặc biến đổi đại số sai.


**Trường hợp biên (Edge case) :** Còn những thiếu sót : Còn mấy thứ như Star Delta Transformation (biến đổi sao - tam giác) và ngược lại, bất đẳng thức Arithmetic Mean - Geometric Mean (AM- GM), Cực trị, Mạch đối xứng... tôi chưa đề cập đến :)

# Kết luận

Cảm ơn đã đọc. Tôi không biết nên ghi gì ở đây. Lưu ý rằng gần như mọi thông tin ở đây đc tổng hợp và biên soạn bởi 1 học sinh lớp 9 (sinh năm 2011), và có thể có sai sót, mặc dù đã qua kiểm tra kỹ lưỡng. Chủ yếu nguồn thì từ Lý thuyết đồ thị, Đại số tuyến tính, Lý thuyết mạch điện,... nếu cần bạn có thể tham khảo sâu hơn những thứ tôi vừa nêu ra, nó vốn dĩ đã được chứng minh và là nền tảng của thế giới hiện nay :), tôi chủ yếu bưng từ đó sang đây xong chế biến lại, vẫn có thể có sai sót.

# =================================

# The Problem 

# Why it happens? 

# Methodology 

# Prevention, and more

# Conclude
