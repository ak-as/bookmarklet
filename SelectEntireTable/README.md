
# テーブル全体の選択

コピー用
```
javascript:((w)=>{var m="選択対象のテーブルの一部を範囲選択して下さい。",s=w.getSelection();if(s.type!="Range"){alert(m);return;}var t=s.anchorNode.parentElement.closest("table");if(!t){alert(m);return;}var r=new Range();r.selectNodeContents(t);s.removeAllRanges();s.addRange(r)})(window)
```

整形用
```
javascript:((w)=>{
  var m="選択対象のテーブルの一部を範囲選択して下さい。",
  s=w.getSelection();
  if(s.type!="Range"){
    alert(m);
    return;
  }
  var t=s.anchorNode.parentElement.closest("table");
  if(!t){
    alert(m);
    return;
  }
  var r=new Range();
  r.selectNodeContents(t);
  s.removeAllRanges();
  s.addRange(r)
})(window)
```




