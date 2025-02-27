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
