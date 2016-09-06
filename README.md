# xblock-wistia
XBlock to embed videos hosted on the Wistia video platform into your courses.

## Installation

```bash
pip install -e "git+https://github.com/appsembler/xblock-wistia.git#egg=wistiavideo_xblock"
```

## Enabling in Studio
You can enable the discussion xblock in studio through the advanced
settings:

1. From the main page of a specific course, click on *Settings*,
   *Advanced Settings* in the top menu.
1. Check for the *Advanced Module List* policy key, and add
   `"wistiavideo"` in the policy value list.
   ![Advanced Module List](https://raw.githubusercontent.com/z4y4ts/xblock-wistia/docs/doc/img/advanced_settings.png)

1. Click on the *Save changes* button.

## Usage

To add Wistia video block to a unit, choose *Wistia video*From the *Advanced Components* list int the Studio.

![Add Wistia video Xblock](https://raw.githubusercontent.com/z4y4ts/xblock-wistia/docs/doc/img/wistia_video_add_xblock.png)

Click the *Edit* button to open up a form where you can enter module title and avideo url address.

![Edit Wistia video Xblock](https://raw.githubusercontent.com/z4y4ts/xblock-wistia/docs/doc/img/wistia_video_edit.png)

## Running Tests

```bash
nosetests wistiavideo
```

## License

Please see `LICENSE` file for details.
