---
title: How to Join
layout: html
---

## Who can join

Interactive fiction creators and fans who have some sort of web presence, and are generally willing to be associated with the [Neo-Interactives](https://neointeractives.tumblr.com)

## Add yourself to the members list

If you would like to be included in this webring, you will need to provide some informations:

- <b>a unique slug</b>: a descriptive text to identify you in the webring. Must be <b>one word in the Latin Alphabet</b> (a-z, A-Z)
- <b>your webpage's name</b>
- <b>your webpage's URL</b>

### Through Github

Add the requested information to <a href={{site.github_repo_url}}/blob/main/_data/members.csv>the members list on GitHub</a> in a pull request.<br>

Pull requests can also be used to change your existing entry or delete your entry.

### Other methods

If you don't have a GitHub account, you can send an e-mail with the relevant information to <a href="mailto:neointeractives@gmail.com">Neo-Interactives</a>, with the required information. You'll receive an answer when your webring links are ready!

You can also contact one of the mods of the <a href="https://neointeractives.tumblr.com">Neo-Interactives</a> or on our discord.


## Add links on your webpage

Once you're on the members list, add links on your webpage to the next and previous members of the webring: **{{'/YOUR-SLUG/next'|absolute_url}}** (next) and **{{'/YOUR-SLUG/previous'|absolute_url}}** (previous), replacing **YOUR-SLUG** with the slug you chose.

Feel free to include a link to **{{'/'|absolute_url}}** (the main webring page) as well.

### Example widgets

```html
    <div id="webring">
        A member of the <a href="https://neoint-webring.netlify.app">Neo-Interactives Webring</a>
        <br>
        <a href="https://neoint-webring.netlify.app/autumnchen/prev">Previous</a> <a href="https://neoint-webring.netlify.app/autumnchen/next">Next</a>
    </div>
```


```html
    <a href="https://neoint-webring.netlify.app/manonamora/previous">[Previous]</a> - <a href="https://neoint-webring.netlify.app/">[All]</a> <a href="https://neoint-webring.netlify.app/manonamora/next">[Next]</a>
```

If using these examples, you should replace `autumnchen` or `manonamora` with your slug.
