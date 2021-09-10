---
---
Friday  
Code snippets  
To render a code block with syntax highlighting:
{% highlight ruby %}
def foo
  puts 'foo'
end
{% endhighlight %}

To render a code block with syntax highlighting:
{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
{% endhighlight %}

Insert HTML to Jekyll post
Create a folder with the name _includes/ in the DocumentRoot of your project  
Then, create an HTML file inside, for example "mycomponent.html" 
Omit <!DOCTYPE html>  
Call it in your post with something like this:

{% highlight ruby %}
{% include mycomponent.html %}
{% endhighlight %}
