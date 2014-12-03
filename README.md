BlinkInnerHtmlBug
=================

Repository created to provide test data for bug discovered in Blink rendering core. The error occurs when a very specific html string is assigned to an element's `innerHtml`.

The issue can be reproduced in both current stable version of Google Chrome on Windows (39.0.2171.71 m) and Opera on Windows (26.0.1656.32).

Demo page of this bug (created form the files in this repository) is on [RawGit](https://rawgit.com/no23reason/BlinkInnerHtmlBug/master/index.html)

The error occurs during the `Element::setInnerHTML` execution. I haven't been able to determine, what is wrong with the input.
