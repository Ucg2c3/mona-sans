# Build process

### Google Fonts Build (`build.sh`)

The `build.sh` script handles building font files that meet Google Fonts specifications and requirements:

```bash
sh sources/build.sh
```
This will also produce the static fonts.

### MonaSansVF Build (via Glyphs.app)

Because we are distributing multiple cuts of the variable font, these exports come from Glyphs.

1. Open the Mona Sans project in Glyphs.app
2. Use File > Export > Variable Font

The exported variable font will include the full feature set and axis range of Mona Sans.

