<!-- tyhp-readme:start -->
# tyhpdef/inertiajs-inertia-laravel

Tyhp type definitions for `inertiajs/inertia-laravel` `3.3.4`.

```bash
composer require --dev tyhpdef/inertiajs-inertia-laravel:3.3.4
```

This is a metapackage. Composer also installs `tyhpdef/inertiajs-inertia-laravel-impl` (type files).
Require **this** name, not `tyhpdef/inertiajs-inertia-laravel-impl`.

See https://tyhplang.com.

## Maintain `inertiajs/inertia-laravel`? Ship the types yourself

If you are a Packagist maintainer of `inertiajs/inertia-laravel`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/inertiajs-inertia-laravel-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `inertiajs/inertia-laravel` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/inertiajs-inertia-laravel": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `inertiajs/inertia-laravel` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `inertiajs/inertia-laravel` with a real constraint,
   `"replace": { "tyhpdef/inertiajs-inertia-laravel": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `inertiajs/inertia-laravel` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/inertiajs-inertia-laravel` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
