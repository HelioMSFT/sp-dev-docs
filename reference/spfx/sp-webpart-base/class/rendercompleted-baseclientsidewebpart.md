# renderCompleted()



This API should be called by web parts that perform Async rendering. Those web part are required to override the isRenderAsync API and return true. One such example is web parts that render content in an IFrame. The web part initiates the IFrame rendering in the render() API but the actual rendering is complete only after the iframe loading completes.

**Signature:** _protected renderCompleted(): void;_

**Returns**: `void`





#### Parameters
None


