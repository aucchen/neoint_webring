---
title: How to Join
layout: html
---

## Who can join

Interactive fiction creators and fans who have some sort of web presence, and are generally willing to be associated with the [Neo-Interactives](https://neointeractives.tumblr.com).

## Add yourself to the members list

If you would like to be included in this webring, you will need to provide some informations:

- <b>a unique slug</b>: a descriptive text to identify you in the webring. 
  - Must be <b>one word in the Latin Alphabet</b> (a-z - lowercase only!)
- <b>your webpage's name</b>
- <b>your webpage's URL</b>

### Through Github

Add the requested information to <a href="{{site.github_repo_url}}/blob/main/_data/members.csv">the members list on GitHub</a> in a pull request.<br>

Pull requests can also be used to change your existing entry or delete your entry.

### Other methods

If you don't have a GitHub account, you can send an e-mail with the relevant information to <a href="mailto:neointeractives@gmail.com">Neo-Interactives</a> (or <b>neointeractives [at] gmail [dot] com</b>, with the required information. You'll receive an answer when your webring links are ready!

You can also contact one of the mods of the <a href="https://neointeractives.tumblr.com">Neo-Interactives</a> or on our discord.


## Add links on your webpage

Once you're on the members list, add links on your webpage to the next and previous members of the webring: **{{'/YOUR-SLUG/next'|absolute_url}}** (next) and **{{'/YOUR-SLUG/previous'|absolute_url}}** (previous), replacing **YOUR-SLUG** with the slug you chose.

Feel free to include a link to **{{'/'|absolute_url}}** (the main webring page) as well.

### Example widgets

Example 1:

```html
    <div id="webring" style="border-style: double; border-width: 2px; padding: 0.5em; max-width: 400px; text-align: center;">
        A member of the <a href="https://neoint-webring.netlify.app">Neo-Interactives Webring</a>
        <br>
        <a href="https://neoint-webring.netlify.app/autumnchen/previous">Previous</a> - <a href="https://neoint-webring.netlify.app/autumnchen/next">Next</a>
    </div>
```

Example 2:

```html
    <a href="https://neoint-webring.netlify.app/manonamora/previous">[Previous]</a> - <a href="https://neoint-webring.netlify.app/">[All]</a> - <a href="https://neoint-webring.netlify.app/manonamora/next">[Next]</a>
```

Example 3:

```html
    <div id="webring" style="display:flex;justify-content:center;align-content:center;">
      <a href="https://neoint-webring.netlify.app/lapinlunaire/previous" title="Previous Webring Member">◄</a>
      <img id="badge" src="BADGE URL.PNG">
      <a href="https://neoint-webring.netlify.app/lapinlunaire/next" title="Next Webring Member">►</a>
    </div>
```

If using these examples, you should replace `autumnchen` or `manonamora` or `lapinlunaire` with your slug. To use Example 3, download one of the badges available below (right-click > save image to your computer > upload on your own website) and replace the `BADGE URL.PNG` in `src` with your own relative url.

## Webring Badges

### 88x31px
Static
<div class="badges"><img src="assets/88x31/88x31 NIStamp1.jpg"><img src="assets/88x31/88x31 NIStamp2.jpg"><img src="assets/88x31/88x31 NIStamp3.jpg"></div>

<details><summary>Animated (.gif)</summary>
    <img src="assets/88x31/88x31 NIStampGif1.gif"><img src="assets/88x31/88x31 NIStampGif2.gif"><img src="assets/88x31/88x31 NIStampGif3.gif">
</details>

### 99x56px

Static
<div class="badges"><img src="assets/n-i stamp1.png"><img src="assets/n-i stamp2.png"><img src="assets/n-i stamp 3.png"></div>

<details><summary>Animated (.gif) badges</summary>
    <img src="assets/n-i stamp gif1.gif"><img src="assets/n-i stamp gif2.gif"><img src="assets/n-i stamp gif3.gif">
</details>
