def la_so_nguyet_to(n):
    # Nếu số nhỏ hơn hoặc bằng 1, không phải số nguyệt tố
    if n <= 1:
        return False
    
    # Kiểm tra từ 2 đến căn bậc hai của n
    for i in range(2, int(n ** 0.5) + 1):
        if n % i == 0:
            return False
    return True

while True:
    # Nhập số từ người dùng
    try:
        n = int(input("Nhập số n để kiểm tra (hoặc nhập 'q' để thoát): "))
    except ValueError:
        print("Chương trình đã dừng.")
        break

    # Kiểm tra và in kết quả
    if la_so_nguyet_to(n):
        print(f"{n} là số nguyệt tố")
    else:
        print(f"{n} không phải là số nguyệt tố")
