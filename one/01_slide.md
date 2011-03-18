!SLIDE 
# Los Angeles Ruby Conference For Kids #

!SLIDE 
# What is Programming #

!SLIDE 
# Computers? More like "organizers" #

!SLIDE 
# Them: 0s & 1s #

!SLIDE 
# Us: everything else! #

!SLIDE
# Basic Ruby #

!SLIDE 
# Commands #

!SLIDE code
puts 1

!SLIDE
Operators

!SLIDE code
puts 1 + 1
puts 10 - 5
puts 10 * 10
puts 10 / 10 + 1

!SLIDE
# Variables #

!SLIDE code
x = 25 * 25
y = 54321
puts x
puts y
puts x + y

!SLIDE
# Hacking Your Math Homework #

!SLIDE code
x = ask "what is x?"
answer = ((37 / 15) + 37 * x) * 3.7
puts answer

!SLIDE
# Strings #

!SLIDE code
puts "cat"
animal = "dog"
puts animal

!SLIDE
# Many Times Puts Something #

!SLIDE code
20.times do
  puts "I love Ruby!"
end

!SLIDE
# Many Times Puts Anything #

!SLIDE code
what_to_say = ask "What should I say?"
10.times do
  puts what_to_say
end

!SLIDE
# Ask How Many Times Puts Anything #

!SLIDE code
how_many = ask "How many times?"
what_to_say = ask "What should I say?"
how_many.times do
  puts what_to_say
end

!SLIDE
# Conditionals #

!SLIDE code
color = ask "What is your favorite color?"
if color == "blue"
  alert "Go Blue!"
else
  alert "Ummm... OK"
end

!SLIDE
# More Fun with Strings #

!SLIDE code
puts "hello" + "there"
puts "hello".upcase
puts "hello".reverse
puts "hello" * 3

!SLIDE
# Hacking Your Writing Homework #

!SLIDE code
holiday = ask "Which holiday?"
familymember = ask "Name of family member?"
activity = ask "What activity?"
smallproblem = ask "Name of small problem"

puts "I just had a fun time over " + holiday + "."
puts "My " + familymember " and I were together."
puts "I also got to " + activity +"."
puts "I had " + smallproblem + " but it was OK."
puts "Pretty much I had a good " + holiday + "with my family."

!SLIDE
# Graphics #

!SLIDE
# Like graphs you draw in school #

!SLIDE
# Etch A Sketch #

!SLIDE
# Turtles #


!SLIDE
# Background Colors #

!SLIDE code
Turtle.start do
  background red
end

!SLIDE
# Draw Line #

!SLIDE code
Turtle.start do
  background yellow
  forward 50
end

!SLIDE
# Draw Square #

!SLIDE code
Turtle.start do
  background yellow
  forward 50
  turnright 90
  forward 50
  turnright 90
  forward 50
  turnright 90
  forward 50
end

!SLIDE
# Draw Square At An Angle #

!SLIDE code
Turtle.start do
  background yellow
  turnright 45
  forward 50
  turnright 90
  forward 50
  turnright 90
  forward 50
  turnright 90
  forward 50
end

!SLIDE
# Draw Color Square At An Angle #

!SLIDE code
Turtle.start do
  background yellow
  pencolor blue
  turnright 45
  forward 50
  turnright 90
  forward 50
  turnright 90
  forward 50
  turnright 90
  forward 50
end

!SLIDE
# Let's Get Random #

!SLIDE code
Turtle.start do
  background black
  pencolor white
  turnright rand(45)
  forward rand(15)
end

