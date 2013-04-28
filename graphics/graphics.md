!SLIDE
# KidsRuby Graphics #

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
      forward 100
    end

!SLIDE
# Draw Square #

!SLIDE
    @@@ ruby
    Turtle.start do
      background yellow
      forward 100
      turnright 90
      forward 100
      turnright 90
      forward 100
      turnright 90
      forward 100
    end

!SLIDE
# Draw Square At An Angle #

!SLIDE
    @@@ ruby
    Turtle.start do
      background yellow
      turnright 45
      forward 100
      turnright 90
      forward 100
      turnright 90
      forward 100
      turnright 90
      forward 100
    end

!SLIDE
# Draw Color Square At An Angle #

!SLIDE
    @@@ ruby
    Turtle.start do
      background yellow
      pencolor blue
      turnright 45
      forward 100
      turnright 90
      forward 100
      turnright 90
      forward 100
      turnright 90
      forward 100
    end

!SLIDE
# Let's Get Random #

!SLIDE
    @@@ ruby
    Turtle.start do
      background black
      pencolor white
      turnright rand(45)
      forward rand(150)
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
        distance = rand(150)
        turnright angle
        forward distance
        backward distance
      end
    end

!SLIDE 
# Now, go have fun! #
