---
layout: default-layout
Title: NormalizedImageElement - Dynamsoft Document Normalizer Android SDK API Reference
Description: The class NormalizedImageElement represents an intermediate result whose type is normalized image, It is inherited from RegionObjectElement and contains image data of normalized result as additional parameter.
Keywords: normalized image element, java, kotlin
needGenerateH3Content: true
needAutoGenerateSidebar: true
noTitleIndex: true
---

# NormalizedImageElement

The `NormalizedImageElement` class represents an intermediate result whose type is normalized image. It is inherited from `RegionObjectElement` and contains image data of normalized result as an additional parameter.

## Definition

*Namespace:* com.dynamsoft.ddn.intermediate_results

*Assembly:* DynamsoftDocumentNormalizer.aar

```java
class NormalizedImageElement extends RegionObjectElement
```

## Methods Summary

| Methods | Description |
| ---------- | ----------- |
| [`getImageData`](#getimagedata) | Gets an [`ImageData`]({{site.dcv_android_api}}core/basic-structures/image-data.html) object as the normalized image. |

### getImageData

Gets an [`ImageData`]({{site.dcv_android_api}}core/basic-structures/image-data.html) object as the normalized image.

```java
ImageData getImageData();
```

**Return Value**

The [`ImageData`]({{site.dcv_android_api}}core/basic-structures/image-data.html) object as the normalized image.