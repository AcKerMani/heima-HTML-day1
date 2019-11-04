### 表格的应用

#### 表格的结构

``` html 
<tbale>
    <thead>
        <tr>
            <th></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td></td>
        </tr>
        <tr>
            <td></td>
        </tr>
    </tbody>
</tbale>
```

- **tr为行**
- **th为标题表格**
- **td为单元格**

#### 表格的属性

1. **align 文字居中**
2. **cellspacing 文字之间的距离**
3. **cellpadding 单元格间的距离默认1px**
4. **border 边框属性**

#### 表格合并

##### 合并要把多余的td删掉

1. **rowspan  行合并**
2. **colspan 列合并** 



### 列表的使用

**一， 无序列表：**

``` html
<ul>
   	<li></li>
</ul>
```

**二，有序列表：**

``` html
<ol>
    <li></li>
</ol>
```

**三，自定义列表**

``` html
<dl>
    <dt>这个为大哥</dt>
    <dd>小弟，简称DD</dd>
</dl>
```



### 表单的使用

#### 表单的表签

``` html
    <form action="demo.php" method="POST" name="content">
        <input type="text" name="text">
        <input type="password" name="password">
        <input type="radio" name="sex" id="" value="男">男
        <input type="radio" name="sex" id="" value="女">女
        <input type="checkbox" name="hobby" id="">
        <input type="checkbox" name="hobby" id="">
        <input type="checkbox" name="hobby" id="">
        <textarea name="content_text" id="" cols="30" rows="10"></textarea>
        <input type="reset" value="点击重置">
        <input type="submit" value="提交">
    </form>
```

**form表单的俩个属性：**

- **action：属性表示要提交的地址**
- **method：属性表示要提交的方式，默认GET**

#### input标签的Type属性

1. **text  用户名**
2. **password 密码框**
3. **radio  单选框**
4. **checkbox 复选框**
5. **button 按钮**
6. **submit 提交按钮**
7. **reset 重置按钮**
8. **file 文件域**
9. **hidden 隐藏域**
10. **image 图片提交按钮**

#### input的属性:

- **value属性：表单传送到后台的值**
- **name属性：后台获取值时，需要的name**
- **checked属性：单选和复选默认选中的属性**
- **maxlength属性：input表单的长度限制**
- **minlength属性：input表单最小长度**

 #### 下拉菜单

​	**下拉菜单的标签**

``` html
<select> //selected 属性默认选中
    <option selected="selected">1</option>
    <option>2</option>
    <option>3</option>
</select>
```

#### 文本域

**文本域只有name就完事了，其余可以用css修改**

``` html 
<textarea></textarea>
```















