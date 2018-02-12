---
templateKey: blog-post
path: /soldering-my-first-keyboard
title: Soldering my first keyboard
date: 2018-01-16T03:04:10.000Z
description: "The first task I set for myself in 2018 was to solder my own custom keyboard. Typing this post on the keyboard now, I can say this task was a massive success. \U0001F60D⌨"
---
# Why solder my own keyboard?

I've used many keyboard over the years, each one bought usually to deal with the frustrations of the previous keyboard. My first "weird" keyboard was this - a Wolf Claw keyboard. 

![Wolf Claw](/img/wolfclaw.jpg)

Weird as it looks, I found it incredibly comfortable to use - the giant vertical space bar on the left made jumping in FPS games easy, the curved number row made weapon selection easy, and in general was a fantastic FPS gaming keyboard. Except for one problem. When playing games, I could not press Shift, A, W, and R all at the same time. Or more specifically, if I was running diagonally in Counter Strike, I could not reload my gun. That frustration led me to start building a list of requirements in my dream keyboard. One keyboard that I would never want to replace, and keep until my dying day.

## 1. Must have NKRO

![Filco Majestouch Ninja](/img/filco_majestouch_ninja_black_us_large.jpg)

This is a mechanical keyboard with NKRO - that is, you could press any number of keys and it would know what you pressed. In addition, I deliberately chose a keyboard with the legend printed on the front, with the thought that I would use the keyboard forever so the legend would last forever. Boy I was wrong about that. The legends did indeed last, but looking at them was frustrating enough to drive me to sell this keyboard. That, and the next problem:

## 2. Must be quiet

My first mechanical keyboard led me to discover an overwhelming problem with mechanical keyboards - nearly all of them are loud. I received complaints from colleagues and coworkers about the noise almost immediately, which was not acceptable for me in a supposedly perfect keyboard.

## 3. Must not have input lag

In my zeal to find a keyboard that made no noise, I found this rather lovely looking keyboard.

![Logitech K810](/img/logitech k810.jpg)

It seemed almost perfect - it looked great, it was quiet. But I'm an avid gamer, and quickly found it had a slight delay, which was enough to cause me to make mistakes in games. With any other keyboard, I could press a letter then click with my mouse, and be sure the mouse click would be received after the keypress. But with this keyboard, all too often I would press a key, click my mouse, and find that the game received the keypress AFTER the mouse click. Completely unacceptable. This keyboard is now back in its box in my wardrobe.

## 4. Must be programmable

I thought I had found my dream keyboard, the iGK64.

![iGK64](/img/img_20171107_233321.jpg)



## 5. Should look fantastic.

Some time around 2010 I discovered online photos of people's amazing office designs. I've paid close attention to people's clever ideas in those setups since then. But in particular, I was struck by this design:

![Wood and leather office](/img/wood and leather.jpg)

In particular, the use of two primary materials - black leather, and dark wood. I decided I wanted the same for myself, but that I'd improve on this design by having a wooden keyboard atop a black leather desk mat.

So with all those requirements, it was time for me to find a keyboard that could actually meet them. As it turns out, there is no off the shelf keyboard that can do all of 

# Building the dream keyboard

## Planning

## Assembly

## Programming

Wasted absurd amount of hours following group buys, even bought and sold a iGK64

Ordered keyboard long ago

Went to keyboard workshop

Made QMK firmware with qmkeyboard.cn

![Layout builder on qmkeyboard.cn](/img/firefox_2018-02-12_08-00-51.png)

Now that I had made some firmware, I had to flash the keyboard with it. This took more Googling than I care to admit, but in the end it required me to do the following:

1. Download and install QMK Toolkit
2. Unplug my keyboard, press and hold Spacebar+B while plugging it in again to start it in bootloader mode
3. Open my firmware in QMK Toolkit, then hit Flash

![QMK Toolbox, after successfully flashing my new firmware](/img/qmk_toolbox_2018-02-12_07-56-35.png)

# Next steps

As much as I enjoy this keyboard, I still have not achieved my vision of a perfect keyboard. So what's wrong with it?

## My keycaps look cheap and goofy.

I find it hard to read the legends on this one and the mismatched heights are annoying me a lot. So I'd be looking to buy a replacement set of keycaps that will last a long time. Something like this:

![MiTo DSA keycaps](/img/md-9678_20151105105359_83ce8bc132116eb3.jpg)

## Pressing the keys feels slightly rattly or scratchy.

This can be solved by lubricating the switches and stabilisers with industrial lubricant - an IMMENSELY time consuming exercise. I've heard people also talk about "snipping" stabilisers, and upgrading them to "screw-in stabilisers". I don't know what this means but if itmakes pressing my Spacebar/Shift/Enter nicer, I'll do it.
