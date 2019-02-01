---
layout: text
title: Typeface and Interface
tags: Writing
discription:
publish: January 2016
year: 2016
image: /images/projects/type_metafont.JPG
permalink: /projects/typeface
---

<img src="/images/projects/type_metafont.JPG">

<p><em>“Fonts need to be edited just as carefully as texts do—and may need to be reedited, like texts, when their circumstances change. The editing of fonts, like the editing of texts, begin before their birth and never ends.”</em> —Robert Bringhurst</p>

<p><em>“A programmer writes some code and inevitably makes the mistakes that result in the malfunctions called bugs. Then, for some period of time, normally longer than the time it takes to design and write the code in the first place, the programmer tries to remove the mistakes.”</em> —Ellen Ullman</p>


<h4>Interface</h4>
<p>Software is <a href="http://www.wsj.com/news/articles/SB10001424053111903480904576512250915629460">eating</a> everything around us—our books, our cameras, our watches, our world. For better and for worse, software is replacing centuries-old technology, freeing them from their fixed past, moving them to a networked, editable, and ever-changing future. The German designer and writer <a href="https://en.wikipedia.org/wiki/Gui_Bonsiepe">Gui Bonsiepe</a> believes that in the future all designers will be “interface designers”<a id="footnote-1-ref" class="footnote" href="#footnote-1">1</a>, for in times of information overload, it’s more important for the designer to design the access to information, the navigation through it, than to design the form of individual messages.</p>

<p>Digital interfaces are designed and developed in an iterative fashion. Where the designer historically designed artifacts in isolation before putting them out into the world fully formed and finished, the interface learns and improves based on its interactions. Developers will release a minimum viable product to learn how the consumer reacts to it: Where do they click? What is working? What is missing? Are there bugs? The release isn’t the end of development—the engineers keep working, refining, fixing, improving.</p>

<p>The writer historically saw her work as finished when it was committed to print—published, released, and read. When the words are complete, it is sent to printing presses, bound, printed and fixed. But the interface has become both the place of creation and consumption, the mode of production dramatically reduced. What happens when the same screen is used to write/create/design but also to distribute/consume/view? In his essay, <a href="http://2x4.org/ideas/26/wysiwyg/">WYSIWYG</a>, Michael Rock writes:</p>

<blockquote>
<p>Perhaps the most significant implication of the WYSIWYG revolution was to bring immediacy back to the process of typography. Now we compose on a screen that simulates the page we have in mind. With that innovation, typography is reunited with writing: the sketch is the design. We still take the sentence as raw material but the work of typography is a real-time elaboration of the language. This is amplified by the fact that the finished product is now often distributed on the very medium on which it is composed, the monitor. The permanent become permanently transient. So now the question becomes: when is typography done?</p>
</blockquote>

<p>Typography has historically been a fixed artifact. Perhaps the longest surviving pieces of graphic design are typefaces—fixed in time, but forever repurposed again and again, year after year. The process of designing a typeface, in a very McLuhan way, has been shaped by the production of the printed text. The early production of type faces was a manual process—letterforms carved in hardwood and set individually, letter by letter, on the press. By the late 1800s, type designers would draw each letterform at large scales which would be traced by engraving machines.</p>

<p>When <a href="http://www.kadist.org/en">Kadist Arts Foundation</a> needed a new logotype in 2010, they commissioned Dexter Sinister, seeking mark that suggested change and mutation, rather than a static corporate brand. Dexter Sinister, the designer/artist duo of David Reinfurt and Stuart Bailey, employed a typeface they designed called Meta-the-difference-between-the-two-Font, which raises the same question as Rock: when is typography done?</p>

<p>Meta-the-difference-between-the-two-Font was developed using MetaFont, the now thirty-year old typography system and the first digital font program.</p>

<h4>Metafont</h4>
<p>Donald Knuth didn’t set out to be a typographer. After receiving a bachelor of science in physics and a PhD in mathematics, Knuth started teaching at Caltech in 1963 and was commissioned to write a book on computer programming language compilers. The book, <em>The Art of Computer Programming</em>, quickly grew into a series of seven volumes, the first published in 1968.</p>

