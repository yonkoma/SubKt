[subkt](../../index.md) / [myaa.subkt.tasks](../index.md) / [ItemGroup](index.md) / [item](./item.md)

# item

`fun item(entry: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`T`](index.md#T)

Get the item corresponding to the specified entry.

``` kotlin
mux.item("vol1") // returns the mux.vol1 task
```

`fun item(task: `[`Task`](https://docs.gradle.org/current/javadoc/org/gradle/api/Task.html)`): `[`T`](index.md#T)

Get the item of the same the entry as the given task.

``` kotlin
tasks(listOf("vol1")) { // configure tasks for vol1 only
    mux {
        merge.item(this) // returns merge.vol1
    }
}
```
