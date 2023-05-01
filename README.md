#creating a queue

from collections import deque

queque = deque()

# add elements to the queque

queque.append(1)
queque.append(2)
queque.append(4)
queque.append(3)


#printing the items on the queue

print (queque)

#removing items from the queue
#This rempoves items at the end
y = queque.pop()
#This removes items at the start 
z = queque.popleft()


#Print the remaining items

print (queque)
