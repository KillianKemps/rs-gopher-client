# Marmotte

This Gopher client written in Rust will be kept minimalistic.

Available commands:
```
get [url]: Get this url
[index]: Follow link index
up: Go up one directory
back: Go back previous page
quit: Quit this program
```

Project features:
- [x] Handle text resources (type 0)
- [x] Handle Gopher menus (type 1)
- [ ] Handle Gopher search (type 7)
- [x] Go one directory up from the path (`up` command)
- [x] Go back several pages before in history (`back`command)
- [ ] Save links into bookmarks
- [ ] Follow links in text/markdown resources
- [ ] Cache pages by default for fast and offline browsing
- [ ] Connect with SSL/TLS when the remote server implements it
