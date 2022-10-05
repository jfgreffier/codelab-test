id: codelab-test

# CodeLab test

## Step 1
Duration: 0:02:00

Are you trying to create easy to use, visually appealing content for the tech community? This CodeLab will show you how to quickly create your own Google CodeLab just like the one you're using right now. 
When creating a Codelab you have two authoring options: 
1. Using a Google Doc
1. Using a markdown file

## Code embedding
Duration: 0:03:00

No language set
```
function fibLike(one, two, length) {
  const result = [one, two];
  for (let i = 2; i < length; i++) {
    result.push(result[result.length - 1] + result[result.length - 2]);
  }
  return result;
}

```

JavaScript (js)
```js
function fibLike(one, two, length) {
  const result = [one, two];
  for (let i = 2; i < length; i++) {
    result.push(result[result.length - 1] + result[result.length - 2]);
  }
  return result;
}

```

iframe
![https://codepen.io/tzoght/embed/yRNZaP](https://en.wikipedia.org/wiki/File:Example.jpg "Try Me Publisher")

## Overview
Duration: 0:10:00

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## How to generate
Duration: 0:01:00

```
claat export codelab.md
serve ./codelab-test
```

