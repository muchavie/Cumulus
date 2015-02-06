---
title: NPSP Code Contributor's Guide: Do the Work
layout: default
---
# [Home](http://developer.salesforcefoundation.org/Cumulus/Contributor/) > Do the Work!

### I've got my IDE. Great ... What should I do?

Phew! You are now all set up to contribute code to NPSP. For each new feature, you should:
Find an existing [github issue](github.com/SalesforceFoundation/Cumulus/issues) or create a new one.

You may have your own ideas for features or feature enhancements that you want to create and make available to the world.  That’s great! First step is to open up a [new github issue](https://github.com/SalesforceFoundation/Cumulus/issues/new) that describes your idea and what you want to build.

If you’re not sure what you want to build but are looking for a way to contribute, it’s actually pretty easy to find something to work on.

First, head back over to the [NPSP github issues](github.com/SalesforceFoundation/Cumulus/issues) and use the big ‘Labels’ tab at the top to select a set of labels to filter the issue list by. ‘Bugs’, ‘Feature Requests’ and ‘Enhancements’ are a good place to start.

You can also post to the [Power of Us Hub’s Nonprofit Start Pack group](https://powerofus.force.com/_ui/core/chatter/groups/GroupProfilePage?g=0F980000000CjRe) to discuss ideas or find inspiration from the community.

If you see something that’s interesting to you, need clarification, have something to add to a conversation, or just want to share an opinion, feel free to comment on the case or just start working.

We recommend always posting on the issue to see if it makes sense to pick it up, just in case somebody else is already working what you’ve selected! Also feel free to ask questions about the issue or discuss proposed solutions directly in the github issue.

# NPSP Apex Documentation

We've put together a handy site that's an invaluable tool in understanding the NPSP code base: [ApexDocs](http://developer.salesforcefoundation.org/Cumulus/). Now all that's left to do is to do the coding!

# Add To The Cumulus Unmanaged Package

If you've added any metadata that needs to be part of NPSP as part of your feature, it needs to be added to the Cumulus unmanaged package. Examples include a new class, trigger, or page, or really anything else like a new field, custom setting, page layout, etc.

1. Navigate to Setup > Create > Packages
2. Click on the Cumulus package name
3. Click Add
4. Select the correct Component Type
5. Check the box next to your component
6. Click Add To Package

Next up, learn how to push your changes to github, and [submit them to the Salesforce Foundation for review](Submit-Your-Feature.html).