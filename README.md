# Reverse engineered API for Bing Image Creator

...just because [original repository](https://github.com/acheong08/BingImageCreator) stopped working and is no longer maintained.

```
git clone https://github.com/olaviinha/BingImageCreator.git
```

### Get authentication (`-U <cookie>`)
- Go to https://bing.com/
- F12 to open console
- Copy/paste to console: `cookieStore.get("_U").then(result => console.log(result.value))` and hit Enter.
- Copy the output. This is used in -U

### Usage
```
$ python3 BingImageCreator/src/BingImageCreator.py -U <cookie> --prompt <prompt> --output-dir <dir>

options:
  -h, --help            show this help message and exit
  -U U                  Auth cookie from browser
  --prompt PROMPT       Prompt to generate images for
  --asyncio             Use async to sync png
  --output-dir OUTPUT_DIR
                        Output directory
```


