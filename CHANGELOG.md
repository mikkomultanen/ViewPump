# Changelog

## Version 2.0.3 *(2019-06-07)*
- Update the LayoutInflater to be compatible with Android Q

## Version 2.0.2 *(2019-04-16)*

- Fix SAM invocation of Interceptor instances via `operator fun invoke()` extension
- Add `Builder.addInterceptor()` convenience extension function that accepts a `(Chain) -> InflateResult` parameter

## Version 2.0.1 *(2019-04-03)*

- Fix nullability and reflection field name
- Disabled generation of unused BuildConfig
- Cleaned up consumer proguard rules
- Update Kotlin to 1.3.21 and use it as `api` dependency
- Add proper Dokka support

## Version 2.0.0 *(2019-01-28)*

- **Breaking change:** Project migrated to [AndroidX](https://developer.android.com/jetpack/androidx/). See the [class and package mappings](https://developer.android.com/jetpack/androidx/migrate) for help migrating
- **Breaking change:** The previously `public` `ReflectionUtils` class is now internal only, and inaccessible to Java users. This class should never have been used anyway though, so ideally should not be a breaking change to most.
- Migrated library to Kotlin. Aside from the two breaking changes listed above, this should otherwise be a non-breaking API change for Java users.

## Version 1.0.0 *(2017-05-01)*

- Initial Release
