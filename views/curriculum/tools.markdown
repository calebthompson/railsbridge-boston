# Other Tools to Help You Learn Ruby

### irb

We've already introduced irb above, but it can't be stressed enough
that having an interactive live session with ruby is invaluable. You
can learn a lot from it.
You can do stuff like:

```ruby
$ irb
>> "blah".methods
=> [:<=>, :==, :===, :eql?, :hash, :casecmp, :+, :*, :%, :[], :[]=, :insert, :length, :size...]
```

All of these methods are available for any string. You can then use
ri to look up the method documentation. It is a great way to find goodies!


### Online Resources

[Ruby Quickref](http://www.zenspider.com/Languages/Ruby/QuickRef.html)  
Google - searching "ruby" and whatever you're looking for usually leads to good stuff.  
[Ruby Koans](http://rubykoans.com/) - a great set of lessons in an interactive form.  
[Test First Training](http://testfirst.org) - learn Ruby, one test at a time.  
[Learn to Program by Chris Pine](http://pine.fm/LearnToProgram) - also available as [a book](http://pragprog.com/book/ltp2/learn-to-program).  
[The Pickaxe](http://pragprog.com/book/ruby3/programming-ruby-1-9) - The definitive ruby reference (and has a great tutorial too).  
[Why's (poignant) Guide to Ruby](http://www.scribd.com/doc/8545174/whys-Poignant-Guide-to-Ruby) - the (crazy) guide to ruby... Try it, you might like it.  

## Checkpoint: Iterate through an array

(A checkpoint is an optional practice question that allows you to apply the concepts introduced in this section.
Talk to your TA if you get stuck, or discuss your solution once you have completed the checkpoint.)

Write a short script that prints out the names of the people in your group.

Hints: 

1. Start by opening up irb. 
2. Create the names as strings in an array. 
3. Store that array to a variable.
4. Then use the `.each` method on the stored array to loop through each of the names.
5. Use the `puts` method to print out the names.

If this script was easy for you, discuss with your TA other ways you could have achieved the same result.

## Extra Credit

If you like, there is always more Ruby to learn. 

* Learn more about [Ruby arrays](extra_credit/01_more_ruby)!
* Learn more about [Ruby classes](extra_credit/06_ruby_classes)!

## Next Step

Wait for the next lecture!  
[(…is the lecture over? Go to the next section)](/curriculum/getting_started)
