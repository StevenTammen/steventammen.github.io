---
permalink: /worthy-projects/
layout: layout
title: Worthy Projects
---

<div class="center">

   <h1>Worthy Projects</h1>

   <a href="https://github.com/StevenTammen/steventammen.github.io/edit/master/pages/worthy-projects.md" target="_blank">
     <img src="https://steventammen.github.io/assets/images/GitHub.png" height="30" width="30">
   </a> &nbsp; &nbsp;

   <a href="http://prose.io/#StevenTammen/steventammen.github.io/edit/master/pages/worthy-projects.md" target="_blank">
     <img src="https://steventammen.github.io/assets/images/Prose.png" height="30" width="30">
   </a>

</div>

## Table of Contents

- [Overview](#overview)
- [Physical Products](#physical-products)
- [Software Programs](#software-programs)
- [Companies](#companies)

## Overview

This is a list of physical products, software programs, and companies that I think should exist but currently do not. I am unsure how many (if any) I will be able to make progress on given my busy schedule. I would prefer to keep everything open source (including designs for physical products), but if somebody wants to take any of these to market, I would be happy to explain in excruciating detail how I would design/implement each thing. In other words, I would rather that they exist in a proprietary form than in no form at all, even though I would prefer that they exist in an open source form.

If you think you can help in any way or are just curious about my thoughts, please email me at [steven@steventammen.com](mailto:steven@steventammen.com). I plan to write more fully on each of these ideas when I get the time. (I'll link to these more full explanations as they are available).

## Physical Products

- Development of an open source, split-hand, concacave, columnar, portable, ergonomic keyboard -- one that takes design cues from the [Dactyl Keyboard](https://github.com/adereth/dactyl-keyboard) while slimming down the number of keys and adding built-in adjustability. Try to get an assembly/distribution service of some sort in place to bring ergonomic, split-hand, concave keyboards to the masses.
- Development of an open source, ergonomic, finger-controlled trackball that allows for a perfectly straight wrist and low pronation.
- Development of an open source, side-actuated mechanical pencil: an update of the now-discontinued [Pentel Original Quicker Clicker](http://www.pentel.com/store/quicker-clicker-mechanical-pencil-original-config). Make it easy to take apart, and make parts replaceable.
- Development of an open source, fully waterproof (i.e., submersible) multi-purpose backpack: an update of the now-discontinued [Ortlieb Flight 27](http://www.wiggle.fr/sac-a-dos-ortlieb-flight-27-litres-avec-tizip/).

## Software Programs

- Development of an open source, cross-platform keyboard program that supports key remapping, hotstrings, layers, macros, running programs through a hotstring/macro, opening URLs in the default browser through a hotstring/macro, and so forth. Also develop a spin-off project for implementing as meany features as possible on the firmware level. (Perhaps contributing to [QMK firmware](https://github.com/qmk/qmk_firmware/)?)
- Development of an open source, cross-platform program to enable Vim/Spacemacs emulation across the entire operating system environment (configurable by .vimrc/.spacemacs files just like Vim/Spacemacs). Focus on making uneditable text selectable, links/menus accessible by keyboard, and commands consistent across programs.
- Development of customizable real-time previews for Emacs Org-mode objects to improve the editing experience
  - See [Typora](https://typora.io/) for an example of this being done with Markdown.
  - Similar to current support for LaTeX blocks: commands to display the source versus displaying the output.
  - Extend concept to source blocks (with options for line numbers, syntax highlighting, etc.), verse blocks, quote blocks, etc. Remove markup from working environment except when necessary. Text in blocks should be editable in the formatted display output.
  - Also create auto-preview for tables with full borders, cell highlighting, header formatting, etc. Make tables editable with styling applied all the time.
  - Work on WYSIWYG implementation of footnotes and [org-ref](https://github.com/jkitchin/org-ref) citations and labels so that footnotes and citations appear how they would in a published document. Enable customization of what gets displayed, and in what format.
  - Give additional configuration options for the inline display of images in Org mode (scaling, alignment, etc.).
  - Support for shortcodes, to be replaced by stylized output within the buffer itself. (Cf. typical shortcodes in templating programs).
  - Have commands to show/hide source across the entire document for all object types, show/hide source across the entire document for one object type, and show/hide source for the object currently under the cursor. Do not automatically show source upon cursor hover to prevent disruption to cursor tracking when editing -- use activation key sequences instead.
  - Shortcuts for easily removing text from current markup object (e.g., delete "#+BEGIN\_SRC" and "#+END\_SRC", bold markup, etc.) and changing the type of object.
- Development of an open source universal electronic publishing standard (for novels, reference books, articles, etc.)
- Development of an open source, cross-platform e-reading program, to be used (non-exclusively) with the standard above. Also develop API for using the optimally designed reading interface in web pages.
- Development of an open source, narrowly scoped networking platform to connect people with others who either do or do not match them quantitatively across attributes. Allow user-defined rankings of attribute importance, and also allow for privatization of attributes (obviously keep data secure). Try to not to limit use cases (e.g., by trying to funnel users into using the platform as a dating app, a business networking app, etc.) and focus on designing an intelligent algorithm to give people an option for having a quantitative base for forming relationships with others -- to take the guesswork out of finding people *like* you (for hobby groups, discussion groups, potential partners, etc.) and people *unlike* you (for getting perspective, having intelligent debates, etc.). Try to enforce a standard of honesty to make results meaningful.
  - Provide options for copious amounts of user-feedback throughout the whole process, and use data analytics to improve the algorithm's predictive power over time.
- Development of an open source, crowd-driven charity app. Focus on completely eliminating overhead and organizing local (or international) groups of volunteers to effectively get stuff done. Have options for users to self-identify in fields related to their talents. For example, a person in building construction can declare so and get matched with people with complementary skills or access to materials -- like a person with organization/leadership skills, a person with supply chain/procurement skills, and a person who has access to a cement-mixer, bulldozer, and paving equipment from his day-job connections. Such a team might accomplish heavy construction tasks like helping lay the foundation for a new women's shelter or clearing a plot of land/paving it to give additional parking space to a volunteer health center. Have built in apprenticeship/knowledge-building aspect: make it easy for inexperienced people to get hands on experience across many different fields without paying for formal education. (Strive to get certifications in place in the long term to make it, combined with MOOC classes from places like edX and Coursera, a full replacement for paid education). Also figure out some way to sort and analyze the validity and urgency of requests for assistance to most effectively prioritize aid.
  - Start out in a narrowly defined field, such as construction/remodelling, website/app development, medical care, etc. to make sure the quality is top notch. Branch out across the volunteering spectrum as resources allow.
- Development of an open source translation platform for international scholarship, allowing multilingul academics to widen access to research that would otherwise be language-restricted. Work to enable a feedback and correction system for the translations, and perhaps even get into natural language processing and AI/machine learning to automate some of the translation (in the long term).
- Development of an open source peer-review scholarship platform to free academia from paywalls, journal exclusivity and snobbishness, and ideas of "publish once and don't update." Much more emphasis on continuous improvement than static content in journals. Try to focus on objective criteria (e.g., problems in research methodology, ideas for replicability and generalizability) over subjective opinions of work. Try to get it accepted by influential academics across many fields to get research in an environment more conducive to actual rapid knowledge advancement: dynamic, open source content vs. static paywall-protected scholarship. Also allow non-academic professionals in related fields to offer their feedback to better connect the perspectives from the ivory tower and the real world.
  - Also try to generalize it to internet content in general. The internet has a vast amount of knowledge, but not all of it is correct/verifiable, and some of it is downright misleading. Creating an environment for academics and knowledgeable laymen to filter the junk from the interesting, useful information for the rest of us would be *huge* in increasing the overall usefulness of internet research across fields.
  - Try not to fall prey to fallacious thinking related to the argument from authority: encourage real discussion, even if it includes dissenting or unpopular opinions. Try to make the system based on data and evidence as much as possible.
- Development of an open source app for connecting homeschooling families in communities and helping them organize effective curricula for their children. Enable scheduling around experts/parents with different focuses to give diverse experiences, and allow for matching families based upon shared interests and perspectives.
- Development of an open-source program for practicing reading clock faces, both of the 12 and 24 hour variety. Also have option for training on 12 hour faces with rollover times (13:00, 14:00, etc.) in the afternoon.

## Companies

- A healthy fast food company with responsible sourcing. For example, a better burger: 1/3 lb. organic grass-fed/grass-finished ground beef patty, organic freshly-milled whole wheat bun, organic grass-fed cheddar cheese slice, organic tomato ketchup (minimally sweetened with a low glycemic sweetner like coconut palm sugar, and absolutely free from high-fructose corn syrup), organic romaine leaves.
  - Encourage the purchase of 1 serving of leafy green vegetables (spinach, kale, etc.) and 1 serving of non-starchy vegetables (broccoli, cauliflower, Brussels sprouts, etc.) with every entree purchase -- create tasty recipes to get more people to eat them. Try to make the cost of adding these healthy options low to encourage the purchase of them.
  - Avoid inflating prices simply because it would be possible to (the supply for healthy, responsibly-sourced, fast food is just about non-existent). Try to create a sustainable business model to fill this market need in the long haul.
  - Could follow a "have it all" type of restuarant model (burgers, Mexican food, pizza, Asian food, etc.), or create different store models managed under one brand.