<p>Knuth had high standards for the printed appearance of his books. The first volume was typeset using mechanical hot type in <a href="https://www.myfonts.com/fonts/mti/monotype-modern/">Monotype Modern 8A</a> but in 1977, due to financial restrictions, volume 2 was set to be printed with new optical typesetting. At the time, the optical typesetting used lower-quality faces, often just copies from the ones designed for Monotype and other foundries. This meant the details and features that Knuth loved seeing on the pages would be lost, replaced with a lower quality facsimile.</p>

<p>Knuth saw typesetting as analogous to programming and started developing a program to set and render type digitally—one or zero, ink or no ink. In 1978, he released <a href="https://www.tug.org/whatis.html">TeX</a>, a typesetting system, and <a href="http://metafont.latex.free.fr">Metafont</a>, the programming language.</p>

<p>Knuth suggested that the design of one letterform, an “A’ for example, presupposes all sorts of design decisions for the other 25 characters. Metafont allowed the user to generate an unlimited number of fonts based on a limited number of parameters such as weight and slant. Following Metafont, Apple and Microsoft developed TrueType and Adobe created PostScript, both outline font standards. Metafont was different in that it didn’t create outlines but rather a series of vectors that could be edited and changed based on variables in the program. For example, within the code, one could adjust the slant or weight with a variable that would then affect the entire font and then output their design as a Postscript bitmap file.</p>

<p>Where Metafont allowed for infinite design decisions based on  limited parameters at different points in time, when Dexter Sinister created Meta-the-difference-between-the-two-Font they wondered if they could make <em>time</em> its own parameter that could also be adjusted. In the Kadist identity, <a href="http://www.kadist.org/en/programs/all/1467">the duo signed a ten-year contract</a> and programmed their face to change everyday—adapting a set of five variables—pen, weight, slant, superbness, and curliness—subtly each day over the next decade. Each time Kadist needs a font, the software produces a new, unique version.</p>
<p><a href="https://vimeo.com/65248695">They describe their typeface</a> as a typographic oxymoron: a <em>single</em> typeface that is also <em>many</em> typefaces.</p>

<h4>Spirit</h4>
<p>Software, unlike a typeface, is not a fixed artifact. Software is famously forever unfinished—living, breathing lines of code that can be edited, updated, refined, and changed. Updates get pushed to our phones and computers while we sleep, gifting us with new features and fixing bugs.</p>

<p>When Apple released iOS9, the operating system for iPhones, iPads, and the Apple Watch, in 2015, they abandoned Helvetica, the typeface used on the iPhone since it launched in 2007 with <a href="https://developer.apple.com/fonts/">San Francisco</a>, a face designed in house by Apple for their software. A few months later, the Mac’s operating system, OS X El Capitan, also replaced Helvetica (which replaced Lucida Grande a year earlier) with San Francisco.</p>

<p>The three major operating systems—from Apple, Google, and Microsoft—are now using custom typography as system fonts. Microsoft unveiled Segoe UI along with Windows 7 (adapted from Steve Mattoon’s Segoe, replacing Tahoma), and Google released <a href="https://www.google.com/design/spec/resources/roboto-noto-fonts.html">Roboto</a> in 2007, designed especially for their Android devices.</p>

<p>When a typeface lives in a digital-only setting, and even more so in a closed system like iOS or Android, the production of the typeface is no longer fixed. It no longer has to remain a static, unchanging artifact like it has for all its history. The design and production of a typeface could, hypothetically, borrow the process of software—released with incremental changes, improvements, and new features overtime. Google has already started experimenting with this. In a piece for New York Magazine, <a href="http://nymag.com/daily/intelligencer/2014/07/google-is-designing-the-font-of-the-future.html">Kevin Roose writes how Roboto has already evolved since its first appearance</a>:</p>

