Bootbox.js is a small JavaScript library which allows you to create programmatic dialog boxes using Bootstrap modals, without having to worry about creating, managing or removing any of the required DOM elements or JS event handlers. Here’s the simplest possible example:

bootbox.alert("Hello world!");

Run example

Overview

The library exposes three functions designed to mimic their native JavaScript equivalents. Their exact function signatures are flexible as each can take various parameters to customise labels and specify defaults, but they are most commonly called like so:

alert

bootbox.alert(message, callback)
prompt

bootbox.prompt(message, callback)
confirm

bootbox.confirm(message, callback)
Each of these three functions calls a fourth public function which you too can use to create your own custom dialogs:

bootbox.dialog(options)
Documentation is available for each of these functions, including the options available for each dialog. You can also find examples for using each of these functions in the (appropriately named) Examples page.

Visit the Getting Started page for guidance on how to add Bootbox to your project.

Please note:

There are some caveats to using Bootbox dialogs in place of native dialogs. Please see the Known Limitations section in the Documentation page to learn more.

About

Bootbox was originally created in 2011 with the sole purpose of wrapping JavaScript’s low level dialog functions with Bootstrap’s high level modal functionality. As such it is a small library focussed on providing basic programmatic dialogs with minimal fuss and overhead.

Bootbox is authored and maintained by Nick Payne (@makeusabrew). Thanks are also due to the contributors!

Get involved!

Bootbox is a free, open source project. As such you can help out in a number of ways from simply raising an issue to forking the project and submitting a pull request.

I’m particularly keen to improve the examples and make a proper start on the API docs, so pull requests contributing towards the gh-pages branch (which you’re looking at!) are extremely welcome.

Lastly — please just help spread the word!