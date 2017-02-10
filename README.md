# jqueryDialog
 jquery.Dialog弹框

 这是一个jquery提供的dialog弹框

 ```
var dialog = $("#dialog").dialog({
    title:"打开jQuery.dialog弹框",
    width:600,
    height:400,
    buttons: [
      {
        text:"关闭",
        className:'button',
        click:function() {
          $(this).dialog("close");
        }
      },
      {
        text:"确定",
        className:'submit',
        click:function() {
          $(this).dialog("close");
        }
      }
    ]
  });
```

| 属性 | 说明 |
| ------------- |:-------------:|
| title | 不定义就不显示标题栏 |
| className | 是自定义的button按钮，默认可缺省，缺省时按钮用的是统一样式 |
| autoOpen | 可缺省，true为默认打开 |


