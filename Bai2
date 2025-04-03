def tinh_giai_thua(n):
    # Giai thừa của 0 là 1
    if n == 0 or n == 1:
        return 1
    
    # Tính giai thừa bằng đệ quy
    return n * tinh_giai_thua(n - 1)

while True:
    try:
        # Nhập số từ người dùng
        n = int(input("Nhập số n để tính giai thừa (hoặc nhập 'q' để thoát): "))
    except ValueError:
        print("Chương trình đã dừng.")
        break

    # Kiểm tra số âm
    if n < 0:
        print("Giai thừa không được định nghĩa cho số âm!")
    else:
        ket_qua = tinh_giai_thua(n)
        print(f"Giai thừa của {n} là: {ket_qua}")
