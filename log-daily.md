### 2025/01/26, Sun. ###

• 1840. Secured this account with MFA; very easy to do.  I used the \
tutorial/introduction pull request/clone tool; cool but not my style. \
Now I understand the web GUI, it is time to return to my beloved terminal. \
I’ve forgotten how to use git twice.  Developers have a reason to use git, \
but I’m not a developer; yet! \

I’ll start with bujo (bullet journal system).  I can write and that’s \
all I need to start with git.  I wanted to use the *unicode bullet* for my \
bullet journal.  After some research I now know the process of typing unicode \
characters on the fly verses copy/paste from the character map program like \
an animal. \

First, use key combinations `alt` + `shift` + `u`.  Now type the code `2022`, \
then press `space` or `enter`.  In my 1950’s console guy voice, “Houston \
we can use bullets”. \

[Alt codes](https://en.wikipedia.org/wiki/Alt_code) \

• 1950. Now I need to research Github’s markdown flavor. I’m currently using  
Pandoc flavor markdown. Github seems to do something strange with the  
hard breaks on lines followed by empty lines. Maybe I’ll use double  
spaces for line breaks, or I could quit guessing and just research Github  
flavor markdown.  
*Sigh:*  The things we do for markdown.  

### 2025/02/02, Sun. ###

• 14:49. Learned about Github flavored markdown (GFM). Follows common  
mark. I changed the license to GPL too. I just wanted to know how to  
change license, not that GPL is better for journal.  

• 15:07. It worked! I'm the greatest novice to ever push buttons  
on a website in the entire **world** (dramatic echo added to  
world). Also I forgot to add the link to the github documentation for  
[GFM](https://github.github.com/gfm/).  

• 15:15. Small format changes to the previous content. I'll leave the  
hard breaks to show visual progress for future Sgoti; he's stupid and  
will need to be reminded.  

• 23:21. OMG, it took forever to learn how to do this from the command  
line! I first cloned my repo from github.com then attempted to see  
my changes made during the (15:07 - 15:15) times. The changes where  
committed/pending and I didn't want to merge using the GUI. Locally I  
changed branches about 20 times `git checkout` trying to figure out why  
I couldn't see the pending changes. Took a break to drink some of my poor  
mans' instant coffee; it simply has to do the job. Now with the taste of  
sun baked tree bark in my mouth I needed to `git` some work done. I read  
over the "Pro git" book some more, attempted some `git fetch` action;  
no luck. Dropped a few magical four letter words then ran a `git pull`;  
this did the trick. I wanted to do the merge manually/separately but  
guess I'll save that adventure for future Sgoti; he's got nothing better  
to do. So in short, I failed my way to success again. Looking forward  
to doing it all over tomorrow. I don't remember if I said this or not,  
I'm doing all of this from the CLI using vim from now on. The web GUI  
gives a better visual on the new information in the branches (scratch-pad  
and quick-notes) but I'll have to get use to it in my home; good ol  
colorful text on a black background. Brain fog is kicking in, time to  
push this puppy to origin. Remember kids if you're going to boink it,  
boink it with sudo! Sgoti:wq  

### 2025/02/12, Wed. ###

• 22:31. Created a Gitea account to work with HPR. Made a PR on  
the hpr_documentation repo. I generated two new keys for the gitea  
account. Added a few aliases to the ol’ `git config` now I’m one  
of the cool kids. Updated my script, it’s a git setup script to make  
all these changes easier/faster in the future. The tiny human was out of  
school today due to snow; drove me crazy all day. I have powerful brain  
fog setting in and I took some sleep aid. These notes are a race against  
the fat old man’s slow metabolism 😁️.  

I just had to find out how to make emojis. I use `ctrl + .` in gedit to  
get the emoji selection menu. This doesn't work in the terminal. There  
are emoji codes like `:lol:` but I’m in no shape to read those tonight.  

I figured out the ssh issue with github, made a show about it, uploaded  
the show and made new ssh keys with my hardware keys for both github and  
gitea. Now I have super ssh powers. I’m not going to proof read any  
of this because it’ll be a wasted effort; brain fog is pretty thick at  
the moment. Time to push this to the public bujo and apply some of that  
good old “hope for the best” medicine I know and love so much. See  
you when I see you. :wq  

### 2025/02/20, Thu. ###

- 18:58 Wow, it's been rough.  Tiny human needed more attention, **SO** handed  
me an eleventh hour task to get a vehicle repaired (naturally this took  
an entire day), and some more crap that spent all my brain points.  I've  
finally got some time to update the LOG.  

First, made another show.  I found Dave's 'The power of GNU Readline'  
series; very well done.  I decided to offer my own experience to the  
series; let the world experience `vi` from the prompt.  Now that I'm ahead  
on shows (one show a month is my current goal), I must maintain ME STUDIES.  
JavaScript seems like a pointless dream someone cooked up then slipped into  
the World Wide Crack Pipe (you thought I was going to say web 🙃️).  
I've seen web technology built to help web-devs get away from JavaScript  
by creating more JavaScript; it's nuts out here.  

I now know that I have made a terrible decision in learning JS, but  
I'm already here.  This journey is like driving one hundred miles to the  
nearest rest stop just to find the only toilet is clogged and filled to the  
point of spilling over, but you **REALLY** have to go.  A man's gotta do  
what a man's gotta do 🫡.  Maybe someday I can use my powers for good.  
Until then, stay strong and carry on.  

**DMARC** is now on my list as well.  I needed to clear up why some mail will  
have `dmarc=pass` and others will have `dmarc=pass(p=none)` or something  
similar.  Looks like **DMARC** has a policy tag that is applied and the tag  
can have three (3) different values:  

    p=none: With this directive, DMARC does not change how email is handled by the receiver. In other words, no action is taken/messages remain unexamined.
    p=quarantine: This policy sets aside questionable emails for further processing, which are usually exiled to the “Junk” folder.
    p=reject: When emails do not come from your email infrastructure, this designation has the receiver outright reject those messages that fail DMARC authentication.

Guess I'll whip up some quick notes on the subject then move them here.  
Holy cow, I made a pun; this branch I'm working on is called quick-notes.  
Git it 😉️.  You look like the kind of geek that would get a joke  
that this.  I'll have to change this branch name later.  Thinking of  
calling it `draft`.  Since I'm one of the cool kids now I should  
use a cool, corporate approved, name for me branches.  So the name  
`drunken-night-writer` is out of the question.  

https://en.wikipedia.org/wiki/DMARC
https://en.wikipedia.org/wiki/TXT_record
https://en.wikipedia.org/wiki/Internet_Engineering_Task_Force
https://www.ietf.org/
https://www.rfc-editor.org/
https://authors.ietf.org/
https://www.rfc-editor.org/rfc/rfc7489.txt
https://datatracker.ietf.org/doc/html/rfc7489

### 2025/04/14, Mon. ###

- 16:24 I've made some progress with podman and my local bujo but failed  
to update here. I'll half to rebuild my public bujo very soon with the  
new changes. I'm not sure if it's better but I'll have to give it a try;  
too much work when into the script, can't stop now. I've got my first merge  
conflict after working late one night. It's with my blessed_configs project  
(here on github). I tried to to maintain a local branch with my personal  
changes and keep 'main' as a boilerplate. This may not be possible or I'm  
doing it wrong. I have to fix it then create another project directory  
(locally) to hold my personal changes to the blessed_configs.  

EOF

