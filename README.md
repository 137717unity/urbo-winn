# Hello world JavaScript action
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2F137717unity%2Furbo-winn.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2F137717unity%2Furbo-winn?ref=badge_shield)


This action prints "Hello World" or "Hello" + the name of a person to greet to the log. To learn how this action was built, see "[Creating a JavaScript action](https://help.github.com/en/articles/creating-a-javascript-action)" in the GitHub Help documentation.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

```yaml
uses: actions/hello-world-javascript-action@master
with:
  who-to-greet: 'Mona the Octocat'
```


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2F137717unity%2Furbo-winn.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2F137717unity%2Furbo-winn?ref=badge_large)