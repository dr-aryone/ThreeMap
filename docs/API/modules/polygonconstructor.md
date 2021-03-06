[ThreeMap](../README.md) > [PolygonConstructor](../modules/polygonconstructor.md)

# External module: PolygonConstructor

## Index

### Functions

* [extrudedPolygon](polygonconstructor.md#extrudedpolygon)
* [flatPolygon](polygonconstructor.md#flatpolygon)
* [polygon](polygonconstructor.md#polygon)

---

## Functions

<a id="extrudedpolygon"></a>

###  extrudedPolygon

▸ **extrudedPolygon**(vertices: *`number`[][]*, data: *[IWorkerData](../interfaces/interfaces.iworkerdata.md)*, style: *[ILayerStyle](../interfaces/interfaces.ilayerstyle.md)*): [IWorkerData](../interfaces/interfaces.iworkerdata.md)

*Defined in [constructor/polygon.ts:64](https://github.com/areknawo/ThreeMap/blob/master/src/constructor/polygon.ts#L64)*

Generates extruded polygon - 3D Object.
*__example__*: `extrudedPolygon(\[\[1,2\],\[3,4\],\[5,6\],\[1,2\]\], {...}, {...});

**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| vertices | `number`[][] |  Preprocessed vertices array. |
| data | [IWorkerData](../interfaces/interfaces.iworkerdata.md) |  Data used for building tile. |
| style | [ILayerStyle](../interfaces/interfaces.ilayerstyle.md) |  Layer's style configuration. |

**Returns:** [IWorkerData](../interfaces/interfaces.iworkerdata.md)

___
<a id="flatpolygon"></a>

###  flatPolygon

▸ **flatPolygon**(vertices: *`number`[][]*, data: *[IWorkerData](../interfaces/interfaces.iworkerdata.md)*, style: *[ILayerStyle](../interfaces/interfaces.ilayerstyle.md)*): [IWorkerData](../interfaces/interfaces.iworkerdata.md)

*Defined in [constructor/polygon.ts:45](https://github.com/areknawo/ThreeMap/blob/master/src/constructor/polygon.ts#L45)*

Generates flat polygon.
*__example__*: `flatPolygon(\[\[1,2\],\[3,4\],\[5,6\],\[1,2\]\], {...}, {...});

**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| vertices | `number`[][] |  Preprocessed vertices array. |
| data | [IWorkerData](../interfaces/interfaces.iworkerdata.md) |  Data used for building tile. |
| style | [ILayerStyle](../interfaces/interfaces.ilayerstyle.md) |  Layer's style configuration. |

**Returns:** [IWorkerData](../interfaces/interfaces.iworkerdata.md)

___
<a id="polygon"></a>

###  polygon

▸ **polygon**(data: *[IWorkerData](../interfaces/interfaces.iworkerdata.md)*, style: *[ILayerStyle](../interfaces/interfaces.ilayerstyle.md)*): [IWorkerData](../interfaces/interfaces.iworkerdata.md)

*Defined in [constructor/polygon.ts:14](https://github.com/areknawo/ThreeMap/blob/master/src/constructor/polygon.ts#L14)*

Parses data for polygon generation.
*__example__*: `polygon({...}, {...});`

**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| data | [IWorkerData](../interfaces/interfaces.iworkerdata.md) |  Data used for building tile. |
| style | [ILayerStyle](../interfaces/interfaces.ilayerstyle.md) |  Layer's style configuration. |

**Returns:** [IWorkerData](../interfaces/interfaces.iworkerdata.md)

___

