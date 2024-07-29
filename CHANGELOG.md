# Changelog

## [2.0.0](https://github.com/bassamsdata/deadcolumn.nvim/compare/v1.0.0...v2.0.0) (2024-07-29)


### ⚠ BREAKING CHANGES

* use `winhl` instead of setting `cc` directly
* add opts.blending option for transparent background
* add opts.blending option for transparent background
* add opts.blending option for transparent background

### Features

* add opts.blending option for transparent background ([137a479](https://github.com/bassamsdata/deadcolumn.nvim/commit/137a4795fa1adf2cfdcef630616517aea38ad4a7))
* add opts.blending option for transparent background ([3388d59](https://github.com/bassamsdata/deadcolumn.nvim/commit/3388d59d4ff4fd618f4891e151611e5f2a191311))
* add opts.blending option for transparent background ([0312c0f](https://github.com/bassamsdata/deadcolumn.nvim/commit/0312c0ff944f55f1ddba3f3afda5d75e3207d9df))
* **autocmd:** cleanup ([1be485d](https://github.com/bassamsdata/deadcolumn.nvim/commit/1be485d8d9e04fd5cfda7166fe7ba463b1a36d41))
* **config:** allow passing callback function to opts.modes ([bc1bdc1](https://github.com/bassamsdata/deadcolumn.nvim/commit/bc1bdc138ed827000c8ffd58ac5cb98ec87110fe))
* **config:** allow passing callback function to opts.scope ([#12](https://github.com/bassamsdata/deadcolumn.nvim/issues/12)) ([8f19d5f](https://github.com/bassamsdata/deadcolumn.nvim/commit/8f19d5fba835689d1c777a9ca697aae058739360))
* **config:** allow setting offset for warning ([1c35515](https://github.com/bassamsdata/deadcolumn.nvim/commit/1c35515d469d5911d5afd1a027beeed6e6292b10))
* **deadcolumn:** expose modules in deadcolumn.lua ([42e44ff](https://github.com/bassamsdata/deadcolumn.nvim/commit/42e44ff2ec85f878942faf68b2a3ff631841697f))
* **doc:** add new section [known issues] ([c37100c](https://github.com/bassamsdata/deadcolumn.nvim/commit/c37100ccb2d3ffcf1329fbebf1cb412f81337aa5))
* **doc:** update FAQ ([5b9f7e2](https://github.com/bassamsdata/deadcolumn.nvim/commit/5b9f7e2ad1a655f7d5363a8016b706cd7a0ed301))
* handle special cases when &termguicolors is not set ([#13](https://github.com/bassamsdata/deadcolumn.nvim/issues/13)) ([6c1f35c](https://github.com/bassamsdata/deadcolumn.nvim/commit/6c1f35c60f1d7766776d03c75bfd1ef77d6fda4e))
* **lsp:** add .luarc.json ([7f62f2f](https://github.com/bassamsdata/deadcolumn.nvim/commit/7f62f2ff8c3b03ea793278a3ec13b1ead2b49da1))
* new option 'extra.follow_tw' ([01a64a4](https://github.com/bassamsdata/deadcolumn.nvim/commit/01a64a483f6bae83ca02fd8216f11f48909a61fb))
* resolve complex colorcolumn settings ([a58150e](https://github.com/bassamsdata/deadcolumn.nvim/commit/a58150e8b219f1cff31bca4581a2f1173bceb405))
* **vimdoc:** add tags ([7c6649b](https://github.com/bassamsdata/deadcolumn.nvim/commit/7c6649b693fd212ca2eb76fb0c8a22abc1297d8d))


### Bug Fixes

* &cc not set to follow &tw in new buffers ([c6d612d](https://github.com/bassamsdata/deadcolumn.nvim/commit/c6d612d16ed1cca46f78c02af965b7a32c05448f))
* `get_hl_hex()` not padding hex color codes ([#15](https://github.com/bassamsdata/deadcolumn.nvim/issues/15)) ([4bec1fa](https://github.com/bassamsdata/deadcolumn.nvim/commit/4bec1fa65234ad5047b957356fb4a5e100cb83ea))
* `nvim_get_hl()` does not have `create` key on nvim 0.9.5 ([#17](https://github.com/bassamsdata/deadcolumn.nvim/issues/17)) ([b84cdf2](https://github.com/bassamsdata/deadcolumn.nvim/commit/b84cdf2fc94c59651ececd5e4d2a0488b38a7a75))
* `opts.scope` is ignored ([0b27192](https://github.com/bassamsdata/deadcolumn.nvim/commit/0b271926037153e7aa69bfab366ff8749ebba521))
* `opts.warning.offset` ignored ([acc37e1](https://github.com/bassamsdata/deadcolumn.nvim/commit/acc37e1a27c19df030cb824297885172e0f29ceb))
* **autocmd:** code cleanup ([3dd6ca2](https://github.com/bassamsdata/deadcolumn.nvim/commit/3dd6ca2bfd785a0ca8f319a6f1f3bad244db8a13))
* **autocmd:** colorcolumn always in warning color ([9cc357e](https://github.com/bassamsdata/deadcolumn.nvim/commit/9cc357e621505be5b8490faec43fd1cc07fecce5))
* **autocmd:** config indexing issue ([bf1770d](https://github.com/bassamsdata/deadcolumn.nvim/commit/bf1770d83446f6632a08b1895a1e5a7aae9122cd))
* **autocmd:** create augroup in make_autocmds() ([11d1f32](https://github.com/bassamsdata/deadcolumn.nvim/commit/11d1f325b93957d1a5bc65c4bcb6a25bc911ff2f))
* **autocmd:** horizontal cursor postion lost when cc is set ([f349e5b](https://github.com/bassamsdata/deadcolumn.nvim/commit/f349e5b3e41166f8c70dd97a1b1617ed4e9b54fe))
* **autocmd:** remove uneeded field in store ([4ec0cdb](https://github.com/bassamsdata/deadcolumn.nvim/commit/4ec0cdb34e2d87b84919c3de9ff5ebe43916cd1c))
* **autocmd:** respect cc settings from modeline when tw is set ([b0916e4](https://github.com/bassamsdata/deadcolumn.nvim/commit/b0916e491977fdb84327f7b9b8e1b1056f0c4441))
* **autocmds:** [#3](https://github.com/bassamsdata/deadcolumn.nvim/issues/3) handle settings from modelines ([6293229](https://github.com/bassamsdata/deadcolumn.nvim/commit/6293229c2f0230466bb7c6f36747977e7c9aa0a7))
* **autocmd:** save & restore win view to prevent cursor from being reset ([5cdaae3](https://github.com/bassamsdata/deadcolumn.nvim/commit/5cdaae3313784562b30bed06ae29f13962d56ce0))
* **autocmd:** should redraw on WinScrolled ([48cb768](https://github.com/bassamsdata/deadcolumn.nvim/commit/48cb768694d49c91752671f822772d23b8868eee))
* **autocmds:** should update colorcolumn on 'UIEnter' ([f154d14](https://github.com/bassamsdata/deadcolumn.nvim/commit/f154d14cb859a10ac2cc48bda67977c28fe96def))
* **colors:** fix weird behavior with transparent background ([72e3d80](https://github.com/bassamsdata/deadcolumn.nvim/commit/72e3d8031d435b3a38ec37e6aeebbc506f17a946))
* **colors:** fix weird behavior with transparent background ([8cdd0e0](https://github.com/bassamsdata/deadcolumn.nvim/commit/8cdd0e05eea954c225ec6819a45fb7e782936a4d))
* **colors:** fix weird behavior with transparent background ([103d031](https://github.com/bassamsdata/deadcolumn.nvim/commit/103d031f685c87e009bb477e448ee6712bcc60b7))
* **configs:** error when using 'buffer' scope in empty buffer ([#16](https://github.com/bassamsdata/deadcolumn.nvim/issues/16)) ([c3eedd2](https://github.com/bassamsdata/deadcolumn.nvim/commit/c3eedd20209617910743f3e3e829082dbedb3356))
* **configs:** error when using 'visible' scope in empty buffer ([d06f166](https://github.com/bassamsdata/deadcolumn.nvim/commit/d06f166cb42e68a15e9c21230dea43f54531eb67))
* **configs:** use cumulative config ([fef1b12](https://github.com/bassamsdata/deadcolumn.nvim/commit/fef1b129779b223ddde9971fc852da20dfa6717d))
* **cursor:** cursor position ([49ecebe](https://github.com/bassamsdata/deadcolumn.nvim/commit/49ecebe1284d94cc028941e8746b37faec3922f0))
* **cursor:** keep cursor column across lines in insert/replace mode ([fd540a6](https://github.com/bassamsdata/deadcolumn.nvim/commit/fd540a66e90732d0f3e0febdbbb034cb9def1963))
* **cursor:** keep cursor column across lines in insert/replace mode ([616ba4b](https://github.com/bassamsdata/deadcolumn.nvim/commit/616ba4bdbbd338f0d4b0b1952c3a073fb45904a3))
* **cursor:** keep cursor column across lines in insert/replace mode ([a4c1667](https://github.com/bassamsdata/deadcolumn.nvim/commit/a4c1667984092c417ae72405e3bdb3426346eefa))
* **doc&autocmd:** typo ([ba3af2e](https://github.com/bassamsdata/deadcolumn.nvim/commit/ba3af2e29d15f4ae3c3d08bf5405d1a89c00c064))
* **doc:** syntax error in default config sample ([9d02a3b](https://github.com/bassamsdata/deadcolumn.nvim/commit/9d02a3b1d35555fcf27e630950a5e91c91f1d0ed))
* **doc:** typo ([0590527](https://github.com/bassamsdata/deadcolumn.nvim/commit/0590527c50c69c9a3d03ab6f4fc8cde623afed45))
* ftplugin detection logic: update vim.b/g.cc only if buf matches ([402b146](https://github.com/bassamsdata/deadcolumn.nvim/commit/402b14633f21699d7586523ac6b3b90942800244))
* ftplugin detection: update vim.b/g.cc only if buf matches ([94a0197](https://github.com/bassamsdata/deadcolumn.nvim/commit/94a01978e51ae1082fdf719016cf60f212a1095a))
* handle ftplugin settings properly ([e58150d](https://github.com/bassamsdata/deadcolumn.nvim/commit/e58150df1f4ddcafa602ffdf6727fe0a3eda7e0d))
* handle ftplugin settings properly ([ae9072b](https://github.com/bassamsdata/deadcolumn.nvim/commit/ae9072b8016fe68d52f4461a37a07c984f9ac7bf))
* handle ftplugin settings: handle global cc settings ([03021ba](https://github.com/bassamsdata/deadcolumn.nvim/commit/03021bac60052726b452f0b9e911a0bc7b0d49f1))
* handle ftplugin settings: should change cc value after buf change ([62bda9a](https://github.com/bassamsdata/deadcolumn.nvim/commit/62bda9a3118c501489869c29b6ec40d74e07eccb))
* handle settings of cc from ftplugins properly ([e18f699](https://github.com/bassamsdata/deadcolumn.nvim/commit/e18f699ee35b3568beb7886cfe36008053affef3))
* invalid alpha (&gt;1) when length > cc ([40a1ddd](https://github.com/bassamsdata/deadcolumn.nvim/commit/40a1ddda3f7adc5d0cc8d230ce8a9e94fc09ef91))
* **logs:** remove debug logs ([31a4868](https://github.com/bassamsdata/deadcolumn.nvim/commit/31a4868461c7d0aaf336c86324c9ba92a9cdef7c))
* **logs:** remove debug logs. ([f4ddbd5](https://github.com/bassamsdata/deadcolumn.nvim/commit/f4ddbd50648e1bbc986a116d329ee2a6c51af84e))
* **logs:** remove logs ([8adee8d](https://github.com/bassamsdata/deadcolumn.nvim/commit/8adee8d19ef75bc67216f834ebc38ada30fa2297))
* **logs:** remove logs ([898eaf5](https://github.com/bassamsdata/deadcolumn.nvim/commit/898eaf58d0509806dc462a72155c28ca23b9b313))
* **readme:** 'opts.scope' example config ([dc859ec](https://github.com/bassamsdata/deadcolumn.nvim/commit/dc859ecb1a39c5d842d26596e02393ab6c54899a))
* **readme:** FAQ instruction ftplugin filename ([7725a44](https://github.com/bassamsdata/deadcolumn.nvim/commit/7725a443cacd1c9f14c1923640f2856cdd97dbd8))
* **readme:** FAQ instructions and format ([480a578](https://github.com/bassamsdata/deadcolumn.nvim/commit/480a5786f12658d9ed2242df4b6c2c21f635d595))
* **readme:** indentation ([f6c4a2b](https://github.com/bassamsdata/deadcolumn.nvim/commit/f6c4a2b20b74417d2cbf7bc41b0342d5d882067d))
* remove logs and add comments ([f07a266](https://github.com/bassamsdata/deadcolumn.nvim/commit/f07a266404f9b0059369c4b73ed7e994a8549822))
* revert cursor fix ([5569596](https://github.com/bassamsdata/deadcolumn.nvim/commit/556959623a18c0b0a932fb808572071b1f91410a))
* save and update colorcolumn background color properly ([0bb5221](https://github.com/bassamsdata/deadcolumn.nvim/commit/0bb522181694ed3e7bd20454ae30e15bb8729a74))
* should redraw colorcolumn on option set ([18c357f](https://github.com/bassamsdata/deadcolumn.nvim/commit/18c357fb5e92718c9623b449baab5834cbbbe469))
* **vimdoc:** FAQ instructions ([a766787](https://github.com/bassamsdata/deadcolumn.nvim/commit/a766787a16e7c36b8747957ae4d6625192138d63))
* **vimdoc:** fix tags ([5a0ee57](https://github.com/bassamsdata/deadcolumn.nvim/commit/5a0ee577322eadc818f0bc95eaa99f004779e5f7))
* **vimdoc:** tag and width; other small fixes ([69ae76b](https://github.com/bassamsdata/deadcolumn.nvim/commit/69ae76b2a62275574b7f37e6354d02eea6d65fe0))
* **vimdoc:** textwidth ([7d09bad](https://github.com/bassamsdata/deadcolumn.nvim/commit/7d09baddb78e1acf6f05c1c6b2250b37a80ea64c))


### Code Refactoring

* use `winhl` instead of setting `cc` directly ([ce15b17](https://github.com/bassamsdata/deadcolumn.nvim/commit/ce15b1750c3bb1f7d2bc26492491f8cdcd313ff5))

## [1.0.0](https://github.com/Bekaboo/deadcolumn.nvim/compare/v0.0.0...v1.0.0) (2024-02-18)


### ⚠ BREAKING CHANGES

* use `winhl` instead of setting `cc` directly

### Features

* **config:** allow passing callback function to opts.modes ([bc1bdc1](https://github.com/Bekaboo/deadcolumn.nvim/commit/bc1bdc138ed827000c8ffd58ac5cb98ec87110fe))
* **config:** allow passing callback function to opts.scope ([#12](https://github.com/Bekaboo/deadcolumn.nvim/issues/12)) ([8f19d5f](https://github.com/Bekaboo/deadcolumn.nvim/commit/8f19d5fba835689d1c777a9ca697aae058739360))
* **config:** allow setting offset for warning ([1c35515](https://github.com/Bekaboo/deadcolumn.nvim/commit/1c35515d469d5911d5afd1a027beeed6e6292b10))
* **deadcolumn:** expose modules in deadcolumn.lua ([42e44ff](https://github.com/Bekaboo/deadcolumn.nvim/commit/42e44ff2ec85f878942faf68b2a3ff631841697f))
* handle special cases when &termguicolors is not set ([#13](https://github.com/Bekaboo/deadcolumn.nvim/issues/13)) ([6c1f35c](https://github.com/Bekaboo/deadcolumn.nvim/commit/6c1f35c60f1d7766776d03c75bfd1ef77d6fda4e))
* **lsp:** add .luarc.json ([7f62f2f](https://github.com/Bekaboo/deadcolumn.nvim/commit/7f62f2ff8c3b03ea793278a3ec13b1ead2b49da1))


### Bug Fixes

* &cc not set to follow &tw in new buffers ([c6d612d](https://github.com/Bekaboo/deadcolumn.nvim/commit/c6d612d16ed1cca46f78c02af965b7a32c05448f))
* `get_hl_hex()` not padding hex color codes ([#15](https://github.com/Bekaboo/deadcolumn.nvim/issues/15)) ([4bec1fa](https://github.com/Bekaboo/deadcolumn.nvim/commit/4bec1fa65234ad5047b957356fb4a5e100cb83ea))
* `nvim_get_hl()` does not have `create` key on nvim 0.9.5 ([#17](https://github.com/Bekaboo/deadcolumn.nvim/issues/17)) ([b84cdf2](https://github.com/Bekaboo/deadcolumn.nvim/commit/b84cdf2fc94c59651ececd5e4d2a0488b38a7a75))
* `opts.scope` is ignored ([0b27192](https://github.com/Bekaboo/deadcolumn.nvim/commit/0b271926037153e7aa69bfab366ff8749ebba521))
* `opts.warning.offset` ignored ([acc37e1](https://github.com/Bekaboo/deadcolumn.nvim/commit/acc37e1a27c19df030cb824297885172e0f29ceb))
* **configs:** error when using 'buffer' scope in empty buffer ([#16](https://github.com/Bekaboo/deadcolumn.nvim/issues/16)) ([c3eedd2](https://github.com/Bekaboo/deadcolumn.nvim/commit/c3eedd20209617910743f3e3e829082dbedb3356))
* **configs:** error when using 'visible' scope in empty buffer ([d06f166](https://github.com/Bekaboo/deadcolumn.nvim/commit/d06f166cb42e68a15e9c21230dea43f54531eb67))
* invalid alpha (&gt;1) when length > cc ([40a1ddd](https://github.com/Bekaboo/deadcolumn.nvim/commit/40a1ddda3f7adc5d0cc8d230ce8a9e94fc09ef91))
* **readme:** 'opts.scope' example config ([dc859ec](https://github.com/Bekaboo/deadcolumn.nvim/commit/dc859ecb1a39c5d842d26596e02393ab6c54899a))
* **readme:** indentation ([f6c4a2b](https://github.com/Bekaboo/deadcolumn.nvim/commit/f6c4a2b20b74417d2cbf7bc41b0342d5d882067d))


### Code Refactoring

* use `winhl` instead of setting `cc` directly ([ce15b17](https://github.com/Bekaboo/deadcolumn.nvim/commit/ce15b1750c3bb1f7d2bc26492491f8cdcd313ff5))
