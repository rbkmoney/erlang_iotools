iotools
=======

Set of useful Erlang's IO tools.

Configuration
-------------

At startup this application set up `standard_io` and `standard_error` with preconfigured options.
In can be redefined by placing new options to `sys.config` as follows:

```
{iotools, [
   {standard_io, [{encoding,unicode}]},
   {standard_error, [{encoding,unicode}]}
]}.

```
