# sr-buildpacks-ffmpeg

A Cloud Native Buildpack for FFmpeg

## Usage

1- Clone the repository:

```bash
git clone https://github.com/carlosbustillordguez/sr-buildpacks-ffmpeg.git
```

2- Add the buildpack to the project:

```bash
pack build myapp --builder heroku/buildpacks:18 --buildpack /path/to/sr-buildpacks-ffmpeg --path /path/to/myapp
```

**NOTE:**

- The FFmpeg version installed is 3.4.2-64bit-static.
- The `ffmpeg` binaries will be available from the `PATH` environment variable.
