## Ruby functions

A test for the basics of Ruby. There are 41 questions - you don't have to do every single one (although if you can, that's great). They vary in level from quite easy to fairly hard. Work through them and check if they're correct by running the specs.

You should be able to answer most questions with a couple of lines of code (often even just one), and just a few methods. If you're writing a long, complex solution, there's probably a better way.
If you find a solution quickly, see if you can find another way of doing the same thing. Of course you can google to your heart's content.


Sign up to [Github](https://github.com/) and [setup git](https://help.github.com/articles/set-up-git/) on your computer.

Clone this repo in your terminal:
~~~
$ cd ~
$ mkdir code
$ cd code
$ git clone https://github.com/fouralarmfire/blank-ruby.git
$ cd blank-ruby
$ ls # => you should see `README.md data lib spec`
~~~

To install rspec:
~~~
$ ruby -v # get your ruby version
$ export PATH=~/.gem/ruby/<the version>/bin:$PATH
$ gem install rspec
$ rspec -v
~~~

Make sure you are in the blank-ruby directory (ie when you run `ls` you should see `lib spec data README.md`) Then run:

The code you will be working on is in lib/questions.rb. Don't worry about what is in data.

To run the specs, open spec/questions_spec.rb, and remove the `x` in front of the `it` statement you want to test.
Then in your terminal run:
~~~
$ rspec
# or
$ rspec spec/questions_spec.rb
~~~

**Quick tip**: to run a single example, change `it` to `fit` on that example, then run

~~~
$ rspec questions_spec.rb --tag focus
~~~

### Rules

* Try and get the RSpec tests to pass (but not by cheating - i.e. hardcoding the expected value)
* You shouldn't need any extra libraries or gems
* The cleaner your code the better!
* Googling is encouraged, but have a think first.

### Tips

* Use the ruby docs http://www.ruby-doc.org/core-2.0.0/String.html
* Try and break down the problems into smaller chunks. For e.g. if you google "How to select elements in an array that start with a", you won't have much luck. Try and find out a) how to select certain elements in an array, b) how to test if a string starts with an 'a'
* Don't forget Enumerable (advanced array methods)
