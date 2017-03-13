# pullDownRefresh


##使用方法
  .outerScroller未外层固定容器  是不滚动的
  .scroll   是容器里面包含滚动内容的容器  是滚动的
  .logoText   是包含logo文字的  当然可以改变样式

  我们的数据调取是在这个监听事件里  使用 ajax 
  
  `
  outerScroller.addEventListener('touchend',function(){
     ajax({
       url:'xxxxxxxx',
       callBakc:function(data){
  }
       })



    })
    `
