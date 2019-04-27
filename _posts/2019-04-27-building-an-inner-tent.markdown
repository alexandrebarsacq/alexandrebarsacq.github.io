---
layout: post
title:  "Building a bug bivy"
date:   2019-04-27 15:37:08 +0200
categories: myog 
---

I designed and sewed a net tent / bug bivy (the border between those two is thin here). This was my first time designing a piece of outdoor equipment, and also my first time sewing. In this article, I'm starting with a presentation of the finished product, then I go in a quite in-depth description of the creation process.

### Table of Contents

* TOC
{:toc}

### Finished product presentation 

### Project story

![image]({{ site.baseurl }}/assets/images/RS485Sniffer/RS485Sniffer_synoptic.png)

MYOG shelter

Shelter presentation s
Inspired of MLD bug bivy.
Size 
Weight
Photos
Fabrics

Tale of overthinking something.

It’s been some time I’ve wanted to switch from sleeping in a tent to a tarp. However my recent hiking trips showed that, for some reason, ticks love me. Hiking with two other friends, I got between 5 to 10 ticks each day, when they got between 0 and 2… Several times, I’ve woken up to several ticks on the inner net of my tent in the morning. This made the idea of sleeping without bug protection a no-go. Actually, since Lyme disease doesn’t seem fun at all, I can’t imagine sleeping without a fully enclosed shelter of some sort anymore. 

I stumbled upon the MLD bug bivy 2 , which looked perfect for my need. However, I live in France, so the price inflated with taxes and shipping is quite steep. Most importantly, I’ve always wanted to start the Make Your Own Gear adventure, and this seemed like a good project to start with. So, I decided to make my own version of the MLD bug bivy 2. 

Choosing this shelter as a model is part of what makes the project complex. You can make very simple net-tents, two triangles on each extremity, two panels of netting, a bathtub and voilà. However the MLD shape is quite a bit more complex. This added complexity to both the design phase and the construction. 

I decided to prototype the shelter with a 3D model. I never used CAD software before, so I learned CAD in the process. I also never sewed before, so I learned sewing in the process. All in all, the finished product is the shelter, but this was mostly a project about learning new stuff.


### Designing the shelter 
Starting the project 

I started this project by reading as much as I could, finding similar projects, educating myself on this whole new activity. Good information sources were the BackPacking Light (BPL) forum and website. I also found interesting information on the myog subreddit. Finally, random googling brought me to interesting websites. I tried to keep track of the interesting links I found through the project, you can find the list at the end of the article in the reference section TODO ADD LINK.

#### Requirements 
Honestly, requirements could be summarized as « be the same as a MDL bug bivy 2 ». It boils down to :
Fully enclosed 
Bathtub
Water resistant, breathable panels for added coverage
Hang below a tarp
Low weight

#### Material choice
Material choice was dictated by a mix of my requirement of low weight and availability from european suppliers. I read quite a bit of literature, mostly from BPL and myog subreddit, to help me with my choice.
I ended up with the following materials : 
Bathtub :  silpoly PU4000 ( ADD WEIGHT HERE)  : its durability/weight/waterproofness characteristics seemed like a good compromise  sourced from adventurexpert
Sidewalls and head/feet triangles : PTX quantum(ADD WEIGHT HERE)  : very light, water resistant, breathable, it also seemed like a good choice for my requirements sourced from extremtextil
Netting : the smallest holes/lightest combo I could find, on extremtextil also.

For complete BOM see : BUILD TODO ADD LINK

#### Design process
I saw some posts of people on BPL building 1:1 scale wood frames of what their shelter would be, then use this to create a pattern. I like that idea, but dealing with the logistics of wood construction in my tiny apartment is a big pain.  My normal day job involves a lot of computers, programming, and so on. Naturally, I decided to base my design process on a 3D model of a tent.  This became an adventure on its own since I didn’t know how to use CAD software. 

Doing this taught me why so many tent designs use triangles. While it might be obvious with some thinking, actually « seeing » it with CAD design was a revelation : a panel with 4 side could easily have its four corners not in the same plane, which forces you to « flatten » the panel in 2d to make a pattern, which creates approximations on the shape. With triangles, there’s always a 2d plane on which you can project the panel.  

I decided to use FreeCAD TODO ADD LINK. People I told about my choice said that was insanity, that it’s not mature enough, etc etc. However it’s free and open source software, so I like that, which also means that all the tools I needed were available for free, even if it required some tweaking. 
At some point, I recreated the design in Fusion360 (which is free for hobbyists), and let’s be honest, it was way faster and easier than in FreeCAD. However, flattening tools are 3rd party in Fusion360 (and not free). 
With some practice, FreeCAD is not that bad to use, and with some polishing it will probably grow to an excellent CAD software in the future. 

