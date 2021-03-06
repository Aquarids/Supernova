# Supernova
Sample webpage to handle url and app-link.

### Import

```groovy
//Add it in your root build.gradle at the end of repositories:
maven { url 'https://jitpack.io' }
```
```groovy
//Add the dependency
compile 'com.github.Aquarids:Supernova:0.0.1'
```
[![import](https://jitpack.io/v/Aquarids/Supernova.svg)](https://jitpack.io/#Aquarids/Supernova)

### Usage
Add [jsBridge.js](https://github.com/Aquarids/Supernova/blob/master/jsBridge.js) to your js file. 

```kotlin
// at your activity
Supernova.launchUrl(context, yoururl, yourhost)
```
```js
// at your web
window.supernovaBridge.call(methodName, options)

```

### Basic API

##### toast：
​	params： message

##### setTitle
​	params: title

##### setNavigationColor
​	params: color (string '#ffffff')

##### setNavigationTextColor
​	params: color

##### showNavigation
​	params: show (boolean)

##### showLoadingDialog
​	params: show (boolean)

##### close
​	close act
 
##### open
​	params: url

License
--------

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
    
       http://www.apache.org/licenses/LICENSE-2.0
    
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
