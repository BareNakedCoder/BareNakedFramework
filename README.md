# BareNakedFramework for PHP Apps #


> “Perfection is achieved, not when there is nothing more to add, but when there is nothing left to take away.”   
> ― Antoine de Saint-Exupéry

Yet another microframework for PHP applications. Super simple and lightweight.

- Route to the application code as fast as possible
  - Load as few PHP files as possible (in prod mode, just 2!)
  - Load and interpret as few (often unused) lines of PHP code as possible
- Enable switch-over deploys
  - Install, some final testing, then a simple switch-over *without needing to shutdown*
  - Problems? Simply switch-back to the previous code (it's still installed)
- Enable framework upgrades: just plug-in the newer BNF part(s)
- Enable pluggable parts for composite web sites
  - Just plug-in apps, sub-apps, other apps, libs, and even non-BNF parts
- Above all, be fast and lean before trying to be feature rich ([YAGNI](http://en.wikipedia.org/wiki/YAGNI)).
  - Avoid regular expressions, excessive OOP, etc.

Don Parakin, BareNakedCoder.com

### Coming Soon! Code Cleanup In-Progress ###
