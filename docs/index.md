# Welcome To The Book Of Programming

## _"Most good programmers do programming not because they expect to get paid or get adulation by the public, but because is fun to program"_

**-Linus Torvalds**

### **_What is Programming_**

The art of writring instructions for a computer to execute.

<!-- Show last 5 posts here -->

{% for post in site.posts %}

<article>
    <header>
        <h2><a href="{{site.baseurl}}{{post.url}}">{{ post.title }}</a></h2>
        <span class="date"><i class="icon-clock"></i><time datetime="{{post.date|date:"%F"}}">{{post.date|date:"%b %d, %Y"}}</time></span><br/>
        <span class="category"><i class="icon-tag"></i> {{ post.categories | category_links }}</span><br/>
        <span class="author"><i class="icon-user"></i> {% if post.author %}{{post.author}}{% else %}{{site.author}}{% endif%}</span>
    </header>
<div class="entry">{{ post.excerpt }}</div>
</article>

{% endfor %}

### **Connect with me**

[Twitter](https://twitter.com/FullStackJQN)

[Instagram](https://www.instagram.com/j_queue_n/)

[Medium](https://jqn.medium.com/)
