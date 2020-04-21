# mpp
map parser
```
//1 cell is 9
+-+
|o| x20
+-+

20x20 = 600x600

//floor:a~z default space
//floor event:A~Z
//wall:|-  default space
//hide door:/
//door:#
0-+1-+2-+3-+4-+5-+6-+7-+8-+9-+0-+1-+2-+3-+4-+5-+6-+7-+8-+9-+
| || || || || || || || || || || || || || || || || || || || |
+-++-++-++-++-++-++-++-++-++-++-++-++-++-++-++-++-++-++-++-+


+y+
yxy
+y+

x:floor
y:wall or door
+:non-read symbol

```
```
let F01= mapp(fixdata)
//F01.debug()  //console.log 
//F01.walk("x01y02.n").draw()
//F01.event("A",eventdata)



//F01.load(data) //walked maskdata
//data=F01.save() //walked maskdata
//F01.getCanvas('2D|3D|mini') //mini is 5x5
//F01.getEvent()
```

```
//usage
let F01 =mapp("F01",`
+0++0++0++0++0+ +0++0++0++0++0+ +0++0++0++0++0+ +0++0++0++0++0+
000000000000000 000000000000000 000000000000000 000000000000000
+0++0++0++0++0+ +0++0++0++0++0+ +0++0++0++0++0+ +0++0++0++0++0+
`)
.event("A",`

`)
.event("B",`
`)
```


