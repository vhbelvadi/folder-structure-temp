---
id: 79905663-de47-45d4-a501-03360b2eeed6
blueprint: single_page
title: Colophon
subtitle: '/ˈkɒləf(ə)n/ <strong class="not-italic">n. sing.</strong> A statement at the end of a book giving information about its authorship and printing'
replicator:
  -
    id: lfyywb35
    heading: Hello
    content: 'Almost every­thing you need to know about me and my cur­rent work can be found [on the homepage](/) or under one of the menu options above. Please feel free to <a href="mailto:hello@vhbelvadi.com">send me an e-mail</a> or con­nect with me on [Mastodon](https://indieweb.social/@vhbelvadi) any­time.'
    type: subpage
    enabled: true
  -
    id: lfyznr70
    heading: Typefaces
    content: |-
      This website is typeset in 15/20 pt GT Sectra and accompanied by GT America, both licensed from Grilli Type. 

      <img src="/assets/images/gtsec-sample.jpg" alt="Sample of the GT America typeface" class="dark:invert">

      GT Sectra is described by its designers (Dominik Huber, Marc Kappeler, Noël Leu) as “a contemporary serif typeface combining the calligraphy of the broad nib pen with the sharpness of the scalpel knive [sic]” and this results in a typeface that has a bold, dark colour on paper, and seemingly both serif and sans-serif forms (and I have not been able to lay a finger on just which it really is). What I love about GT Sectra, though, is how frustratingly, incredibly readable it is: on small and large screens, and on light and dark schemes alike. Read more about [how GT Sectra was developed](https://www.grillitype.com/blog/typeface-stories/gt-sectra-development) at Grilli Type.

      <!-- <span class="font-sans text-[95%] font-bold">Söhne</span> is used here in two weights. It is a typeface that its designer Kris Sowersby of Klim Type Foundry says is “the memory of Akzidenz-Grotesk framed through the reality of Helvetica.” It is a sober and crisp-looking typeface as good for text as it is for interface elements, and the latter is where it finds its primary use on this website. Read more about [how Söhne was developed](https://klim.co.nz/blog/soehne-design-information/) at Klim Type. -->

      <img src="/assets/images/gtam-sample.jpg" alt="Sample of the GT America typeface" class="dark:invert">

      The accompanying typeface **GT America** is also from Grilli Type and is set between 12–13/17–18 pt depending on your device. Designed by Nöel Leu, GT America combines European grotesque and American gothic sensibilities to create a [“large, yet coherent and functional typeface family”](https://www.grillitype.com/api/storage/app/uploads/public/60d/345/f19/60d345f199446740803227.pdf), an exercise that, surprisingly, had never been done before. The end result is the only typeface that ticks off all the boxes I like from a sens-serif type: rounded dots, grotesque letter forms, double-storey g, the letter ‘a’ and ‘l’ without hooks, a well-proportioned width for reading long-form text, and tapered stems to create a pleasanter colour on the page (i.e. screen), all packaged in a quiet, sturdy, yet unapologetically individual typeface that lends much more to the content it is setting than it draws for itself.

      Monospaced text, such as `code and stuff` are set in the beautiful [Input Mono by DJR](https://djr.com/input/) licensed via Adobe Fonts. I also happen to use this typeface on VS Code which I use to develop this website—Input Mono is [free for private use](https://input.djr.com/download/).
    type: subpage
    enabled: true
  -
    id: lfyzpcbq
    heading: Workflow
    content: |-
      Once upon a time my workflow in editing and managing this website involved the Atom code editor, iA Writer, Gitlab, Netlify and what not. With real life getting in the way I decided to simplify things and switch from Hugo to a GUI- and Tailwind-powered website engine. My answer was [Statamic](https://statamic.com). This now my one-stop management and writing space for the most part.

      The advantage of this is that I can switch devices with ease without having to push and pull via Git. However, I do use Git but only while fixing bugs, updating Statamic or other one-off instances. These are things one makes time for rather than  routine updating and publishing, which is handled with greater ease thanks to Statamic.

      As for images, I usually run them through ImageOptim at some point to shrink them down to a more palatable size for websites. This requires my computer rather than my iPad (which I’m comfortable using quite often) so I am currently on the lookout for a simpler, cross-platform solution to this.
    type: subpage
    enabled: true
  -
    id: lfyzphll
    heading: Maintenance
    content: |-
      Maintaining the site via code updates is restricted to my Mac in case of major changes that call for lots of testing. I used to use Atom (and Brackets before that) but now I use VS Code for updating, testing, designing and improving. This of course means working quite a bit in the Terminal. Part of the reason why web design and development is restricted to my Mac is the fact that iPadOS does not support running a local server yet, at least as of iPadOS 17.

      Compared to my past workflows I find this to be mature, streamlined, simple and straightforward, which makes maintenance and updating (including writing new stuff) easy and incredibly quick. That last part—a quick workflow—ensures I can care for this website without sacrificing too much time or putting in an unjustifiable lot of effort. To those of you who e-mail me asking how I manage all this, the answer is simple: _find a workflow that is efficient for you_.
    type: subpage
    enabled: true
  -
    id: lfyzqjnz
    heading: 'External credits'
    content: |-
      While nearly all content on this website is my own, I enjoy highlighting others’ works when doing so is legally permissible—or I have explicit permission. Particularly for essays, cover images usually showcase a related work that I like from other artists.

      Due credit is provided in all places where others’ work is used. If you noticed that your work was used but not credited to your satisfaction please <a href="mailto:hello@vhbelvadi.com">write to me</a> and I will quickly set things in order.
    type: subpage
    enabled: true
  -
    id: lfyzr3id
    heading: Set-up
    content: |-
      This website runs on flat files rather than databases. It was built on a Mac, then rebuilt and then rebuilt again—all also on a Mac—mostly because I cannot help myself from constantly tinkering with it. All content is hosted by a green webhost in the Netherlands, a key decision in making this website [one of the most climate-friendly websites](https://www.websitecarbon.com/vhbelvadi-com) currently on the internet.

      For its first ten years this web­site ran on Word­Press, the excel­lent, free and open-source CMS. Between 2017 and 2019 it ran on the much slim­mer, quicker, more straight­for­ward (and data­base-free) system, Kirby. In an attempt to avoid Kirby’s license fee inflation and migration headaches from v2.0 to v3.0—and to escape its non-standard YAML front-matter fomat— I decided to move to a static website model powered by Hugo. This originally proved to make writing, website design and management all a pleasure once again. The problem with Hugo was that it did not give me enough time to focus on my other interests.

      I decided that I needed the best of both worlds: a back-end that communicates well with my existing Hugo content files; a robust and modern framework that supports Tailwind (etc.) as a core step rather than as an afterthought; and a neat GUI. I found the perfect answer in Statamic, so this website is powered by the Statamic v4.0 flat-file system.
    type: subpage
    enabled: true
  -
    id: lfyzrgt2
    heading: Third-party
    content: |-
      Icons used on this website were sourced from [Icon SVG](https://iconsvg.xyz). 

      This website uses Cloudflare Analytics for anonymised visitor statistics and to keep track of any breakages on the site. If you subscribe to my newsletter you will be part of a Buttondown-powered newsletter management system which is safe, secure and private.

      This website also has full SSL to ensure you are always on a secure connection. Read more in the [privacy policy](/privacy-policy).
    type: subpage
    enabled: true
updated_by: b5b32860-ebab-42d8-95fe-bff6933f0df6
updated_at: 1703096178
template: default
images: colophon-copy-2.png
---
