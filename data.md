# Sources of data

# Raw sources

[W3C API](https://api.w3.org/doc) contains the list of W3C groups, and the list of W3C published specifications.

GitHub provides a [REST API](https://docs.github.com/en/rest) and a [GraphQL API](https://docs.github.com/en/graphql). It contains list of repositories and issues. [w3c/github-cache](https://github.com/w3c/github-cache) does provide a cache for some information, exposed through [labs.w3.org](https://labs.w3.org/).

[common-labels.json](https://w3c.github.io/common-labels.json) contains the list of horizontal repositories, used for review requests and horizontal issues tracking.

@@WHATWG

@@IETF

@@WPT

@@ASH-NAZG

# Curated sources

Curated sources provide data that has been curated automatically (such as dropping invalid JSON files) and manually (such as patching raw data or complementing raw data).

[w3c/groups](https://www.w3.org/groups) contains [repositories.json](https://github.com/w3c/groups/blob/main/repositories.json), to associate a github repository with a set of W3C groups. The crawler, [w3c/groups-server](https://www.w3.org/groups-server), processes [w3c.json files](https://w3c.github.io/w3c.json.html) with various GitHub organizations.

[browser-specs](https://github.com/w3c/browser-specs/) contains [index.json](https://w3c.github.io/browser-specs/index.json), to associate the URL of a specification, with its groups (W3C, WHATWG, IETF, etc.), shortname, github repository, etc.

[webref](https://w3c.github.io/webref/) contains [index.json](https://w3c.github.io/webref/ed/index.json) and [idlnames](https://w3c.github.io/webref/ed/idlnames.json), to associate a specification with its IDL definitions.
