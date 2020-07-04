# Sup

Sup is a console-based email client for people with a lot of email.

<img src="https://sup-heliotrope.github.io/images/old_screenshot_1.png" />

## Installation

[See the wiki][Installation]

## Features / Problems

Features:

* GMail-like thread-centered archiving, tagging and muting
* [Handling mail from multiple mbox and Maildir sources][sources]
* Blazing fast full-text search with a [rich query language][search]
* Multiple accounts - pick the right one when sending mail
* [Ruby-programmable hooks][hooks]
* Automatically tracking recent contacts

Current limitations:

* Sup does in general not play nicely with other mail clients, not all
  changes can be synced back to the mail source. Refer to [Maildir Syncback][maildir-syncback]
  in the wiki for this recently included feature. Maildir Syncback
  allows you to sync back flag changes in messages and to write messages
  to maildir sources.

* Unix-centrism in MIME attachment handling and in sendmail invocation.

## Problems

Please report bugs to the [GitHub issue tracker](https://github.com/sup-heliotrope/sup/issues).

## Links

* [Homepage](https://sup-heliotrope.github.io/)
* [Code repository](https://github.com/sup-heliotrope/sup)
* [Wiki](https://github.com/sup-heliotrope/sup/wiki)
* IRC: [#sup @ freenode.net](http://webchat.freenode.net/?channels=#sup)
* Mailing list: supmua@googlegroups.com (subscribe: supmua+subscribe@googlegroups.com, archive: https://groups.google.com/d/forum/supmua )

## Alternatives

Sup is a stable, production-quality mail client.
The maintainers are not intending to add new major features in future.
If Sup is missing a feature you are interested in, it might be
possible to accomplish using Sup's [powerful hooks mechanism][hooks].
Otherwise, here are some alternatives to consider:

* The [notmuch mail](https://notmuchmail.org/) project was inspired by Sup,
  and there is a wide variety of different
  [clients](https://notmuchmail.org/frontends/) available for it.

## License

```
Copyright (c) 2013--     Sup developers.
Copyright (c) 2006--2009 William Morgan.

This program is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License
as published by the Free Software Foundation; either version 2
of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA
02110-1301, USA.
```

[sources]: https://github.com/sup-heliotrope/sup/wiki/Adding-sources
[hooks]: https://github.com/sup-heliotrope/sup/wiki/Hooks
[search]: https://github.com/sup-heliotrope/sup/wiki/Searching-your-mail
[Installation]: https://github.com/sup-heliotrope/sup/wiki#installation
[ruby20]: https://github.com/sup-heliotrope/sup/wiki/Development#sup-014
[maildir-syncback]: https://github.com/sup-heliotrope/sup/wiki/Using-sup-with-other-clients
