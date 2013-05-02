!SLIDE
# KidsRuby Robots #

!SLIDE
# What Is A Robot? #

!SLIDE
# A Machine That Can Do Things In The "Real World" #

!SLIDE
# Sphero #

!SLIDE
# Go Forward #

!SLIDE
```ruby
require 'socket'
socket = TCPSocket.new("localhost", 4567)

require 'sphero'
forward = 0

Sphero.start socket do
  roll 90, forward
  keep_going 10

  stop
end
```

!SLIDE
# Forward and Backward #

!SLIDE
```ruby
require 'socket'
socket = TCPSocket.new("localhost", 4567)

require 'sphero'
forward = 0
backward = 180

Sphero.start socket do
  roll 90, forward
  keep_going 10

  roll 90, backward
  keep_going 10

  stop
end
```

!SLIDE
# Square #

!SLIDE
```ruby
require 'socket'
socket = TCPSocket.new("localhost", 4567)

require 'sphero'
Sphero.start socket do
  roll 90, FORWARD
  keep_going 10

  roll 90, RIGHT
  keep_going 10

  roll 90, BACKWARD
  keep_going 10

  roll 90, LEFT
  keep_going 10

  stop
end
```

!SLIDE
# Mars Mission #

!SLIDE
```ruby
require 'socket'
socket = TCPSocket.new("localhost", 4567)

require 'sphero'

Sphero.start socket do
  roll 90, FORWARD
  keep_going 10
  stop
  rgb 0, 0, 255
  sleep 10

  roll 90, RIGHT
  keep_going 10
  stop
  rgb 0, 255, 0
  sleep 10

  roll 90, BACKWARD
  keep_going 10
  stop
  rgb 255, 0, 0
  sleep 10

  roll 60, LEFT
  keep_going 10
  stop
  rgb 0, 0, 255
end
```

!SLIDE
# Mars Mission (Improved) #

!SLIDE
```ruby
require 'socket'
socket = TCPSocket.new("localhost", 4567)

require 'sphero'

Sphero.start socket do
  def move(direction)
    roll 90, FORWARD
    keep_going 10
    stop
  end

  move(FORWARD)
  rgb 0, 0, 255
  sleep 10

  move(RIGHT)
  rgb 0, 255, 0
  sleep 10

  move BACKWARD
  rgb 255, 0, 0
  sleep 10

  move LEFT
  rgb 0, 0, 255
end
```

!SLIDE
# Demolition Derby #

!SLIDE
# Maze/Racetrack #
