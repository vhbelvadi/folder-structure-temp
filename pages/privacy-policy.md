---
id: 13fde6b4-5e25-4e0a-933f-547541fd9f33
blueprint: single_page
title: 'Privacy policy'
subtitle: 'The simple rules that govern your use of this site and respect your privacy.<br/><small class="not-italic text-base text-foreground-light mt-0.5">Updated November 2023</small>'
replicator:
  -
    id: lfz2ajmu
    heading: Introduction
    content: |-
      This is a flat-file website which means it does not use databases to query and server content on the fly. The files that run this website are universal and contain all the data needed to render a page which is generated on demand and cached. As a result of this secure flat-file set-up, none of your personally identifiable data is ever collected or used by this website. Continue reading for a full explanation or [skip to the summary](#summary) at the end.

      Although we have no interest in collecting or using your personal data, this website may, from time to time, interact with third-party services (e.g. social media links) which may take you to areas on the web governed by the terms of use of these third-parties. Remember that there is nothing this website can do about data used by third-party services as their use of your data is governed by their own terms of service and privacy policies. <!-- But first let us talk about our use of service workers. -->
    type: subpage
    enabled: true
  -
    id: lfz2a8vn
    heading: 'Service workers'
    content: |-
      This website uses service workers. Chris Love [explains service workers](https://love2dev.com/blog/service-worker-cache/) thusly:

      > Service workers are this wonderful new web platform feature that lights up some great functionality like URL response caching. This caching is the magic that enables progressive web applications to work offline.

      The idea behind service workers is to speed up loading of this website and make past pages available offline. The first part was accomplished by caching before—and still is—but caching gives developers poor control and promises weak persistence of data. Service workers are generally more reliable. The second part is unique to service workers: if you visit a bunch of pages on this website or read a handful of articles, those articles will be available for you to view even when you are offline. Try it now: turn off your internet connection and refresh this page and it will load just fine.

      Service workers do not make this site available offline eternally, however. In the interest of updating changes and the possibility that you have lost interest in this site nothing is stored for long after you stop visiting this site. In short, service workers improve your experience on this site without harming your system in any way or invading your privacy.
    type: subpage
    enabled: false
  -
    id: lfz2a4ab
    heading: Analytics
    content: |-
      We use *Google Analytics* to monitor the popularity and readership demographics of this website. This is used for entirely non-commercial purposes, mainly to ensure the visibility of this website online. Analytics helps ensure that this website is generally accessible to people interested in its content, that it is usable on mobile devices, and that there are no glaring code errors that make it hard to use or index.

      We use a *tracking cookie* i.e. a cookie that helps track user behaviour on the site. These type of cookie is used by nearly every website you visit and, on this website at least, are not of concern as they do not identify you personally. We may find, via analytics, that more people in one country visited this website on a given day than another, but no data on these individual visitors will every be collected or tracked. Further, you are not tracked after you leave this website.

      For more information please read the [Google Analytics terms of service](https://marketingplatform.google.com/about/analytics/terms/us/). Keep in mind that we respect your preferences: if you block tracking at your browser level or operating system level, no Analytics monitoring will occur on this website.
    type: subpage
    enabled: false
  -
    id: lfz29u9b
    heading: 'Social media'
    content: |-
      I may embed tweets for which Twitter will serve some of its own javascript. Or I may embed a Youtube or Vimeo video in which case those companies will serve their scripts.

      I do my best to ensure that in most cases a tweet and its embedded page on this site are not used for purposes that include personalised suggestions and personalised ads from Twitter. Likewise I do my best to ensure that in most cases YouTube does not store your information on this website for their own analytics and personalised ads unless you play a YouTube video embedded on this site. Unfortunately, YouTube gives neither me nor you enough control in that there is no way to watch a YouTube video if we decline consent to such personalised ads and analytics (at least as of 2023).

      Along the same lines—although much more leniently—Vimeo, Apple (Music), Spotify and others have their own terms of use as does any other service platform whose content may be displayed from time to time as necessary on this website. This is rare but it _may_ happen. More common are external links to these services that take you out of this website and into those third-party websites. Please consult these third-party services to better understand how they use yout data as this is not under the control of this website.
    type: subpage
    enabled: true
  -
    id: lfz29kll
    heading: Newsletter
    content: |-
      If you subscribe to my fortnightly newsletter **Confluence** (you can <a href="#" onclick="showNL()">subscribe right now</a> for free if you have not done so already) your e-mail will be processed through, and saved in, the _Buttondown_ newsletter management suite. This is safe and secure and private (for example, _Buttondown_ does not sell your e-mail or use it to market to you).

      Every e-mail you receive after subscribing on this website will carry an unsubscribe link that will let you stop your subscription and delete your e-mail from the mailing list in a couple of clicks, without having to talk to someone about it. Further, this website never asks for anything but your e-mail address and, in fact, strongly discourages you from building your profile unless you absolutely feel the need to.

      You need not provide any personal information to subscribe to our newsletter besides the e-mail address where you would like to receive the newsletter. If you have any trouble with the newsletter, please <a href="mailto:hello@vhbelvadi.com">e-mail me straight away</a>.
    type: subpage
    enabled: true
  -
    id: lfz28hv4
    type: subpage
    enabled: true
    heading: Cookies
    content: |-
      I believe there’s no real need for cookies on this website right now. I have little use for specific, invasive tracking and analytics; and I do not display any ads whatsoever. That said, most websites need a small set of cookies—often classified as ‘strictly necessary’ and allowed for use under GDPR—to function properly. This website uses three such cookies, all first-party:

      1. ***STATAMIC_SESSION*** (Necessary, First-party) This cookie monitors any logged in users of this website or users trying to log in or fill forms, such as my newsletter subscription form. If you do not interact with any of these, this cookie does nothing. But without it, core functionality of this website will break.
      2. ***XSRF_TOKEN*** (Necessary, Security, First-party) This token ensures the visitor’s (your) browser security by preventing cross-site request forgery. This cookie is essential for the security of this website as well as you.
      3. ***CF_CLEARANCE*** (Necessary, Security, First-party) This is a token set by Cloudflare, the CDN I use on this website for edge caching to ensure quicker page loads, to make sure only humans visit this website and not bots that might disrupt the host server.

      Please note that your use of this website means accepting the use of necessary cookies. Since no other cookies (e.g. advertising, analytics, tracking) are used, you will not see options to reject any cookies.

      [GDPR guidelines](https://gdpr.eu/cookies/) specifically state, “When people complain about the privacy risks presented by cookies, they are generally speaking about third-party, persistent, marketing cookies.” And stated above, no third-party cookies are in use on this website.
      <!-- ***Your preferences*** As of now, your preferences for these cookies have been registered for {{ oreos }}{{ title }} cookies {{ explicit ? 'explicitly' : 'implicitly' }} and {{ /oreos }} you may change your preferences here anytime: -->
      {{# partial:vendor/statamic-oreos/form-simple #}}
  -
    id: lfz28cij
    heading: Summary
    content: |-
      Here is an honest summary of our privacy and cookie policies:

      - We do not collect or use your personal data on this site.
      - We may embed works posted to social media platforms (e.g. Youtube, Vimeo) or service offerings (e.g. Apple Music, Spotify) in which case they will serve their scripts and your use of these embeds etc., regardless of your direct interaction with them, will be governed by the policies of their respective platforms of origin.
      - If you subscribe to my newsletter, your e-mail will be stored safely and privately with _Buttondown_ who will themselves never use your e-mail address in any way except to send you my newsletter.

      <!-- - We use service workers to cache some core portions of this website, speed up page load times and make parts of this site available to you offline.
      - We use Google Analytics to better understand our readership/visitors without ever personally identifying them -->
      <!-- - We use technology as an enabler and try to strike a balance by minimising tracking as this website is fundamentally against privacy-invading features: we try to use session storage over cookies where possible, and prevent tracking except on direct interaction as far as possible, and we use third-party services only when necessary -->
      <!-- - Ignore 
      - You can review your cookie preferences on this page any time but know that this website employs only cookies considered ‘strictly necessary’ and first-party. -->

      At the end of the day, a lot of the features and techology we use are either designed to improve your experience on this website or to improve the functionality of this website for your experience. None of it is directly harmful to you as a user, to your privacy, or to your system.

      Enjoy this website and have a lovely day.
    type: subpage
    enabled: true
updated_by: b5b32860-ebab-42d8-95fe-bff6933f0df6
updated_at: 1702406014
template: default
images: eye-copy-2.png
---
