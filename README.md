# Work-Shop iA-Writer Template

This file is an ongoing iteration of Work-Shop's iA Writer Proposal Template. We use this template to compile markdown documents into printable or presentation material.

## Installation

Clone this repository to your workspace. iA-Writer templates are Mac OSX packages, so we need to do a little bit of additional configuration before we're ready to use the template.

1. ```cd``` into your iA Writer Template directory. By default this is  ```"/Applications/iA Writer.app/Contents/Resources/Templates"```. All iA Writer templates are placed in this directory. Make a new directory in this location with ```mkdir Work-Shop.iatemplate``` and enter it (you may need to ```sudo``` your ```mkdir```).

2. Next, you need to symbolically link the cloned repository to this location. If you cloned this repository to ```User/<username>/<workspace-name>/workshop-iawriter-template``` then run ```ln -s "User/<username>/<workspace-name>/workshop-iawriter-template/Contents" Contents```. This should create a directory called contents in the iA Writer template directory.

3. Finally, in Finder, navigate to ```"/Applications/iA Writer.app/Contents/Resources/Templates"``` and drag the icon for ```Work-Shop.iatemplate``` over the iA Writer icon. The template should install itself.
