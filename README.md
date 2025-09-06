This repository provides easy access to ZoomUs android sdk.

[![](https://jitpack.io/v/vuduc4793/jitpack-zoom-us.svg)](https://jitpack.io/#vuduc4793/jitpack-zoom-us)

You can check JitPack link [jitpack-zoom-us](https://jitpack.io/#vuduc4793/jitpack-zoom-us)

Library includes sdk archives:
- mobilertc.aar

### Usage

```gradle
allprojects {
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```

Now you can add dependency:
```gradle
dependencies {
    implementation 'com.github.vuduc4793:jitpack-zoom-us:6.5.10.32669'
}
```

Note: You can use commit hash instead of Tag.


### Available Versions

| Tag           | Dependencies     | Notes                                                                    |
| :-----------: |:-----------------| :----------------------------------------------------------------------  |
| 6.5.10.32669  |  |    16kb page size  |
| 6.0.12.22275  |  |    |


`BROKEN`: JitPack seem to remove files from time to time hence some versions get broken. Health of version can be verified using https://www.jitpack.io/com/github/vuduc4793/jitpack-zoom-us/$TAG/ - it should show `.aar` file.

### Links
- [publishing](./docs/DEV.md)
