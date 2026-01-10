+++
date = '2026-01-10T16:18:21-05:00'
title = 'Criticism of Wayland'
+++
As this new year starts, I decided to continue writing stuff on my website. I guess this can be called a "blog" or something, but in general I hate that term because it kind of connects websites to social media in a sense which I really do not like. But I will not be talking about that in this post, I will just be doing some technical talk in comparison of my experience on Wayland and the other "old" display server every Linux or Unix-like system user knows which people usually call Xorg/X11/xserver and the related.

# Hyprland

A lot of new people for some reason decided to follow some YouTuber's footsteps who is not even a YouTuber anymore and switch to Hyprland, now there is a perception of Arch Linux being Hyprland "only" for some reason. Either way I decided to give it a shot and it was quite good, but I really hate animations. Turn them off then? So I did. It is nice to have options but it still has very big differences that I will probably never get used to, or refuse to accept. This is still however the closest best option I have, and it is definitely the best window manager right now.

# Sway

This window manager or whatever Wayland people call those "wayland compositors" is basically i3, it has no dynamic tiling. While I used i3 in the past this was not a "drop-in replacement" my config did not work fully and I had to change some things, either way it is absolute shit and I grew out of i3 because I cannot do manual tiling anymore.

# Wayland

Wayland in general is way too different from Xorg, due to how the protocol is implemented there will always be a mouse sensitivity difference between them. There are many other things that are extremely different, but they all add to the complications of both of these servers. This brings us to one point, everything always repeats. When Pipewire came around, not everyone switched from Pulseaudio, and even if you do switch a lot of programs still use Pulseaudio they just run through a layer like pipewire-pulse, this is the same with Wayland with their xwayland layer. Wayland might be better than Xorg but I simply do not care for that, I used a lot of different window managers for Xorg. I am now using DWM which currently does have a similar option called DWL in wayland but it is currently not being updated. 2026 is definitely not my year for Wayland and for a lot of people it will not be.

## Criticism

Wayland will not have a lot of window managers or as they call them "wayland compositors" because it is way harder to write them for Wayland, the documentation of the protocols and functions is absolutely terrible. You have to implement a lot of things from scratch when you are writing a compositor and a window manager, and yes you have to write them both because it is a "wayland compositor" after all. Just to be clear, I do not really hate the protocol but it is implemented very poorly.

# Conclusion

I am not using Wayland.
