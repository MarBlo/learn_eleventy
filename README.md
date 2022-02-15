# Learn Eleventy

I am trying to follow _Andy Bell`s_ course. I know it is a bit outdated (made in 2020) because
in meantime _11ty 1.0.0_ has been released.

The first 6 lessons went smooth.

In lesson 7 I stumbled over one line
`{{ helpers.getLinkActiveState(item.url, page.url) | safe }}`
which led to stoping the rendering.
Leaving this piece out makes the code work again - and as much as I can see right now -
like it should.
