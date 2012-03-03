!SLIDE 
# Welcome To KidsRuby #

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

!SLIDE
    @@@ ruby
    puts 1

!SLIDE
# Operators

!SLIDE
    @@@ ruby
    puts 1 + 1
    puts 10 - 5
    puts 10 * 10
    puts 10 / 10 + 1

!SLIDE
# Variables #

!SLIDE
    @@@ ruby
    x = 25 * 25
    y = 54321
    puts x
    puts y
    puts x + y

!SLIDE
# Hacking Your Math Homework #

!SLIDE
    @@@ ruby
    x = ask "what is x?"
    answer = ((37 / 15) + 37 * x) * 3.7
    puts answer

!SLIDE
# Strings #

!SLIDE code
    @@@ ruby
    puts "cat"
    animal = "dog"
    puts animal

!SLIDE
# Many Times Puts Something #

!SLIDE
    @@@ ruby
    20.times do
      puts "I love Ruby!"
    end

!SLIDE
# Many Times Puts Anything #

!SLIDE
    @@@ ruby
    words = ask "What should I say?"
    10.times do
      puts words
    end

!SLIDE
# Ask How Many Times Puts Anything #

!SLIDE
    @@@ ruby
    words = ask "What should I say?"
    count = ask("How many times?")
    count.times do
      puts words
    end

!SLIDE
# Conditionals #

!SLIDE
    @@@ ruby
    color = ask "What is your favorite color?"
    if color == "blue"
      alert "Go Blue!"
    else
      alert "Ummm... OK"
    end

!SLIDE
# More Fun with Strings #

!SLIDE
    @@@ ruby
    puts "hello" + "there"
    puts "hello".upcase
    puts "hello".reverse
    puts "hello" * 3

!SLIDE
# Hacking Your Writing Homework #

!SLIDE
    @@@ ruby
    holiday = ask "Which holiday?"
    familymember = ask "Family member?"
    activity = ask "Activity?"
    smallproblem = ask "A small problem?"

    puts "It was just " + holiday + "."
    puts "I was with my " + familymember + "."
    puts "I also went " + activity +"."
    puts smallproblem + " but it was OK."
    puts "It was a good " + holiday + "."

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

!SLIDE
    @@@ ruby
    Turtle.start do
      background red
    end

!SLIDE
# Draw Line #

!SLIDE
    @@@ ruby
    Turtle.start do
      background yellow
      forward 50
    end

!SLIDE
# Draw Square #

!SLIDE
    @@@ ruby
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

!SLIDE
    @@@ ruby
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

!SLIDE
    @@@ ruby
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

!SLIDE
    @@@ ruby
    Turtle.start do
      background black
      pencolor white
      turnright rand(45)
      forward rand(15)
    end

!SLIDE
# Starburst #

!SLIDE
    @@@ ruby
    Turtle.start do
      background black
      pencolor white
      100.times do
        angle = rand(45)
        distance = rand(100)
        turnright angle
        forward distance
        backward distance
      end
    end

!SLIDE 
# Now, go have fun! #
