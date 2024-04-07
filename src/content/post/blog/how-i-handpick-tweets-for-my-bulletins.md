---
publishDate: 2024-04-07T05:00:00+00:00
title: 'How I handpick tweets for my bulletins'
excerpt: See my decision making on picking tweets plus my workflow on transforming my handpicked tweets to blog sections of my bulletins
image: https://res.cloudinary.com/dxsornfee/image/upload/v1712466526/Capture_8_vzqlew.png
tags:
  - blog
category: blog
metadata:
  canonical: https://levelup.news/blog/how-i-handpick-tweets-for-my-bulletins
---

Hello folks!

For those who subscribed on my newsletter, it is pretty common to see handpicked tweets from the bulletins you get.

On this article, I am sharing parts of my workflow on handpicking tweets.

### Reducing Friction

The focal point of my workflow is reducing friction as I can. As you can guess, the handpicked tweets are handpicked with ease.

#### Ease of curation

With ease? Yes. Part of reducing friction is making sure the process can happen with ease. It should be enjoyable too.

To accomplish this, I make sure that everything I handpick is handpicked as I scroll through Twitter, during my free time.

Wow. Looks the process is very natural. But how?

### Twitter Account and Circles

First, you need to have a Twitter account that is closely connected to tech & startup circles. I have built an account for the past 6 months which is closely connected to those circles.

#### What are those circles?

My circles include people from tech, startups, and indie hacking communities, so it makes the process of picking easier.

### Picking tweets

I usually scroll on Twitter to see updates from my circles, and when I see a very interesting tweet, it only takes seconds for me to decide if I should include the tweet on my bulletins or not.

#### Criteria

My criteria is very loose, but I usually include tweets that are **either viral or valuable, or both.**

1. Viral

Tweet has lots of impressions, replies, and likes. Viral tweets are usually controversial, but there is always stimulating effect on it. It makes you think, and the replies are always interesting to read.

2. Valuable

Tweet has lots of bookmarks. Valuable tweets are very straightforward. They can be guides, a personal account, a collective experience where everyone resonates, and often provides something new for the reader to learn.

#### Decision Making

If I see a viral tweet, I check if it is valuable. If it is just a shitpost with nothing to learn from, I skip.

If I see a valuable tweet with enough valuable replies or even just a single valuable reply, I still include it even if it is not viral.

### Handpicked Tweets Automation Workflow

Last, I will share about my automation workflow.

#### This workflow ensures the following:

1. Wherever I am, and whether I am scrolling from a computer or phone, I can still pick a tweet for my bulletins. Convenient and easy, frictionless even.

2. I can easily get embeddable blockquotes and plug them on my blog posts. Again, frictionless.

Speaking of an embed, below is an example:

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Here&#39;s an Easter surprise:<br><br>The Postman work is the start of something bigger:<br>Me optimizing my curation process for Level Up, Founders! Newsletter<br><br>Guess how it works?<br><br>Tomorrow&#39;s bulletin will reveal the sauce.<br><br>Best way to not miss it? <br>By subscribing👉<a href="https://t.co/ASJUsRB4rH">https://t.co/ASJUsRB4rH</a> <a href="https://t.co/ywht5Kungd">https://t.co/ywht5Kungd</a> <a href="https://t.co/7agKEPBo9Q">pic.twitter.com/7agKEPBo9Q</a></p>&mdash; Raymel is building in public 🚀 (@pseudokid) <a href="https://twitter.com/pseudokid/status/1774496886470193328?ref_src=twsrc%5Etfw">March 31, 2024</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

#### The Automation Workflow

1. Send tweet to [Pocket](https://getpocket.com/home).
2. For every new entry in Pocket, a [Zapier](zapier.com) workflow appends it to a Google Sheet

![image](https://res.cloudinary.com/dxsornfee/image/upload/v1712481950/Capture_81_fjghkm.png)

3. A Google Sheet macro calls Twitter oEmbed API to get the Tweet blockquote, and supplements the new Google Sheet row with the blockquote of the newly appended tweet

![image](https://res.cloudinary.com/dxsornfee/image/upload/v1712483135/Capture_82_joolr2.png)

4. An Apps Script script exposes the Google Sheet, making an API endpoint out of it. I will call the API endpoint manually to fetch all the Tweet blockquotes for my bulletin, and paste it as blog sections on my bulletin.

![image](https://res.cloudinary.com/dxsornfee/image/upload/v1712483641/Capture_83_dvaelj.png)

That's it.

I will share updates of my workflow, as I continue to improve my automation workflows.

If you find this helpful, feel free to share it to your friends!

---

**Level Up, Founders!**

Thank you for being part of the Level Up community! Before you go:

- Follow me on [Twitter](https://twitter.com/pseudokid)
- <a href="#" data-eo-form-toggle-id="adf19cae-dd6a-11ee-97ab-2b51af71a780">Subscribe to the newsletter</a> to not miss any new blog posts
