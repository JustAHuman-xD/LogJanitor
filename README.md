# LogJanitor
A VaultHunters addon mod cleaning up your log by fixing errors & hiding mass info messages. 
I made this mostly just for myself because I got so annoyed scrolling through hundreds and hundreds
of warnings, info lines, etc, that were always going to be in the log.

LogJanitor goes about shrinking the log by trying to fix some of the problems or just hiding
the log messages (whether casued by a "problem" or just an info message). All of the log suppresion
is done either through fixing/adding assets or through mixins which can be enabled/disabled indidually in the mod's config.

To change the config (if you want any surpressed messages not surpressed) you need to have launched your
game completely at least once. It will generate the config once fully loaded and then if you edit
the config you can change any of the mixins to false, disabling the mixin. Then the next time you launch
your game the mixin will be disabled and the surpressed logging messages restored.

There is currently not a way to disable any supression done by solving the problem (for ex. the tiki torch
issues or some vault model issues solved just by adding the missing assets).
