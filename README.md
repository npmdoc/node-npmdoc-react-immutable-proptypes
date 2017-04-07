# api documentation for  [react-immutable-proptypes (v2.1.0)](https://github.com/HurricaneJames/react-immutable-proptypes)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-immutable-proptypes.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-immutable-proptypes) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-immutable-proptypes.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-immutable-proptypes)
#### PropType validators that work with Immutable.js.

[![NPM](https://nodei.co/npm/react-immutable-proptypes.png?downloads=true)](https://www.npmjs.com/package/react-immutable-proptypes)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-immutable-proptypes/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-react-immutable-proptypes_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-immutable-proptypes/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-immutable-proptypes/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-immutable-proptypes/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "James Burnett",
        "email": "HurricaneJamesEsq@gmail.com",
        "url": "https://github.com/HurricaneJames/react-immutable-proptypes"
    },
    "bugs": {
        "url": "https://github.com/HurricaneJames/react-immutable-proptypes/issues"
    },
    "dependencies": {},
    "description": "PropType validators that work with Immutable.js.",
    "devDependencies": {
        "babel": "^4.6.6",
        "babel-eslint": "^3.1.1",
        "eslint": "^0.21.0",
        "eslint-plugin-react": "^2.2.0",
        "expect.js": "^0.3.1",
        "immutable": "^3.7.4",
        "istanbul": "~0.3.7",
        "mocha": "^2.3.3",
        "react": "^0.14.0",
        "react-dom": "^0.14.0"
    },
    "directories": {},
    "dist": {
        "shasum": "023d6f39bb15c97c071e9e60d00d136eac5fa0b4",
        "tarball": "https://registry.npmjs.org/react-immutable-proptypes/-/react-immutable-proptypes-2.1.0.tgz"
    },
    "gitHead": "121f65236c22a68ff056bb751d664862fc0c2aa5",
    "homepage": "https://github.com/HurricaneJames/react-immutable-proptypes",
    "keywords": [
        "react",
        "immutable-js",
        "immutable",
        "immutablejs",
        "proptype"
    ],
    "license": "MIT",
    "main": "dist/ImmutablePropTypes.js",
    "maintainers": [
        {
            "name": "hurricanejames",
            "email": "HurricaneJamesEsq@gmail.com"
        }
    ],
    "name": "react-immutable-proptypes",
    "optionalDependencies": {},
    "peerDependencies": {
        "immutable": ">=3.6.2"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/HurricaneJames/react-immutable-proptypes.git"
    },
    "scripts": {
        "build": "./scripts/build",
        "lint": "eslint ./src",
        "prepublish": "npm run build",
        "test": "./scripts/test",
        "test-cov": "./scripts/test-cov"
    },
    "version": "2.1.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module react-immutable-proptypes](#apidoc.module.react-immutable-proptypes)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>contains (shapeTypes)](#apidoc.element.react-immutable-proptypes.contains)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>iterable ()](#apidoc.element.react-immutable-proptypes.iterable)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>iterableOf (typeChecker)](#apidoc.element.react-immutable-proptypes.iterableOf)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>list ()](#apidoc.element.react-immutable-proptypes.list)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>listOf (typeChecker)](#apidoc.element.react-immutable-proptypes.listOf)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>map ()](#apidoc.element.react-immutable-proptypes.map)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>mapContains (shapeTypes)](#apidoc.element.react-immutable-proptypes.mapContains)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>mapOf (valuesTypeChecker, keysTypeChecker)](#apidoc.element.react-immutable-proptypes.mapOf)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>orderedMap ()](#apidoc.element.react-immutable-proptypes.orderedMap)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>orderedMapOf (valuesTypeChecker, keysTypeChecker)](#apidoc.element.react-immutable-proptypes.orderedMapOf)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>orderedSet ()](#apidoc.element.react-immutable-proptypes.orderedSet)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>orderedSetOf (typeChecker)](#apidoc.element.react-immutable-proptypes.orderedSetOf)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>record ()](#apidoc.element.react-immutable-proptypes.record)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>recordOf (recordKeys)](#apidoc.element.react-immutable-proptypes.recordOf)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>seq ()](#apidoc.element.react-immutable-proptypes.seq)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>set ()](#apidoc.element.react-immutable-proptypes.set)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>setOf (typeChecker)](#apidoc.element.react-immutable-proptypes.setOf)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>shape (shapeTypes)](#apidoc.element.react-immutable-proptypes.shape)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>stack ()](#apidoc.element.react-immutable-proptypes.stack)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>stackOf (typeChecker)](#apidoc.element.react-immutable-proptypes.stackOf)
1.  object <span class="apidocSignatureSpan">react-immutable-proptypes.</span>ImmutablePropTypes

#### [module react-immutable-proptypes.ImmutablePropTypes](#apidoc.module.react-immutable-proptypes.ImmutablePropTypes)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>contains (shapeTypes)](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.contains)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>iterable ()](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.iterable)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>iterableOf (typeChecker)](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.iterableOf)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>list ()](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.list)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>listOf (typeChecker)](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.listOf)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>map ()](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.map)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>mapContains (shapeTypes)](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.mapContains)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>mapOf (valuesTypeChecker, keysTypeChecker)](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.mapOf)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>orderedMap ()](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.orderedMap)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>orderedMapOf (valuesTypeChecker, keysTypeChecker)](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.orderedMapOf)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>orderedSet ()](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.orderedSet)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>orderedSetOf (typeChecker)](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.orderedSetOf)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>record ()](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.record)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>recordOf (recordKeys)](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.recordOf)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>seq ()](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.seq)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>set ()](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.set)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>setOf (typeChecker)](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.setOf)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>shape (shapeTypes)](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.shape)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>stack ()](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.stack)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>stackOf (typeChecker)](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.stackOf)

#### [module react-immutable-proptypes.iterable](#apidoc.module.react-immutable-proptypes.iterable)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>iterable ()](#apidoc.element.react-immutable-proptypes.iterable.iterable)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.iterable.</span>isRequired ()](#apidoc.element.react-immutable-proptypes.iterable.isRequired)

#### [module react-immutable-proptypes.list](#apidoc.module.react-immutable-proptypes.list)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>list ()](#apidoc.element.react-immutable-proptypes.list.list)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.list.</span>isRequired ()](#apidoc.element.react-immutable-proptypes.list.isRequired)

#### [module react-immutable-proptypes.map](#apidoc.module.react-immutable-proptypes.map)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>map ()](#apidoc.element.react-immutable-proptypes.map.map)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.map.</span>isRequired ()](#apidoc.element.react-immutable-proptypes.map.isRequired)

#### [module react-immutable-proptypes.orderedMap](#apidoc.module.react-immutable-proptypes.orderedMap)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>orderedMap ()](#apidoc.element.react-immutable-proptypes.orderedMap.orderedMap)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.orderedMap.</span>isRequired ()](#apidoc.element.react-immutable-proptypes.orderedMap.isRequired)

#### [module react-immutable-proptypes.orderedSet](#apidoc.module.react-immutable-proptypes.orderedSet)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>orderedSet ()](#apidoc.element.react-immutable-proptypes.orderedSet.orderedSet)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.orderedSet.</span>isRequired ()](#apidoc.element.react-immutable-proptypes.orderedSet.isRequired)

#### [module react-immutable-proptypes.record](#apidoc.module.react-immutable-proptypes.record)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>record ()](#apidoc.element.react-immutable-proptypes.record.record)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.record.</span>isRequired ()](#apidoc.element.react-immutable-proptypes.record.isRequired)

#### [module react-immutable-proptypes.seq](#apidoc.module.react-immutable-proptypes.seq)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>seq ()](#apidoc.element.react-immutable-proptypes.seq.seq)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.seq.</span>isRequired ()](#apidoc.element.react-immutable-proptypes.seq.isRequired)

#### [module react-immutable-proptypes.set](#apidoc.module.react-immutable-proptypes.set)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>set ()](#apidoc.element.react-immutable-proptypes.set.set)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.set.</span>isRequired ()](#apidoc.element.react-immutable-proptypes.set.isRequired)

#### [module react-immutable-proptypes.stack](#apidoc.module.react-immutable-proptypes.stack)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>stack ()](#apidoc.element.react-immutable-proptypes.stack.stack)
1.  [function <span class="apidocSignatureSpan">react-immutable-proptypes.stack.</span>isRequired ()](#apidoc.element.react-immutable-proptypes.stack.isRequired)



# <a name="apidoc.module.react-immutable-proptypes"></a>[module react-immutable-proptypes](#apidoc.module.react-immutable-proptypes)

#### <a name="apidoc.element.react-immutable-proptypes.contains"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>contains (shapeTypes)](#apidoc.element.react-immutable-proptypes.contains)
- description and source-code
```javascript
function createShapeChecker(shapeTypes) {
  return createShapeTypeChecker(shapeTypes);
}
```
- example usage
```shell
...

'''js
var ImmutablePropTypes = require('react-immutable-proptypes');
var MyReactComponent = React.createClass({
    // ...
    propTypes: {
        myRequiredImmutableList: ImmutablePropTypes.listOf(
            ImmutablePropTypes.contains({
                someNumberProp: React.PropTypes.number.isRequired
            })
        ).isRequired
    }
    // ...
});
'''
...
```

#### <a name="apidoc.element.react-immutable-proptypes.iterable"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>iterable ()](#apidoc.element.react-immutable-proptypes.iterable)
- description and source-code
```javascript
iterable = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.iterableOf"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>iterableOf (typeChecker)](#apidoc.element.react-immutable-proptypes.iterableOf)
- description and source-code
```javascript
function createIterableOfTypeChecker(typeChecker) {
  return createIterableTypeChecker(typeChecker, "Iterable", Immutable.Iterable.isIterable);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.list"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>list ()](#apidoc.element.react-immutable-proptypes.list)
- description and source-code
```javascript
list = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.listOf"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>listOf (typeChecker)](#apidoc.element.react-immutable-proptypes.listOf)
- description and source-code
```javascript
function createListOfTypeChecker(typeChecker) {
  return createIterableTypeChecker(typeChecker, "List", Immutable.List.isList);
}
```
- example usage
```shell
...
Usage is simple, they work with and like any 'React.PropType.*' validator.

'''js
var ImmutablePropTypes = require('react-immutable-proptypes');
var MyReactComponent = React.createClass({
    // ...
    propTypes: {
        myRequiredImmutableList: ImmutablePropTypes.listOf(
            ImmutablePropTypes.contains({
                someNumberProp: React.PropTypes.number.isRequired
            })
        ).isRequired
    }
    // ...
});
...
```

#### <a name="apidoc.element.react-immutable-proptypes.map"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>map ()](#apidoc.element.react-immutable-proptypes.map)
- description and source-code
```javascript
map = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.mapContains"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>mapContains (shapeTypes)](#apidoc.element.react-immutable-proptypes.mapContains)
- description and source-code
```javascript
function createMapContainsChecker(shapeTypes) {
  return createShapeTypeChecker(shapeTypes, "Map", Immutable.Map.isMap);
}
```
- example usage
```shell
...

* 'ImmutablePropTypes.mapOf' allows you to control both map values nad keys (in Immutable.Map, keys could be _anything_ including
 another Immutable collections). It accepts two arguments - first one for values, second one for keys (optional). If you are interested
 in validation of keys only, just pass 'React.PropTypes.any' as the first argument.

'''es6
// ...
aMap: ImmutablePropTypes.mapOf(
React.PropTypes.any, // validation for values
ImmutablePropTypes.mapContains({ // validation for keys
    a: React.PropTypes.number.isRequired,
    b: React.PropTypes.string
})
)
// ...
const aMap = Immutable.Map([
[Immutable.Map({a: 1, b: '2'}), 'foo'],
...
```

#### <a name="apidoc.element.react-immutable-proptypes.mapOf"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>mapOf (valuesTypeChecker, keysTypeChecker)](#apidoc.element.react-immutable-proptypes.mapOf)
- description and source-code
```javascript
function createMapOfTypeChecker(valuesTypeChecker, keysTypeChecker) {
  return createMapOfTypeCheckerFactory(valuesTypeChecker, keysTypeChecker, "Map", Immutable.Map.isMap);
}
```
- example usage
```shell
...

* 'ImmutablePropTypes.listOf' is based on 'React.PropTypes.array' and is specific to 'Immutable.List'.

* 'ImmutablePropTypes.mapOf' allows you to control both map values nad keys (in Immutable.Map, keys could be _anything_ including
 another Immutable collections). It accepts two arguments - first one for values, second one for keys (optional). If you are interested
 in validation of keys only, just pass 'React.PropTypes.any' as the first argument.

'''es6
// ...
aMap: ImmutablePropTypes.mapOf(
    React.PropTypes.any, // validation for values
    ImmutablePropTypes.mapContains({ // validation for keys
        a: React.PropTypes.number.isRequired,
        b: React.PropTypes.string
    })
)
// ...
...
```

#### <a name="apidoc.element.react-immutable-proptypes.orderedMap"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>orderedMap ()](#apidoc.element.react-immutable-proptypes.orderedMap)
- description and source-code
```javascript
orderedMap = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.orderedMapOf"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>orderedMapOf (valuesTypeChecker, keysTypeChecker)](#apidoc.element.react-immutable-proptypes.orderedMapOf)
- description and source-code
```javascript
function createOrderedMapOfTypeChecker(valuesTypeChecker, keysTypeChecker) {
  return createMapOfTypeCheckerFactory(valuesTypeChecker, keysTypeChecker, "OrderedMap", Immutable.OrderedMap.isOrderedMap);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.orderedSet"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>orderedSet ()](#apidoc.element.react-immutable-proptypes.orderedSet)
- description and source-code
```javascript
orderedSet = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.orderedSetOf"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>orderedSetOf (typeChecker)](#apidoc.element.react-immutable-proptypes.orderedSetOf)
- description and source-code
```javascript
function createOrderedSetOfTypeChecker(typeChecker) {
  return createIterableTypeChecker(typeChecker, "OrderedSet", Immutable.OrderedSet.isOrderedSet);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.record"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>record ()](#apidoc.element.react-immutable-proptypes.record)
- description and source-code
```javascript
record = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.recordOf"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>recordOf (recordKeys)](#apidoc.element.react-immutable-proptypes.recordOf)
- description and source-code
```javascript
function createRecordOfTypeChecker(recordKeys) {
  function validate(props, propName, componentName, location, propFullName) {
    for (var _len = arguments.length, rest = Array(_len > 5 ? _len - 5 : 0), _key = 5; _key < _len; _key++) {
      rest[_key - 5] = arguments[_key];
    }

    var propValue = props[propName];
    if (!(propValue instanceof Immutable.Record)) {
      var propType = getPropType(propValue);
      var locationName = location;
      return new Error("Invalid " + locationName + " '" + propFullName + "' of type '" + propType + "' " + ("supplied to '" + componentName
 + "', expected an Immutable.js Record."));
    }
    for (var key in recordKeys) {
      var checker = recordKeys[key];
      if (!checker) {
        continue;
      }
      var mutablePropValue = propValue.toObject();
      var error = checker.apply(undefined, [mutablePropValue, key, componentName, location, "" + propFullName + "." + key].concat
(rest));
      if (error) {
        return error;
      }
    }
  }
  return createChainableTypeChecker(validate);
}
```
- example usage
```shell
...

* 'ImmutablePropTypes.iterableOf' is the generic form of listOf/mapOf. It is useful when there is no need to validate anything other
 than Immutable.js compatible (ie. 'Immutable.Iterable'). Continue to use 'listOf' and/or 'mapOf' when you know the type.

* 'ImmutablePropTypes.recordOf' is like 'contains', except it operates on Record properties.

'''js
// ...
aRecord: ImmutablePropTypes.recordOf({
    keyA: React.PropTypes.string,
    keyB: ImmutablePropTypes.list.isRequired
})
// ...
'''

* 'ImmutablePropTypes.mapContains' is based on 'React.PropTypes.shape' and will only work with 'Immutable.Map'.
...
```

#### <a name="apidoc.element.react-immutable-proptypes.seq"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>seq ()](#apidoc.element.react-immutable-proptypes.seq)
- description and source-code
```javascript
seq = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.set"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>set ()](#apidoc.element.react-immutable-proptypes.set)
- description and source-code
```javascript
set = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.setOf"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>setOf (typeChecker)](#apidoc.element.react-immutable-proptypes.setOf)
- description and source-code
```javascript
function createSetOfTypeChecker(typeChecker) {
  return createIterableTypeChecker(typeChecker, "Set", Immutable.Set.isSet);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.shape"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>shape (shapeTypes)](#apidoc.element.react-immutable-proptypes.shape)
- description and source-code
```javascript
function createShapeChecker(shapeTypes) {
  return createShapeTypeChecker(shapeTypes);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.stack"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>stack ()](#apidoc.element.react-immutable-proptypes.stack)
- description and source-code
```javascript
stack = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.stackOf"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>stackOf (typeChecker)](#apidoc.element.react-immutable-proptypes.stackOf)
- description and source-code
```javascript
function createStackOfTypeChecker(typeChecker) {
  return createIterableTypeChecker(typeChecker, "Stack", Immutable.Stack.isStack);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-immutable-proptypes.ImmutablePropTypes"></a>[module react-immutable-proptypes.ImmutablePropTypes](#apidoc.module.react-immutable-proptypes.ImmutablePropTypes)

#### <a name="apidoc.element.react-immutable-proptypes.ImmutablePropTypes.contains"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>contains (shapeTypes)](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.contains)
- description and source-code
```javascript
function createShapeChecker(shapeTypes) {
  return createShapeTypeChecker(shapeTypes);
}
```
- example usage
```shell
...

'''js
var ImmutablePropTypes = require('react-immutable-proptypes');
var MyReactComponent = React.createClass({
    // ...
    propTypes: {
        myRequiredImmutableList: ImmutablePropTypes.listOf(
            ImmutablePropTypes.contains({
                someNumberProp: React.PropTypes.number.isRequired
            })
        ).isRequired
    }
    // ...
});
'''
...
```

#### <a name="apidoc.element.react-immutable-proptypes.ImmutablePropTypes.iterable"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>iterable ()](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.iterable)
- description and source-code
```javascript
iterable = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.ImmutablePropTypes.iterableOf"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>iterableOf (typeChecker)](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.iterableOf)
- description and source-code
```javascript
function createIterableOfTypeChecker(typeChecker) {
  return createIterableTypeChecker(typeChecker, 'Iterable', Immutable.Iterable.isIterable);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.ImmutablePropTypes.list"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>list ()](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.list)
- description and source-code
```javascript
list = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.ImmutablePropTypes.listOf"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>listOf (typeChecker)](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.listOf)
- description and source-code
```javascript
function createListOfTypeChecker(typeChecker) {
  return createIterableTypeChecker(typeChecker, 'List', Immutable.List.isList);
}
```
- example usage
```shell
...
Usage is simple, they work with and like any 'React.PropType.*' validator.

'''js
var ImmutablePropTypes = require('react-immutable-proptypes');
var MyReactComponent = React.createClass({
    // ...
    propTypes: {
        myRequiredImmutableList: ImmutablePropTypes.listOf(
            ImmutablePropTypes.contains({
                someNumberProp: React.PropTypes.number.isRequired
            })
        ).isRequired
    }
    // ...
});
...
```

#### <a name="apidoc.element.react-immutable-proptypes.ImmutablePropTypes.map"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>map ()](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.map)
- description and source-code
```javascript
map = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.ImmutablePropTypes.mapContains"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>mapContains (shapeTypes)](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.mapContains)
- description and source-code
```javascript
function createMapContainsChecker(shapeTypes) {
  return createShapeTypeChecker(shapeTypes, 'Map', Immutable.Map.isMap);
}
```
- example usage
```shell
...

* 'ImmutablePropTypes.mapOf' allows you to control both map values nad keys (in Immutable.Map, keys could be _anything_ including
 another Immutable collections). It accepts two arguments - first one for values, second one for keys (optional). If you are interested
 in validation of keys only, just pass 'React.PropTypes.any' as the first argument.

'''es6
// ...
aMap: ImmutablePropTypes.mapOf(
React.PropTypes.any, // validation for values
ImmutablePropTypes.mapContains({ // validation for keys
    a: React.PropTypes.number.isRequired,
    b: React.PropTypes.string
})
)
// ...
const aMap = Immutable.Map([
[Immutable.Map({a: 1, b: '2'}), 'foo'],
...
```

#### <a name="apidoc.element.react-immutable-proptypes.ImmutablePropTypes.mapOf"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>mapOf (valuesTypeChecker, keysTypeChecker)](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.mapOf)
- description and source-code
```javascript
function createMapOfTypeChecker(valuesTypeChecker, keysTypeChecker) {
  return createMapOfTypeCheckerFactory(valuesTypeChecker, keysTypeChecker, 'Map', Immutable.Map.isMap);
}
```
- example usage
```shell
...

* 'ImmutablePropTypes.listOf' is based on 'React.PropTypes.array' and is specific to 'Immutable.List'.

* 'ImmutablePropTypes.mapOf' allows you to control both map values nad keys (in Immutable.Map, keys could be _anything_ including
 another Immutable collections). It accepts two arguments - first one for values, second one for keys (optional). If you are interested
 in validation of keys only, just pass 'React.PropTypes.any' as the first argument.

'''es6
// ...
aMap: ImmutablePropTypes.mapOf(
    React.PropTypes.any, // validation for values
    ImmutablePropTypes.mapContains({ // validation for keys
        a: React.PropTypes.number.isRequired,
        b: React.PropTypes.string
    })
)
// ...
...
```

#### <a name="apidoc.element.react-immutable-proptypes.ImmutablePropTypes.orderedMap"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>orderedMap ()](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.orderedMap)
- description and source-code
```javascript
orderedMap = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.ImmutablePropTypes.orderedMapOf"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>orderedMapOf (valuesTypeChecker, keysTypeChecker)](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.orderedMapOf)
- description and source-code
```javascript
function createOrderedMapOfTypeChecker(valuesTypeChecker, keysTypeChecker) {
  return createMapOfTypeCheckerFactory(valuesTypeChecker, keysTypeChecker, 'OrderedMap', Immutable.OrderedMap.isOrderedMap);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.ImmutablePropTypes.orderedSet"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>orderedSet ()](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.orderedSet)
- description and source-code
```javascript
orderedSet = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.ImmutablePropTypes.orderedSetOf"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>orderedSetOf (typeChecker)](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.orderedSetOf)
- description and source-code
```javascript
function createOrderedSetOfTypeChecker(typeChecker) {
  return createIterableTypeChecker(typeChecker, 'OrderedSet', Immutable.OrderedSet.isOrderedSet);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.ImmutablePropTypes.record"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>record ()](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.record)
- description and source-code
```javascript
record = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.ImmutablePropTypes.recordOf"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>recordOf (recordKeys)](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.recordOf)
- description and source-code
```javascript
function createRecordOfTypeChecker(recordKeys) {
  function validate(props, propName, componentName, location, propFullName, ...rest) {
    var propValue = props[propName];
    if (!(propValue instanceof Immutable.Record)) {
      var propType = getPropType(propValue);
      var locationName = location;
      return new Error(
        'Invalid ${locationName} \'${propFullName}\' of type \'${propType}\' ' +
        'supplied to \'${componentName}\', expected an Immutable.js Record.'
      );
    }
    for (var key in recordKeys) {
      var checker = recordKeys[key];
      if (!checker) {
        continue;
      }
      var mutablePropValue = propValue.toObject();
      var error = checker(mutablePropValue, key, componentName, location, '${propFullName}.${key}', ...rest);
      if (error) {
        return error;
      }
    }
  }
  return createChainableTypeChecker(validate);
}
```
- example usage
```shell
...

* 'ImmutablePropTypes.iterableOf' is the generic form of listOf/mapOf. It is useful when there is no need to validate anything other
 than Immutable.js compatible (ie. 'Immutable.Iterable'). Continue to use 'listOf' and/or 'mapOf' when you know the type.

* 'ImmutablePropTypes.recordOf' is like 'contains', except it operates on Record properties.

'''js
// ...
aRecord: ImmutablePropTypes.recordOf({
    keyA: React.PropTypes.string,
    keyB: ImmutablePropTypes.list.isRequired
})
// ...
'''

* 'ImmutablePropTypes.mapContains' is based on 'React.PropTypes.shape' and will only work with 'Immutable.Map'.
...
```

#### <a name="apidoc.element.react-immutable-proptypes.ImmutablePropTypes.seq"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>seq ()](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.seq)
- description and source-code
```javascript
seq = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.ImmutablePropTypes.set"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>set ()](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.set)
- description and source-code
```javascript
set = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.ImmutablePropTypes.setOf"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>setOf (typeChecker)](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.setOf)
- description and source-code
```javascript
function createSetOfTypeChecker(typeChecker) {
  return createIterableTypeChecker(typeChecker, 'Set', Immutable.Set.isSet);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.ImmutablePropTypes.shape"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>shape (shapeTypes)](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.shape)
- description and source-code
```javascript
function createShapeChecker(shapeTypes) {
  return createShapeTypeChecker(shapeTypes);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.ImmutablePropTypes.stack"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>stack ()](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.stack)
- description and source-code
```javascript
stack = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.ImmutablePropTypes.stackOf"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.ImmutablePropTypes.</span>stackOf (typeChecker)](#apidoc.element.react-immutable-proptypes.ImmutablePropTypes.stackOf)
- description and source-code
```javascript
function createStackOfTypeChecker(typeChecker) {
  return createIterableTypeChecker(typeChecker, 'Stack', Immutable.Stack.isStack);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-immutable-proptypes.iterable"></a>[module react-immutable-proptypes.iterable](#apidoc.module.react-immutable-proptypes.iterable)

#### <a name="apidoc.element.react-immutable-proptypes.iterable.iterable"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>iterable ()](#apidoc.element.react-immutable-proptypes.iterable.iterable)
- description and source-code
```javascript
iterable = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.iterable.isRequired"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.iterable.</span>isRequired ()](#apidoc.element.react-immutable-proptypes.iterable.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-immutable-proptypes.list"></a>[module react-immutable-proptypes.list](#apidoc.module.react-immutable-proptypes.list)

#### <a name="apidoc.element.react-immutable-proptypes.list.list"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>list ()](#apidoc.element.react-immutable-proptypes.list.list)
- description and source-code
```javascript
list = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.list.isRequired"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.list.</span>isRequired ()](#apidoc.element.react-immutable-proptypes.list.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-immutable-proptypes.map"></a>[module react-immutable-proptypes.map](#apidoc.module.react-immutable-proptypes.map)

#### <a name="apidoc.element.react-immutable-proptypes.map.map"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>map ()](#apidoc.element.react-immutable-proptypes.map.map)
- description and source-code
```javascript
map = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.map.isRequired"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.map.</span>isRequired ()](#apidoc.element.react-immutable-proptypes.map.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-immutable-proptypes.orderedMap"></a>[module react-immutable-proptypes.orderedMap](#apidoc.module.react-immutable-proptypes.orderedMap)

#### <a name="apidoc.element.react-immutable-proptypes.orderedMap.orderedMap"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>orderedMap ()](#apidoc.element.react-immutable-proptypes.orderedMap.orderedMap)
- description and source-code
```javascript
orderedMap = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.orderedMap.isRequired"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.orderedMap.</span>isRequired ()](#apidoc.element.react-immutable-proptypes.orderedMap.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-immutable-proptypes.orderedSet"></a>[module react-immutable-proptypes.orderedSet](#apidoc.module.react-immutable-proptypes.orderedSet)

#### <a name="apidoc.element.react-immutable-proptypes.orderedSet.orderedSet"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>orderedSet ()](#apidoc.element.react-immutable-proptypes.orderedSet.orderedSet)
- description and source-code
```javascript
orderedSet = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.orderedSet.isRequired"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.orderedSet.</span>isRequired ()](#apidoc.element.react-immutable-proptypes.orderedSet.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-immutable-proptypes.record"></a>[module react-immutable-proptypes.record](#apidoc.module.react-immutable-proptypes.record)

#### <a name="apidoc.element.react-immutable-proptypes.record.record"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>record ()](#apidoc.element.react-immutable-proptypes.record.record)
- description and source-code
```javascript
record = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.record.isRequired"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.record.</span>isRequired ()](#apidoc.element.react-immutable-proptypes.record.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-immutable-proptypes.seq"></a>[module react-immutable-proptypes.seq](#apidoc.module.react-immutable-proptypes.seq)

#### <a name="apidoc.element.react-immutable-proptypes.seq.seq"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>seq ()](#apidoc.element.react-immutable-proptypes.seq.seq)
- description and source-code
```javascript
seq = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.seq.isRequired"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.seq.</span>isRequired ()](#apidoc.element.react-immutable-proptypes.seq.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-immutable-proptypes.set"></a>[module react-immutable-proptypes.set](#apidoc.module.react-immutable-proptypes.set)

#### <a name="apidoc.element.react-immutable-proptypes.set.set"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>set ()](#apidoc.element.react-immutable-proptypes.set.set)
- description and source-code
```javascript
set = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.set.isRequired"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.set.</span>isRequired ()](#apidoc.element.react-immutable-proptypes.set.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-immutable-proptypes.stack"></a>[module react-immutable-proptypes.stack](#apidoc.module.react-immutable-proptypes.stack)

#### <a name="apidoc.element.react-immutable-proptypes.stack.stack"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.</span>stack ()](#apidoc.element.react-immutable-proptypes.stack.stack)
- description and source-code
```javascript
stack = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-immutable-proptypes.stack.isRequired"></a>[function <span class="apidocSignatureSpan">react-immutable-proptypes.stack.</span>isRequired ()](#apidoc.element.react-immutable-proptypes.stack.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
