# pi-emote Lo-Fi Girl

A Lo-Fi-inspired pixel-art emote set for [`cgxeiji/pi-emote`](https://github.com/cgxeiji/pi-emote).

## Preview

![Lo-Fi Girl hero preview](assets/preview-hero.png)

[![Watch the pi-emote demo](assets/pi-emote-demo.gif)](assets/pi-emote-demo.mp4)

## Included states

- `hi`
- `idle`
- `think`
- `talk`
- `read`
- `write`
- `tool`
- `success`
- `failure`
- `compact`

## Use

Copy `emotes/lofi-girl/` into one of pi-emote's emote search locations, for example:

```text
~/.pi/agent/extensions/pi-emote/emotes/lofi-girl/
```

Then map it in your pi-emote config:

```json
{
  "emotes": [
    { "model": "*", "emote-set": "lofi-girl" }
  ]
}
```

## Notes

- All state PNGs are 64x64 with a consistent 1px transparent border.
