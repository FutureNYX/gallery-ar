# Gallery AR

WebAR wall placement for the gallery website.  
Built on 8th Wall XR engine + A-Frame.

## How it works

Each painting page embeds a "View in your room" button that opens:

```
https://your-netlify-url.netlify.app/?img=IMAGE_URL&w=WIDTH_CM&h=HEIGHT_CM&title=PAINTING+NAME
```

## Params

| Param | Description | Example |
|-------|-------------|---------|
| `img` | Direct URL to painting image | `https://...` |
| `w` | Width in centimetres | `80` |
| `h` | Height in centimetres | `60` |
| `title` | Painting name | `Sunset+Over+Moors` |

## Setup

1. Connect this repo to Netlify (auto-deploys on every push)
2. Get 8th Wall app key and replace `NEEDS_REAL_KEY` in index.html
3. Embed button on your gallery product pages

## Status

- [x] Repo created
- [x] AR page skeleton built
- [ ] 8th Wall app key added
- [ ] Netlify connected + live URL
- [ ] Tested on iOS + Android
- [ ] Embedded on gallery website
