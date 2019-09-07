~~~R
head(iris)
str(iris)
install.packages("ggplot2")
library(ggplot2)

ggplot(data=iris, aes(x=Sepal.Length, y=Sepal.Width))+geom_point()
ggplot()+geom_point(data=iris,aes(x=Sepal.Length, y=Sepal.Width))
~~~
