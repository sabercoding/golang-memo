## 转换成 int 类型
* string转成int：

```golang
int, err := strconv.Atoi(string)
```

* string转成int64：

```golang
int64, err := strconv.ParseInt(string, 10, 64)
```