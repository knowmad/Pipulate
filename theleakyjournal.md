# Beginning of Journal
--------------------------------------------------------------------------------
## Tue Mar 20 

    let @j = '/Beginning of Journal^Mo^M^M^M^M^[kkkk80i-^[j! date^Mi## ^[^Mjzzi'

...becomes:

    let @j = '/Beginning of Journal^Mo^M^M^M^M^[kkkk80i-^[j! date^MwwwD0i##^[^Mjzzi'

It's really that simple. Changed highly detailed timestamps from the Unix
(Linux, of course) "date" command from highly detailed to just:

    Tue Mar 20

...with the addition of:

    wwwD0

...somewhere into a macro, which I keep in a .vimrc file, which I keep in a
repo called vim in a public github repo so that I can pull it down from
anywhere, get the idea?

As an added bonus, if I leave my cursor at the top of the pipulate version of
the journal, when I switch to it with a :bn (for buffer, next in vim-speak) I
know just hitting the p for paste and then saving it, and then going back to
the top of the document and hitting :bn again sort of "stages it" both to be
published on the next inevitable commit and push of changes to the Pipulate
project from this machine, but it's also staged for the very easy publishing of
my next bit of stuff. No fancy system-building. Just one file in
/usr/local/sbin so that every time I open a new terminal, I can just type:

    j[Enter]

...and have both journals loaded for easy permission-controlled publishing, yet
all from just vim and git. No graphical OS really even required here. This is
less than wristwatch-level power you're requiring here to host your
journal/publishing system... for life. Just add Internet connection and common
free stuff.

--------------------------------------------------------------------------------
## Tue Mar 20 11:06:48 DST 2018

Okay, I have a lot to do today, but first it's time to eliminate accurate
timestamps in my private journal macro. It's been attempted to be used against
me even one little bit, so it's gone. But none of the actual benefits of the
journal itself will be gone. Nope, rather my loud and very distinct inner voice
is going to not be talked-over, and it's going to go, yup. Solution provided. I
control the timestamps. I control the reality. Timestamps are only as accurate
as the day's date. Morning, night, who knows? There's some sense of linear
sequence, but I think out loud a lot on my lunchbreak and on the subway now
with my Surface Book 2 laptop, where I can work anywhere quite well to be
always-there, always-on and at my own expense for the best laptop in the world
right now available-- although middle-of-the-line, because I'm not made of
money. I just like my tools. And I think I need to assert myself from time to
time to keep this situation and the opportunities here viable, and me free off
all the signs of burn-out that have already set-in after just 2 years. Nope.
Fix or leave. Fixing begun. Timestamps...

--------------------------------------------------------------------------------
## Tue Mar 20 

Beginning of... oops can't type that or I'll mess up my Macro. Time to get
a'crackin'. My mission today is this SQL Query thing to go back a year ago in
revenue numbers... wow! I should of done that yesterday... or maybe even
Friday, but wow. The office move, the new laptop freeing me to work anywhere,
and all the settling in, which is... oh, let me tell you about it! But wow, can
I do some cool samurai data moves on that thing now. I need a more full-time
built-in WiFi, and I was hoping for... wait! I'm going to publish this. I know
that. This is a critical part of the Datamaster journal-- calibrating one's
tools for maximum effectiveness under all the conditions you're likely to find
yourself in. For too long, I've used old Mabook Airs... 3 of them, to be
precise, haha! I have 2 now still myself. Gotta set Adi up on one, but they're
so old-school: no touch-screens and high-res artist's stylus. What's that you
say? Neither do modern Macs? You've got to be kidding, that's got to be a
joke... what? At least their Phablet has a Stylus so that Differently Thinking
Artists can... what? No stylus, either? What happened? Does Apple still
exist... oh, a consumer goods company yous say? Maximum profitability, sheep,
Jobs is dead and all that? Okay, got it. Still wearing my Apple Watch and
making the SE my wallet-phone. The NYC 212-NYB-1337 number is getting ported to
the Note 8, because I needed a phone-number as cool as everything else in my
life, now that my transplanted roots are really beginning to set in... here...
in New York City, where I live with the best view of it right on the edge of
Staten Island. I've finally gone UrbyLife.

