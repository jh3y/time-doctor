# time-doctor :man_health_worker: (WIP)
## declarative CSS timeline composition :sparkles:

### Motivation :muscle:
CSS animations aren't always the tricky part. It's composing or structuring them in a timeline. The same goes for transitions. We have certain JavaScript APIs that could help like `element.getAnimations()` and `document.timeline`. But, what if we straight up declared the composition in HTML? (as a proof of concept :eyes:)

```html
<!-- Element has two animations, scale-up and spin. spin follows scale-up with infinite iterations 1s after scale-up ends -->
<div data-doctor-timeline="scale-up, spin+ +1"></div>
```

How should it work though? What's the syntax? Ideally you could run this from PostCSS somehow based on a custom property that overrides the "animation" property perhaps :thinking:

Let's play! ʕ •ᴥ•ʔ

### Get involved!
Got some ideas, hit me up here or somewhere else!

### Development
- `bun install`
- Set up `localhost` keys with `mkcert install && mkcert localhost`
- `bun run dev`

---

Ideated by @jh3y 2022 ʕ·ᴥ·　ʔ


