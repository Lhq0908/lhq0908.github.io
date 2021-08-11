例子网址
https://blog.csdn.net/weixin_41949878/article/details/115303105

.box {
        width:auto;
        height:auto;
        display:inline-block !important; /* div宽度适应内容宽度 */
        display:inline;
        background:
                    radial-gradient(circle at left, transparent 10px, red 0) left, /* 左边的圆，circle表示圆形，可以换成其他形状ellipse表示椭圆/ */
                    radial-gradient(circle at right, transparent 10px, red 0) right;/* 右边的圆*/
        background-repeat: no-repeat;
        background-size: 50% 100%;
        text-align:center; 
    }

