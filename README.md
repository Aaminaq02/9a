> m<-c(1,2,3,4,5,6)
> t<-c(25,22,30,34,45,52)
> #Label the chart
> png(file="Linear Regression")
> plot(t,m,col="red",main="Months and Temperature",
abline(lm(m~t)),cex=1.6,pch=10,xlab="Months",ylab="Temperature")
> dev.off()
null device
 1
> plot(t,m,col="red",main="Months and Temperature",
abline(lm(m~t)),cex=1.6,pch=10,xlab="Months",ylab="Temperature")
