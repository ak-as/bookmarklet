
# WebページのタイトルとURLのコピー


コピー用
```javascript
javascript:((d,l)=>{var t=d.title,h=l.href,ta=d.createElement("textarea");ta.textContent=t+"\n"+h;d.body.appendChild(ta);ta.select();d.execCommand("copy");d.body.removeChild(ta);})(document,location)
```

整形版
```javascript
javascript:((d,l)=>{
  var t=d.title,h=l.href,ta=d.createElement("textarea");
  ta.textContent=t+"\n"+h;
  d.body.appendChild(ta);
  ta.select();
  d.execCommand("copy");
  d.body.removeChild(ta);
})(document,location)
```


