# neu
neu is 

```js

var MAX_W=10
var MAX_H=10
var DUNG=[27]
var EVENT=[27]
;
DUNG[1]=`
０１２３４５６７８９
１壁壁壁壁壁壁壁壁壁
２壁　　　　　　　壁
３壁　　　　　　　壁
４壁　　　　　　　壁
５壁壁壁壁あ壁壁壁壁
６壁　　　　　　　壁
７壁　　　　　　　壁
８壁　　　　　　　壁
９壁壁壁壁壁壁壁壁壁
`.trim();
EVENT[1]={};
var E1=EVENT[1]
E1['あＮ']=`
しばらくすすむと　くずれたかべがあった
ここから　むこうがわに　いけるようだ
`
E1['あＳ']=`
ここから　もとのみちに　もどれそうだ　
`

function getevent(f,ch,v){
 var floor=EVENT[f];
 if(!floor)return void 0;
 v=fn.tobig(v);
 return floor[ch+v]||floor[ch]||void 0
}

;

```
