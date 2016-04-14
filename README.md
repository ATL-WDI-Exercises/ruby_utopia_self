##Utopia - The "self" Examination


1) Copy and paste the entirety of the following code snippet into pry.



```ruby
class Utopia
  def initialize(name)
    @name = name
  end

  def name
    @name
  end

  def self.define
    puts "I am the bodiless notion of a near-perfect society."
    self
  end

  def define
    puts "I am #{name}, a tangible society that you can reach out and touch in which everyone is content." 
    self
  end

  def say_hello
    self.define
  end

  def say_hello_again
    define
  end
end
```

<br>
2) Still in pry, instantiate a new Utopia object and store it in the variable `madison`

<br>
3) Enter the following and examine the output in pry:
  
  * `Utopia.define`
  * `madison.define`
  * `madison.say_hello`
  * `madison.say_hello_again`

<br>
4) Now enter the following and examine the output:
  
  * `Utopia.define` (Yes, again.)
  * `Utopia.say_hello`
  * `Utopia.say_hello_again`
