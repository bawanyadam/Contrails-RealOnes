
# recordName

> This is the feed's ID which can be letters, numbers, or dashes. Spaces are not allowed. Maximum length is 15 characters.

adams-real-people

# displayName

> This is the title of the custom feed. Maximum length is 24 characters.

Real Ones

# description

> This is the description of the feed.

My Little Feed of Friends Even If They Don't Realize It

# searchTerms

> There are three types of search terms:
>
> - Keywords: Test these in [https://bsky.app/search](https://bsky.app/search). `AND` is implicit, so `cat dog` on one line will require both `cat` and `dog`. You can use quotes as well `"hot dog"`.
> - Users: links such as `https://bsky.app/profile/why.bsky.team` will pull in the user's posts. To include replies and reposts, you can add the following flags: `https://bsky.app/profile/why.bsky.team +replies +reposts`.
> - Pinned posts: links such as `https://bsky.app/profile/saddymayo.bsky.social/post/3jxju2wwap22e` will pin at the top of the feed. One link per line, please.

- https://bsky.app/profile/aek.bsky.social +replies
- https://bsky.app/profile/wormholecowgirl.bsky.social +replies
- https://bsky.app/profile/gabagirl.bsky.social +replies
- https://bsky.app/profile/cw2e.bsky.social +replies
- https://bsky.app/profile/jennydeath.bsky.social +replies
- https://bsky.app/profile/sqruinch.bsky.social +replies
- https://bsky.app/profile/shyboy.bsky.social +replies
- https://bsky.app/profile/courtneyskye.bsky.social +replies
- https://bsky.app/profile/aziz.lol +replies
- https://bsky.app/profile/faildaughter.bsky.social +replies
- https://bsky.app/profile/oopsyjuice.bsky.social +replies
- https://bsky.app/profile/milvaspectre.bsky.social +replies
- https://bsky.app/profile/pgb.bsky.social +replies


# safeMode

> Safe mode limits the total number of API calls coming from Cloudflare.
>
> Set to `false` if you have higher limits via a paid Cloudflare plan.

false

# avatar

> This must link to an image (PNG or JPEG) in the same directory as this CONFIG.md. It doesn't have to be called `avatar.png`, but just be sure this CONFIG.md points to the correct file.

![](avatar.png)
