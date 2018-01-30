## 使用说明
### 在项目中引入JS及其CSS文件

<script src="./js/jquery.editable-select.js" type="text/javascript"></script>

### 配置设置

 <script>
        $(function(){
            $('#select').editableSelect({
                effects: 'slide'
            });
        });
 </script>
 
### 选项设置

isFilter:true //是否根据条件过滤下拉选项，即当输入内容时下拉选项会匹配输入的字符，支持中文，true/false，默认true。

effects：动画效果，当触发弹出下拉选择框时的下拉框展示过渡效果，有default，slide，fade三个值，默认是default。

duration：下拉选项框展示的过渡动画速度，有fast，slow，以及数字（毫秒），默认是fast。

case_sensitive: false, // 是否匹配

items_then_scroll: 10 ,// 设置下拉选项的数目

bg_iframe: true, //是否加iframe

### 事件

onCreate：当输入时触发。

onShow：当下拉时触发。

onHide：当下拉框隐藏时触发。

onSelect：当下拉框中的选项被选中时触发。

### 扩展

这款插件允许用户输入内容，同时下拉选项中会及时匹配相关选项，支持键盘操作，还支持html选项内容，当然还能让下拉的过程带有动画效果。
