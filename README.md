
# Dopagaki BBS

BBS running on ENiGMA1/2, sysopped by dopagaki AKA ogreload3d

## The whole idea

The whole idea is that with all these social networks turning into ad-filled hellscapes, I want to explore lightweight and autonomous modes of communication between friends and family that is easily set up and can be used to share information somewhat easily through the personal computer (not the mobile phone).

We used to have forums, but those run on PHP, and will be hacked. 
We used to have IRC, but that is so easily bottable, and keeping a "history" that you can go back to needs to set up a bouncer.
My mode of connection is relatively off-hands. I do my stuff during the day, and catch up in the evening. I also like to write long ass texts, and people can follow me directly by reading my blog. But here's the problem: there's no good way to see if they actually accessed my stuff, no easy way to talk to me or eachother, and no way for them to "express themselves" in more ways they could imagine.

We could yeah move into LINE or Whatsapp or whatever, or just use emails, but the problem is that there will always be "somebody else" hosting it. What if Gmail decides to ban me tomorrow? What if LINE packs up their stuff? What if all we got is a telephone line?
There's also all these ELEMENT and Matrix and whatever things, about how "decentralized" it all is. Well, riddle me this then: if it's so fucking decentralized and privatized, why can I log in with my GMAIL account huh?

I hope I am being just paranoid, but it's just an nice exercise of thought: what if we could no longer share huge files to eachother, but still need to tell eachother how much we mean to eachother. We could yeah send out mails but with the way Omniva is dropping the ball big time, then that's NOT a way we could do.

## Getting started

Clone it, then create runtime directories:

```bash
mkdir -p config db logs filebase art mods mail
```

various docker commands:

```bash
docker compose up -d
docker compose logs -f
docker compose down
docker compose restart
```

## Data

