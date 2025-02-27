---
title: Pairwise
type: tags
order: 412
meta_title: Pairwise Tags to Compare Objects
meta_description: Label Studio Pairwise Tags customize Label Studio with pairwise to compare objects for machine learning and data science projects.
---

Pairwise element. Compare two different objects, works with any label studio object

### Parameters

| Param | Type | Description |
| --- | --- | --- |
| name | <code>string</code> | Name of the element |
| toName | <code>string</code> | Names of the elements you want to compare, comma-separated |
| [selectionStyle] | <code>string</code> | Style of the selection |

### Example
```html
<View>
  <Pairwise name="pairwise" leftClass="text1" rightClass="text2" toName="txt-1,txt-2"></Pairwise>
  <Text name="txt-1" value="Text 1" />
  <Text name="txt-2" value="Text 2" />
</View>
```
### Example

You can also style the appearence using the View tag:

```html
<View>
  <Pairwise name="pw" toName="txt-1,txt-2"></Pairwise>
  <View style="display: flex;">
    <View style="margin-right: 1em;"><Text name="txt-1" value="$text1" /></View>
    <View><Text name="txt-2" value="$text2" /></View>
  </View>
</View>
```
