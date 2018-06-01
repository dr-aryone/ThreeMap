[ThreeMap](api-readme.md) > [Extension](api-modules-extension.md) > [Extension](api-classes-extension.extension-1.md)



## Class: Extension


Base class provided for creating ThreeMap Extensions

### Constructors

* [constructor](api-classes-extension.extension-1.md#constructor)


### Properties

* [map](api-classes-extension.extension-1.md#map)
* [onFeature](api-classes-extension.extension-1.md#onfeature)
* [onTileCreated](api-classes-extension.extension-1.md#ontilecreated)
* [onTileRemoved](api-classes-extension.extension-1.md#ontileremoved)
* [onUpdate](api-classes-extension.extension-1.md#onupdate)
* [style](api-classes-extension.extension-1.md#style)



---
## Constructors
<a id="constructor"></a>


### ⊕ **new Extension**(handlers: *[IHandlers](api-interfaces-extension.ihandlers.md)*): [Extension](api-classes-extension.extension-1.md)


*Defined in [Extension.ts:70](https://github.com/areknawo/Three-Map/blob/41e1f78/src/Extension.ts#L70)*


*__example__*: `new Extension({onFeature: ()=>{}, onTileCreated: ()=>{}, onTileRemoved: ()=>{}, onUpdate: ()=>{}});`



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| handlers | [IHandlers](api-interfaces-extension.ihandlers.md)   |  Functions to apply for ThreeMap's corresponding events. |





**Returns:** [Extension](api-classes-extension.extension-1.md)

---


## Properties
<a id="map"></a>

###  map

**●  map**:  *`Object3D`* 

*Defined in [Extension.ts:50](https://github.com/areknawo/Three-Map/blob/41e1f78/src/Extension.ts#L50)*



ThreeMap ThreeJS base object - tiles container




___

<a id="onfeature"></a>

###  onFeature

**●  onFeature**:  *`function`* 

*Defined in [Extension.ts:54](https://github.com/areknawo/Three-Map/blob/41e1f78/src/Extension.ts#L54)*



Function to be executed when new tile feature is loaded.

#### Type declaration
►(e: *[IOnFeatureEvent](api-interfaces-extension.ionfeatureevent.md)*): `__type`



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| e | [IOnFeatureEvent](api-interfaces-extension.ionfeatureevent.md)   |  - |





**Returns:** `__type`






___

<a id="ontilecreated"></a>

###  onTileCreated

**●  onTileCreated**:  *`function`* 

*Defined in [Extension.ts:58](https://github.com/areknawo/Three-Map/blob/41e1f78/src/Extension.ts#L58)*



Function to be executed when new tile is added to ThreeMap parent element

#### Type declaration
►(e: *[IOnTileCreatedEvent](api-interfaces-extension.iontilecreatedevent.md)*): `__type`



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| e | [IOnTileCreatedEvent](api-interfaces-extension.iontilecreatedevent.md)   |  - |





**Returns:** `__type`






___

<a id="ontileremoved"></a>

###  onTileRemoved

**●  onTileRemoved**:  *`function`* 

*Defined in [Extension.ts:62](https://github.com/areknawo/Three-Map/blob/41e1f78/src/Extension.ts#L62)*



Function to be executed when tile is removed from ThreeMap parent element

#### Type declaration
►(e: *[IOnTileRemovedEvent](api-interfaces-extension.iontileremovedevent.md)*): `__type`



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| e | [IOnTileRemovedEvent](api-interfaces-extension.iontileremovedevent.md)   |  - |





**Returns:** `__type`






___

<a id="onupdate"></a>

###  onUpdate

**●  onUpdate**:  *`function`* 

*Defined in [Extension.ts:66](https://github.com/areknawo/Three-Map/blob/41e1f78/src/Extension.ts#L66)*



Function to be executed on every ThreeJS controls update - e.g. pan, move etc.

#### Type declaration
►(e: *[IOnUpdateEvent](api-interfaces-extension.ionupdateevent.md)*): `__type`



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| e | [IOnUpdateEvent](api-interfaces-extension.ionupdateevent.md)   |  - |





**Returns:** `__type`






___

<a id="style"></a>

###  style

**●  style**:  *[IStyle](api-interfaces-interfaces.istyle.md)* 

*Defined in [Extension.ts:70](https://github.com/areknawo/Three-Map/blob/41e1f78/src/Extension.ts#L70)*



ThreeMap style configuration object




___

