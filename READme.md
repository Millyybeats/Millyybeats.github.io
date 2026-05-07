#Millyybeats Website 

This is how I approached building my website using html and textmate. 
Claude helped me out alot for this project. I first started out by pasting Rachel's website html code into claude and told it to break it down line by line so I knew 1. how to edit the code to make it my own and 2. to understand what each line is doing. 
Then Claude explained what every line of code is to me. For EX, here is Rachel's Code
<!doctype html> (what type of file this is (HTML))
<html lang="en"> (language of website)
<header> 
<meta charset="UTF-8"> ((Sets the character encoding so special characters (accents, emoji, etc.) display correctly.)
<title>tabby cat</title>
<link href="styles.css" rel="stylesheet"> (HREF is basically telling the code what to lead. For Ex. if it was a link you need to put what is writting on line 27)
<script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.11.1/p5.js"></script> (the script lines load something from another server and display it here. P5.js is used here so we put <script> to load that server)
<script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.11.1/addons/p5.sound.min.js"></script>
</header>
<body>
<h1> (HTML uses different header levels h1 being the biggest(which is usually the main title))
good afternoon, 261!
</h1>
<p>
  <h2>yooooooooooo</h2> (h2 smaller than the main header that is h1)
  <hr />
  <div>
  <blockquote><b><i><u> "meoooooooow" </u></i></b></blockquote> (blockquote shows the lettering "meoooooooow" on the website with the U, i, and b, menaing italic, bold, and underlind)
</div> (Line breaks on the website)
  <br>
  <div>
  <a href="http://racheldevorah.studio"> my real website </a> 
  </div>
   <br>
  <div>
  <img src="oprah.gif">
</div>
    <div>
<ul>
		<li>corn</li> (LI is for list which makes bullet points in the website. I am still not sure why you can't just type the bullets out and just write it out)
		<li>squash</li>
		<li>beans</li>
</ul>
</div>
<br>
<div>
  <audio controls> <source src="mtec343.mp3" type="audio/mpeg"></audio> 
  <br>
</div>
<div>
	    <script src="orbits.js"></script>
</div>
</p>
</body>
</html>
The most tedious thing about coding in html was the fact that every single line needs a closing and opening. The opening  <???> and the ending </???> with a / right after the <. This has to be on every single line or else the code won't know when to start or end. It's very important that the first line is open <html> and the last line is closed </html>

But now that I have somewhat of an understanding I starting using Claude to give me the blueprint for my website. (ALL SS ARE ATTACHED IN THE WEBSITE CHAT FOLDER)

I asked Claude to make me a portfolio website that showcases my services as well as some of the songs I produced and some of my sound design projects. The first website it created was very interactive, but I wanted to keep the minimalistic design of Rachel's website, but with a little more razzle dazzle. The finished product I wanted was a minimalistic website that had an "about me" section, a "production" section that has a paragraph about me, a "contact" section that contained an email form, and a "sound design" section that has embedded videos of some of my student projects that I had done at Berklee that showcase my sound design/foley skills. 

ALL MY CLAUDE CONVERSATIONS ARE INCLUDED
I had claude make and explain how to embed youtube videos within the website which was very different than my embedded videos from my computer which I also had to do. To do this it created lines such as   <div class="video-row"> and <div class="video-block"> which create divider/headers with an action video-block which creates the outline for what needs to be embedded. Then, these lines src="https://www.youtube.com/embed/Ca7GTTZ49_k" actually link the video to that embedded block dedicated to the video. I repeated this 4 times for each song I wanted to have on the website. 

Then for the embedded videos that were mp4 files on my computer, it created more <div class="video-block"> for the outline then it made <source src="video2.mp4" type="video/mp4"> This is so that whatever file I named video.mp4, would show up on the website as long as it was in my github folder with my index.html file. I did this 2 more times for each video I had. 
	
For my social media links, Claude made these lines of code where then I put the actual links of my pages in. <a href="https://www.instagram.com/millyybeats/">Instagram</a> |
    <a href="https://soundcloud.com/millyybeatss">SoundCloud</a> |
    <a href="https://youtube.com/@millyybeats">YouTube</a>
The a href just creates the link that say Instagram, youtube, etc, and when those are clicked they bring you to my pages. 

Lastly for the email form, I had to use Formspree, which is a website where it basically embeds the code of your form to be able to work within your website. AGAIN COVNOS ARE SS. 

And boom, my first html website. Now whenever I wan't to update or replace things for my website I always have this html file to edit. I pushed it to github and now my wesbite is public under "https://millyybeats.github.io/"   

