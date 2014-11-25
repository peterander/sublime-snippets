sublime-snippets
================

Summary
-------

A collection of snippet configurations for the Sublime text editor to enable routine or predictably formatted pieces of code to be written more efficiently.

Naming Convention
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

Type into your working file the name/trigger identified in the `<tabTrigger>` element of your snippet code. When auto-complete option appears, press enter and elaborate or edit as needed.
