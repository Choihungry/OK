~~~R
head(iris)
str(iris)
install.packages("ggplot2")
library(ggplot2)

ggplot(data=iris, aes(x=Sepal.Length, y=Sepal.Width))+geom_point()
ggplot()+geom_point(data=iris,aes(x=Sepal.Length, y=Sepal.Width))
~~~
~~~R
ggplot(data=iris, aes(x=Petal.Length, y=Petal.Width))
+ geom_point(aes(color=Species, shape=Species), alpha=0.5, size=2.5)
~~~
~~~R
gp+ggtitle("IRIS data")
+ theme(plot.title = element_text(size=13, face="bold",color="Green", hjust=0))
~~~
