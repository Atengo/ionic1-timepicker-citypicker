# ionic1-timepicker-citypicker
timepicker&amp;&amp;citypicker base ionic1

使用方法

在主html中导入
```js
  <link href="..yourpoth/citypicker.css" rel="stylesheet">
  <script src="..yourpoth/citydata.js"></script>
  <script src="..yourpoth/citypicker.js"></script>
  
module中导入
```
  angular.module('yourmodule', ['citypicker']);
  
时间插用使用：
```
 <city-Picker tag="-" backdrop=true backdrop-click-to-close=false ok-text="确定" citydata="{{info.birthday}}" handle="0"datatype="date" button-Clicked="editbirthday()"></city-Picker>
 
城市插件作用
```
 <city-Picker tag="-" backdrop=true backdrop-click-to-close=false ok-text="确定" citydata="{{info.birthcity}}" handle="1"datatype="city" button-Clicked="editbirthcity()"></city-Picker>
  