<blockquote>
<p>Unlike pre-digital fonts, which were essentially set in stone after being finished, Google got to keep working on Roboto. And in subsequent editions, the typeface got a face-lift. The uppercase B got a little slimmer. The comma was made less angular. “The old model for releasing metal typefaces doesn’t make sense for an operating system that is constantly improving,” Duarte said. “As the system evolves over time, the type should evolve along with it.”</p>
</blockquote>

<p>Apple seems to view San Francisco in the same way. So far, the face has only appeared in the interface and developed as a digital native face<a id="footnote-2-ref" class="footnote" href="#footnote-2">2</a>. ”San Francisco is a modern font,” <a href="https://medium.com/@mach/the-secret-of-san-francisco-fonts-4b5295d9a745#.frr2y72os">writes Akinori Machino</a>, “It will change the typefaces dynamically according to the context. It is a kind of “Digital Native” fonts for the digital age.” There are multiple version of the font and the operating system can serve up the appropriate letterforms depending on the context. The watch, for example, uses a slightly condensed version. Like a traditional face, there are Display and Text faces but the software can detect the specified size and switch to the appropriate weight.</p>

<p>Apple can update, refine, and edit San Francisco and push it to our devices with each software update if it wished, leaving no record of how it looked before, save for those who don’t download the new release. San Francisco is its own typographic oxymoron—a single typeface that is also many typefaces.</p>

<p>In 1985, fellow mathematician Douglas Hofstadter read about Metafont in an article Knuth wrote in a publication called <em>Visible Language</em>. Hofstadter, inspired by Knuth’s theory, believed there was more to type design than mathematical proportions and fixed parameters: “Clearly there is much more going on in typefaces than meets the eye,” <a href="https://books.google.com/books?id=o8jzWF7rD6oC&amp;pg=PA240&amp;lpg=PA240&amp;dq=douglas+hofstadter+metafont&amp;source=bl&amp;ots=jRAb-sJmjt&amp;sig=emQ6YRMHm1g7q-9epAVxFpnyxb8&amp;hl=en&amp;sa=X&amp;ved=0ahUKEwjBy9rtt5PKAhVGeT4KHXYfAZYQ6AEIIzAB#v=onepage&amp;q=douglas%20hofstadter%20metafont&amp;f=false">he wrote</a>, “underneath or behind each instance of ‘A’ there lurks a concept, a Platonic entity, a spirit.” He went on write about the difference between “the letter of the law” and “the spirit of the law”—lawyers interpret the law, he argued, bringing their own experiences to it and therefore changing and evolving laws to fit the new time. He believed typefaces may be the same way.</p>

<p>Leonardo da Vinci is credited with saying a painting is never finished, only abandoned. The same is true of software. Software is a living piece of code—constantly being updated, refined, corrected, and added to. There never comes a moment when an application or a website is complete. To borrow Bonsiepe’s prediction, perhaps a type designer is an interface designer. “A design today is rarely a substantive, realized product.” writes Max Bruinsma in his essay, <a href="http://maxbruinsma.nl/index1.html?ideal-e.html"><em>An Ideal Design is Not Yet</em></a>, “More and more often it is a proposal that gains its final form in the interaction with the audience, for better or for worse.”</p>
<p>The same is true of the typeface: an artifact is static, but the spirit moves. &#10006;</p>


<!--Footnotes -->
<div class="notes">
<h4>Notes</h4>
<ol>
<li><p id="footnote-1">I learned about Bonsiepe’s work in the exhibition catalog for the 2013 show <em>All Possible Futures</em>, organized by Jon Sueda in San Francisco. <a href="#footnote-1-ref">↩</a></p></li>

<li><p id="footnote-2">Although I wouldn’t be surprised if they start using it in marketing material as well. They are using San Francisco in the word marks for the Apple Watch and Apple Music but the rest of their new marketing, website, and advertising still use Myriad. <a href="#footnote-2-ref">↩</a></p></li>
</ol>
</div>
