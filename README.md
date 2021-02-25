## Feladat 02.22.
vn=scan(file = "vn1960.txt")
rnorm(length(vn), mean(vn), sd(vn))
plot(vn, type = "l", xlab = "t [nap]", ylab="h [cm]", lwd=2)
lines(vn1)
summary(vn)
quantile(vn)
sd (vn)
IQR (vn)
sd(vn)*2
lines(vn1)
