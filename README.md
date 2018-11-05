<!-- banner: can be a image or a large font-->
<h1 align="center" style="font-weight: bold; margin-top: 20px; margin-bottom: 20px;">git-template</h4>

<!-- blurb: shortest possible summary (one line max) -->
<h3 align="center" style="font-weight: bold; margin-top: 20px; margin-bottom: 20px;">A simple and clean git repository template.</h4>


<!-- badges: meaningful meta information (one line max), do NOT include anything immediately visible -->
<p align="center">
	<a href="#changelog"><img src="https://img.shields.io/github/release-pre/nqtronix/git-template.svg" alt="release: NA"></a>
    <a href="https://github.com"><img src="https://img.shields.io/badge/platform-github.com-blue.svg" alt="platform: github.com"></a>
	<a href="#status"><img src="https://img.shields.io/badge/status-maintained-green.svg" alt="status: maintained"></a>
	<a href="https://github.com/nqtronix/git-template/issues"><img src="https://img.shields.io/github/issues/nqtronix/git-template.svg" alt="issues: NA"></a>
	<a href="#license"><img src="https://img.shields.io/github/license/nqtronix/git-template.svg" alt="license: NA"></a>
</p>

<!-- quick links: local links (one line max) -->
<!-- Link to the (most important) h2 chapters, but do NOT link to anything visible without scrolling -->
<p align="center">
  <a href="#getting-started">Getting Started</a> •
  <a href="#documentation">Documentation</a> •
  <a href="#under-the-hood">Under the Hood</a> •
  <a href="#support">Need Help?</a> •
  <a href="#about">About</a> •
  <a href="#credits-and-references">Credits</a>
</p>

<!-- separate h2 chapters with white space: <br> -->
<br>

## Introduction
**Open Source is amazing.** It lets us create new things without having to re-invent the wheel every time. Well, at least in theory. Most things have been done by someone, somewhere, but only a fraction is published and documented. And that's likely because many developers don't like the overhead of writing documentation. **So, let's make it dead simple!**

**git-template** contains all the essential files to make your repository **useful _and_ pretty**. Copy templates, fill in your details and get back to do the things you love most. It's that simple, really. Check out the [documentation](#documentation) to learn about our design principles.

<br>

## Key Features
 - **best of git:** embraces common design practices used in dozens of repositories
 - **skim-able:** most relevant info is visible at first glance
 - **pre-formatted**: the design is ready-to-use, just fill in your details
 - **self documenting:** instead of placeholders, this file contains details about itself

<br>

## Usage Example
This readme is a template _and_ a usage example of itself, so technically no separate example is needed.

The screenshot below is from one of my projects, which uses this template.

```c
// This is a chicken and egg problem. This readme will be updated once the other readme is written & uploaded.
```

