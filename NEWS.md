# NEWS for Ruby 2.8.0 (tentative; to be 3.0.0)

This document is a list of user visible feature changes since the
 **2.7.0** release, except for bug fixes.

Note that each entry is kept so brief that no reason behind or reference
information is supplied with.  For a full list of changes with all
sufficient information, see the ChangeLog file or Redmine
(e.g. `https://bugs.ruby-lang.org/issues/$FEATURE_OR_BUG_NUMBER`).

## Language changes

## Command line options

## Core classes updates (outstanding ones only)

* Hash

    * Modified method

        * Hash#transform_keys now accepts a hash that maps keys to new
          keys.  [[Feature #16274]]

## Stdlib updates (outstanding ones only)

## Compatibility issues (excluding feature bug fixes)

* Regexp literals are frozen [[Feature #8948]] [[Feature #16377]]

    ```
    /foo/.frozen? #=> true
    ```

* The bundled gems

    net-telnet and xmlrpc has been removed from the bundled gems.
    If you interested in the maintain them, Please comment your plan
    to https://github.com/ruby/xmlrpc or https://github.com/ruby/net-telnet.

## Stdlib compatibility issues (excluding feature bug fixes)

## C API updates

## Implementation improvements

## Miscellaneous changes


[Feature #8948]:  https://bugs.ruby-lang.org/issues/8948
[Feature #16274]: https://bugs.ruby-lang.org/issues/16274
[Feature #16377]: https://bugs.ruby-lang.org/issues/16377
