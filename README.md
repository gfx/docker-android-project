# Dockerfile for Android Projects

This is a Dockerfile to make minumum images for Android projects.
No `ant`, `maven`, nor `android-ndk` are included.

## Included

* JDK 8
* Android SDK
* Android Support Libraries
* Google Play Services

## Maintainance

* Just rebuild it for minor updates
* Update components for major updates
  * You can find component ids by `android list sdk --all --extended`

# Author

FUJI Goro (gfx) <g.psy.va+github@gmail.com>

# License

http://www.apache.org/licenses/LICENSE-2.0
