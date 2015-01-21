## General Idea: The Effects of Using Open-source Code
I would like to create an easily digestible way to communicate the relationship of OSS with non-OSS code, illustrating how open-source and proprietary code can interact, and the legal effects of those interactions under various open-source licenses.





## Details
Specifically, I hope to both legally categorize (perhaps based on [this assessment](#legal-assessment)) and visually represent the types of worries proprietary code owners and creators have when using, running, relying on, or interacting with open-source code under different licenses.  My goal is to do for the average programmer's code-license-interaction worries what Creative Commons has done for the average graphic designer's image-licensing worries: give creators easily digestible cues as to the impact of their code use, using both language and visual icons to describe the effects of existing open-source licenses.

## Possible Legal Issues to Assess and Graphically Represent
* Direct code copying (e.g., permissive MIT License vs. GPL)
* Statically linking
* Dynamically linking
* Derivative works in interpreted (runtime-compiled) languages
* ...others?


## Comparable Creative Commons Categorizations and Visual Representations
### Creative Commons license-descriptor icons (buttons)
These icons are applied to individual works in order to describe what creators may do to them under their corresponding Creative Commons licenses. Note that they describe the license; they do not legally constitute a license on their own. Each icon represents several of the most important legal issues involved in copying or using the work to which it is affixed.

![Creative Commons button icons](/images/creative-commons-button-icons.png)

### Creative Commons legal-issue icons (large icons)
Each icon represents a single legal issue, which can be used on its own when discussing that issue or incorporated into a license-descriptor icon like those above.
![Creative Commons large icons (each showing a single issue)](images/creative-commons-large-icons.png)


## Intended Audience
The intented audience for the end product is developers, policy-makers (within developer organizations) who set rules on what licenses can and cannot be incorporated into the development process, and the segment of the open-source community that purports to assist developers in selecting licenses for their own code.



## Links

* ### Legal assessment
  * https://www.softwarefreedom.org/resources/2014/SFLC-Guide_to_GPL_Compliance_2d_ed.html

* ### Example Icons
  * http://creativecommons.org/about/downloads
  * http://commons.wikimedia.org/wiki/Creative_Commons_icons

* ### Background
  * https://en.wikipedia.org/wiki/GNU_General_Public_License Wikipedia: GNU GPL]
  * https://en.wikipedia.org/wiki/GNU_Lesser_General_Public_License#Choosing_to_license_a_library_under_the_GPL_or_the_LGPL
  * https://wiki.creativecommons.org/CC0_FAQ
  * http://www.markosproject.eu/

* ### For Programmers
  * http://www.fsf.org/licensing/
  * http://www.gnu.org/licenses/license-recommendations.html
  * http://www.gnu.org/licenses/license-list.html
  * http://www.gnu.org/licenses/gpl-faq.html

* ### For Project Managers
  * https://www.clahub.com/
  * http://elinux.org/Developer_Certificate_Of_Origin
  * http://selector.harmonyagreements.org/

* ### For Auditors
  * https://www.blackducksoftware.com/products/black-duck-suite/protex/black-duck-code-label
  * http://sourceauditor.com/blog/tag/lawsuits-on-open-source/
  * http://arstechnica.com/information-technology/2009/05/cisco-settles-fsf-gpl-lawsuit-appoints-compliance-officer/
