[net](../../index.md) / [com.drake.net](../index.md) / [android.content.Context](index.md) / [syncDownloadImage](./sync-download-image.md)

# syncDownloadImage

`fun `[`Context`](https://developer.android.com/reference/android/content/Context.html)`.syncDownloadImage(url: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, with: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 0, height: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 0): `[`File`](https://docs.oracle.com/javase/6/docs/api/java/io/File.html)

同步下载图片, 图片宽高要求要么同时指定要么同时不指定
要求依赖 Glide

### Parameters

`url` - 请求图片的绝对路径

`with` - 图片宽度

`height` - 图片高度