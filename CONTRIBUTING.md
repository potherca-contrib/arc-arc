# How to contribute

Thanks for wanting to contribute. Here's a quick guide.

## Getting Started

* Make sure you have a [GitHub account](https://github.com/signup/free)
* Submit a ticket for your issue, assuming one does not already exist.
  * Clearly describe the issue including steps to reproduce when it is a bug.
  * We're using http://waffle.io/ariadne-cms/arc-base to keep track of issues, you can too.
* Fork the repository on GitHub

## Making Changes

* ARC has its very own personality and way of doing things, make sure you understand
  how \arc\path and \arc\tree are used in all components and see if you can make use
  of them in your own changes as well
* Keep state out of the lowercase named classes, unless you're making a factory method,
  in which case use \arc\context as a dependency injection container.
* Keep it small and clean. ARC focuses on small code size and a small, simple and beautiful
  API. Don't cram in unneeded features.
* Don't extend other classes. Really. Unless you have tried composition ( proxying ) and 
  traits first. And then still don't.
* ARC conforms to PSR-2 for coding style, not because we love it, but because we need 
  a standard so we don't start fighting about it.
* Make sure you have added the necessary tests for your changes.
* Run _all_ the tests to assure nothing else was accidentally broken.


## Submitting Changes

* Commit your changes to your fork with complete, readable and english commit messages
* Push to your fork
* Submit a pull request
* Wait for us and hang out at #ariadne at ircnet, try http://webchat.xs4all.nl/ for a web interface
