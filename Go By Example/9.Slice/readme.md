# 9 切片 Slice

切片是 Go 中一个关键的数据类型，是一个比数组更加强大的序列接口。

与数组不同，切片的类型仅由它所包含的元素类型所决定，而无需元素的个数。

创建一个长度非零的空切片：需要使用 `make` 方法。

创建了一个长度为 3 的 `string` 类型切片：

```go
s := make([]string, 3)
fmt.Println("创建一个空数组，结果是:", s)
```

可以和数组一样设置和得到值：
```go
s[0] = "a"
s[1] = "b"
s[2] = "c"
fmt.Println("set:", s)
fmt.Println("get:", s[2])
```

```shell

```


