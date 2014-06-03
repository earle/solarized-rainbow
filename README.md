solarized-rainbow
=================

Modified Solarized theme for Light Table.  This theme has reasonable color overrides for the Rainbow
plugin for nested parenthesis.

## usage

1. Copy solarized-rainbow.css into your LightTable ``core/themes/css`` directory

2. Add the following to your Default: Behaviors configuration

```
    (:lt.objs.style/provide-theme "solarized-rainbow" "core/css/themes/solarized-rainbow.css")
```

3. Add the following to your User: Defaults :Editor configuration

```
    (:lt.objs.style/set-theme "solarized-rainbow") 
```

4. Enjoy.
