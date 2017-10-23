# laravel-package-md5hasher(laravel加密扩展)
## 用法

`composer require hiphup/hasher
`

下载完毕后，直接配置`app/config.php`的providers：

`
//Illuminate\Hashing\HashServiceProvider::class,
\Hiphup\Hasher\MD5HasherProvider::class,
`

