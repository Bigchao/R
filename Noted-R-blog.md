To Learn more
-
* [John Cook's blog post][eng-doc].
[eng-doc]:http://www.johndcook.com/R_language_for_programmers.html
* [Google's R Style Guide][1]
[1]:http://google-styleguide.googlecode.com/svn/trunk/google-r-style.html
* [Online chart of R colors](http://research.stowers-institute.org/efg/R/Color/Chart.R)

### 2.3.1 Entering Data from Keyboard
	mydata <- data.frame(age=numeric(0),gender=character(0),weight=numeric(0))
	madata<- edit(madata)

用上述的的指令就可以实现键盘编辑数据

### 2.3.2 Importing data from a delimited text file
	mydataframe <- read.table(file,header=logical_value,sep="delimiter",row.name="name"
更多查看`help(read.table)`