I basically created the wireframe of the tent, then used those wire to create the surfaces
I’m pretty sure that it’s not the conventional way to design in freecad, however, for my defense, it was simpler this way and it works. It also kind of mimics the technique of creating a wooding frame which I described above, so I guess there’s a logic to it. 

Once the 3D model was created, which allowed me to see the proportions and tweak it a bit, I used tools to unfold the parts and flatten them, then used inkscape to create a pattern out of it. 

I give more tips at the end of the article on using freecad and inkscape for patterning. TODO ADD LINK.

Once I had the pattern sorted out, it was time to learn a bit more about sewing. 

### Sewing the shelter
Disclaimer : complete beginner in sewing, so take this for what it is.

#### Assembling panels.
There are many techniques to assemble two panels together. I identified two seams as relevant for my case : flat felled seam and top stitched French seam. Both of those seams ensure that the fabric edge is tucked inside the seam, ensuring that it will not unravel. They also ensure that stitches go through several layers of fabric, which is good for strength.
In theory, the flat felled seam seems like the best of all. 2 rows of stitches passing through 4 layers of fabric each ensure a very strong result. 
TODO IMAGE real flat felled seam
Flat felled seam is best made on an industrial sewing machine with 2 needles. I don’t have that kind of machine. You can find a lot of tutorials on making a flat felled seam with a home sewing machine. However, many of these are not « real » flat felled seams : some don’t go through all layers of fabric, etc. You can find some tutorials for a real flat felled seam, but in any case it involves a lot of folding, which is a pain with ultralight fabric.
Enter the top stitched French seam. I discovered it through the Yama Mountain Gear website which has this superb tutorial on making the stitch : ADD LINK HERE. This seam is probably a bit less resistant than the flat felled seam, but it doesn’t require any folding, any weird asymmetric seam allowance : sew 3 straight lines and voilà. 
When I make my tarp I’ll probably try a flat felled seam, but for this current application, the simplicity of the top stitched French seam won my heart, and I’m pretty sure the strength will be more than enough for a net tent.

#### Thread tension.
Tension is a pain. You want to go really low with ultralight fabric. I bought quite a lot of extra fabric that I used for testing, making lines and lines again with several settings. On my sewing machine, I don’t know if it’s usual or not, there’s a small spring that tensions the upper thread, independent from the tension setting. This puts a minimum baseline on upper tension, even if I set it to zero. In my quest of lowering the tension, I tried circumventing that spring but it would make the machine malfunction. I also disassembled the external frame of the machine, in the hope of finding « something », and out of curiosity also, it did not yield any results, but I documented the procedure here : TODO ADD LINK.
For my machine (Toyota RS 2000), the process of finding the correct tension ended up being : start from lowest possible upper thread tension, and then adjust the bobbin tension to match it. I’m pretty sure a lower overall tension would be better, but I can’t test that assertion with my machine. 
Did you see what I wrote just above ? I wrote it before starting the actual sewing. It's not completely true. When I wrote this, I was trying to find the correct tension for 2 pieces of one specific fabric. However in this project there are 3 different fabric. Also, depending on what you are sewing, you might be sewing through 2, 3, 4 or even more layer of fabric. Each of these combination have their own ideal tension. So the real way to find the correct tension ended up being : sew some stitches, check what they look like, adapt tension, repeat. With practice it gets better.

#### Needles and thread.
With ultralight fabric, go small, very small. The smaller the less puckering.
I ended up using a ADD NEEDLE SIZE HERE and THREAD here. 
This is smaller than recommended size, but as someone said somewhere on BPL (sorry I didn’t keep the link), that thread manufacturers have a tendency to advice bigger needle size than required.

#### Building the shelter
A really helpful tutorial is this one TODO ADD LINK, from Yama Mountain Gear. 
Actually the instructions given below are, without a doubt, of lower quality than this tutorial, so I would advise to use the instruction below as guidelines, but to refer to the Yama Mountain Gear tutorial for actual techniques.

# AAAA
## BBB
### CCC
![My helpful screenshot](/assets/pictures/nettent/0_head_pattern.jpg)

Get the 
Finished product

sewing the tent

1 sew together mesh panels.
Goal : avoid measuring and folding fabric : solution : sew together mesh panels then deal with zipper seam allowance

Sew together
add zipper
cut


### References


You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
