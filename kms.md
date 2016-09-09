# Assginments

R file
![image](C:\Users\Lenovo\Assginments.images.jpg)

```
# loading data of R workshop
  
path ="C:\\Users\\Lenovo\\Assginments"
 
 
##    meter readings of a car at each stop in KMs

    load the Workspace file into RGui and
    provide R-Code for these Questions



## no. of KM travelled before each stop
diff(distance)


## total number of KMs travelled 
sum(diff(distance))



## total number of KMs travelled using min() and max()
mini=min(distance)
maxi=max(distance)
maxi-mini

## total number of KMs travelled using indices of vector
mini=distance[1]
maxi=distance[length(distance)]
maxi-mini


## total number of KMs travelled using rev()
sum(rev(diff(distance)))


## total number of KMs travelled using head() and tail()
maxi=head(distance[1])
maxi
mini=tail(distance[8])
mini
maxi-mini

## total number of KMs travelled using head() and rev()
mini=head(distance[1])
maxi=tail(rev(distance[1])
maxi-mini
```





