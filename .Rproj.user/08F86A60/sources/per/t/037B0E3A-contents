# murari's lesson on R
## Data structure 
# scaler (variable type 1)
weight=78
kamal=78
class=44

# data type vector- one dimesnsional data either in form of row or column
year=2011:2020
year=seq(2011,2020,by=1)
popyear=seq(1961,2011,by=10)
temp=c(22.5,23.7,23.3,22.1,24.8,23.6,24.3,21.9,23.9,24.7) # concatenating 

plot(year,temp)

# data sructure matrix - spreadsheet 
A=seq(1,20,by=1)
MatA=matrix(A,nrow=4,ncol=5)
MatA1=matrix(A,nrow=4,ncol=5,byrow=TRUE)

### higher dimension 
TEMP=array(A,dim=c(2,2,5))

AA=rnorm(20,2,3)
TEMP=array(AA,dim=c(2,2,5))

ContingencyTables_CSV <- read.csv("E:/BigDataInitiatives/EPGDA/Introduction2R/ExcerciseR/Data folder/ContingencyTables_CSV.csv", header=TRUE)

View(ContingencyTables_CSV)

## Data Frame 
## a matrix , but its column names are defined 
Dis=Data$District
Bwells=Data$No.of.borewell # no. of borewells 
barplot(Bwells,names=Dis)
GIA=Data$GIA...000ha. # Gross irrigated area 

## y=mx+c   ### parameters m and c

### esttimte parameters 
### least aqure method ......
# y1=m1x+c1   sum((y-y1)^2)/nos.
# y2=m2x+c2   sum((y-y2)^2)/nos.
....
...
#yn=mnx+cn....sum((y-yn)^2)/nos.

h=lm(GIA~Bwells)
summary(h)