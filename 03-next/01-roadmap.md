# Roadmap

Our primary goal is to provide a first version, which is fast and stable.

But for the next versions we are planing to focus on these major areas:

1. More data types and editor for field management.
2. Better administration tools for user managment and custom accounts without Google Login.
3. Integration points, for example Webhooks or pushing events to RabbitMq.

It is very likely that our plans will change when we get the first user feedback. We will publish new versions as often as possible and upgrade the version number when we think the new features are stable. We will use [semantic versioning](http://semver.org/).

## Version 1.X

### Version 1.1 (More Fields)

* Rating editor for numbers
* Markdown editor for string.
* Wysiwyg editor for strings, e.g [TinyMCE](https://www.tinymce.com/)
* Datetime fields including editors.
* Time fields including editors.
* Json fields including editor, e.g [ACE](https://ace.c9.io/).
* Geolocation fields including editor with Google Maps.

### Version 1.2 (Media Management)

* Upload media files and other documents.
* Support for different storages, e.g. file system or azure blobs.
* Basic image editing (If we can find an open source image editor for javascript).
* Assign documents to content fields.

### Version 1.3 (Integration)

* Support for Webhooks
* Integration of queues like RabbitMq.

### Version 1.4 (User Management)

* Github login.
* Internal accounts with registration forms.
* Linking different accounts, e.g. github with googlemail.
* Profile settings, e.g. change profile picture and display name.
* More features for account management.

## Version 2.X (Advanced Schemas)

* Array with nested Schemas
* Nested objects and schemas.

## Planned but not prioritized yet

* Performance reports
* Private bookmarks.
* Bookmarks for all app contributors.
* Collaboration features, e.g. comments.
* Flexible dashboard.
* Account management for external users, lightweight version of [auth0](https://auth0.com).
* Features for the paid version of Squidex.
* Statistics about number of contents, usage and so on.
* Support to invalidate CDN entries.

And of course ...

* Improvement of documentation.
* Performance improvements.
* Bugfixes
