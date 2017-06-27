# Amedia Parallax Starter

This seed repo serves as an Parallax starter for anyone looking to get up and running with custom parallax ad.

## Getting Started

* `fork` this repo
* `clone` your fork
* `npm install`
* `npm run dev` the example file is open in your browser
* Start building awesome stuff

## Build steps and best practises

Ensure the ad takes up all available space

```css
html, body, #banner {
  width: 100vw;
  height: 100vh;
}
```

Work with media queries to ensure all vital information is viewable in different screen sizes. Usually its based on the content thats have to fit. Start with the smallest and work your way up.

In the `examples/custom.html` we have a this big copy text thats transforms from smallest font-size of `62px`, `125px` to `150px` depending on available space.

## Hosting and delivery

Available delivery options are [iframe](https://developer.api.no/adverts/html5_adverts_specification.html#hosting-av-materiell-hos-kunde) or [3party script tag](https://developer.api.no/adverts/html5_adverts_specification.html#levering-av-materiell-som-tredjeparts-script).  
