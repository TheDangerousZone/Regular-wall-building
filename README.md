roofswag
CODE
-- Variables
X = 3
Y = 25
y = 23
Z = 12
z = 12

for n = 1, X do

  turtle.up()
  
  for n = 1, Y do
   
   ItemPick()
   turtle.placeDown()
    turtle.forward()

   end
   
   turtle.turnRight()
   turtle.turnRight()
   turtle.forward()
   turtle.turnLeft()
   turtle.forward()
   
  for n = 1, Z do
  
      ItemPick()
      turtle.placeDown()
      turtle.forward()
      
   end
   
   ItemPick()
   turtle.placeDown()
   turtle.turnRight()
   turtle.forward()
   
   for n = 1, y do 
 
     
      ItemPick()
      turtle.placeDown()
      turtle.forward()
                     
   end
   
    ItemPick()
    turtle.placeDown()
    turtle.turnRight()
    turtle.forward()
      
   for n = 1, z do
    
    ItemPick()
    turtle.placeDown()
    turtle.forward()
   
  end
   
    turtle.turnRight()                                                                                                                                             
    
                                                                                                                                                                                                                                                                                                                                                                                                                                     
end
