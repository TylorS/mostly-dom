<a name="6.0.0"></a>
# [6.0.0](https://github.com/TylorS/mostly-dom/compare/v5.0.0...v6.0.0) (2018-10-22)


### Features

* upgrade to typescript 3.1.1 ([21923a6](https://github.com/TylorS/mostly-dom/commit/21923a6))



<a name="5.0.0"></a>
# [5.0.0](https://github.com/TylorS/mostly-dom/compare/v4.4.0...v5.0.0) (2018-03-06)


### Bug Fixes

* ensure importing from correct directory ([fe041df](https://github.com/TylorS/mostly-dom/commit/fe041df))
* use Element instead of Node ([0e3aebd](https://github.com/TylorS/mostly-dom/commit/0e3aebd))
* use undefined ([aeae37e](https://github.com/TylorS/mostly-dom/commit/aeae37e))


### Features

* allow extending props to skip and attributes to remove ([22d3c5b](https://github.com/TylorS/mostly-dom/commit/22d3c5b))
* JSX support, target -> currentTarget, no default modules ([50aab85](https://github.com/TylorS/mostly-dom/commit/50aab85))
* remove dependencies ([e505cb3](https://github.com/TylorS/mostly-dom/commit/e505cb3))
* upgrade CSS types ([183e9d3](https://github.com/TylorS/mostly-dom/commit/183e9d3))
* upgrade to typescript 2.7 + strict mode ([f2f5b09](https://github.com/TylorS/mostly-dom/commit/f2f5b09))



<a name="4.4.0"></a>
# [4.4.0](https://github.com/TylorS/mostly-dom/compare/v4.3.0...v4.4.0) (2018-03-06)



<a name="4.3.0"></a>
# [4.3.0](https://github.com/TylorS/mostly-dom/compare/v4.2.0...v4.3.0) (2017-09-02)


### Features

* **HtmlProperties:** convert VNodeProperties from type alias to interface ([7b7ebdb](https://github.com/TylorS/mostly-dom/commit/7b7ebdb))



<a name="4.2.0"></a>
# [4.2.0](https://github.com/TylorS/mostly-dom/compare/v4.1.0...v4.2.0) (2017-08-29)


### Bug Fixes

* **props:** fix props module ([f69be9c](https://github.com/TylorS/mostly-dom/commit/f69be9c))



<a name="4.1.0"></a>
# [4.1.0](https://github.com/TylorS/mostly-dom/compare/v4.0.0...v4.1.0) (2017-08-24)


### Bug Fixes

* **updateElement:** remove previous className and id from element ([b13051c](https://github.com/TylorS/mostly-dom/commit/b13051c))



<a name="4.0.0"></a>
# [4.0.0](https://github.com/TylorS/mostly-dom/compare/v3.6.2...v4.0.0) (2017-08-18)


### Features

* **hyperscript:** remove the ability to define className/id in selector ([f61c008](https://github.com/TylorS/mostly-dom/commit/f61c008))
* **modules:** expose module factory functions ([f2cd4cb](https://github.com/TylorS/mostly-dom/commit/f2cd4cb))


### BREAKING CHANGES

* **hyperscript:**   h and various hyperscript-helpers no longer accept a className/id selector
* **modules:**   No longer are the modules concatenated, but instead they can be overridden.
  before init required an array of modules, but now it is optional. To continue
  having the same behavior as before use init() with no arguments



<a name="3.6.2"></a>
## [3.6.2](https://github.com/TylorS/mostly-dom/compare/v3.6.0...v3.6.2) (2017-08-07)


### Bug Fixes

* **updateElement:** correctly remove previous properties ([06456fd](https://github.com/TylorS/mostly-dom/commit/06456fd))



<a name="3.5.0"></a>
# [3.5.0](https://github.com/TylorS/mostly-dom/compare/v3.4.0...v3.5.0) (2017-06-22)


### Bug Fixes

* **hasCssSelector:** support className and id set using props ([1e26434](https://github.com/TylorS/mostly-dom/commit/1e26434))



<a name="3.4.0"></a>
# [3.4.0](https://github.com/TylorS/mostly-dom/compare/v3.3.0...v3.4.0) (2017-06-09)



<a name="3.3.0"></a>
# [3.3.0](https://github.com/TylorS/mostly-dom/compare/v3.2.0...v3.3.0) (2017-06-09)


### Bug Fixes

* **hh:** missing import ([e06d256](https://github.com/TylorS/mostly-dom/commit/e06d256))


### Features

* **events:** make each event optional ([c45dd7c](https://github.com/TylorS/mostly-dom/commit/c45dd7c))
* **modules:** implement events module ([f34a97c](https://github.com/TylorS/mostly-dom/commit/f34a97c))
* **props:** skip over on property for props ([00d7fe9](https://github.com/TylorS/mostly-dom/commit/00d7fe9))
* **types:** parameterize each hh function with event types ([49d9f32](https://github.com/TylorS/mostly-dom/commit/49d9f32))



<a name="3.2.0"></a>
# [3.2.0](https://github.com/TylorS/mostly-dom/compare/v3.1.0...v3.2.0) (2017-06-08)


### Bug Fixes

* **src:** cleanup tslint error ([03ee4e3](https://github.com/TylorS/mostly-dom/commit/03ee4e3))
* **types:** add slot to tagnames ([62d0e7c](https://github.com/TylorS/mostly-dom/commit/62d0e7c))



<a name="3.1.0"></a>
# [3.1.0](https://github.com/TylorS/mostly-dom/compare/v3.0.0...v3.1.0) (2017-05-30)


### Features

* **hyperscript:** export parseSelector function ([1fdf3d0](https://github.com/TylorS/mostly-dom/commit/1fdf3d0))



<a name="3.0.0"></a>
# [3.0.0](https://github.com/TylorS/mostly-dom/compare/v2.1.1...v3.0.0) (2017-05-30)


### Features

* **types:** use VNode with default type parameters ([40ac337](https://github.com/TylorS/mostly-dom/commit/40ac337))


### BREAKING CHANGES

* **types:** deletes VirtualNode and ElementVirtualNode types



<a name="2.1.1"></a>
## [2.1.1](https://github.com/TylorS/mostly-dom/compare/v2.1.0...v2.1.1) (2017-05-08)


### Bug Fixes

* **types:** correct HTMLTitleElementProperties ([3384818](https://github.com/TylorS/mostly-dom/commit/3384818))



<a name="2.1.0"></a>
# [2.1.0](https://github.com/TylorS/mostly-dom/compare/v2.0.3...v2.1.0) (2017-05-08)


### Features

* **elementToVNode:** parameterize elementToVNode ([fdb7ce6](https://github.com/TylorS/mostly-dom/commit/fdb7ce6))



<a name="2.0.3"></a>
## [2.0.3](https://github.com/TylorS/mostly-dom/compare/v2.0.2...v2.0.3) (2017-05-08)


### Bug Fixes

* **init:** parameterize init instead of patch ([1368dc1](https://github.com/TylorS/mostly-dom/commit/1368dc1))



<a name="2.0.2"></a>
## [2.0.2](https://github.com/TylorS/mostly-dom/compare/v2.0.1...v2.0.2) (2017-05-06)


### Bug Fixes

* **hyperscript:** improve typings ([1d6db71](https://github.com/TylorS/mostly-dom/commit/1d6db71))



<a name="2.0.1"></a>
## [2.0.1](https://github.com/TylorS/mostly-dom/compare/v2.0.0...v2.0.1) (2017-05-06)


### Bug Fixes

* **patch:** allow parameterizing patch with element type ([351d8b1](https://github.com/TylorS/mostly-dom/commit/351d8b1))



<a name="2.0.0"></a>
# [2.0.0](https://github.com/TylorS/mostly-dom/compare/v1.5.0...v2.0.0) (2017-05-06)


### Features

* **hyperscript:** create element-specific hyperscript-helpers ([24fde72](https://github.com/TylorS/mostly-dom/commit/24fde72))
* **mostly-dom:** parameterize VNodeProps and Hooks ([d94cd68](https://github.com/TylorS/mostly-dom/commit/d94cd68))


### BREAKING CHANGES

* **hyperscript:** can no longer set properties that do no exist for a given element type



<a name="1.5.0"></a>
# [1.5.0](https://github.com/TylorS/mostly-dom/compare/v1.4.2...v1.5.0) (2017-04-29)


### Features

* **types:** support ReadonlyArray children ([db0d296](https://github.com/TylorS/mostly-dom/commit/db0d296))



<a name="1.4.2"></a>
## [1.4.2](https://github.com/TylorS/mostly-dom/compare/v1.4.1...v1.4.2) (2017-03-01)


### Bug Fixes

* **modules:** fix module bugs ([98c5934](https://github.com/TylorS/mostly-dom/commit/98c5934))



<a name="1.4.1"></a>
## [1.4.1](https://github.com/TylorS/mostly-dom/compare/v1.4.0...v1.4.1) (2017-02-28)


### Bug Fixes

* **styles:** always set updated styles ([b845124](https://github.com/TylorS/mostly-dom/commit/b845124))



<a name="1.4.0"></a>
# [1.4.0](https://github.com/TylorS/mostly-dom/compare/v1.3.1...v1.4.0) (2017-02-14)


### Features

* **mostly-dom:** add focus module ([a457faf](https://github.com/TylorS/mostly-dom/commit/a457faf))



<a name="1.3.1"></a>
## [1.3.1](https://github.com/TylorS/mostly-dom/compare/v1.3.0...v1.3.1) (2017-02-07)


### Bug Fixes

* **hyperscript:** fix typescript 2.1.5 compiler errors ([e85b786](https://github.com/TylorS/mostly-dom/commit/e85b786))
* **patchVNode:** check element type before setting properties ([84ea0dc](https://github.com/TylorS/mostly-dom/commit/84ea0dc)), closes [motorcyclejs/motorcyclejs#27](https://github.com/motorcyclejs/motorcyclejs/issues/27)
* **props:** add \\`class\\` to PROPERTIES_TO_SKIP ([3c5056c](https://github.com/TylorS/mostly-dom/commit/3c5056c))



<a name="1.3.0"></a>
# [1.3.0](https://github.com/TylorS/mostly-dom/compare/v1.2.1...v1.3.0) (2017-02-06)


### Features

* **hh:** add i helper ([ee6cf30](https://github.com/TylorS/mostly-dom/commit/ee6cf30))
* **VNodeProps:** Add ability to give in extra classes as a key-value dictionary where the key is th ([629075f](https://github.com/TylorS/mostly-dom/commit/629075f))



<a name="1.2.1"></a>
## [1.2.1](https://github.com/TylorS/mostly-dom/compare/v1.2.0...v1.2.1) (2017-01-10)


### Bug Fixes

* **package:** add missing dep ([217d966](https://github.com/TylorS/mostly-dom/commit/217d966))



<a name="1.2.0"></a>
# [1.2.0](https://github.com/TylorS/mostly-dom/compare/v1.1.2...v1.2.0) (2017-01-10)


### Bug Fixes

* **types:** correct VirtualNode types ([32a32e3](https://github.com/TylorS/mostly-dom/commit/32a32e3))


### Features

* **hasCssSelector:** match more complex css selectors ([7c3e8e7](https://github.com/TylorS/mostly-dom/commit/7c3e8e7))
* **hyperscript:** export new functions ([fb1de4d](https://github.com/TylorS/mostly-dom/commit/fb1de4d))
* **querySelector:** implement vNode querySelector ([015a7a7](https://github.com/TylorS/mostly-dom/commit/015a7a7))
* **querySelectorAll:** implement vNode querySelectorAll ([6088521](https://github.com/TylorS/mostly-dom/commit/6088521))



<a name="1.1.2"></a>
## [1.1.2](https://github.com/TylorS/mostly-dom/compare/v1.1.1...v1.1.2) (2017-01-03)


### Bug Fixes

* **elementToVNode:** add text element to textVNode ([3de43ea](https://github.com/TylorS/mostly-dom/commit/3de43ea))



<a name="1.1.1"></a>
## [1.1.1](https://github.com/TylorS/mostly-dom/compare/v1.1.0...v1.1.1) (2017-01-02)


### Bug Fixes

* **mostly-dom:** add a fix for adding scopes to children ([9027d81](https://github.com/TylorS/mostly-dom/commit/9027d81))



<a name="1.1.0"></a>
# [1.1.0](https://github.com/TylorS/mostly-dom/compare/v1.0.0...v1.1.0) (2017-01-02)


### Features

* **h:** create function variations with template types ([5fb8b7f](https://github.com/TylorS/mostly-dom/commit/5fb8b7f))
* **hasCssSelector:** add utility function that checks for CSS classes on VNode. ([4ba729a](https://github.com/TylorS/mostly-dom/commit/4ba729a))
* **hyperscript:** add hyperscript helper functions ([40af759](https://github.com/TylorS/mostly-dom/commit/40af759))
* **types:** add HTML tag name types ([b36080a](https://github.com/TylorS/mostly-dom/commit/b36080a))



<a name="1.0.0"></a>
# [1.0.0](https://github.com/TylorS/mostly-dom/compare/0.0.0...v1.0.0) (2017-01-02)


### Features

* **mostly-dom:** complete implementation ([a07539a](https://github.com/TylorS/mostly-dom/commit/a07539a))


### BREAKING CHANGES

* **mostly-dom:** initial implementation



<a name="0.0.0"></a>
# [0.0.0](https://github.com/TylorS/mostly-dom/compare/2aa8a52...0.0.0) (2016-12-17)


### Features

* **mostly-dom:** initial commit ([2aa8a52](https://github.com/TylorS/mostly-dom/commit/2aa8a52))



