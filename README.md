phpdfg
======

PHP 'disable_functions' Generator.

Populates the 'disable_functions' directive in php.ini given
the path to a PHP codebase, excluding disused functions.

Optionally, generates a warning if dangerous functions are
in use, where dangerous are defined as those known to 
facilitate arbitrary code execution (in any environment,
not necessarily all environments).

Usage:
 phpdfg [-q] <path>
  -q     Quiet mode. Do not emit warnings.
  <path> The path to the source code repository you wish to
         configure against.
