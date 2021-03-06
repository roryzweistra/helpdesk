* JavaScript Bubbling Library
* http://www.bubbling-library.com

* Copyright (c) 2008, Caridy Pati�o
* All rights reserved.
***************************************************************************
* YUI-CMS Bubbling Library Release Notes

*** version 1.50 *** (Tested over YUI 2.5.1)

This release synchronizes the SourceForge version with Bubbling Library -- version number 1.50.
Please see the following article for information on this specific version increment at:
http://www.bubbling-library.com/eng/releases/2008/04/22/yui-cms-150-released

This release is focused in the correction of a series of bugs and optimization and the inclusion of new examples. This is the most stable version ever.

The following components are updated with this release:

   * Bubbling Core: Improving the decoupling support. Read more here:
     http://yuiblog.com/blog/2008/04/22/caridy-decoupling/

   * Dispatcher: Integration with the YUI Get Utility to load external sources. Introducing a new pipeline to allow redefinition of the eval routine (now you can use your own method to execute inline script). Integration with the loading mask.

   * Wizard: Full integration with the Dispatcher, now support Tabview Delegation like the dispatcher does. Integration with the loading mask.
   
   * Loading Mask: Solving the issue with the Flash Components on body resize. Including new pipelines for AJAX routine.

In addition to new features, you'll find updates and bug fixes throughout the extension.

*** version 1.40 *** (Tested over YUI 2.4.1)

This release synchronizes the SourceForge version with Bubbling Library -- version number 1.40.
Please see the following article for information on this specific version increment at:
http://www.bubbling-library.com/eng/releases/2008/01/31/yui-cms-140-released

NOTE: I was away from my work for more than a month, and after a surgery in my left hand, I'm back and working, with a lot of ideas and energies, so you don't worry about the future of the Bubbling Extension, I've plans to keep it on track and watching the YUI's releases in this new year.

This huge release introduce new components and reorder the oldones, correction of a series of bugs (thanks guys for sent me the feedbacks), and of course the inclusion of new examples.

The following new components are introduced with this release:

   * Accordion Manager (Widgets): See how to create the correct HTML's markup and the CSS's rules to create expandable and collapsible areas, including horizontal and vertical accordion, also reusing the YUI Panel Sam Skin, animation and sound's effect features.
   
   * Sound Manager (Plugins): See how to integrate the Javascript with Flash to play sounds, effects and mp3 in general in your web pages. You can easily use this plugin to add sound effects to the DOM's elements based on the classname of the elements.
   
   * Core Package (Script): Similar to the YUI utilities.js, to group the most common components in a single file:
			* Bubbling Core
			* Loading Mask
			* Dispatcher Plugin
			* Form Manager Plugin
			* Translator Plugin
			* Lighter Plugin
			* Tooltip Manager
			* Accordion Manager
			* BASE64 and CRC utility
   
The following components are updated with this release:

   * Bubbling Core: Now called (YAHOO.Bubbling).

   * Dispatcher: Now called (YAHOO.plugin.Dispatcher).

   * Selector: The selector plugin was renamed in this version because the YUI's Team have released a DOM Selector utility with the same name... so, I just decided to change the name to Lighter (Area Highlighter Manager: YAHOO.plugin.Lighter).

   * Wizard: Now called (Form Manager: YAHOO.plugin.WizardManager). Improved mechanism for forms with file fields (upload file), and support for mixing traditional forms and dynamic forms in the same area using the classname for the form.

   * Loading Mask: Now support dynamic message update before display it.

   * Translator Plugin: Now mounted over the YUI Json Package.
   
NOTA: All the components' names updated will keep the backward compatibility name for a while, except the Lighter (former selector) plugin.

You can see it in action in the examples.
http://www.bubbling-library.com/eng/examples

In addition to new features, you'll find updates and bug fixes throughout the extension.

*** version 1.32 *** (Tested over YUI 2.3.1)

This release synchronizes the SourceForge version with Bubbling Library -- version number 1.32.
Please see the following article for information on this specific version increment at:
http://www.bubbling-library.com/eng/releases/2007/11/05/yui-cms-132-released

This minor release is focused in the correction of a series of bugs, the inclusion of new examples, and the introduction of a new widget.

The following components are updated with this release:

   * Bubbling Core: Included a generic communication mechanism for widget2widget, widget2browser and widget2server messages.

   * Dispatcher: Two new moments included (onStart, onLoad, onError), and an improved mechanism for multiple areas in the same page.

   * Wizard: Improved mechanism for multiple submitions, clearing the YUI connection's data form after each transaction.

