# Tomomi's Portfolio Website


# Aim

I set my theme as "Modern Japanese", because:
- It expresses my background 
- It is simple, yet not too formal, elegant but has a touch of quirkiness ― exactly the style I love.
- Used square, thick, geometric style to avoid looking too "kawaii" (means innocent and girly in Japanese).


# My inspiration comes from:
- Japanese food package design
- Japanese anime
- Japanese card games – [Hanafuda](https://en.wikipedia.org/wiki/Hanafuda) and [karuta](https://en.wikipedia.org/wiki/Karuta)
- Taisho era (1910 ~ 20s) inspired art
- Yumeji Takehisa

# Design Process 1 – Mood board
I chose to use Pinterest because it lets me pin any images around the internet.  
<br/>
<br/>
![Pinterest](https://raw.githubusercontent.com/okichan/portfolio_v2/master/assets/pinterest.png "Pinterest")
<br/>
<br/>
[View Tomomi's Pinterest](https://au.pinterest.com/madeinwatashi/japanese-modern/)
<br/>
<br/>

# Design Process 2 – Font selection  
#### First I went for traditional brush script.  
![Kaisho](https://raw.githubusercontent.com/okichan/portfolio_v2/master/assets/kaisho.gif "Kaisho")  
But it felt too traditional and there's no modernness so did not choose it.
------------------------------
Next I found this one.  
![Mameron](https://raw.githubusercontent.com/okichan/portfolio_v2/master/assets/mameron.png "Mameron")
It was not bad, but it felt a bit too nostalgic and mellow which does not quite match the look and feel I wanted to achieve.

------------------------------
So I tried this one next.
![Wadaken](https://raw.githubusercontent.com/okichan/portfolio_v2/master/assets/wadaken.png "Wadaken")

and I finally am settle in this one, this font is geometric and a little sharp which I thought gives the modern touch I was looking for. Also I wanted to treat Japanese characters more of a symbol rather than actual text (not many people can read anyway!!), I though this one does that job too.

# Design Process 3 – Figma
The one at the top was my very first idea which I quickly got bored.
<br/>
<br/>
![Figma](https://raw.githubusercontent.com/okichan/portfolio_v2/master/assets/figma.png "Figma")
<br/>
<br/>
[View Tomomi's Figma](https://www.figma.com/file/HSQQXVgZZxc1hClYtX8x0IWr/Portfolio)

# Technical challanges
- I was struglling to place all the frames in a place I want. However I start to have understanding of what `relative` or `fixed`, `absolute` does, although I still tend to choose one hoping for the best.
- Text rotation to vertical. Some texts flied to nowhere when all I did was just rotating it.
- z-index. Apparently it all has to belong `position: relative`?



# Lessons learnt:
- Preparation is (almost) everything.
I was recalling myself Abraham Lincoln's quote, which goes as follows:
> **_"Give me six hours to chop down a tree and I will spend the first four sharpening the axe."_** 

This was so true, I spent majority of hours desiging in Figma and the actual coding part was pretty smooth.
- **Edit your file in local unless you know what you are doing!!!** <br>
This was my official effed up moment.  
I once wiped out my 5-hour work of `readme.md` because there was a conflict between local file and remote. And I force overwrote my latest one saved in the remote with the old one saved in the local by doing `git push -f`. <br>
This happened because I kept editing my `readme.md` in remote repository directly.  
I did create `.gitignore` in my local to exclude any `.md` files but it wasn't working for some reasons and thus `readme.mb` was pushed to remote when I only meant to push other files. Screw me.


