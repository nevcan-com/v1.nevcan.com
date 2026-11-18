# nevcan.com v1 (2011–2012)

The first version of nevcan.com, live from late 2011 to mid 2012: a Joomla 1.7 site with a
welcome page, "Nevcan Hakkında" (why I bought the domain, and who I am), "Referanslarım" (my
website work), "Beni Takip Edin" (social accounts) and a contact form.

Online at **[v1.nevcan.com](https://v1.nevcan.com)** as part of the nevcan.com version archive,
hidden from search engines. The current site is [www.nevcan.com](https://www.nevcan.com).

| Path | Page |
| --- | --- |
| `/`, `/index.php/` | Hoşgeldiniz (home) |
| `/index.php/using-joomla/extensions/components/content-component/article-category-list/8-nevcan-hakkinda/` | Nevcan Hakkında |
| `/index.php/using-joomla/extensions/components/content-component/article-category-list/50-referanslarim/` | Referanslarım |
| `/index.php/using-joomla/extensions/components/content-component/article-category-list/35-beni-takip-edin/` | Beni Takip Edin |
| `/index.php/component/contact/contact/9/` | Contact |

The long paths are Joomla's own; they are kept so the links between the pages still work.

## Source

There was no copy of this version. Its pages survived in the Internet Archive's Wayback Machine,
captured 21 times between November 2011 and July 2012, but none of its CSS, JavaScript or images
were. The first 21 commits are those captures in order, each dated when it was taken; links to
nevcan.com are made site-relative and nothing else is changed. Tags: `2011.11` (first version) and
`2012.07` (last). The Joomla sample pages that were still on the site, and a December 2011 "server
is being upgraded" page, are left out.

The next commit makes it run again:

- **Template.** The site used RocketTheme's Quasar template (colour style 1) on the Gantry
  framework, both GPL. Quasar's CSS and images come from a later release (1.5.1); Gantry is 3.2.11
  and Joomla's own scripts are from Joomla 1.7.3, the versions of the time.
- **Stand-ins, not the original files:**
  - `templates/rt_quasar/images/logo/style1/logo.png`: my logo, redrawn from memory on the
    template's logo, which it closely resembled: "nevcan" in place of "quasar" and ".com" in
    place of "gpl template", right-aligned (Comfortaa font).
  - `images/logos/*_logo.png`: nine of the social icons, drawn from the
    [Zocial](https://github.com/smcllns/css-social-buttons) 1.1.1 icon font (2012, MIT).
- **Missing.** Every other image shows its file name instead.
- **Archive changes.** The robots meta tag is changed to `noindex, nofollow`, a `robots.txt`
  disallows everything, and the contact form shows a note instead of sending. The site had no
  analytics.

## Missing files

If any of these turn up in an old backup, add the file at the same path and push; the pages
already point there.

- `favicon.ico`
- `images/328096_10150317549801239_707426238_8126898_779264704_o.jpg` (a photo on the "Nevcan
  Hakkında" page)
- `images/logos/movescount_logo.png`
- `nossa.webm` (the "Ai Se Eu Te Pego" video linked on the home page)

## Stack

Joomla 1.7, RocketTheme Quasar on Gantry 3.2, MooTools. Hosted on GitHub Pages as static pages.
