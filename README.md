# -Excellence-Technosoft-Pvt-Ltd-test-solution

Question1 - Use python lists and make an list of numbers. Write a function which returns sum of the list of numbers

solution 

def listsum(numList):
    theSum = 0
    for i in numList:
        theSum = theSum + i
    return theSum

print(listsum([1,3,5,7,9]))


Setup a dict structure like this in python
Dict1: (this is a key, value pair of user id and username)
{
   “1” : “name1”,
   “2” : “name2”,
   “3” : “name3”
} etc.. 
Dict2: (this is a key value pair of user id and exam score) 
{
   “1” : 50,
   “2” : 60
   “3” : 70
}
These are just sample data assume there are hundreds of users 

Write a function in python in python, which will return maximum i.e function should return dictionary like
{
  “3” : 70
}


