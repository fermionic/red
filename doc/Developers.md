Red Developer Guide
===================

**Here is how you can join us.**

First, get yourself a working git package on the system where you will be
doing development.

Create your own github account.

You may fork/clone the Red repository from [https://github.com/friendica/red.git](https://github.com/friendica/red.git).

Follow the instructions provided here: [http://help.github.com/fork-a-repo/](http://help.github.com/fork-a-repo/)
to create and use your own tracking fork on github

Then go to your github page and create a "Pull request" when you are ready
to notify us to merge your work.

**Translations**

Our translations are managed through Transifex. If you wish to help out translating the Red Matrix to another language, sign up on transifex.com, visit [https://www.transifex.com/projects/p/red-matrix/](https://www.transifex.com/projects/p/red-matrix/) and request to join one of the existing language teams or create a new one. Notify one of the core developers when you have a translation update which requires merging, or ask about merging it yourself if you're comfortable with git and PHP. We have a string file called 'messages.po' which is gettext compliant and a handful of email templates, and from there we automatically generate the application's language files.   

**Important**

Please pull in any changes from the project repository and merge them with your work **before** issuing a pull request. We reserve the right to reject any patch which results in a large number of merge conflicts. This is especially true in the case of language translations - where we may not be able to understand the subtle differences between conflicting versions.

Also - **test your changes**. Don't assume that a simple fix won't break something else. If possible get an experienced Red developer to review the code. 

Further documentation can be found at the Github wiki pages at: [https://github.com/friendica/red/wiki](https://github.com/friendica/red/wiki).
