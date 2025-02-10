# cgiup

This script serve static files form the specified directory (current working directory by default) over HTTP, but there is a catch!  Any file in the `/cgi-bin/` directory will be executed as a CGI script.

## Usage

```sh-session
bundle install
bundle exec ./cgiup ~/Projects/my-website
```
