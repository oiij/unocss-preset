# library-starter

Features:

- Bundle with [tsup](https://github.com/egoist/tsup)
- Test with [vitest](https://vitest.dev)

## Usage

```bash
pnpm add @oiij/unocss-preset -D
```

```ts
import { oiijPreset } from '@oiij/unocss-preset'
import { defineConfig, presetUno } from 'unocss'
export default defineConfig({
  presets: [
    presetUno(),
    oiijPreset()
  ]
})
```

## Shortcuts

```ts
const shortcuts = {
  'wh-full': 'w-full h-full',
  'flex-center': 'flex justify-center items-center',
  'flex-col': 'flex flex-col',
  'flex-col-center': 'flex-col flex-center',
  'flex-col-stretch': 'flex-col items-stretch',
  'flex-x-center': 'flex justify-center',
  'flex-y-center': 'flex items-center',
  'i-flex-center': 'inline-flex justify-center items-center',
  'i-flex-x-center': 'inline-flex justify-center',
  'i-flex-y-center': 'inline-flex items-center',
  'i-flex-col': 'inline-flex flex-col',
  'i-flex-col-stretch': 'i-flex-col items-stretch',
  'flex-1-hidden': 'flex-1 overflow-hidden',
  'absolute-lt': 'absolute left-0 top-0',
  'absolute-lb': 'absolute left-0 bottom-0',
  'absolute-rt': 'absolute right-0 top-0',
  'absolute-rb': 'absolute right-0 bottom-0',
  'absolute-tl': 'absolute-lt',
  'absolute-tr': 'absolute-rt',
  'absolute-bl': 'absolute-lb',
  'absolute-br': 'absolute-rb',
  'absolute-center': 'absolute-lt flex-center wh-full',
  'absolute-full': 'absolute inset-0',
  'fixed-lt': 'fixed left-0 top-0',
  'fixed-lb': 'fixed left-0 bottom-0',
  'fixed-rt': 'fixed right-0 top-0',
  'fixed-rb': 'fixed right-0 bottom-0',
  'fixed-tl': 'fixed-lt',
  'fixed-tr': 'fixed-rt',
  'fixed-bl': 'fixed-lb',
  'fixed-br': 'fixed-rb',
  'fixed-center': 'fixed-lt flex-center wh-full',
  'fixed-full': 'fixed inset-0',
  'transition-base': 'transition-all duration-300 ease-in-out',
}
```

## License

MIT
