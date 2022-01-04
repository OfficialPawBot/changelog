# Changelog

All notable changes to [Paw Bot](https://paw.bot) will be documented here.

# 3.2.5 - (2022-01-04)

## Bug Fixes

- **main:** Catch dispatcher errors ([b1009f9](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/b1009f9333df21b9227af6175a6bb1904d6dc110))
- Short shard start timeout duration ([42a768f](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/42a768f8fadff5d756dbf77468b3cfb9b87419aa))
- No exiting on uncaught exception ([a21e6aa](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/a21e6aa8c92d792b75025f8240f4a33b2ad8237b))
- **Dispatcher:** Defer interaction before responding ([93daf64](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/93daf649caee2077094a07df09c0bbc3d41d874f))
- **constraints:** Check if interaction has channel ([afa85fa](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/afa85fae6dd79c01ee15bc47b61e6b21fd510a16))
- **Dispatcher:** Catch possible Discord api errors ([6c5412f](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/6c5412f20cc60ec1e553a9d08f2e97e8fbe91863))

## Features

- **commands:** Add `propose` command ([0fed7fc](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/0fed7fc4f99cca0cdaa625fa58724148fea0b59d))
- **commands:** Add `lick` command ([62e7e4f](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/62e7e4f9b622d135b29e1ec56491b5486c563f18))
- **commands:** Add `kiss` command ([85b4999](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/85b49995e79f0a12e70abc2e8924a6535fc6f7f3))
- **commands:** Add `hug` command ([a1f8c60](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/a1f8c6046cc5b6cd0317405113b0afcbd3034821))
- **commands:** Add `howl` command ([481d747](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/481d7472e2ec45f04d3aee8e4e1cf9fd26695761))
- **commands:** Add `hold` command ([54b9ffa](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/54b9ffa8fbef85319aefdcd8fd97aec383432373))
- **commands:** Add `flop` command ([0b9a11d](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/0b9a11d441651ca4ed448e1f8bc01d09c296bcbc))
- **commands:** Add `cuddle` command ([2a640f0](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/2a640f055e01fb278f4ab8f3c2273e6288c8ed5f))
- **commands:** Add `boop` command ([ded5365](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/ded536515fb9686535d452fbe722d6e670a05e40))
- **commands:** Add `e926` command ([797ae14](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/797ae1496a3932a1c7c688589344630d08918e8c))
- **commands:** Add `e621` command ([ef35d00](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/ef35d0023f1fa77a93840e0db7da907879b2aea1))
- **commands:** Add `yiff-catboy` command ([7842c45](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/7842c4510f158d1f504f16ab15db94a58f003b82))
- **commands:** Add `yiff-dickgirl` command ([de222cf](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/de222cfa75d4b6df05f47e6a6fb642b37b6ea768))
- **commands:** Add `yiff-lesbian` command ([0e88de7](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/0e88de7ba472571ae7cb328b84d4c5f029ad6a49))
- **commands:** Add `yiff-gay` command ([ba44883](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/ba448838f78dcfd71d971755a71e23474ccbc30c))
- **commands:** Add `yiff-straight` command ([092898e](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/092898e7cacc19586ea21b76c433810a9ab39a02))
- **API:** Add `yiff` endpoint ([471b60f](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/471b60f537ba121390342a1ce9578182a54cab6c))

## Refactor

- **Command:** Edit message content upon error ([83a9f5f](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/83a9f5f028aadf4567f44c98613609c694f8d324))
- **Request:** Prefer env version for user-agent ([0cbc9f8](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/0cbc9f8cc42396408e564b7d0eda3091dd0938c6))
- **API:** Remove hard-coded tokens ([11ecfc9](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/11ecfc9817aea5ae1033529ad8ddc92819dbc2c5))

# 3.0.0 - (2022-01-03)

## Bug Fixes

- **main:** Acquire `GUILDS` gateway intent for nsfw constraint ([5644176](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/56441763c6dd849ceff83d6b83f4add8c3d9cdb8))
- **ConstraintRegistry:** Incorrect iteration & pushing of constraints ([46b338b](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/46b338b17eaf20d08efe053249fcd33513d7af18))
- Extendable module not binding class functions ([91259f3](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/91259f335061c5c4d78b80555b51050df031f747))
- **constraints:** Nsfw constraint should return string reason ([4b99e3a](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/4b99e3a998d6a6b8dbe0b20fb51f6b320bd34af2))
- Process being initialised after first use ([9558ce6](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/9558ce622be116484d63e029510c11ae95206c1d))
- **API:** `foxes` using a redirect url ([d9ce966](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/d9ce966d6c5a501834e142d5fa37c9a591f58354))
- Set global timezone to UTC ([f8e7834](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/f8e7834e7ccae4035428be6cad914bbf36b7badf))
- **main:** Register slash commands only for first shard ([ffd4ed0](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/ffd4ed0a180a17459a551596fbbae24c7d202e77))
- **CommandContext:** Allow `files` option ([9db9a15](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/9db9a158492f8530a61f20a65acec84802565a0f))
- **BooleanArgumentType:** Stringify `value` before processing ([a6e2257](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/a6e2257b2608b6b658ec817d9d44efb0c870f372))
- **Command:** Null `description` ([7dec8c7](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/7dec8c75b638ef5572d5d7bc6ea8bd4c88624942))
- **API:** `parameters` cannot be used in `POST`/`HEAD` requests ([7d6a78a](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/7d6a78a48dc9ec05c807796dbc22a2ba8eb91e09))
- **Request:** TypeError & log errors ([cc605a5](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/cc605a5517c2bc2e85a216c241a5d7d8156cfc24))
- **Argument:** Default for argument being ignored ([ad60a27](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/ad60a27fbf5b2cbd8f5feacf80da90b2edec76d7))
- **Locale:** Catch-revert-to `en` lang causing hang due to bad condition ([07d3a78](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/07d3a78bb94dd5aafd0d70b0a5603009c87fc098))
- **Locale:** Hash table provided with no object without options ([00748f1](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/00748f17141a4958b07d47d2631cbbf13c301026))
- **LanguageRegistry:** Fix `cldr-data` locale check ([9b9f761](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/9b9f7614f9c1e9f2372b8e83b1d12cec6e37a971))
- Check if args exist before iterating ([07c48fd](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/07c48fdbe831de35ed6e5450473165e25b532b5d))
- Description not being added to commands ([b231027](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/b2310273973440471b654ff09b26d3734ecca461))

## Features

- **commands:** Add `bulge` command ([db2db65](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/db2db658bb5287d4f4249a077b952638b99c6246))
- Error and exit handling, post notifications ([ea2bfe3](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/ea2bfe3aaeab3b95576f892549231ffbb52b2ee2))
- Automatic restart & updater ([841561b](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/841561bcc7e13158b7aac97f94ee14a35d59a099))
- **commands:** Add `img-jpg` command ([646bd92](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/646bd923bf05a2bb5c48ae416b4ede41557f4243))
- **commands:** Add `img-mirror` command ([74a8fe7](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/74a8fe74762b4207724b0d99fd915bff2c177223))
- **commands:** Add `img-png` command ([1e9bfb2](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/1e9bfb23d0447038cc98ffa961fc4431b201f7a5))
- **commands:** Add `img-rotate` command ([04ae575](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/04ae57519a54911d11cbcdbeb5984010b92b7e10))
- **commands:** Add `img-webp` command ([15d96bc](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/15d96bc2b1471c7d3134a89ae4d11bfa3e5feb83))
- **commands:** Add `fursuit` command ([c18846e](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/c18846e45b7c04f0e95ca060a75376820a5e58aa))
- **commands:** Add `shibe` command ([efa09f2](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/efa09f2caa395ebf578119a0924ac6a53ad9e34f))
- **commands:** Add `fursuit` command ([3812ff5](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/3812ff50794437a794b081992301c1c33d6d2b0d))
- **commands:** Add `urban` command ([dd4998f](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/dd4998fd9f71bf3ef76730158b2857660127f04a))
- **commands:** Add `math` command ([20fd1f3](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/20fd1f333407e6f54ee76e26a7aa826a0ff4b3a2))
- **commands:** Add `img-flip` command ([58df2a7](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/58df2a77fbda85104ae5ff6ef89bb778c0d1ba26))
- **commands:** Add `fox` command ([edfd927](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/edfd927c0fcfae1f97930f35493a08943b62c101))

## Refactor

- **Dispatcher:** Ephemeral failed commands ([0591fc3](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/0591fc378ca44dc1bad1e25d8e78b40c68f700b0))
- **Embed:** Use env variables for footer content ([90d2692](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/90d2692abd7ebfc01b3f73f78327851ad4c706e4))
- **Registry:** Remove unused `HelperRegistry` ([66287be](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/66287be18a5da5f9370eebee84dec8e684dec54c))
- Code cleanup & linting ([acde495](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/acde4958d23c72c1bc5f9c80f18674d599cfaec0))
- **main:** Remove unneeded `GUILD` gateway intent ([1806577](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/1806577ff037e3e08327e3cfba32f1cd79617ed6))
- **commands:** Remove testing commands ([1f64c59](https://github.com/OfficialPawBot/paw-bot-overhaul/commit/1f64c59704475cc8417e6443c0e3b48980a70f8e))

