#																										HelloWorld!

This is my configuration of i3 window manager.

Firstly I would like to tell you why I decided to use i3wm. Well it is because of it is simplicity 
and productivness and also of it`s really low RAM footprint. When you first start using i3, it might be a bit "bumpy"
because you don`t get you usual kind of looking window with big border on top and buttons (quit,minimize,maximize).
You might be also confused with the fact that your new window get right next to each other and it does not float 
(you can get floating windows by i3 but not defaultly).But after fewhours you get completely used to it and your 
fingers will be flyoing across your keyboard for keyboard shortcuts.

I encourage you to watch this video https://youtu.be/j1I63wGcvU4 and also to read user guide on i3wm.org. 
User guideis bassicly describedin thefirstand second video,but is deffinitely worth reading it. 
At least you get to know al of the keyboard shortcuts and what is i3 really capable of.Those videos 
get me really inspired and so, my config file is bassicly a copy of the one used in the video. I`ve only 
changed few things, most of them was just tofit my screen resolution 1366*786. 

I`ll be glad if you use my config. It would make me feel, that I helped someone. 
But if you want to use it you need to do few things first, because if you just replace your config 
with mine, your i3wm will be completely messed up. 

#	1. Fonts 
		You need to download and install fonts from my .fonts directory (installation is in ReadMe file). 
		If you dont want to use SanFrancisco display font, you need to 	replace it with another font (default 
		is monospace).
	
#	2. i3-blocks
		I3-Blocks is replacement, or addition for i3-bar. Bar is the bottom panel. To use and configurate it,
		you need to download i3-blocks. I think that most of distributionshave i3-blocks in their repositories 
		(if linux-mint does, then every distro does). Defaultly i3 uses "feature" called status, which in my 
		oppinion is not very useful. For example it does not show volume level, or if you are on 
		notebook battery status. i3-blocks does. So it`s better to use this instead of i3status. 
		More information in ReadMe file in etc directory. 
	
#	3.Rofi 
		Rofi is used as replacement for D-menu. As in video said, D-menu is not as easy to customize as Rofi is. 
		And Rofi looks Waaaay more niccer and interesting than D-menu. To download Rofi just look at 
		their official site https://davedavenport.github.io/rofi/ but some distros got rofi in their repos. 
		My rofi is configurated for my screen resolution which is 1366*786 but you can easily change it to yours.
	
#	4.Compton
		Compton just enables opacity of windows because i3 does not defaultly support opacity on windows. 
		To do this just install compton from repositories or https://github.com/chjj/compton.
		If you done all of this, there are few more things to do. Changing font in gtk applications, gtk 
		theme and icon theme, maybe installing few more applications or disabling them in i3config. 
	
#	Theme
		I am using arc-darker theme. I liked this theme since I firstly used SolusOS. As in video, same 
		theme is used.Collors are same as the collors of arc-darker theme. To install it, just follow 
		these steps https://github.com/horst3180/Arctheme. You can install firefox theme if you 
		want https://github.com/horst3180/arc-firefox-theme.