Also, this release introduces a new widget called "loading", this utility will allow you to create a simple loading mask, you can see it in action in the examples.

In addition to new features, you'll find updates and bug fixes throughout the extension.

*** version 1.31 *** (Tested over YUI 2.3.0)

This release synchronizes the SourceForge version with Bubbling Library -- version number 1.31.
Please see the following article for information on this specific version increment at:
http://www.bubbling-library.com/eng/releases/2007/09/04/yui-cms-131-released

This minor release is focused on the correction of a series of bugs, the inclusion of new examples, and the introduction of features for the existed components.

The following components are updated with this release:

   * Bubbling Core: Included the form elements "input" as a genuine trigger for click events (now support: YUI Buttons / Anchors / Inputs).

   * Dispatcher: Included the new mechanism for memory management, offering a new custom event to destroy components included in the area during the content's update.

   * Selector: The mouseout event will be triggered only when the mouse go out of the area (discarding mouseout for internal elements).

   * Wizard: Support more than one form for each area.

*** version 1.30 *** (Tested over YUI 2.3.0)

This release synchronizes the SourceForge version with Bubbling Library -- version number 1.30.
Please see the following article for information on this specific version increment at:
http://www.bubbling-library.com/eng/releases/2007/08/10/yui-cms-130-released

The following components are updated with this release:

   * Bubbling Core: New and refining mechanism for the bubbles stuff, and including now the "Keyboard shortcuts".

   * Dispatcher: The dispatcher now have cssInjection (a last feature to create plug and play widgets), also includes inline and remote CSS syntax, and relative paths for CSS resources (images).

   * Tooltip: Using the panel control to implement the new tooltips control (Tips / Helps).  Now with external manipulation to customize the control, drag and drop feature for static tooltips, images and links inside the overlay, etc.

   * Selector: Now with external manipulation to customize the effects, extending the CSS's features more than never before, inclusing animation effects.

Also, this release introduces a bunch of new examples, and the general adoption of the new SAM skin.

In addition to new features, you'll find updates and bug fixes throughout the extension.

*** version 1.05 *** (Tested over YUI 2.2.2)

This release synchronizes the SourceForge version with Bubbling Library -- version number 1.05.
Please see the following article for information on this specific version increment at:
http://www.bubbling-library.com/eng/releases/2007/07/11/yui-cms-105-released

This minor release is focused on the correction of a series of bugs, the inclusion of new examples, and the introduction of a new BETA plugin.

The following new plugin is introduced with this release:

   * Translator (BETA): New YUI plugin for internationalization onDemand, you will be able to translate all the "Language Sentences" in your JavaScript without duplicate your code for each interface, and also support switching between different languages on the fly.

The following components are updated with this release:

   * Feeds (widget): The new version of the feeds widget is based on the translator plugin, using an external language pack to build a context menu.

   * Bookmarks (widget): The new version of the bookmarks widget is based on the translator plugin, using an external language pack to build a context menu.


*** version 1.04 *** (Tested over YUI 2.2.2)

This release synchronizes the SourceForge version with Bubbling Library -- version number 1.04.
Please see the following article for information on this specific version increment at:
http://www.bubbling-library.com/eng/releases/2007/06/06/yui-cms-104-released

The following new components are introduced with this release:

   * Selector: YUI plugin to the management of simple forms, pear forms, pear wizards, multi-page forms, and dynamic areas with forms inside.

   * Wizard: YUI plugin to highlighting areas within the document when the mouse go into each area.

The following components are updated with this release:

   * Dispatcher: The new version of the dispatcher support cross-domains capabilities using the most common technique (proxy) and monolithic execution (remote script are tied to a single domain), also introduce a new method "jsLoader", for remote script loading (components onDemand), and the hashtable to discard the multiple execution for the same remote script.

   * Tooltip: New and Improved functionality, bug fixed, and now as a YUI Overlay and introduce the new feature for load contents onDemand using the YUI connection manager.

Also in this release, the directory structure has been modified to provide more component's organization, similar to YUI.

yui/
  |
  -- build/
  | |
  | -- dispatcher/
  | |
  | | -- assets/
  | |
  | | -- dispatcher.js
  | |
  -- docs/
  | |
  | -- dispatcher/
  | |
  -- examples/
  | |
  | -- dispatcher/
  | |
  | | -- images/

Notice there are three immediate directories under the root YUI-CMS.

Each functional example is also available and functional on www.bubbling-library.com/.  They reproduced here as part of the distribution for your convenience.