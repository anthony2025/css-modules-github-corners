### GitHub Corners

Tim Holman's [github-corners](https://github.com/tholman/github-corners) as a ready to use React component using CSS Modules.

### Screenshot
visit the [original project page](http://tholman.com/github-corners) to see the animations.

![Screenshot](https://i.imgur.com/703iLiS.png)

### Props
```js
GithubCorner.propTypes = {
  repository: PropTypes.string.isRequired,
  bgColor: PropTypes.string,
  mainColor: PropTypes.string,
  left: PropTypes.bool
}

GithubCorner.defaultProps = {
  bgColor: '#000',
  mainColor: '#FFF',
  left: false
}
```


### Acknowledgements
Copyright (c) 2016 Tim Holman - http://tholman.com

[The MIT License](https://github.com/tholman/github-corners/blob/master/license.md)
