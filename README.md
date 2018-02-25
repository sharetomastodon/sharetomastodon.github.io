Advanced Sharer for Mastodon
=========================

This project is a fork of [Advanced Sharer for Diaspora](https://github.com/sharetodiaspora/sharetodiaspora.github.io), adapted to work with mastodon

Advanced Sharer is a tool able to share links to any
[Mastodon](https://github.com/tootsuite/mastodon) instance.
[Learn more](https://sharetomastodon.github.io/about).

## Usage

![Demo GIF](demo.gif)

The same parameters from advanced diaspora* sharer for title,
URL and notes can be used, just add them to the URL:

```
https://sharetomastodon.github.io/?url=joinmastodon.org&title=The%20mastodon%20Project&notes=Welcome%20to%20mastodon
```

[Try it!](https://sharetomastodon.github.io/?url=joinmastodon.org&title=The%20mastodon%20Project&notes=Welcome%20to%20mastodon)

**Note**: If you've marked *Remember my choice* then you
will be always redirected to the instance you chose that time.
To avoid this, add the parameter `&redirect=false` on the URL.

## Contributing
Any fixes and improvements are greatly appreciated. Feel
free to [fork the project](https://github.com/sharetomastodon/sharetomastodon.github.io/fork)
and tinker with it :)

### Translations
We're currently using [L20n](https://github.com/l20n/l20n.js)
by Mozilla for localization. To contribute a translation the
*Github way*, you can fork this project and add a locale folder
for your language under `locales`. Copy the file `index.l20n`
from another locale and use it to translate to your language.
Then create a pull request to send them to the original repo.
