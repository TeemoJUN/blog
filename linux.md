在linux系统中读取java的class文件时



```linux
vim -b SelectTopMapper.class
```
![fa](./SelectTopMapper.png)


```
:%!xxd
```

![fa](./SelectTopMapper2.png)

`:i`现在可以修改了

```
:%!xxd -r
```
又可以回到读的样子了

`:wq`

