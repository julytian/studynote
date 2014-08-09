==============   2014/8/7 10:39:38  style 样式封装 =====================================

    function getStyle(obj,attr) {  //二个参数，第一个是对象，第二个是那个属性
        return obj.currentStyle ? obj.currentStyle[attr] :getComputedStyle(obj)[attr]；
      } 
 
