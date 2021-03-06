<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

## serverConfig

[src/defaults.js:17-27][1]

Server configuration

Type: [Object][2]

### Parameters

-   `options` **[Object][2]** object
    -   `options.osrmPath` **[string][3]** path to \*.osrm file [OSRM][4]
    -   `options.radius` **[number][5]** distance to draw the buffer as in
        [@turf/buffer][6]
    -   `options.cellSize` **[number][5]** the distance across each cell as in
        [@turf/point-grid][7]
    -   `options.intervals` **[Array][8]&lt;[number][5]>** intervals for isochrones in minutes
    -   `options.concavity` **[number][5]** relative measure of concavity as in [concaveman][9] (optional, default `2`)
    -   `options.deintersect` **[boolean][10]** whether or not to deintersect the final isochrones (optional, default `true`)
    -   `options.lengthThreshold` **[number][5]** length threshold as in [concaveman][9] (optional, default `0`)
    -   `options.units` **[string][3]** any of the options supported by turf units (optional, default `'kilometers'`)

[1]: https://github.com/urbica/galton/blob/f55f4478d36913fdfbbcff3f23dd9b4e50ae121e/src/defaults.js#L1-L16 "Source code on GitHub"

[2]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Object

[3]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/String

[4]: https://github.com/Project-OSRM/osrm-backend

[5]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Number

[6]: https://github.com/Turfjs/turf/tree/master/packages/turf-buffer

[7]: https://github.com/Turfjs/turf/tree/master/packages/turf-point-grid

[8]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Array

[9]: https://github.com/mapbox/concaveman

[10]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Boolean
