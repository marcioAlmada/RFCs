# RFCs

A home for my unfinished RFCs while they are not proposed on [wiki.php.net/rfc](https://wiki.php.net/rfc).

Suggestions and pull requests with RFC improvements are encouraged :octocat:

# Active RFCs

> Waiting for PHP 7.1 season

# Accepted RFCs

### Context Sensitive Language [![status](https://img.shields.io/badge/Status-Accepted-green.svg?style=flat-square)](https://wiki.php.net/rfc/context_sensitive_lexer) [![status](https://img.shields.io/badge/Merged-✓-grey.svg?style=flat-square)](https://github.com/php/php-src/pull/1221)

> PHP currently has around **64** globally reserved words that not infrequently clash with legit alternatives to userland API declarations. This RFC proposes a solution for that by adding a **context sensitive lexer** with support for **semi-reserved** words.

### Group Use Declarations [![status](https://img.shields.io/badge/Status-Accepted-green.svg?style=flat-square)](https://wiki.php.net/rfc/group_use_declarations) [![status](https://img.shields.io/badge/Merged-✓-grey.svg?style=flat-square)](https://github.com/php/php-src/pull/1005)

> This RFC aims to improve current PHP namespace implementation by introducing the concept of Group Use Declarations.


# Dead

### Strict Argument Count On Function Calls [![status](https://img.shields.io/badge/Status-Withdrawn-ccc.svg?style=flat-square)](https://wiki.php.net/rfc/strict_argcount)

> This RFC proposes to conditionally add a strict argument count check for function calls on PHP7, being sensitive towards implementations already depending on the variable-length argument lists API.

## Requests

If you have an idea for an RFC that could benefit community but have no clue how to do it all by yourself, please open an issue describing your proposal and, **maybe**, after some discussion, I could create the RFC. Keep in mind that:

- You will have to be really convincing. RFCs are hardwork, don't expect me to spend time and resources if you can't prove your idea is really useful, do a research first.
- I may not accept all the RFC suggestions but I can help you navigate the proccess or seek for orientation in case you decide to write your first RFC.

## Copyright

This work is licensed under a [Creative Commons 3.0 Unported License](http://creativecommons.org/licenses/by-nc-sa/3.0/).

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/">
    <img alt="Creative Commons License" src="https://i.creativecommons.org/l/by-nc-sa/3.0/88x31.png" />
</a>
