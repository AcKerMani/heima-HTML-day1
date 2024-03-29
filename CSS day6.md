#### 定位讲解

##### 定位组成

1. **定位 = 定位模式 + 边偏移**
2. **定位模式的值：position**
   1. **relative  相对**
      1. **相对于自身移动**
      2. **不脱离文档流，本身会占用位置**
   2. **absolute 绝对**
      1. **相对于父级定位，如果父元素没有 定位，就以body定位**
      2. **如果祖先有定位，就以最近一级带定位的祖先元素为参考**
   3. **fixed  固定**
      1. **以浏览器的可视窗口来进行定位**
      2. **跟父元素无关，不随滚动条滚动**
      3. **固定定位不保留标准流的位置**
   

##### 绝对居中：

``` html
position：定位属性;
left:50%; 
top:0;
margin-left: 负的本身长度的一半;
```

4. **粘性定位：sticky**
   1. **以浏览器的可视窗口来进行定位**
   2. **粘性定位据有标准流的位置**
   3. **必须添加top，left，right，bottom其中的一种才有效**

##### 层叠顺序：z-index:

1. **只有具有定位的属性，才能使用**
2. **值越大，优先级就越高**





























