# 3d-lottery
3d  js 年会抽奖 不可重复中奖

```
//不能重复中奖 (删除已经中奖的人员)
i = 0;
for (; i < Obj.luckyResult.length; i++) {
    newarr.push(Obj.luckyResult[i])
}
newarr =  newarr.sort(function(a,b){
    return b-a;
})
console.log(newarr)
for(let val of newarr){
    console.log("newarr:"+val)
    personArray.splice(val,  1)
}
newarr = []
console.log(personArray)
        
```

![image](https://github.com/xieyuhua/3d-lottery/assets/29120060/f6de0546-5cf6-45fd-b9bd-4130e45ca9d1)

![image](https://github.com/xieyuhua/3d-lottery/assets/29120060/5405b783-2c22-46a1-a592-44d064435e90)

![image](https://github.com/xieyuhua/3d-lottery/assets/29120060/79b07053-1f2b-425e-ae9e-faf365fc2bf6)

