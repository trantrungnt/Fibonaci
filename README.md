# Dãy Fibonacci
Dãy Fibonacci là dãy vô hạn các số tự nhiên bắt đầu bằng hai phần tử 0 và 1 hoặc 1 và 1, các phần tử sau đó được thiết lập theo quy tắc mỗi phần tử luôn bằng tổng hai phần tử trước nó. Số Fibonaci thứ n, ký hiệu F(n), được định nghĩa như sau :

```
F(n) = 1, nếu n=1 hoặc n=2
F(n) = F(n-1) + F(n-2), nếu n>=3
Yêu cầu : tính số fibonaci thứ n với n cho trước.
```

## Tham khảo
+ [Định nghĩa Dãy Fibonacci](https://vi.wikipedia.org/wiki/D%C3%A3y_Fibonacci)
+ [Dùng đệ quy để tạo dãy Finbonacci](https://huynhminhkhoa.wordpress.com/c-cshap-vb-net/co-ban-ve-thuat-toan-de-quy/)

##Bài toán Fibonacci
+ Nhập và Hiển thị mảng a gồm n phần tử
+ Nếu các phần tử trong mảng a thuộc dãy Finbonnacci thì hiển thị ra

```
//dinh nghia ham Finbonacci
    int Finbonacci(int x)
    {
        if(x<3)
            return 1;
        
        return Finbonacci(x-1) + Finbonacci(x-2);
    }
```
