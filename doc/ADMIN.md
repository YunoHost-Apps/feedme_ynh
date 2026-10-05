Just point your RSS feed reader to `https://__DOMAIN____PATH_WITHOUT_TRAILING_SLASH__/extract?url=https://example.com/` to retrieve a feed coming from `https://example.com`.

Supplying the URL will be enough for most pages, however [additional parameters](https://github.com/ardi4s/feedme/blob/main/docs/parameters.md) such as custom selectors can be added, and you can also build the feed using the web GUI.
 
Advanced parsing can also be done by dropping a YAML file in `__DATA_DIR__/sites/` as [described in the official documentation](https://github.com/ardi4s/feedme/blob/main/docs/site-configs.md).
