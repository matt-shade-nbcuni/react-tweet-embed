# react-tweet-embed-in-span

# forked from
https://www.npmjs.com/package/react-tweet-embed

## Install
```
npm i react-tweet-embed-in-span
```

## Quickstart

```javascript
import TweetEmbed from 'react-tweet-embed-in-span'

<TweetEmbed id='692527862369357824' />
```

You don't have to put `//platform.twitter.com/widgets.js` script in your index.html as this lib will put it there if `twttr` is not found on window.  


## Using Options

```
<TweetEmbed id='783943172057694208' options={{cards: 'hidden' }}/>
<TweetEmbed id='771763270273294336' options={{theme: 'dark' }}/>
```

Embedded-Tweet Options Reference:
https://dev.twitter.com/web/embedded-tweets/parameters
