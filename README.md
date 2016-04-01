# js-xz-area
省市二级联动，默认选择全部

# 使用方法

    <select id="s1"></select>
    <select id="s2"></select>
    
    <script src="xz-area.js"></script>
    <script>
    xzArea({
      select1:"#s1",
      select2:"#s2",
      selected1:'江苏',//可选，指定选择省份，在编辑的时候特别有用
      selected2:'南京'//同上
    })
    </script>
  
# 说明

删除了直辖市和特别行政区内的区信息，二级select默认选择"全部"。
