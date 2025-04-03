def fibonacci_quy_hoach_dong(n):
    # Tạo mảng để lưu các giá trị Fibonacci
    fib = [0] * (n + 1)
    
    # Trường hợp cơ bản
    if n == 0:
        return 0
    if n == 1:
        return 1
    
    # Gán giá trị ban đầu
    fib[0] = 0
    fib[1] = 1
    
    # Tính các giá trị Fibonacci từ 2 đến n
    for i in range(2, n + 1):
        fib[i] = fib[i - 1] + fib[i - 2]
    
    return fib[n]

while True:
    try:
        # Nhập số n từ người dùng
        n = int(input("Nhập số n để tính số Fibonacci thứ n (hoặc nhập 'q' để thoát): "))
    except ValueError:
        print("Chương trình đã dừng.")
        break

    # Kiểm tra số âm
    if n < 0:
        print("Vui lòng nhập số không âm!")
    else:
        ket_qua = fibonacci_quy_hoach_dong(n)
        print(f"Số Fibonacci thứ {n} là: {ket_qua}")