You can find that project and many more under [related projects](#related-projects).

<br>

## Getting Started
You've never written a readme and want to do it _right_ straight from the start? Then just follow the steps below. If you run into problems, please [ask for clarification](#get-help).<br>

### Step 1: Software and Tools
There are countless programs that can edit markdown formatted files:

 - **[markdownify][prog-markdownify] [Windows, free]**<br>
   My personal favorite. The code is highlighted and converted into a live preview. The UI is intuitive and minimalistic. Local links are supported and even images from the internet (such as badges) are shown in the preview.
   
 - **[markdown editor][prog-markdown-editor] [Web, free]**<br>
   Not as good as markdownify, but available without installing anything. Its formatting closely resembles how it will look on GitHub.
   
 - **Any text editor:**<br>
   You may already use Notepad++, Atom or any other editor. They all work, but may not offer a preview and therefore I wouldn't recommend them to beginners.

### Step 2: Download **git-template**
 - **Copy this repository**<br>
   Clone it or hit [Download][git-download] and extract the .zip file.

### Step 3: Add your details
 - **Copy the files to your repo:**<br>
   If you don't have any of the included files, just drag + drop them into your existing repository. 

 - **Edit it:**<br>
   Open the file with the editor of your choice and tailor it to your project. Delete everything you don't need, add stuff you think is missing. It's _your_  readme after all.

<br>

## Documentation

>No one reads anything on the internet. <sup>[[link][video-people-dont-read]]

Not even your readme. Especially not if you treat it like many people and just dump a bunch of information about your project in it. So let's take a more interesting approach.

**Your readme is the landing page for your project, the first thing every visitor sees.** To convince someone to stay, you have no more [than a few seconds][article-few-seconds]. So make them count:

<br>

1. **State Your Purpose**<br>
   All your creative efforts have a reason. [Start by telling _why_][video-start-with-why] your project exists and _why_ anyone should have interest in it. As humans we crave meaning and purpose more than anything else. Be short and precise. 

2. **First Things First**<br>
   Outline the the scope of your project. Even if visitors are inspired by your _why_, it dosen't matter if it does not fit their requirements, no matter how great your code is. And that is ok. [Badges](#--badges) are a perfect tool to visualize what your project is and what it isn't. 

3. **No Clutter**<br>
   Get rid of everything else. No worries, you can bring it up later, but for for now it's just distraction. When in doubt, be generous with white space. Less is More.

<br>

### Write it Skim-able

> People don't read, they **_scan_**. <sup>[[link][video-people-dont-read-scan]]

If a paragraph seems useless, they skip to the next. This results in an [F-shaped pattern][video-fshape] of attention. Naturally you should place important things at the beginning of the page. Limit your paragraphs to **one idea** and try to indicate it at its start.

<br>
Additionally you can provide **visual clues** with a good formatting:

  - meaningful images
  - bullet lists
  - variation in typeface ([link][git-readme], **bold**, _etc_)
  - code snippets
  - quotes
  - white space
  
Together these changes can increase the comprehension of your text [by up to 124%][article-read-on-the-web].

<br>

### RDD - Readme Driven Development

The term "Readme Driven Development" was coined by Tom Preston-Werners and [this blog post][article-rdd]. The key takeaway is, that you should write your readme prior to **anything else**. No code, not documentation, no use cases should be written before a readme. This allows you to clarify your thoughts and remind you of the things you need to implement. I honestly think it's a good practice to follow.

Of course, that readme will be vastly different from the readme you are reading write now. There will be almost no formatting, minimal links, no pictures and no badges. 

**This doesn't mean that you have to start over to adopt this template.** Just copy & paste your notes into the chapters "Documentation" and "Under The Hood".

<br>


### Structure
The structure of your readme should follow the principles laid out in the previous two sections. Each project has some different requirements, so feel free to remove or add new chapters to the template.

These are the contents of my **ideal readme**. They are described in the next chapter in detail.

```
README.md
├───┬── Banner
│   ├── Summary
│   ├── Badges
│   └── Quick Links
├───┬── Introduction
│   ├── Key Features
│   ├── (Dependencies)
│   └── Usage Example
├── Getting Stated (Install & Configure)
├── Documentation (Usage/API/Testing)
│   ├── ...
│   └── ...
├── Under the Hood (Internals)
│   ├── ...
│   └── ...
├── Support
│   ├── FAQ
│   ├── Get Help
│   └── Contribute
├── About
│   ├── Status
│   ├── Known Issues
│   ├── Planned Features
│   ├── Changelog
│   └── Contact (The Author/Maintainer)
├── Credits and References
│   ├── Projects Used
│   ├── Related Projects
│   └── Additional Resources
└── License
```

<br>

## Under the Hood

<!-- the colon (:) behind each entry below is to distinguish it in local links: [link](#key-features) is different form [link](#key-features:) -->

### - Banner
Start the readme with the name of your project in a large font. Alternatively you can create a banner or a logo to stand out. ~~If you feel like it, you can even use some ASCII art.~~ Although you can use ASCII art, github can't be conviced to center it.

### - Summary
Write a _single line_ to summarize the essence of the project. It doesn't even have to be a full sentence. Expressing clearly what your goal is can be insanely hard, but is a crucial part of the introduction. If you can't tell what this is all about, who else will be?

<br>

### - Badges
Metadata is best added in form of **badges** right below the summary. They help viewers to decide whether your project meets their requirements. The information is picked up intuitively: <a href="#--badgers"><img src="https://img.shields.io/badge/category-value-blue.svg" alt="category: value"></a>

The left side classifies the category, the right side the value. The background color can be customised to illustrate the value. Often they are click-able and take you to a page with more detailed information. There are even a few dynamic badges based on data from the GitHub API or external tools.

<br>

**Badges should be used to provide additional information _only_.** Meaningless badges de-valuate the important ones. [A recent study][study-badges-paper] shows that the number of downloads (and therefore the community interest) is greatest with 4 to 6 badges. If yours fit into one line, you should be generally fine, though.

For more details about which badges you should consider, check out the included [**badges.md**][git-badges] file.


<br>

### - Quick Links
Many readmes have a table of contents (TOC), which adds a lot of bloat to the beginning of the readme. Most of the links won't be used anyway. So instead I suggest to add **a single line of quick links**, inspired by [markdownify][prog-markdownify]'s readme.

Each link refers to a main chapter of the readme. The first chapters "_Introduction_", "_Key Features_" and "_Getting Started_" are visible without scrolling and don't need a link. Note that the keywords don't have to match up with the chapters title. For example I prefer "_Need Help?_" instead of "_Support_" as it seems more friendly to me.

<br>

### - Introduction
The introduction should be short and to the point as described in [documentation](#documentation).

Generally I'd suggest to split the introduction into **two short paragraphs**:

1. Why does your project exist? What was the problem, that had to be addressed?
2. How does your project address that problem? What does it do in a nutshell?

The second paragraph should ideally start with the projects name in bold, followed by a verb describing what it does. Limit yourself to about 5 lines per paragraph.

<br>

### - Key Features
Make a bullet list of your projects best features. This is more about what aspects _you_ value, than all the great things it can do. You probably already know what you what to put there anyway.

<br>

### - Usage Example
A picture, screenshot or a few lines of code say more than a thousand words. Choose a common use case and demonstrate how _intuitive and straightforward_ your project handles that situation. Link to more complex examples if you want to.

<br>

### - Getting Started
Assume your viewer has a general understanding of programming, but does not know your tools or workflow well. The very first experience should work out-of-the-box, so give detailed starting instructions. Breaking it down into manageable steps can be very helpful for this. Link to all the software that has to be installed. **Make starting as trivial as you can.**

The "Getting Started" section in this readme seems ridiculous, I know, and I've definitely overdone it a bit (every programmer can edit a text file, I hope). However I think it illustrates my point quite nicely.

<br>

### - Documentation
Quite often you hear documentation belongs in a separate document and that is definitely true for large project. But for the smaller projects I don't consider it required.

Your documentation should tell the reader _how to use_ the software and _not how it works_. Write about what each function does, what their arguments are, what it returns. That sort of thing. **When in doubt, give examples.**

<br>

### - Under the Hood
You've done something clever and are eager to talk about it? Now you can! write about the internals of your project to your hearts content. Everyone who got this far actually cares about the details, so most of the viewers _care_ about what you have to say. Talk about how it all came to be, what problems you've face, what didn't work or teach a few cool tricks. But if you don't want to, that's fine too.

<br>

### - Support
Provide help for the most common issues and error messages; a [FAQ](#faq) can be particularly useful. Offer some way of asking all questions that are not answered yet. You can use the build-in issue tracker or an external tool for this.

Although many GitHub users will know how to contribute to a project, be friendly to the new users and point them to your [CONTRIBUTING.md][git-contribute] for additional information.

<br>

### - About
The about section contains any meta information about the project. Explain the current status, list major known issues, planned features, give a short changelog (but that can be a separate file, too) and offer some way of contacting you.

<br>

### C- redits and References
**Say "Thanks"** to all the people, whose work somehow helped you and include a link, if applicable. You should do this even if you're not obligated by any license. A little appreciation can go a long way (and make someones day).

<br>

### - License
Every project **needs** a license. If you don't, now one is allowed to do anything with your code. Considering you put all this effort into publishing it, I dont think that's what you want. **If you are unsure what license is best for you, visit [choosealicense.com][choosealicense.com]**.

<br>

The most popular license is the [MIT License][license-mit]. It is permissive and short enough to be understood without a lawyer. It is recommended by Tom Preston-Werner on his [blog][article-open-source-everything].

You might be tempted to give up all your rights and put your project int "public domain", but this simply does not work in some countries.  [This answer on opensource.stackexchange.com][license-mit-vs-cc0] explains some issues quite well. If you still want to do that, the [CC0 1.0 License][license-cc0] might be the best option. It's advantage above other "public domain" licenses is it's fallback clause [to function as a license][license-cc0-fallback].

**That said, I am not a lawyer and will not take responsibility for any choice you make.**

<br>

## Support

### FAQ

- **Q: But _why_ should I use your template and not [this][readme-fvcproductions], [this][readme-fcpb], [this][readme-richardlitt], [this][readme-zalando] or [that][readme-noffle]?**<br>
  A: Feel free to use whatever you like. I've read them and many more (yes, even the long blocks of text), but wasn't particularly happy with any of those option. So I made my own. You may use it, too.
  
- **Q: It's all too much!**<br>
  A: Delete whatever you don't need: Sections, badges, formatting; nothing is set in stone. In fact for each of my projects I will copy this readme and delete a good part of it. But having a single, complete readme ensures that all derived works share the same structure.
  
- **Q: You love badges, don't you?**<br>
  A: YES, as long as they are useful. Please do not add a bunch of them in the middle of your readme, unless you're writing about badges.

- **Q: Nobody asked these questions, right?**<br>
  A: Uhhh, maybe? Look, I did need examples to fill this section. And nobody is going to notice anyway. Not this far down in the document, on the fourth question. There's no way. Have I told that I'm on instructables.com? I've still got a few pro membership codes, just tell me if you want one. I bet it takes months until someone notices this.
  
- **Q: What's your favorite color?**<br>
  A: This is getting ridiculous. Don't you have something better to do than reading a made up FAQ? 
  
<br>

### Get Help

**Your question or problem wasn't solved in the FAQ?** No worries! Just open up a new issue in the [GitHub issue tracker][git-issues]. Please provide all information to reproduce your problem. If you don't have a GitHub account (and can't be bothered to create one,) you can [contact](#contact) me directly.

<br>

### Contribute

**Spotted an error?** [Open an issue][git-issues] or submit a pull request.

There is no CONTRIBUTING.md yet, sorry. Contributions will inherit the [license](#license) of this project. If you have any questions, just ask.

<br>

## About
### Status
**This project is currently classified as** <a href="https://github.com/nqtronix/git-template/blob/master/badges.md#project-status"><img src="https://img.shields.io/badge/status-maintained-green.svg" alt="status: maintained"></a><br>
_The developers intend to keep the code in working condition by updating dependencies, fixing bugs and solving issues._

Without a doubt the readme is an important part of open source projects. I wanted to get it _right_ with everything I publish. This template is the result of my research. I do not consider it perfect, but "good enough" for most repositories. Major changes are not planned.

<br>

### Known Issues

 - none (that are reported)
 
<br>
 
### Planned Features

 - Add a CONTRIBUTING.md file
 
<br>

### Changelog
This project uses [**Semantic Versioning 2.0.0**][semver.org]. During initial development (0.x.x versions) any _major_ increase is substituted with a _minor_ increase (0.1.0->0.2.0 instead of 0.1.0->1.0.0).

The message of each commit contains detailed information about the changes made. The list below is a summary about all significant improvements.

 - **0.1.0 (latest)**
   - initial release

<br>

### Contact

If you haven't done so already, please check out [Get Help](#get-help) for the fastest possible help on your issue. Alternatively you can find my public email address on my [profile][git-profile].

<br>

## Credits and References

### Projects Used
- **[Awesome Readme][readme-matiassingers]** - _A curated list of awesome READMEs_<br>
   Thanks @matiassingers for all the examples, hints and inspiration! This template would be quite different without you.
   
- [**Structured README**][readme-shaloo]<br>
  Unfortunatly I found this little gem just after this readme was completed, but we share many common ideas. Thanks @shaloo!

- **[markdownify][prog-markdownify]** - _A minimal markdown editor desktop app_<br>
   A intuitive and responsive editor with all the features you could wish for. It even fetches badges from the internet and displays them! It may sound odd, but it has been quite fun to write this readme. Thanks @amitmerchant1990 for that great tool!

- **[shields.io][shields.io]** - _badges as a service_ <br>
   A very clever solution to deliver custom and scalable badges. Thanks to the whole @badges team!

- **[Text ASCII Art Generator][prog-ascii-art]**<br>
   Get any in a variety of ASCII Art fonts. It's very simple and intuitive to use. Thanks @patorjk!

<br>

### Related Projects

 - none (yet)
 
Want yours to be listed here, too? Create a merge request or [**get in touch**](#get-help).

<br>

### Additional Resources

All works referenced throughout this readme are listed below for your convenience. Thank you for sharing your thoughts and ideas with the world.

<br>

#### Human Behavior

- [**How to Write Documentation for People that Don't Read**][video-people-dont-read] by Kevin Burke
- [**How Users Read on the Web**][article-read-on-the-web] by Jakob Nielsen
- [**F-Pattern in Reading Digital Content**][video-fshape]
- [**Do You Have A 7 Second Website?**][article-few-seconds]
- [**Start with _why_**][video-start-with-why] TED Talk by Simon Sinek
- **[Study on badges on GitHub][study-badges], or as a [pdf][study-badges-paper]** - _"Adding Sparkle to Social Coding: An Empirical Study of Repository Badges in the npm Ecosystem"_

#### Thoughs about the Readme

- [**Readme Driven Development**][article-rdd] by Tom Preston-Werner, founder of GitHub (@mojombo)
- [**Sample Readme**][readme-fvcproductions] by @fvcproductions
- [**Open Source Project Template**][readme-fcpb] by @cfpb
- [**Art of README**][readme-noffle] by @noffle
- [**Standard Readme**][readme-richardlitt] by @richardlitt
- [**Zalando's README Template**][readme-zalando] by @ zalando


#### Formatting

- [**Basic writing and formatting syntax**][markdown-git] on GitHub
- [**Markdown Cheatsheet**][markdown-cheatsheet] by @adam-p

#### Licensing

 - [**choosealicense.com**][choosealicense.com]
 - [**License MIT**][license-mit]
 - [**License CC0**][license-cc0]
 - [**License CC0 - fallback clause**][license-cc0-fallback]
 - [**How can I place software in the public domain?**][license-mit-vs-cc0] on opensource.stackexchange.com
 - [**Open Source (Almost) Everything**][article-open-source-everything] by Tom Preston-Werner (@mojombo)

<br> 

## License
This project is proudly licensed under the [MIT license][git-license].

The MIT license was chosen to give you the freedom to use this project in any way you want, while protecting all contributors from legal claims. Good code works, great code works for everyone. If this code has become a part of one of your projects, a link back to us would be highly appreciated. Thanks!


<!-- LINKS -->
<!-- in-line references: websites -->

[choosealicense.com]:https://choosealicense.com
[shields.io]:https://shields.io
[hackaday.io]:https://hackaday.io
[semver.org]:https://semver.org/


<!-- in-line references to github -->

[git-download]:https://github.com/nqtronix/git-template/archive/master.zip
[git-issues]:https://github.com/nqtronix/git-template/issues
[git-readme]:https://github.com/nqtronix/git-template/blob/master/README.md
[git-license]:https://github.com/nqtronix/git-template/blob/master/LICENSE.md
[git-contribute]:https://github.com/nqtronix/git-template/blob/master/CONTRIBUTING.md
[git-badges]:https://github.com/nqtronix/git-template/blob/master/badges.md
[git-profile]:https://github.com/nqtronix

<!-- in-line references by tag -->

[prog-markdownify]:https://github.com/amitmerchant1990/electron-markdownify
[prog-markdown-editor]:https://jbt.github.io/markdown-editor/
[prog-ascii-art]: http://patorjk.com/software/taag

[readme-matiassingers]:https://github.com/matiassingers/awesome-readme
[readme-fvcproductions]:https://gist.github.com/fvcproductions/1bfc2d4aecb01a834b46
[readme-fcpb]:https://github.com/cfpb/open-source-project-template
[readme-noffle]:https://github.com/noffle/art-of-readme
[readme-richardlitt]:https://github.com/richardlitt/standard-readme
[readme-zalando]:https://github.com/zalando/zalando-howto-open-source/blob/master/READMEtemplate.md
[readme-shaloo]:https://github.com/shaloo/structuredreadme

[markdown-cheatsheet]:https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
[markdown-git]:https://help.github.com/articles/basic-writing-and-formatting-syntax

[article-rdd]:http://tom.preston-werner.com/2010/08/23/readme-driven-development.html
[article-open-source-everything]:http://tom.preston-werner.com/2011/11/22/open-source-everything.html
[article-read-on-the-web]:https://www.nngroup.com/articles/how-users-read-on-the-web
[article-few-seconds]:https://www.hallme.com/blog/do-you-have-a-7-second-website

[study-badges]:https://cmustrudel.github.io/projects/badges/
[study-badges-paper]:https://cmustrudel.github.io/papers/icse18badges.pdf

[license-mit]:https://opensource.org/licenses/MIT
[license-mit-vs-cc0]:https://opensource.stackexchange.com/questions/1371/how-can-i-place-software-in-the-public-domain/1381#1381
[license-cc0]:https://creativecommons.org/publicdomain/zero/1.0/
[license-cc0-fallback]:https://wiki.creativecommons.org/wiki/CC0_FAQ#How_does_it_work.3F

[video-people-dont-read]:https://youtu.be/sQP_hUNCrcE?t=68
[video-people-dont-read-scan]:https://youtu.be/sQP_hUNCrcE?t=90
[video-fshape]:https://www.youtube.com/watch?v=XU1-Rz2Q7-E
[video-start-with-why]:https://www.youtube.com/watch?v=u4ZoJKF_VuA
