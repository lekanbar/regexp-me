Regexp-me is a Java Me (j2me) regular expression package based on [Jakarta Regexp](http://jakarta.apache.org/regexp/index.html). Regexp-me is CLDC1.0 compatible and has partial Unicode support.

## Usage ##

First you need to import `me.regexp` package:

```
import me.regexp.*;
```

Here is the basic example of pattern matching:

```
RE r = new RE("abc(\\w*)");            // Create new pattern
if (r.match("abcdefg"))                // Match pattern
    System.out.println("oh yeah!");    // Oh Yeah!
```

More examples [here](http://unknown.kaban7.com/regexp-me/). See [API Documentation](http://regexp-me.googlecode.com/svn/trunk/regexp-me/doc/index.html).

## Unicode ##

To turn on Unicode support in source code you need to use [Netbeans](http://www.netbeans.org/) preprocessor. In _Netbeans IDE_ go to project _Properties - Ablities_ and add _RE\_UNICODE_ ability.

_Warning: Unicode support eats memory!_

## Feedback ##

Feedback is positively welcomed. Feel free to join [regexp-me discussion group](http://groups.google.ru/group/regexp-me).

_zobaken -(at)- gmail.com_