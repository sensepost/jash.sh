# Just Another SensePost Hacker

For the [SensePost](https://sensepost.com/) 2018 artwork, we ran an internal competition to develop polyglot's (i.e. code that runs in multiple languages) to print out the text "JASH". This is a throw back to the old [Just Another Perl Hacker](https://en.wikipedia.org/wiki/Just_another_Perl_hacker) competitions. Feel free to submit your own idea with a [pull request](https://github.com/sensepost/jash.sh/compare).

### Winning entry

<a href="https://github.com/sensepost/jash.sh/blob/master/images/jash.png"><img src="https://raw.githubusercontent.com/sensepost/jash.sh/master/images/jash.png" align="center" height="200" width="200" alt="SensePost 2018 JASH Art" /></a>

### The Rules

* The primary aim is to submit a polyglot that runs in the most languages with the fewest characters.
  * Differences in major version numbers of languages can count as different languages
* However, polyglots that use novel techniques, or run in esoteric languages are encouraged.
* As are beautiful polyglots i.e. elegant code or pictographic code.

### Submissions

By @[leonjza](https://github.com/sensepost/jash.sh/blob/master/polyglots/leonjza)
```python
#<?
print("JASH");
```
Runs in 9: python2/3, R, Ruby, Perl, Lua, Julia, php7.1, hack/hhvm

By @[singe](https://github.com/sensepost/jash.sh/blob/master/polyglots/singe)
```python
#/*<?#*/
#include <stdio.h> /*
print 'JASH';exit;#?>
__DATA__ = 1
""""
__END__
*/
int main() { printf("JASH"); } /*
"""#*/
```
Runs in 7: python2, zsh, Ruby, Perl, php, C, C++
