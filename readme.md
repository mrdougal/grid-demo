# Display Grid


Grid doesn’t replace flex, they’re for different jobs.

- Grid works in two directions, rows and columns
- Flex works in one direction - the flex direction

“Intrinsic design” - term coined by Jen Simmons. Code what you mean vs hacks. I believe grid gets us a lot closer to this utopia

Racheal Andrew - author of grid, said how she wished grid and flex box came out at the same time.

List of links
http://jensimmons.com/post/feb-27-2017/learn-css-grid

Due to grid being a new standard, it's probably best to serve your CSS rules inside a [feature query](https://developer.mozilla.org/en-US/docs/Web/CSS/@supports).
As modern browsers should also understand the `@supports` query

```css
@supports (display: grid) {
  .myTable {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  }
}
```

<img width="882" alt="screen shot 2019-03-07 at 7 13 12 am" src="https://user-images.githubusercontent.com/9635/53903444-9e896a80-40a8-11e9-9834-bcc7d74c5491.png">
