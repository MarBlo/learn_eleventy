# Learn Eleventy

I am trying to follow _Andy Bell`s_ course. I know it is a bit outdated (made in 2020) because
in meantime _11ty 1.0.0_ has been released.

The first 6 lessons went smooth.

In lesson 7 I stumbled over one line

`{{ helpers.getLinkActiveState(item.url, page.url) | safe }}`

in the codeblock

```js
<ul class="nav__list">
  {% for item in navigation.items %}
  <li>
    <a href="{{ item.url }}" {{ helpers.getLinkActiveState(item.url, page.url) | safe }}
      >{{ item.text }}</a
    >
  </li>
  {% endfor %}
</ul>
```

in `side-head.html`.

This stopped rendering.
Leaving this piece out made the code work again - and as much as I can see right now -
like it should.

## Lesson 9

Went well. Although the steps around `npm install node-fetch` showed some error messages,
those went away after `uninstalling` and the then following step `npm install @11ty/eleventy-cache-assets`
