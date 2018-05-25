# formatio-not-available
A repository to investigate why people can't install formatio, specifically with the error message:

```text
npm ERR! 404 no such package available : @sinonjs/formatio
```

In [formatio package not available](https://github.com/sinonjs/formatio/issues/14) there is a discussion about different solutions to the challenge that some users cannot install `@sinonjs/formatio` during the install of `sinon`.

This repository is an attempt at creating a *shareable*, reproducible test case.

## How to verify you are affected

1. `git clone https://github.com/mroderick/formatio-not-available.git`
1. `cd formatio-not-available`
1. `npm install`

Are you seeing `npm ERR! 404 no such package available : @sinonjs/formatio` in the log?

Please report your findings in [formatio package not available](https://github.com/sinonjs/formatio/issues/14).