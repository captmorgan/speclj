# 1.2.0

* around components now execute around befores and afters
* removed AOT compilation of clojure src which caused problems on other versions of clojure
* fixed typo that prevented src from properly reloaded by Vigilant Runner
* spec files are sorted before running

# 1.1.0

* fixed problem where vigilant runner would crash with :reload or :verbose in ns
* colorize output
* standard runner won't evaluate specs until they're all loaded
* `with` components are only bound within their context
* nested describe/context
* `after`s are invoked even after failures or errors
* should= support for doubles (use delta)
* Lazy seqs print nicely in output (@trptcolin)

# 1.0.3

* First release
