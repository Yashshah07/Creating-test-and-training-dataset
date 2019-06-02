rm(list=ls())   # Clears the environment , removes all the objects 

#Load the "breast-cancer-wisconsin.data.csv" from file location

Cancerdataset<-read.csv("breast-cancer-wisconsin.data.csv", header=TRUE)
Cancerdataset
View(Cancerdataset)


index<-sample(nrow(Cancerdataset),size =0.25*(nrow(Cancerdataset)),replace=TRUE, prob=NULL )
index
test<-Cancerdataset[index,]
test

#25% of 699 rows is 174 row items please run the view function to check
View(test)

#View all the data in the same output
trainingdata<-Cancerdataset[-index,]
trainingdata
View(trainingdata)
