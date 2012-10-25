jquery.bx.tabs
==============

A simple light weight jquery tab plugin.

Tabs are a great way of displaying content when you have limited space on the screen to play with. I built a little jQuery tab plugin a while ago and it has come in handy a few times.

The plugin is relatively easy to setup, simple apply the plugin to the tabs and specify the content panels using the option parameter tabbedContentSelector.

Example:

$(function() {
    $('ul.bxTabs li').bxTabs({ tabbedContentSelector: 'ul.bxTabContent li' });
});

I have also added an accessible function to jump between tabs. You will need to specify the index of the tab you like displayed.
Note: index starts at ’0'

Example:

$('ul.bxTabs li').bxTabs.goToTab(2);

Happy tabbing!