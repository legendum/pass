# pass
create a strong password that's *easy* to regenerate from *memory*

First, setup "pass" by exporting environment variable PASS\_SALT to a word
you're very likely to remember. Use the same word for every installation!

Second, put the "pass" command somewhere in your PATH e.g. your "bin" folder.

Third, run "pass" by passing a password phrase to the command "pass" like so:

```
> pass
my secret phrase

QYYL96XiEsg+WmJt&~+ZJ/+DBY9+tOMZxjmBGjDgqG4xo
```

(If you didn't setup the PASS_SALT environment variable, you should see this)

Note that *all* passwords are 45 characters long and include 2 special chars.
