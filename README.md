# querystring

A minimal query string library in zepto. It is in alpha right now.

## Usage

There are two basic routines, `querystring:build` and `querystring:parse`.

Using them looks somewhat like this:
```clojure
(import-all "querystring")
(querystring:parse "somekey=someval&otherkey=otherval")
=> #{somekey: someval, otherkey: otherval}
(querystring:build #{video anime.mp4 referer google})
=> "video=anime.mp4&referer=google"
```

<br/>

*Have fun!*
