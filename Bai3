def bubble_sort(arr):
    n = len(arr)
    # Duyệt qua mảng
    for i in range(n):
        # Duyệt từ đầu đến phần tử thứ n-i-1
        for j in range(0, n - i - 1):
            # Nếu phần tử hiện tại lớn hơn phần tử tiếp theo, hoán đổi
            if arr[j] > arr[j + 1]:
                arr[j], arr[j + 1] = arr[j + 1], arr[j]
    return arr

# Nhập số lượng phần tử của mảng
n = int(input("Nhập số lượng phần tử của mảng: "))

# Nhập các phần tử của mảng
arr = []
for i in range(n):
    phan_tu = int(input(f"Nhập phần tử thứ {i + 1}: "))
    arr.append(phan_tu)

# Sắp xếp mảng bằng Bubble Sort
mang_sap_xep = bubble_sort(arr)

# In mảng đã sắp xếp
print("Mảng sau khi sắp xếp tăng dần:", mang_sap_xep)
