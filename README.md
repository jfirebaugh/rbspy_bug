```
$ bundle && sudo --preserve-env rbspy record -- bundle exec ruby -e "require 'webmock/minitest'"
[snip]
Bundle complete! 6 Gemfile dependencies, 50 gems now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
Dropping permissions: running Ruby command as user john
rbspy is recording traces. Press Ctrl+C to stop.
Dropped 21/21 stack traces because of errors. Please consider reporting a GitHub issue -- this isn't normal.
Warning: no profile samples were collected
Wrote raw data to /Users/john/Library/Caches/rbspy/2022-09-16-P1QnakSghm.raw.gz
Wrote formatted output to /Users/john/Library/Caches/rbspy/2022-09-16-IOCishdwar.flamegraph.svg
Something went wrong while rbspy was sampling the process. Here's what we know:
- Failed to copy memory address 0
```
