# Example of README.md
## R Script of Test Question 5
?mtcars
dat = mtcars
pmatrix = scale(dat)
d = dist(pmatrix)
c = hclust(d, method = "ward.D2")
plot(c)
rect.hclust(c, k=2)