Okay, I still have a little publishing resistance because there are some
annoying kung fu keyboard moves of loading another file on a different path
into the second vim buffer. I can totally do it, but I'm fatigued just thinking
about what that would take. 

    The light! The light! 
    The lite, the lite, the lite.
    So, fight! So, fight! 
    And fight and fight and fight.

Even on this floor, there will be big-time mental distractions. The sound of
your inside voice has to be as loud as the chatter, or else people won't
realize their chatter is a part of your background noise while you're trying to
work. That's okay. That's the cubicle deal. People type, and I'm using a very
high quality keyboard, thank you very much. And I shouldn't HAVE TO try to
drown it out with headphones blasting music into my head, and I'll damn-well
talk about it as a focus and survival strategy for creatives in the cubicles of
modern business, readily. It's a fine topic to discuss, especially at the very
moment it's an issue, and you need something as your ohhhhm to regain center,
and get back to some important work.

Okay, there.

Now where were we?

Oh yes, make it so that publishing this will be nice and easy from here on out.
And that means either a something.sh in your current directory (which you'll
never be quite sure you're in) or putting it somewhere in your path, and
chmod'ing it to have +x permissions (execution). So, this is your second step,
because it is true, everything is a LITTLE BIT difficult. They used to joke
about Unix that that was intentional to make an elite class of techs, and well
yeah, sorta. It's called smart enough to appreciate inside jokes, and it's
important in the Unix world, which WAS a priesthood even though its progenitors
were badboys, because of the great commercial and proprietary potential of Unix
to vendors like AT&T... and Novell... and SCO. Oops, proprietary was something
special, was it? Not when it's the commodities, and basically free because it's
only already-ripped-off data, because it's digital data. Blackbox copying has
inconsequential cost, which is what Linux and RMS did. So...

So, bash shortcuts in sbin. Sbin is a funny thing. It's supposed to be these
tiny little one-off script files that you plan to use a lot, and they're still
usually script or bash or shell files. They're all sort of the same since bash,
the "Bourne-again shell", became so durn popular. It's got to be more than just
the basic vanilla Unix "shell" with no command-line history or completion, so
everyone at least uses the first mega-popular one that nothing else ever quite
displaced. So, the language flavor of Unix scripting you should be using is
bash, and they usually just have a .sh extension for shell.

Okay, getting there might take a little while but the payoff is enormous. This
entire seeing the sausage factory process of permanently improving my
day-to-day workflow is being exposed here in the Pipulate repo for everyone to
see... haha! But the world is different forever once achieved. Everything
hinges on moments like these, such as the next time I want to publish like this
won't be anywhere near as difficult.

Keep my go/zd gnu screen session going that shows my every 10-minute heartbeat
after the daily regimine of scripts stops running... or really is just paused
waiting for later in the day when the speed-checks begin, so it gets a fair
assessment of the speeds of different sites (can't run that during the night).
But that report will probably be changing now that Google has an site speed
check now for almost precisely the same scorecard type thing. So much I can gut
and take a sawzaw to, and build newer better stuff to replace it... easily and
more easily than maintaining the old stuff, and that's like one of the big
points about having an employee like my. My stuff is only built to last for
about a year until realities change. Lean into that. Allow scrap and rebuild to
occur, but don't keep me playing little dutch boy and the dike. If a dam's
going to bust if left unchecked and I've said so a lot, then I'm just going to
let it bust. I'm not paid enough to keep old dams from busting AND building new
ones. That's a losing proposition, so I've got a plan.

That plan is sbin.

Gotta always remind yourself of the location. 

It's an odd incantation, but this is it:

    echo $PATH

9 times out of 10, it's going to be /usr/local/sbin and it's going to be the
first thing in your path. Understand that, and you're going to understand a lot
about Unix and Linux. The next step, I'm going to tell you to do in vim as your
frustrating and fateful first encounter with the big green monster. Wanna be a
badass tech always packing sharp quarrels in your quiver that'll really make
'em shiver when they see the kind of tech who is really good as heck. Oh, I
don't even need a .sh extension.

    sudo vim /usr/local/sbin/j
    :i
    vim /home/journal/index.html /mnt/c/Users/whome/github/pipulate/theleakyjournal.md
    [Esc]:wq
    sudo chmod +x /usr/local/sbin/j

Left out some details like how you should hit enter. Wave. Quit... tested! Wow!
Now, go publish this shit.

--------------------------------------------------------------------------------
## Fri Mar
### Getting down the rhythm of the Pipulate workflow

You lost the flow. Time to re-establish. These things are taking you wayyyy
longer than they should. I've got idea... I'm going to change my vim macro to
only give the day in the timestamp... hahaha! Only the day is important to
anyone who lacks the ability to see when the git commits occurred-- hahaha!
Wow, I've become a tech asshole. You people have to watch me. I really don't
want to become what I hate, those Green Arrows can eat my Blue Beetles. But not
until after the work-and-hand is done. So far, we have...

- Templates are for purple cows
- Whipping docs get nuked for morbid
- Copy from a Pipulating GSheets (create consistent compelling language here)
- Copy from the Purple Cow farm.

Now, you've got Whipping Doc with no more tabs than what you absolutely need...
not quite true. One blank sheet may still be in there, which you can delete
because you don't need anymore.

Good language developing: "Oh yeah, that's a pipulating sheet. Don't reorganize
those columns (or do) because that's pipulating live. It's a pipulating live
pipulating sheet. Don't pipulate with me, I'll pipulate your pipulate.
Recursion limit reached."

Okay, recover state...

- NOW ADD NEW TEMPLATE COLUMNS INTO LOCATION

Ah, Newspace! A purple cow in the cow farm need not a column or row more than
it need. It should indeed be pruned so you can click the copy-whole-spreadsheet
magical place in all spreadsheet software. That is VERY GOOD. This is the sort
of non-system system invention that Pipulate should be built from. Just know if
you do these such-and-such obvious-in-hindsight things (trimming unnecessary
rows and columns) everything will go more smoothly in your Pipulate workflow...
something that is very worth getting worked-out just-so because of the
effortless mastery things like fixed-position brings to them over time. Every
fixed position where you can re-acquire home and recalibrate and regain state
real quick is a treasure.

Newsflash: Conditional formatting doesn't copy-paste even with "Paste special"
between sheets. Consequently, there's definitely got to be a lot of
right-clicking on tabs to "copy them into" other sheets. That seems to preserve
it, but there's none of the required formatting in my Purple Cow Farm template
tab, which I realized late in that project. And I fixed it in the Whipping Doc,
but I have to copy it back from the Whipping Doc to the Purple Cow Farm... wow,
this is going to work.

Okay, confirmed. Copying sheets through GSheet's "Copy to" on the Tab's menu
preserves the conditional formatting... pshwew! Purple cows can stay purple.
Oh, always color-code a the tabs in The Purple Cow farm purple... color coding
is going to be some powerful stuff in this non-system system.

--------------------------------------------------------------------------------
## Fri Mar

Okay, when doing new work, the work-rhythm looks like this:

Make sure the Purple Cow Farm has your template checked-in (so to speak).

Nuke your whipping-doc for morbid. Know 2 things are about to be zapped into
there. You are merging 2 source-documents:

- Your live-deployed GSheet that's back-ended by "scheduled" pipulate.
- Your template from the purple cow
- Copy-to Recent from the "Tab" menu in GSheets is going to be a common thing.
- Once a tab is copied that way, it gets renamed to "Copy of [Old sheet name]"

--------------------------------------------------------------------------------
## Fri Mar 16
### Blank The Whipping Doc for Morbid. It's the only way to be sure.

Okay, now down to business... again. And this time for real. This is very
serious business. But my distractions were in forming a very focused mental
model for this type of work today and FOREVER FORWARD MORE IMPORTANT THAN IT
LOOKED distraction. Tired of leaping for peanuts.

Speaking of speaking my mind. I know it's probably politically incorrect, but a
WORK-IN-PROGRESS document is a whipping doc. It's got a very powerful concept
there. You can blank the whipping doc. It is wise to blank the whipping doc, in
fact because if you have a Purple Cow Farm with your format in it, All other
instances than what's live in-scheduling will just muddle don't force a rhyme.
vim out!

--------------------------------------------------------------------------------
## Fri Mar 16 
### If I Saw a Purple Cow, I'd Pick Out a Good Nickname

Time is an illusion. Okay, Purple Cow Farm in-hand, we have a solid "from"
place, once our template-work (sculpting light) is done in whatever, wherever
format woo hoo everything-independent where we can be. We copy all that
artistic header-area stuff of the WORK-IN-PROGRESS document (anything, anywhere
like Excel or another GSheet) into the Purple Cow document. You ALWAYS include
the first data-row, which is the row usually immediately below your frozen
title rows. There's some ambiguity around what we call this area, but I'll use
header for consistency with typical office-speak. So, we put the complete
header and first data-row into its own tab in The Purple Cow Farm. Things line
Red/Green color-coding rules get carried in that first data-row, so it's really
important. I wouldn't try blanking the data in there, or you're in for all
sorts of accidental formatting-loss issues. Just assume all the data in Purple
Cow is for-position-only (FPO). Okay... now we have a destination document.
It's where we "blend into" and should be the SAME as your work-progress
document, so you don't have to be giving out new Google Sheet URLs all the
time. Even the SEO in me screams out no to that concept. WIP (work-in-progress)
documents should get good strong nicknames and have a long life as such a
kooky-nicknamed thing... until you rename it for a demo to a stakeholder who
doesn't need to see it by that name. But then, it's almost an inside joke that
it's really the such-and-such document, because you've touched them on an
emotional level with a just-so-perfect nickname...

And that my friends is SEO. Walk the walk so you can talk the talk... be DEEPLY
engaged in the game by partaking in all the plentiful Noosphere being created
by every move Google makes... every step it takes, we'll be... oh wait, it's
watching us... nevermind.

--------------------------------------------------------------------------------
## Fri Mar 16
### Just Invented Purple Cow Farms for Templates

I just hit on a very, very powerful method. Why just use one journal in vim
when you could be using two! One of them in a private git repo and the other in
a public Github repo, but with no special effort taken to format or publish it,
besides naming the file with a .md extension and putting it in the parent
directory of a repo I think I'll be driving a lot of eyes to and think I'll be
able to turn this into a good lesson in iron bars to not a prison make nor
cubicles a circus. Minds both intent and focused can still squeak out a
workplace. As non-technical people suspect and sometimes fear, the shell-game
in doing very advanced-seeming stuff in tech requires a lot less actual work
than what it appears. But that cover of being busy and stressed-out and always
intently working on something is very important. Mechanical keyboards that you
can feel click under your fingers is important too. Get into the zone whatever
way you can, and if that means throwing up a shield of better not interrupt,
then so be it. 1, 2, 3... 1? Templates are PURPLE! MAKE YOUR PURPLE TEMPLATE
DOCUMENT. A purple cow farm. HAHAHA! You sometimes look for the proper amount
of ridculoustemity in your nicknames. Ohhh, push this out.

1, 2, 3... 1: Go find your Purple Cow.

--------------------------------------------------------------------------------
## Fri Mar 16

    Different rhymes for different times
    And if you don't renew 'em
    From time to time, you'll fail to climb
    And fall down in a ruin.

    Purple is for templates now;
    The other colors taken.
    Make them be your Purple Cow
    To never be forsaken!

    I've only got one document
    That's named The Purple Cow Farm;
    Templates-tabs-- from there are sent
    With minimum of brain-harm.

    The Purple Cow will teleport
    The columns where they function
    While you try to stop a fork
    Off version we be junkin'

--------------------------------------------------------------------------------
## Fri Mar 16 

Make donuts. 1, 2, 3... 1? Source Templates! It's all about reflecting the
right light with the proper incantations. Everything will shine through your
Google Docs templates, which you really should set up ahead of time, because
although you CAN apply some formatting with PyGal which apparently doesn't use
GData but something else more formal under the Developer Console (GData is so
old it predates API-unification under-console). I need to get this stuff out,
because it's important about Pipulate. Getting started on a project in the
morning where ambitions are high because they realize the: if Data Samurai,
then following views we've never before been able to consistently:

- produce
- make readily/easily available
- yet still secure the data

...that one would thing should easily be possible. It's not. But I'm here to
solve that. You're gonna have to drink some Koolaid, so ya had better get used
to it. What, you think Google is going away? What, you think the search game is
going to be disrupted because of some AI-startup? Forget it. A 10x early-mover
advantage in this game is exponentially more than you think. Thinks are
learning and those learnings are persisting and trickling out all over have its
input improved from all over the place... not human by a long-shot, but a damn
bigger chasm that newcomers need to cross than you can imagine.

So, why even try.

Different game, lads. I'm in a different game, with what I hope is another 20
years of exploi... ahem, exploration left to do.

Forget the #xbook tag. Just publish in the Pipulate repo. This is what you were
born to do. vim out.

--------------------------------------------------------------------------------
## Fri Mar 16 

I'm just kidding. I won't leak. But I'll probably sanitize as I type so that
when I copy/paste daily journal entries over here, I won't have to do much
editing. Consider this a history with the most recent thoughts posted as an
entry at the top. Let's make up a word for this... oh, it's on the web, and
it's a log. I know! Let's call it a blog. And here's my first copy/pasta...

--------------------------------------------------------------------------------
## Fri Mar 16

1, 2, 3... 1? List.

You will have various 1, 2, 3... 1? List's in your life.
https://docs.google.com/spreadsheets is one

This is because Google Sheets is 80/20-rule good enough. And I will go into
that a lot more soon. In the meanwhile, I'm thinking to myself how this gets
published and pushed out in a reasonable way, and I'm thinking to myself, the
Pipulate repo, dumbass! There's going to be some eyes on that thing, and this
maybe forever forward in the quite interesting by now never-rebased but
definitely should have been but keeping it that way for more badassitute oughta
watch my mouth paid my dues on Jupyter Notebook now and appreciate what I've
got because... Flask version of Pipulate... OMG! I needed nested bubbling
yields used generically through Pipulate-compatible functions if you wanted
that twinkling UI-feedback that could be sent on the same response that was to
the original page-request, just don't stop building the page and use that no
ajax webserver tech required cause it all uses the highly compatible magical
capabilities of modern browsers to pull it off no JavaScript libraries required
genuingenuity. BAM. Should'a started that project on Python 3 where yields
actually could nest and bubble. Oh, but the complexity, and the trap had it
really worked well... would not be on Jupyter Notebook today really
appreciating it for the miracle the iPython and Continuum.io people really
pulled off there.

Okay, that was my "I am a true Samurai-repurposer of tech once I've aquired it
old'skool real. Oh there I go again with hyperbole. See! I can't even just say
hype. Well, that's me. Welcome to full-on corny nerd. And it's going in right
here, because performance art. Bust-out-ittude and other crazy made-up SEO
words because that's it. I'm an SEO. I'm here to walk the walk while I talk
the talk, and if you're not out here doing something interesting on Github,
then you're not out here. STOP! Reports checked. Now, bake donuts. Recover this
state. It is important. vim out!

--------------------------------------------------------------------------------
## Fri Mar 16 

It's time to bake the donuts.

No, first check the reports!

And get into the mindset of santizing this again as you write, timestamps
removed of course in a time-displaced published version... who knows when this
occurred unless you're reading over my shoulder. Oh, permissions and
securities, and the philosophy behind your thoughts truly being V for Vendetta
versus eventually enough on the Cloud... well, whatever.

For now, we check reports then bake donuts... then stop and survey the
landscape.

- What's most broken?
- Which work gives us the most bang for the buck?
- What plates need spinning (think about 3rd or else there goes your day)

--------------------------------------------------------------------------------
## Thu Mar 15 

Might as well be on the best. I want to be on the best hardware of my life
while I'm doing the best work of my life.


