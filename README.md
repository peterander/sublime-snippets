sublime-snippets
================

Summary
-------

A collection of snippet configurations to enable routine or predictably formatted pieces of code to be written more efficiently in Sublime Text editor.

Naming convention
-----------------
Files should be named as `[snippetname].sublime-snippet`.

Example of file contents
-------
```xml
<snippet>
  <content><![CDATA[var ${0:AppName} = angular.module('${0:AppName}, []);]]></content>
  <tabTrigger>ngmod</tabTrigger>
  <scope>source.js</scope>
  <description>AngularJS module declaration</description>
</snippet>
```

How to use
----------

First, save a file named and formatted as above into the appropriate Sublime Text directory (for example, `\Sublime Text 2\Packages\User\`). Next, type into any working file the name/trigger identified in the `<tabTrigger>` element of your snippet code. As long as the file format you are editing corresponds with the one nindicated in the `<scope>` element of your snippet markup, an auto-complete option will appear. Press enter to choose the auto-complete option, then elaborate or edit as desired.
