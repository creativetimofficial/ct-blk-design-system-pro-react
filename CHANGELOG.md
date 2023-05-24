# Change Log

## [1.2.2] 2023-05-24

- Update the dependencies
- Fix the installation issue

## [1.2.1] 2021-08-04

- Update the dependencies
- Migration to React 18
- Migration to sass from node-sass

## [1.2.0] 2020-12-08
### Enhancements
- **Full Hooks Support**: Change `class` components usage with `functional` ones in order to support Hooks
### Bug fixing
### Misc
- Add new branch, named `main`, this will replace the `master` branch
### Major style changes
- Remove `src/assets/scss/blk-design-system-react/bootstrap` folder and start using the `node_modules/bootstrap` one
- Add `src/assets/scss/blk-design-system-react/react/_custom-forms.scss` for usage of Bootstrap Switch / Reactstrap CustomInput of type switch
### Deleted components
### Added components
- `src/components/TagsInput/TagsInput.js` instead of `react-tagsinput@3.19.0`
### Deleted dependencies
- react-bootstrap-switch
  - This project was not longer maintained, and it had issues with the new React version. The styles for it are still kept inside the product, but we do not recommended using the plugin anymore. You can use the simple Reactstrap CustomInput of type switch or the basic HTML Bootstrap Switch one.
- react-google-maps (and its dependencies: `@types/react`,`@types/googlemaps`, `@types/markerclustererplus`)
  - instead of the react-google-maps, since they are not maintained anymore, we've used default JS and Google Maps API: https://developers.google.com/maps/documentation/javascript/overview
- eslint-plugin-flowtype
- react-tagsinput
### Added dependencies
```
"@fortawesome/fontawesome-free": "5.15.1",
"@testing-library/jest-dom": "5.11.6",
"@testing-library/react": "11.2.2",
"@testing-library/user-event": "12.2.2",
"bootstrap": "4.5.3",
"jquery": "3.5.1",
"node-sass-package-importer": "5.3.2",
"web-vitals": "1.0.1"
```
### Updated dependencies
```
chart.js                   2.9.3   →     2.9.4
eslint-plugin-flowtype    3.13.0   →     5.2.0
headroom.js               0.11.0   →    0.12.0
moment                    2.24.0   →    2.29.1
node-sass                 4.14.0   →    4.14.1
nouislider                14.2.0   →    14.6.3
react                    16.13.1   →    17.0.1
react-chartjs-2            2.9.0   →    2.11.1
react-datetime            2.16.3   →     3.0.4
react-dom                16.13.1   →    17.0.1
react-router               5.1.2   →     5.2.0
react-router-dom           5.1.2   →     5.2.0
react-scripts              3.4.1   →     4.0.1
react-select               3.1.0   →     3.1.1
react-slick               0.25.2   →   0.27.13
reactstrap                 8.4.1   →     8.7.1
typescript                 3.8.3   →     4.1.2
```
### Important Notes
**The jQuery and TypeScript dependencies are installed only to stop console warnings on install. They are not actually used in our product. So the product is not based on jQuery, and it is not based on TypeScript!**
### Warning
_Some warnings may appear when running the installation command, but they do not affect the UI or the functionality of the product._
_The following warnings will appear when running the installation command, but they do not affect the UI or the functionality of the product (they will be solved in our next update):_
```
npm WARN react-datetime@3.0.4 requires a peer of react@^16.5.0 but none is installed. You must install peer dependencies yourself.
npm WARN react-select@3.1.1 requires a peer of react@^16.8.0 but none is installed. You must install peer dependencies yourself.
npm WARN react-select@3.1.1 requires a peer of react-dom@^16.8.0 but none is installed. You must install peer dependencies yourself.
npm WARN react-input-autosize@2.2.2 requires a peer of react@^0.14.9 || ^15.3.0 || ^16.0.0-rc || ^16.0 but none is installed. You must install peer dependencies yourself.
npm WARN react-popper@1.3.7 requires a peer of react@0.14.x || ^15.0.0 || ^16.0.0 but none is installed. You must install peer dependencies yourself.
npm WARN create-react-context@0.3.0 requires a peer of react@^0.14.0 || ^15.0.0 || ^16.0.0 but none is installed. You must install peer dependencies yourself.
```

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
