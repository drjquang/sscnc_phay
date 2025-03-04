Mon, 24/02/2022
-----------------------------------------------------------------
G75 = tiện rãnh
-----------------------------------------------------------------
Tiện CNC
Chương trình O0021.cnc
Work piece = phi 30, length 77
Tool = B phi 5, length 12, corner 0.2
Tiện 3 rãnh 5 và một rãnh 8 trong cùng từ phi 30 xuống phi 26

-----------------------------------------------------------------
G74 = khoan chính tâm
-----------------------------------------------------------------
Tiện CNC
Chương trình O0022.cnc
Work piece = phi 60, length 100
Tool = 2 mũi khoan phi 8 và phi 40 tại T04 và T05
Khoan lỗ phi 40 vào sâu Z-60, sử dụng mũi khoan nhỏ mồi trước

-----------------------------------------------------------------
G71 = tiện thô dọc trục
G70 = tiện tinh
-----------------------------------------------------------------
Tiện CNC
Chương trình O0024.cnc
Work piece = phi 140, length 200
Tool = mũi khoan thô cán 160, chip CNMG có radius = 0.2
Bù bằng G41 cho đường kính đúng tiêu chuẩn đề bài, còn distance thì không giống

-----------------------------------------------------------------
G41 = bù trái hướng tiến dao
G43 = bù chiều dài dao với offset = -165, gauge cao 100
-----------------------------------------------------------------
Phay CNC
Chương trình O3025.cnc
Work piece = 80x80 dày 50 nhưng ăn sâu 0.3
Tool = phay ngón Flat phi 20 dài 120
Bù trái G41 đi từ ngoài X-60 Y-60 vào tiếp tuyến, di chuyển ngược chiều kim đồng hồ

-----------------------------------------------------------------
Bài tập tiện tổng hợp 34
-----------------------------------------------------------------
Tiện CNC
Chương trình O1034.cnc
Work piece = phi 65 dài 150
T0101 = dao tiện ngoài, bù G42, vị trí 3
T0202 = dao tiện rãnh B3

-----------------------------------------------------------------
Bài tập tiện tổng hợp 35
-----------------------------------------------------------------
Tiện CNC
Chương trình O2222.cnc
Work piece = phi 80 dài 200
T0101 = dao tiện ngoài, không bù, vị trí 2
T0202 = dao tròn button, đường kính 10, vị trí 6
T0303 = dao tiện ren

-----------------------------------------------------------------
Bài tập phay lỗ
-----------------------------------------------------------------
Phay CNC
Chương trình O3001.cnc là chương trình chính, O3002 thay đổi Z và O3003 là biên dạng lỗ
Work piece = 100x100 dày 50
T1 = phay ngón phi 10, dài 100
Lộ = phi 30, bù dao phi 10
