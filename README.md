# Reverse engineered API for Bing Image Creator

...just because [original repository](https://github.com/acheong08/BingImageCreator) stopped working and is no longer maintained.

### Get authentication (`-U <authentication>`)
- Go to https://bing.com/
- F12 to open console
- Copy/paste to console: `cookieStore.get("_U").then(result => console.log(result.value))` and hit Enter.
- Copy the output. This is used with -U

### Installation & usage
```
$ git clone https://github.com/olaviinha/BingImageCreator.git
$ python3 BingImageCreator/src/BingImageCreator.py -U <authentication> --prompt <prompt> --output-dir <dir>
```


