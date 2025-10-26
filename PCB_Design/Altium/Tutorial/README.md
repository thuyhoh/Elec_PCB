# Altium - Tutorials
## I. Thanh phần trong Altium


## II. Thêm thư viên vào Altium
## III. Tạo Template
## IV. Tự tạo linh kiện
## Shortcuts
### SHC
- Vẽ dây: `P W`
- Vẽ bus: `P B`
- Đặt net label: `P N`
- Đặt power port: `P P`
- Đặt component: `P C`
- Xoay linh kiện: `pacebar`
- Lật linh kiện: `X/Y`
- Hiển thị/ẩn tên hoặc giá trị linh kiện: `T S `/`T V`
- Lọc linh kiện: `SHIFT F` => chọn linh kiện và điều kiện lọc
### PCB
- Đặt track: `P T`
- Đặt via: `P V`
- Đặt pad: `P P`
- Đặt polygon pour: `P G`
- Lật đối tượng qua lớp kia: `L`
- Đo khoảng cách: `Ctrl M`
- Xem toàn bộ board: `V F`
- Zoom đến vùng chọn: `Z A`
### 3D
- Lật board: `CTRL F`
- Xóa xanh linh kiện 3D: `T M`
### Copy specific 
- Chọn linh kiện > CTRL C
- Edit > Copy 
## IV. Tự động đặt tên trong SHC
tools>


## net color
### SHC
``` 
view > set net color > choice color > Chọn Net 
```
### PCB
- Nếu SHC đã chọn màu sắc của Net
```
Panels > PCB > Nets >  highlighted > Chọn Net
```
- Nếu SHC không chọn màu sắc của Net
```
highlighted > chuột phải > change Net color
```

## phóng to thu nhỏ

### Design board shape
```
- Chọn layer: keep out layer 
- place > keep out > track > vẽ hình board muốn cắt
- design > board shape > design board shape form selection object
```
shift space
PCB > L > Add Component Layer

##
d r
ẩn phủ đồng
l > view option > hidden polygons


## net class


## set lại goc toa do
edit > origin > set

## căn chỉnh linh kiện
bôi đen > A

di chuyển 
e m move offset

kiểm tra lỗi trong pcb
PCB rules and violations
rule calss 
    net anten > chuột trái > run DRC > Short cut uncourt
## Tạo một layer mới 
```
Design > Layer stack manager > Stackup > add > below > chọn signals/plane
```
## Plane
```
- chọn layer plane đã tạo > nhóm các via cùng một loại thành phân vùng bằng đường line (P L)
- click doup vào phân vùng đã tạo > chọn Net tương ứng với và via trong plane
```
## tạo via mới
```
- Design > layer stack manager > Via Types > add 
- properities > chọn First layer/Last layer
```