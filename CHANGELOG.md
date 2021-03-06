# Change Log - AWS AppSync SDK for Android

## [Release 2.6.18](https://github.com/awslabs/aws-mobile-appsync-sdk-android/releases/tag/release_v2.6.18)

### New Features

* Adds OpenID Connect (OIDC) support as an authorization option.

## [Release 2.6.17](https://github.com/awslabs/aws-mobile-appsync-sdk-android/releases/tag/release_v2.6.17)

### Enhancements

* Improve synchronization of shared data structures in multiple subscriptions.
* Fixed bug that caused sigv4 signing not to be attached when okhttp client was specified in builder. See [PR #4](https://github.com/awslabs/aws-mobile-appsync-sdk-android/pull/4)

## [Release 2.6.16](https://github.com/awslabs/aws-mobile-appsync-sdk-android/releases/tag/release_v2.6.16)

### New Features

* Subscription support.
* Complex objects allow fields to be S3 objects.
* Conflict resolution surfaces mutation conflicts so that they can be resolved through a callback.

## [Release 2.6.15](https://github.com/awslabs/aws-mobile-appsync-sdk-android/releases/tag/release_v2.6.15)

### New Features

* Initial release with support for Cognito UserPools, Cognito Identity, and API key based authentication.
* Optimistic updates allow the cache to be updated before a server response is received (i.e. slow network or offline)
* Offline mutation allows mutations to be queued while client is offline until online again.
