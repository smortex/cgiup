# cgirun

This script serve static files form the document root (set with `--document-root`, default to `.` when not set) over HTTP, but there is a catch!  Any file in the cgi-bin directory (set with `--cgi-bin`, default to `./cgi-bin` when not set) will be executed as a CGI script.

## Usage

```sh-session
bundle install
bundle exec ./cgirun --document-root ~/Projects/my-website/public --cgi-bin ~/Projects/my-website/cgi-bin
```
