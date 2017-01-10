# pass
create a strong password that's *easy* to regenerate from *memory*

First, setup "pass" by exporting environment variable `PASS_SALT` to a word
you're very likely to remember. Use the same word for every installation!

Second, put the "pass" command somewhere in your PATH e.g. your "bin" folder.

Third, run "pass" by writing a password phrase to the command "pass" like so:

```
> pass
my secret phrase

WARNING: using default salt "Himalayan"
         please set your env variable PASS_SALT

my secret phrase ===> QYYL96XiEs$gWmJtZJDBY9t$OMZxjmBGjDgqG4xo
```

(If you didn't setup the `PASS_SALT` environment variable, you should see this)

Note that passwords are at least 30 characters long and include 2 special chars.

## Example

First you might set your `PASS_SALT` environment variable to be "yellowBIRD123".

Then maybe for your Google account "john.doe@gmail.com" you choose the pass
phrase "Gmail John Doe" - i.e. the service name followed by the person's name.
At Facebook, maybe the pass phrase would be "Facebook John Doe" instead.

This would provide the following passwords:

* Gmail: _Uwvf6g3cWrrM5M1IKk3VTQ54sqhDodd%zv40o5^d5qfL_
* Facebook: _03n#E5b2yMmDpT@7zVvdlObc32bxnarX1IMtYYaj0Z_

To crack your password, a hacker would need to know both your `PASS_SALT` value
*and* your memorized formula for composing pass phrases. Obviously you should
share neither of these with other people. They'd also need this "pass" program,
so you might want to keep this a secret too.

I hope you find "pass" to be useful!

Author: kevin.hutchinson@legendum.com

