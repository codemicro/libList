# Golang

See also: [avelino/awesome-go](https://github.com/avelino/awesome-go)

### Authentication

* [dchest/captcha](https://github.com/dchest/captcha) - A CAPTCHA library that supports output to WAV and PNG formats. Includes the option to add a custom storage adapter

### Automation 

* [chromedp/chromedp](https://github.com/chromedp/chromedp) - A browser controller to drive Google Chrome with no external dependencies
* [mxschmitt/playwright-go](https://github.com/mxschmitt/playwright-go) - Microsoft's Playwright framework for Go.
* [tebeka/selenium](https://github.com/tebeka/selenium) - You know what [Selenium](https://www.selenium.dev/) is.

### Code generation

* [awalterschulze/goderive](https://github.com/awalterschulze/goderive) - Code generation for functional programming in Go (`map`, `reduce`, etc)

### Configuration

* [joho/godotenv](https://github.com/joho/godotenv) - `.env` loading and parsing (a port of the Ruby `dotenv` project)

### Data

* [go-bindata/go-bindata](https://github.com/go-bindata/go-bindata) - One of many things to embed arbitrary files into a Go binary
* [patrickmn/go-cache](https://github.com/patrickmn/go-cache) - Simple, thread safe, in-memory `map[string]interface{}` cache with expiration times
* [wcharczuk/go-chart](https://github.com/wcharczuk/go-chart/) - A basic charting library, written in raw Go.
* [go-echarts/go-echarts](https://github.com/go-echarts/go-echarts) - Generate charts as HTML and JS in Go
* [mmcdole/gofeed](https://github.com/mmcdole/gofeed) - Parse RSS feeds in Go
* [tinylib/msgp](https://github.com/tinylib/msgp) - A [MessagePack](https://msgpack.org/) library for Go (it's like JSON, but fast and small!)
* [gomodule/redigo](https://github.com/gomodule/redigo) - A Redis client for Go

### Data storage

* [huandu/go-sqlbuilder](https://github.com/huandu/go-sqlbuilder) - A SQL string builder - a "zero config" alternative to a full fledged ORM, like GORM
* [go-gorm/gorm](https://github.com/go-gorm/gorm) - It's an ORM, and it works pretty well
* [go-reform/reform](https://github.com/go-reform/reform) - "A better ORM for Go" with concrete types and code generation
* [C2FO/vfs](https://github.com/C2FO/vfs) - A file system abstraction library, to make dealing with S3, GCP or local file storage simple through a unified API.
* [spf13/afero](https://github.com/spf13/afero) - Another, more popular, file system abstraction library without support for S3

### Error handling

* [rotisserie/eris](https://github.com/rotisserie/eris) - Error creation, wrapping and stack traces
* [rs/zerolog](https://github.com/rs/zerolog) - A zero allocation JSON error logger
* [hashicorp/go-multierror](https://github.com/hashicorp/go-multierror) - Represent single errors as one!

### Searching

* [blevesearch/bleve](https://github.com/blevesearch/bleve) - A text indexing library

### Testing 

* [cweill/gotests](https://github.com/cweill/gotests) - Automatically generate Go test boilerplate from source code

### User interfaces

* [schollz/progressbar](https://github.com/schollz/progressbar) - A simple, thread-safe progress bar
* [wailsapp/wails](https://github.com/wailsapp/wails) - Build native GUIs in Go with web technologies (think Electron but without Chrome or JavaScript)

### Web

* [fiber/fiber](https://github.com/gofiber/fiber) - A lightning fast web framework, with an Express JS inspired API
  * [fiber/jwt](https://github.com/gofiber/jwt) - JWT authentication middleware
  * [fiber/storage](https://github.com/gofiber/storage) - Storage drivers for various middlewares
* [PuerkitoBio/goquery](https://github.com/PuerkitoBio/goquery) - HTML parsing library with a jQuery like interface
* [parnurzeal/gorequest](https://github.com/parnurzeal/gorequest) - A HTTP request library
* [valyala/quicktemplate](https://github.com/valyala/quicktemplate) - Lightning fast templating using code generation

### Misc.

* [logrusorgru/aurora](https://github.com/logrusorgru/aurora) - Console colours, but it's not a pain in the arse to use!
  * Yes, it does work on Windows (potentially with or without changes, depending on whatever version of Windows and what terminal you're using)
* [fatih/color](https://github.com/fatih/color) - Console colours that's less simple but actually says it supports Windows.
* [jordan-wright/email](https://github.com/jordan-wright/email) - Simple and flexible SMTP client for Go
* [skwair/harmony](https://github.com/skwair/harmony) - WIP Discord API library
* [AlekSi/pointer](https://github.com/AlekSi/pointer) - You can't do `&"hello"` but you can do `pointer.ToString("hello")`
