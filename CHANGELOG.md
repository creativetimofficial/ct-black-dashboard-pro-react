## [1.1.0] 06-03-2020
### Bug fixing
- Change the usage of `.env` file for absolute imports to `jsconfig.json` file
- Changed the usage of `.jsx` files to `.js` ones
- Github Issues:
  - https://github.com/creativetimofficial/ct-black-dashboard-pro-react/issues/20
  - https://github.com/creativetimofficial/ct-black-dashboard-pro-react/issues/18
  - https://github.com/creativetimofficial/ct-black-dashboard-pro-react/issues/17
  - https://github.com/creativetimofficial/ct-black-dashboard-pro-react/issues/15
  - https://github.com/creativetimofficial/ct-black-dashboard-pro-react/issues/14
  - https://github.com/creativetimofficial/ct-black-dashboard-pro-react/issues/12
  - https://github.com/creativetimofficial/ct-black-dashboard-pro-react/issues/11
  - https://github.com/creativetimofficial/ct-black-dashboard-pro-react/issues/10
  - https://github.com/creativetimofficial/ct-black-dashboard-pro-react/issues/6
### Major style changes
- Almost all files from the `src/assets/scss/*` were changed due to the update of the scss/css/styles to the latest version of [Black Dashboard PRO by Creative Tim](https://themes.getbootstrap.com/product/black-dashboard-pro-premium-bootstrap-4-admin/?ref=creativetim)
### Deleted components
### Added components
### Deleted dependencies
### Added dependencies
- For our copyrights:
  + gulp@4.0.2
  + gulp-append-prepend@1.0.8
- To stop the following warnings we've added:
  + eslint-plugin-flowtype@3.13.0
  + typescript@3.8.2
```
npm WARN eslint-config-react-app@5.2.0 requires a peer of eslint-plugin-flowtype@3.x but none is installed. You must install peer dependencies yourself.
npm WARN tsutils@3.17.1 requires a peer of typescript@>=2.8.0 || >= 3.2.0-dev || >= 3.3.0-dev || >= 3.4.0-dev || >= 3.5.0-dev || >= 3.6.0-dev || >= 3.6.0-beta || >= 3.7.0-dev || >= 3.7.0-beta but none is installed. You must install peer dependencies yourself.
```
### Updated dependencies
```
chart.js                       2.7.3   →         2.9.3
history                        4.7.2   →        4.10.1
moment                        2.23.0   →        2.24.0
node-sass                     4.11.0   →        4.13.1
nouislider                    12.1.0   →        14.1.1
prop-types                    15.6.2   →        15.7.2
react                         16.7.0   →       16.13.0
react-big-calendar            0.20.2   →        0.24.0
react-bootstrap-sweetalert     4.4.1   →         5.1.9
react-chartjs-2                2.7.4   →         2.9.0
react-dom                     16.7.0   →       16.13.0
react-jvectormap               0.0.4   →        0.0.16
react-notification-alert       0.0.9   →        0.0.12
react-router-dom               4.3.1   →         5.1.2
react-scripts                  2.1.3   →         3.4.0
react-select                   2.2.0   →         3.0.8
react-table                    6.8.6   →        6.11.5
reactstrap                     7.0.2   →         8.4.1
@types/googlemaps            3.30.16   →        3.39.3
@types/react                 16.7.18   →       16.9.23
```
### Warning
**We haven't updated react-table to the latest version (version 7), since it is still in testing. Also, on a future udpdate, we will drop support for this component and replace it with another dynamic table, such as DataTables.net!**
**The folowing components make react throw errors for using life-cycle methods that will be dropped in React 17.x: react-jvectormap, react-bootstrap-switch, react-datetime, react-tagsinput. But the UI or functionality of the product is not affected. When we'll update the product to React 17.x, if the issue will persist, we'll drop support for these components and replace them with other ones that create the same or a similar UI. Also, the warnings are only present in the development, and not in production.**
**The following warnings on installation could not be solved, due to some of our dependencies, however, they do not affect the functionality or the UI of the product:**
```
npm WARN deprecated request@2.88.2: request has been deprecated, see https://github.com/request/request/issues/3142
npm WARN deprecated popper.js@1.16.1: Popper changed home, find its new releases at @popperjs/core
npm WARN deprecated core-js@2.6.11: core-js@<3 is no longer maintained and not recommended for usage due to the number of issues. Please, upgrade your dependencies to the actual version of core-js@3.
npm WARN react-bootstrap-wizard@0.0.7 requires a peer of reactstrap@7.x.x but none is installed. You must install peer dependencies yourself.
```

## [1.0.0] 2019-01-14
### Original Release
- Added Reactstrap as base framework
- Added design from Black Dashboard PRO by Creative Tim
