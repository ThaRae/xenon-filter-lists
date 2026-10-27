# xenon-filter-lists

uBlock Origin's filter lists, converted for [Xenon](https://github.com/ThaRae/Xenon)'s content blocker by
[xenon-ublock](https://github.com/ThaRae/xenon-ublock), rebuilt every day. Xenon downloads them from here once a day,
and uses them only if `manifest.json.sig` is a valid signature of `manifest.json` by Xenon's key.

Everything outside `.github/` is generated: the workflow in `.github/workflows/update.yml` rewrites it every day at
05:17 UTC. Its source is `Meta/ci/filter-lists-workflow.yml` in Xenon, and `Documentation/FilterListUpdates.md` there
describes the format.

The lists are third-party data under their own licenses (GPL-3.0, GPL-3.0 or CC BY-SA, and CC0). `NOTICE.txt` lists
each one's source and license, and `LICENSE-GPL-3.0.txt` has the GPL's text.
