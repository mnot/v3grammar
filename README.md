# XML2RFCv3 Relax NG Compact Grammar Evolution

This repo tracks evolution of the [XML2RFCv3](https://www.rfc-editor.org/rfc/rfc7991.html) RNC grammar, starting with that included
in the RFC and updated using [this repo](https://github.com/rfc-format/v3grammar) as a source.

See annotations in the form of comments on [the commits](https://github.com/mnot/v3grammar/commits/main/v3.rnc). Currently, I'm focusing on whether the changes are documented in [RFC7791bis](https://tools.ietf.org/html/draft-iab-xml2rfc-v3-bis-00.html), whether they appear on its [issues list](https://github.com/rfc-format/draft-iab-xml2rfc-v3-bis/issues), and whether they are _backwards-compatible_. Note that I'm not saying much about whether I think the changes are a good idea (for now).

A change to the schema is _backwards-compatible_ if it does not invalidate a document that was valid according to a previous schema, and does not change it semantics.
