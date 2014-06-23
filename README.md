# NAME

Any::Moose - \*deprecated\* - use Moo instead!

# VERSION

version 0.24

# DEPRECATION

日本語翻訳: http://blog.64p.org/entry/2013/02/06/094906

Please use [Moo](https://metacpan.org/pod/Moo) instead of Any::Moose for new code.

Moo classes and roles will transparently and correctly upgrade to
Moose when needed. This is a fundamentally better design than what
Any::Moose offers. Mouse metaclasses do not interact with Moose
metaclasses which leaks abstractions all over the place.

Any::Moose had a good run. It was a simplistic but expedient answer
for getting Moose syntax on the cheap but with the transparent
upgrade path to Moose when you needed it. But really, please don't
use it any more. :)

You may find [MooX::late](https://metacpan.org/pod/MooX::late) useful for porting your code from
Any::Moose to Moo.

For the sparse documentation Any::Moose used to include, see
[https://metacpan.org/module/SARTAK/Any-Moose-0.18/lib/Any/Moose.pm](https://metacpan.org/module/SARTAK/Any-Moose-0.18/lib/Any/Moose.pm)

# AUTHORS

- Shawn M Moore <code@sartak.org>
- Florian Ragwitz <rafl@debian.org>
- Stevan Little <stevan@iinteractive.com>
- Tokuhiro Matsuno <tokuhirom@gmail.com>
- Goro Fuji <gfuji@cpan.org>
- Ricardo Signes <rjbs@cpan.org>

# COPYRIGHT AND LICENSE

This software is copyright (c) 2014 by Best Practical Solutions.

This is free software; you can redistribute it and/or modify it under
the same terms as the Perl 5 programming language system itself.

# CONTRIBUTORS

- Chris 'BinGOs' Williams <chris@bingosnet.co.uk>
- Graham Knop <haarg@haarg.org>
- Karen Etheridge <ether@cpan.org>
- Stevan Little <stevan.little@iinteractive.com>
- gfx <gfuji@cpan.org>
- tokuhirom <tokuhirom@gmail.com>
