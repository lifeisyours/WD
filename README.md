# freecode-2018
bootstrap样式

> https://cdn.bootcss.com/bootstrap/3.3.7/css/bootstrap.min.css

有序列表

    <ol>
     <li type="checkbox">每个诗人心中都有自己的致橡树，by 舒婷。</li>
     <li>每个程序猿心中都有自己的偶像，写一个致敬页来向自己的偶像致敬。</li>
     <li>当你看不到右边的视频时，说明你还身处防火墙中，赶紧翻墙去体验<a href="#">自由无阻碍的互联网</a>。</li>
     <li>如果你还不明白翻墙对个人成长的重要性，请去看电影<a href="#">《肖申克的救赎》</a>。</li>
    </ol>
## 部分笔记 ##
**复选框**
    <lable><input type="checkbox">text</lable>
**栅格使用**
    $("input").addClass("col-xs-1");
**点击checkbox后面文字颜色改变**

    1.使用label包含  input type='checkbox' 这样点击文本就可以勾选
    2.勾选后,只有checkbox 或 radio有:selected状态所以只能设置兄弟节点或直接点. 通过将文本放在span中. 
    3.使用选择器:     :checked+li  其中 +是相邻兄弟选择器 来实现样式
    节点添加属性 checked="checked"
    
    input:checked + li {
            color: #337ab7;
    }
      $("input").click(function(){
      $("li").css("opacity","0.4");
      

  
  作品查看地址

      https://codepen.io/Ritachou/pen/LJpogQ