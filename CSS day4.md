### 盒子，文字阴影

#### 边框阴影：

-  **box-shadow: X轴偏移量** 

  ​      **Y轴偏移量 [阴影模糊半径]** 

  ​      **[阴影扩展半径] [阴影颜色]** 

  ​      **[投影方式]inset为内阴影 默认为外阴影;**

#### 文字阴影：

​    **文字阴影设置：text-shadow**

​      **text-shadow: X-Offset Y-Offset blur color;**

​      **X,y 为阴影的X和Y轴的距离**

​      **blur 为模糊的半径**

​      **color为颜色**

#### 浮动：

- **传统布局的三种：**
  - **标准流**
  - **浮动流**
  - **定位流**

**布局标准：**

​		**多个块级竖向排列用标准流，**

​		**多个块级元素横向排列用浮动**

#### 浮动特性：

- **脱离文档流**
- **不再保留原先位置**
- **一行显示多个，默认高度根据内容，具有行内块特性**
- **并不会压住标准流 的文字**

#### 清除浮动：

**清除浮动的本质就是清除浮动造成的影响：**

**清除浮动：`clear:both;`**

- **额外标签法：**

  - **就是再最后一个浮动的元素加一个DIV，设置`clear:both;`**

- **父级添加 `overflow :hidden;`**

- **利用伪元素：**

  - ``` html
    :after{
        content:''; 必须的元素
        dipslay:block; 设置成块元素
        clear:both; 清除浮动
        visibility:hidden;占位隐藏
        height:0;
    }
    .clear{
        /* 兼容IE6/7 */
        *zoom:1;
    }
    ```

- **双伪元素清除：**-

  - ``` html
    :after,:before{
    	content: '';
    	display: table;
    }
    :after{
    	clear: both;
    }
    ```

    

















