# mediainfo-buildpack

MediaInfo - https://mediaarea.net/en/MediaInfo

## Usage

Add the following link in your `.buildpacks` file:

```
https://github.com/code-pms/mediainfo-buildpack.git

```

Or use the following command via heroku CLI:

```
heroku buildpacks:add https://github.com/code-pms/mediainfo-buildpack.git
```

## Github Actions

Use [github actions](https://github.com/code-pms/mediainfo_buildpack/actions/workflows/mediainfo.yml) to auto generate mediainfo tar directly from the source.
