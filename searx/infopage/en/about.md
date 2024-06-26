
# About Moa

Moa is a [metasearch engine] based on SearXNG that aggregates the results
of other search engines while not storing information about its users.


The SearXNG and Moa projects are driven by an open community,
come join us on Matrix and Telegram if you have questions or just want to chat about SearXNG or Moa at [#searxng:matrix.org] & [@moa_engine:telegram.com](https://t.me/moa_engine).

Make Moa better.

- You can improve Moa / SearXNG translations on [Weblate], or...
- Track development, post contributions, and report issues at [Moa sources].
- For more information, see the SearXNG project documentation at [SearXNG docs].

## Why use it?

- Moa may not offer you as personalized results as Google, but it doesn’t generate a profile about you.
- Moa doesn’t care about what you search for, never shares anything with a third-party, and it can’t be used to compromise you.
- Moa is free software, the code is 100% open, and everyone is welcome to make it better.

If you do care about privacy, want to be a conscious user, or otherwise
believe in digital freedom, make Moa your default search engine
or run it on your own server!

## How do I set it as the default search engine?

Moa supports [OpenSearch]. For more information on changing your default
search engine, see your browser’s documentation:

- [Firefox]
- [Microsoft Edge] - Behind the link, you will also find some useful instructions for Chrome and Safari.
- [Chromium]-based browsers only add websites that the user navigates to without a path.

When adding a search engine, there must be no duplicates with the same name. If
you encounter a problem where you cannot add the search engine, you can either:

- Remove the duplicate (default name: "{{get_setting('general.instance_name')}}") or
- Contact the owner to give the instance a different name than the default.

## How does it work?

Moa is a fork of SearXNG which itself is a fork from the well-known [searx] [metasearch engine] which was
inspired by the [Seeks project]. It provides basic privacy by mixing your
queries with searches on other platforms without storing search data. Moa
can be added to your browser’s search bar; moreover, it can be set as
the default search engine.

The {{link('stats page', 'stats')}} contains some useful anonymous usage
statistics about the engines used.

## How can I make it mine?

Moa appreciates your concern regarding logs, so take the code from the
[Moa sources] and run it yourself!

Add your instance to this [list of public instances]({{get_setting('brand.public_instances')}}) to help other people
reclaim their privacy and make the internet freer. The more decentralized the
internet is, the more freedom we have!


[Moa sources]: {{get_setting('brand.git_url')}}
[#searxng:matrix.org]: https://matrix.to/#/#searxng:matrix.org
[SearXNG docs]: {{get_setting('brand.docs_url')}}
[searx]: https://github.com/searx/searx
[metasearch engine]: https://en.wikipedia.org/wiki/Metasearch_engine
[Weblate]: https://translate.codeberg.org/projects/searxng/
[Seeks project]: https://beniz.github.io/seeks/
[OpenSearch]: https://github.com/dewitt/opensearch/blob/master/opensearch-1-1-draft-6.md
[Firefox]: https://support.mozilla.org/en-US/kb/add-or-remove-search-engine-firefox
[Microsoft Edge]: https://support.microsoft.com/en-us/help/4028574/microsoft-edge-change-the-default-search-engine
[Chromium]: https://www.chromium.org/tab-to-search
