# Change Log

## [0.3] upcoming
- Retoot mode is no longer triggered by using a specific hastag, but by preceding
the mention with an Exclamation Mark like "!@mastodon"

## [0.2] - 2018-08-24
### Added
- Configurable retoot mode
Public mentions from group members are now retooted if they include a trigger
hashtag. That way thei will point to the originating user. Direct messages are
sent as new toots just like before, but the originating user will not be shown
in that case. This is NOT a privacy feature since the group admin will still see
who created a specific message. However, it can be handy for some use cases.
Both options can be enabled or disabled during setup.

## [0.1] - 2018-08-19
### Initial commit
- Basic proof of concept.
- Manual installation and setup required
- Create new toots from direct messages of group members only