<div align="center">

## A FUNNY CIRCLE


</div>

### Description

FUNNY CIRCLE
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Piyush Khandelwal](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/piyush-khandelwal.md)
**Level**          |Advanced
**User Rating**    |3.5 (14 globes from 4 users)
**Compatibility**  |C, C\+\+ \(general\)
**Category**       |[Graphics/ Sound](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/graphics-sound__3-15.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/piyush-khandelwal-a-funny-circle__3-9233/archive/master.zip)





### Source Code

```
#include<stdio.h>
	#include<conio.h>
	#include<dos.h>
	#include<graphics.h>
	#include<math.h>
	void main() 	{
	float pi=3.1415927;
	float x1,y1,x2,y2;
	int i,j,r1;
	int gd=DETECT,gm;
	initgraph(&gd,&gm,"");
	j=100;
	circle(250,250,j);
	i=0;
	while(i<=750)
	{
	x1=80*cos(i*pi/360);
	y1=80*sin(i*pi/360);
	x2=((x1+j)*(x1+j));
	y2=y1*y1;
	r1=floor(sqrt(x2+y2));
	delay(90);
	circle(floor(x1+250),floor(y1+250),r1);
	i=i+10; 	}
	getch();	}
```

