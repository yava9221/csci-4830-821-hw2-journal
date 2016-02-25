# Contributing to tinycbor

## Author

[colagrosso](https://github.com/colagrosso)

## The Project

[01org/tinycbor](https://github.com/01org/tinycbor)

## License

MIT. See [LICENSE](http://github.com/01org/tinycbor/blob/master/LICENSE).

## Timeline

*   Started: 2016-02-23
*   Completed: 2016-02-25

The total amount of technical work was about two hours, and that included a lot
of time thinking about the best way to present this change. The non-technical
work was about an hour of filing the issue and responding to pull request
comments.

## The Change

There are a few compilation warnings in tinycbor that I would like to squash.

## Progress

*   2016-02-25: The project owner requested a few more changes to the commit
    message and responded quickly when I added more commits and replied on the
    pull request. Finally, the owner signed-off on the commit and added it to
    the repo.

*   2016-02-24: I created issue [01org/tinycbor#21]
    (https://github.com/01org/tinycbor/issues/21) that described the problem and
    filed a [pull request](https://github.com/01org/tinycbor/pull/22) that fixes
    it. I got an initial review very quickly.

*   2016-02-23: I thought about different ways to solve the problem and tried
    them in my local Git repo. I looked very closely at the output of `git diff`
    for each approach and tried to imagine how it would look from a reviewer's
    point-of-view who hasn't seen this change before. I found an approach I'm
    happy with because it touches only a small section of the code and won't be
    triggered that often (only when there is an error). The more-straightforward
    approach would have made the common case slower, and I was worried that
    would be poorly-received.
