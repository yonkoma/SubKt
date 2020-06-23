[subkt](../../index.md) / [myaa.subkt.ass](../index.md) / [Section](index.md) / [parse](./parse.md)

# parse

`abstract fun parse(data: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`KeyValLine`](../-key-val-line/index.md)`>, extraData: `[`ExtraData`](../-extra-data.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Deserializes a list of lines in [KeyValLine](../-key-val-line/index.md) format and adds
them to this section.

### Parameters

`extraData` - The extradata read from the input file.
Only affects [EventSection](../-event-section/index.md).