#	Plaid CTF 2020 Web

This repo is the backup of Plaid CTF 2020 web attachment.



##	Catalog (500pts 0 solves)

###	Story

> Having thoroughly explored the anime section of the HQB Multimedia Library, you decide to venture on into the other sections. Next on your list is a section of comic books.
>
> You've flipped through a few of the issues available, but they all seem like the standard fare. (Even if there's some really rare stuff in here—not that you'd expect *Action Comics No. 1 or Detective Comics No. 27* to be worth all that much in virtual form.) As you look around, one empty space on the shelf has catches your attention. There's an open spot for a series called Plaid Comics, which also appears to only have a single issue. Interesting.
>
> Fortunately, the library has [a catalog website](http://catalog.pwni.ng/), so you can look up the missing volume! The site's a bit strange; it seems like it's something of a community effort, and allows you to add your own descriptions for issues if they're missing. However, descriptions aren't public until an admin approves, and while you were able to find the [issue in question](http://catalog.pwni.ng/issue.php?id=3), it appears that the description isn't public. But if an admin can see it, that's just as good as if you could see it, right?



###	Problem Details

[Here’s the site](http://catalog.pwni.ng/). The flag is on [this page](http://catalog.pwni.ng/issue.php?id=3).

Browser: Chromium **with uBlock Origin 1.26.0 installed and in its default configuration**

Flag format: `/^PCTF\{[A-Z0-9_]+\}$/`

**Hints**:

- To view your post, the admin will click on a link on the admin page.
- You might want to read up on User Activation.
- The intended solution does not require you to submit hundreds of captchas.

###### Hint: Admin Bot Timeout

The admin bot will always disconnect after about 30 seconds.

No solvers yet



##	Contrived Web Problem(350pts, 27 solves)

###	Story

> You decide that the only way you’re going to be able to get any rest is to be back in your own bed. You teleport to your house and pull on your PJs. Of course, as soon as you climb under the covers, the day’s events start replaying in your head. You can’t believe how lucky you’ve been so far in the challenges—every single flag has appeared naturally to you as the result of your own curiosity. You didn’t need to force any of them.
>
> Your thoughts were running too fast, so you decide to pull out your phone and scroll through some feeds. As you pull it out, something seems off. You could swear that you had chosen the green case at the store last week. And why is it so *triangular*? That’s the kind of phone that three-fingered iguana avatars use.
>
> You close your eyes for a second; you really are tired. When you open them again, the phone’s blue. Huh? You close and open them. Red. Close, open. Square. Close, open. Purple and pointy. Who can use a phone like that?
>
> The curious thing is that you’re still able to see your phone screen just fine. Maybe there’s a way to figure this one out, too.



###	Problem Details

[Here’s the site](http://contrived.pwni.ng/) [Download](./contrived.tgz)



##	Mooz Chat(550pts, 1 solves)

###	Story

> After chasing the dog around and around Carnival, you decide to take a walk to cool off. The smell of fried dough wafts past you as you walk back through the rigged games section. Everything looks familiar, but the spot where you found the fortune teller is gone. It’s not like the fortune teller is gone; the spot itself is gone. The pinned throws and the spinning knives are right next to each other as if there was never anything between them. It’s not clear how this is possible, but somehow the world has warped to hide where the fortune teller once was. That’s weird.
>
> You continue to puzzle over this as you continue on to the booths. The Westworld booth looks even more realistic and gruesome up close. You shudder and decide not to go into that one. You don’t need to be throwing around anybody’s brain. Right next to that one, you see one that tickles your fancy a little bit more. The people crowded around this booth are all dressed in silly costumes; dinosaurs, superheroes, robots, secret agents, and more. They all carry weapons and pickaxes of a multitude of designs. As you get closer, you see a bush shift… and then stand up! There was a person inside! The group is a cacophony of noise; each one is dancing to a different short clip of music. One furiously flosses while several dab. Should you join in?
>
> Further along, you see a booth shaped like a giant goose. Around its neck hangs a sign, “Untitled”. You walk into the belly of the goose and see a gardener diligently tending his plants. You manage to steal the keys with your newly-formed beak. Having a neck this long is really handy. You open the gate and continue deeper into the booth…
>
> As you leave the goose, you return to your original size. “Blegh. That tasted awful.” Having to constantly use your mouth to move things around isn't really what you were looking for when you thought of "fun". Looking for a change of pace, you see that Animal Crossing booth that caught your eye earlier. You walk in to see the familiar face of Isabelle, smiling at you and welcoming you to the island. You explore for a little while, catching an oarfish to the applause of those around you, before walking into one of the many houses around.
>
> The inside looks oddly familiar. You puzzle over this for a moment, before realizing that it looks exactly like your house. You walk over to the full-length mirror to admire your Animal-Crossing-ified self. As you’re staring, your Nook phone buzzes. You pull it out, but the screen is blank. Puzzled, you look back up at the mirror, and see your regular face looking back at you. You (the other you) is trying to say something, but you (the not other you) can’t make it out.
>
> “... people are hack… REFUGE … safe …”
>
> The other you looks frantic, and is getting more frantic as they can see that you aren’t getting it. Suddenly, the other you tilts sideways and your view of them splits in half. Bits and pieces of the other you move around, while some stay in place. In an instant, the fragmented world disappears and you’re left staring at your own reflection.
>
> You decide to puzzle over your Nook phone to see if you can figure out how you triggered the vision.



##	Probleam Details

[The app](https://chat.mooz.pwni.ng/) [Download](./mooz_chat.tar.gz)

**Part 1:** Tom Nook and Isabelle have been exchanging text messages over Mooz recently. Is Tom Nook looking for something besides bells these days?

**Part 2:** Timmy and Tommy are now using Mooz to manage their store from a safe distance. Thankfully their video chats are end-to-end encrypted so nobody can steal their secrets.

**Part 1 (150 pts) — 7 solves**

**Part 2 (400 pts) — 1 solves**