# Change Log

## [1.1.0] 2020-04-24
### Bug fixing
- https://github.com/creativetimofficial/ct-blk-design-system-pro-react/issues/5
- https://github.com/creativetimofficial/ct-blk-design-system-pro-react/issues/4
- https://github.com/creativetimofficial/ct-blk-design-system-pro-react/issues/2
- https://github.com/creativetimofficial/ct-blk-design-system-pro-react/issues/1
### Major style changes
- `src/assets/scss/blk-design-system-pro/custom/_example-pages.scss`
- `src/assets/scss/blk-design-system-pro/custom/_sections.scss`
- `src/assets/scss/blk-design-system-pro/_example-pages.scss`
- `src/assets/scss/blk-design-system-pro/sections/_headers.scss`
- `src/assets/scss/blk-design-system-pro/react/plugins/_plugin-headroomjs.scss`
- `src/assets/scss/blk-design-system-pro/react/_tooltips.scss`
- `src/assets/scss/blk-design-system-pro/react/react-differences.scss`
### Deleted components
### Added components
### Deleted dependencies
### Added dependencies
+ eslint-plugin-flowtype@3.13.0 (to stop terminal/cmd Warning)
### Updated dependencies
```
chart.js              2.8.0   →     2.9.3
headroom.js           0.9.4   →    0.11.0
node-sass            4.12.0   →    4.14.0
nouislider           13.1.5   →    14.2.0
react                16.8.6   →   16.13.1
react-chartjs-2       2.7.6   →     2.9.0
react-dom            16.8.6   →   16.13.1
react-router          5.0.0   →     5.1.2
react-router-dom      5.0.0   →     5.1.2
react-scripts         3.0.1   →     3.4.1
react-select          2.4.3   →     3.1.0
react-slick          0.24.0   →    0.25.2
reactstrap            8.0.0   →     8.4.1
@types/googlemaps   3.30.20   →    3.39.3
@types/react        16.8.17   →   16.9.34
typescript            3.4.5   →     3.8.3
```
### Warning
**The following warnings may appear when running the installation command, but they do not affect the UI or the functionality of the product:**
```
npm WARN deprecated request@2.88.2: request has been deprecated, see https://github.com/request/request/issues/3142
npm WARN deprecated popper.js@1.16.1: Popper changed home, find its new releases at @popperjs/core
npm WARN deprecated core-js@2.6.11: core-js@<3 is no longer maintained and not recommended for usage due to the number of issues. Please, upgrade your dependencies to the actual version of core-js@3.
```
**The fllowing warnings appear in development (not in production) due to some of our dependencies: Component (DateTime), DateTime, Switch, TagsInput, withScriptjs(withGoogleMap(Component)), withGoogleMap(Component), but they do not affect the UI or the functionality of the product. If the issues will persist in React v17, we will drop the usage for them, and replace them with other plugins, or create ourselves these libraries:**
```
Warning: componentWillMount has been renamed...
```
```
Warning: componentWillReceiveProps has been renamed...
```

## [1.0.0] 2019-05-20
### Original Release
- Added Reactstrap as base framework
- Added design from BLK Design System by Creative Tim
