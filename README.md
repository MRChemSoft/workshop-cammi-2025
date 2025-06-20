# NMQC workshop 2025

Built with [Zola](https://www.getzola.org/) using a modified version of the [Juice theme](https://juice.huhu.io/)

## Work on the website locally

- Clone this repository.
- Install [Zola](https://www.getzola.org/documentation/getting-started/installation/).
- Build and serve the website with:

  ```
  $ zola serve
  ```
- Open `localhost:1111` in your browser.
- Making changes to *any* of the sources will instantly reload the local
  webserver, so you can look *live* at your changes taking effect.

### Notes

- to change the size of the logo, tweak the `sass/juice.scss` file, play with the `width` and `height` variable to set your desired logo size

```scss
.logo {
  img {
    width: 60px;
    height: auto;
    margin: 0 25px;
  }
}
```