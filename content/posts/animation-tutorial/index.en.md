---
title: "Easily Animate Your Characters"
date: 2023-06-20T11:00:21-05:00
draft: false
author: Dougie
images: ["/sConcept-boy.png"]

featuredImage: "featured-image.png"


tags: ["Art", "Animation", ]
categories: ["Tutorials"]
music: true


lightgallery: true

weight: 3
url: "/animation/"
---
Want to quickly add **life** to your original characters? Here’s a quick method I use.

<!--more-->
---
{{< admonition note "Hey!" false >}}
It roughly takes me 20 minutes to create an idle animation using this technique.
{{< /admonition >}}

While creating tons of characters for my project, I decided to show how I add idle animations quickly. After creating my first frame of my character, then I focus on creating 3 frames.


---
# Overview
We'll start by creating 3 frames to animate our character. By focusing on *key frames*, we'll make sure our desired result is shown with the smallest amount of frames.

This is what you'll learn to make!
![Results](/images/luma-final.gif "Idle Animation")

### Total frames:
1. Normal
1. Squish
1. Stretch
1. Return
---

## Create Key Frames 
### Frame 1: Normal
Use the sketch of your character as the *normal* frame. The character should appear *at rest* or *neutral*.
![Key Frame](/images/sLuma-normal.png "Normal Frame")

### Frame 2: Squish
Simply, duplicate the frame of your character and *squish* it. Shorten and widen your character by a few pixels. 
{{< admonition tip "Tip">}}
Use the *selection* tool to move pixels around easily.
{{< /admonition >}}
![Key Frame](/images/sLuma-squish-edit.png "Squished Luma")

By using the *selection* tool, you'll avoid adding extra mass or unnecessary pixels. After shortening and widdening your character, simply fill in the *blank space* with the correct pixels. 

![Key Frame](/images/sLuma-squish-final.png "Squished Luma Filled")
___
### Frame 3: Stretch
Next, duplicate your *normal* frame to create your *stretch* frame. Again, start by using the selection tool to heighten and narrow your character.
![Key Frame](/images/sLuma-narrow-edit.png "Stretched Luma")

Once your character is stretched, fill in the pixels with the appropriate colors.
{{< admonition tip "Tip" false >}}
Think of the *stretch* frame as the opposite of the *squish* frame!
{{< /admonition >}}

![Key Frame](/images/sLuma-narrow-final.png "Stretched Luma Filled")
___
### Frame 4: Return
**You've just finished the hard part!**. Now, we're going to blend the last frame (the *stretch* frame) with our *normal* frame.

Start by duplicating your *normal* frame again. Repeat the same process in *Step 3*, BUT be slightly less agressive.
![Key Frame](/images/sLuma-return.png "Luma is Home")

___

## Rough Draft
By now, we created our 3 **:(fas fa-key fa-fw): frames**, as well as our 1st *normal* frame. Our sprite sheet should look like this.
### Sprite Sheet
1. Normal
1. Squish
1. Stretch
1. Return

![Sprite Sheet](/images/sLuma-spritesheet.png "Rough Draft")

If we played our *gif* right now, the character appears *too* extreme, or *too* choppy. 

{{< admonition note "Hey!" false >}}
BUT we have tricks to slip more detail into our small 4 frame animation.
{{< /admonition >}}

___
## Final Draft
To make our animation appear less choppy and extreme, we'll focus on *blending* our frames together. 
{{< admonition tip "Tip" false >}}
There's no need to add *blending* frames, we'll instead use:
* Anticipation
* Momentum
{{< /admonition >}}
### Anticipation
> Anticipation shows your character *preparing* to do the desired action. 

For example, this is often seen in a jump animation. Before the character jumps, the character will *squish* down. This shows the stored energy the character has, making your animation more lively.

{{< admonition success "Nice!" true >}}
We've already blended our *squish* frame with our *stretch* frame by showing our character is *preparing* to bounce and stretch.
{{< /admonition >}}

___

## Momentum
> Momentum shows that each action has an effect on your character.

A simple way to think of momentum is slowing your character's *appendages* by one frame. For example:
### Stretch Final 
![Momentum](/images/sLuma-narrow-hair.png "Polished Stretch Frame")
Notice the small changes with the *stretch* frame. 
- [x] Hair is squished
- [x] Eyes are lowered, furthur apart, and squished

{{< admonition success "Nice!" true >}}
All changes show the *momentum* from the *squish* frame.
{{< /admonition >}}

Let's repeat the process with the return frame.

### Return Final
![Momentum](/images/sLuma-return-arms.png "Polished Return Frame")
Notice the small changes with the *return* frame. 
- [x] Arms are raised
- [x] Eyes are furthur apart

{{< admonition success "Nice!" false >}}
All changes show the *momentum* from the *stretch* frame.
{{< /admonition >}}

Lastly, we'll use the same technique with our starting frame.

### Normal Final
![Momentum](/images/sLuma-normal-hair.png "Polished Normal Frame")
Notice the small changes with the *normal* frame. 
- [x] Hair is raised

{{< admonition success "Nice!" false >}}
All changes show the *momentum* from the *return* frame.
{{< /admonition >}}

Personally, momentum is my most effective way to blend frames together. 

### Results
Easily compare the changes we've made to polish our animation. By applying momentum our character appears more smoothly and snappy, while only using **4 frames!**
![Results](/images/sLuma-spritesheet-final.png "Sprite Sheet")

![Results](/images/luma-final.gif "Idle Animation")

# Conclusion
Thank you for reading my tutorial! I hope you learned how to quickly animate your characters. 
{{< admonition tip "Hey!" true>}}
Press *Ctrl+D* to bookmark :(fas fa-bookmark fa-fw): the page ૮ ˶ᵔ ᵕ ᵔ˶ ა.
{{< /admonition >}}

{{< music url="/music/Duck.mp3" name="Quack" artist=Duck cover="/images/sDucky_stand.gif" >}}