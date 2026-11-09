# Changelog

## [5.0.0](https://github.com/arjanvlek/libtado/compare/4.3.1...5.0.0) (2026-11-09)


### ⚠ BREAKING CHANGES

* **auth:** Tado does not support password grant flow as authentication flow anymore.

### Features

* Allow passing home_id to save an API call to /me ([#594](https://github.com/arjanvlek/libtado/issues/594)) ([0c5ba66](https://github.com/arjanvlek/libtado/commit/0c5ba66d3a5cdc738e8c9b64db860dc40cea6409))
* **api:** Add dayReport API Call ([975cbc5](https://github.com/arjanvlek/libtado/commit/975cbc536a5e4e7087ade8a3da3e32d1f6babb91))
* **api:** Add missing apis and add a 'tado status' overview to the 'tado' tool ([#17](https://github.com/arjanvlek/libtado/issues/17)) ([3b0e141](https://github.com/arjanvlek/libtado/commit/3b0e1414cc75f9c12af3e4026ae0cad597c12507))
* **api:** Add support for retrieving central heating flow temperature (OpenTherm) ([#605](https://github.com/arjanvlek/libtado/issues/605)) ([6ef71cb](https://github.com/arjanvlek/libtado/commit/6ef71cb6fa8186606c6d3727b8f966d09e522f67))
* **api:** Air comfort endpoint ([#5](https://github.com/arjanvlek/libtado/issues/5)) ([d203d20](https://github.com/arjanvlek/libtado/commit/d203d2015b151267acdbf01fc99f8d39d893b607))
* **api:** Provides energy insights metrics ([#107](https://github.com/arjanvlek/libtado/issues/107)) ([4541c50](https://github.com/arjanvlek/libtado/commit/4541c50ee0757bf62303349617ae16a304d96384))
* **api:** Provides energy savings results ([#112](https://github.com/arjanvlek/libtado/issues/112)) ([9986a14](https://github.com/arjanvlek/libtado/commit/9986a142874eafa11d885d735a751b34c30c8778))
* **auth:** Implement new OAuth device code grant flow ([#478](https://github.com/arjanvlek/libtado/issues/478)) ([a5d3e04](https://github.com/arjanvlek/libtado/commit/a5d3e04f990ae4ccb53fa06292e91169ac3c27ce))
* **build:** Deploy on PyPi ([28f7805](https://github.com/arjanvlek/libtado/commit/28f7805aa746e5ffe45cc49e206613c9121799bf))
* **cli:** Add device VA02E on tado devices command ([#125](https://github.com/arjanvlek/libtado/issues/125)) ([687c112](https://github.com/arjanvlek/libtado/commit/687c1125dd3c37981661a9f9f7aadc5243916714)), closes [#124](https://github.com/arjanvlek/libtado/issues/124)
* **cli:** Provides energy insights metrics ([#108](https://github.com/arjanvlek/libtado/issues/108)) ([78d158b](https://github.com/arjanvlek/libtado/commit/78d158b81c3d6c1c3998ff564b83222fbd7cdd08))
* **example:** Add script example ([7b2fc89](https://github.com/arjanvlek/libtado/commit/7b2fc891f62987111a2e0aedb41256687d17f5fe))
* **login:** Add CLIENT_SECRET in parameters ([38fa412](https://github.com/arjanvlek/libtado/commit/38fa412c1503f96adab751555153d9ba7a96b2ff))
* Offer API call usage and rate limiting info ([#532](https://github.com/arjanvlek/libtado/issues/532)) ([b1eca99](https://github.com/arjanvlek/libtado/commit/b1eca99de588acd55dd65700e7b243ea47b45399))
* **python:** Deprecate python 3.7 ([#159](https://github.com/arjanvlek/libtado/issues/159)) ([b91992b](https://github.com/arjanvlek/libtado/commit/b91992b1e491ac2cbdc5e7c1a628b5c5d0a698fd))


### Bugfix

* Add get_consumption_details endpoint ([#456](https://github.com/arjanvlek/libtado/issues/456)) ([ea4ff05](https://github.com/arjanvlek/libtado/commit/ea4ff05ba190f3e0f2f5de7b575df186a3e41f85))
* **api:** Add api call from page Care & Protect ([#101](https://github.com/arjanvlek/libtado/issues/101)) ([3ad1f7f](https://github.com/arjanvlek/libtado/commit/3ad1f7f4116db6423043217d5670bdd0cc175cd2))
* **api:** Enable incidents detection ([#294](https://github.com/arjanvlek/libtado/issues/294)) ([c80ea0a](https://github.com/arjanvlek/libtado/commit/c80ea0a6c1b893f8d4857c5a07036b8ad5da26a5))
* **api:** Energy insights ([#111](https://github.com/arjanvlek/libtado/issues/111)) ([31367e9](https://github.com/arjanvlek/libtado/commit/31367e99561083835d22900f0e60a0554a9ffa03))
* **api:** Get and Set schedule by day type ([#224](https://github.com/arjanvlek/libtado/issues/224)) ([acb39ea](https://github.com/arjanvlek/libtado/commit/acb39ea40a6196d4f363c63b64287fdece1c855b))
* **api:** Get Consumption Overview ([#195](https://github.com/arjanvlek/libtado/issues/195)) ([35026d9](https://github.com/arjanvlek/libtado/commit/35026d9c9464e9709e659908cf75901601f762b5))
* **api:** Get Energy Insights ([#198](https://github.com/arjanvlek/libtado/issues/198)) ([122ade1](https://github.com/arjanvlek/libtado/commit/122ade1e8e4dc5a222c258f3ae6fe4bc686fa05d))
* **api:** Get Energy Settings ([#196](https://github.com/arjanvlek/libtado/issues/196)) ([19e2a17](https://github.com/arjanvlek/libtado/commit/19e2a179a3319c7e35c6e7611a115f5017f519da))
* **api:** Improve method set_schedule_block_by_day_type ([#540](https://github.com/arjanvlek/libtado/issues/540)) ([ce31ddd](https://github.com/arjanvlek/libtado/commit/ce31ddd8cff13b4e3a8fce076069ef8004e64fb7))
* **api:** Put Heating System Boiler ([#199](https://github.com/arjanvlek/libtado/issues/199)) ([3ee9acb](https://github.com/arjanvlek/libtado/commit/3ee9acbf868327a4bf92dc54fa700a3aec9a965d))
* **api:** Put method for Away Configuration ([38068c2](https://github.com/arjanvlek/libtado/commit/38068c288c717032bfb485e90f5e392b66ed1e75))
* **api:** Put Zone Order ([#200](https://github.com/arjanvlek/libtado/issues/200)) ([bbe7a60](https://github.com/arjanvlek/libtado/commit/bbe7a602cc333d4c5468cc3e372bd89c4cb3e1bf))
* **api:** Send and revoke home invitation with email ([#292](https://github.com/arjanvlek/libtado/issues/292)) ([78147d8](https://github.com/arjanvlek/libtado/commit/78147d8c6df52ce7d70b03b99859363014717a17))
* **api:** Set Cost Simulation ([#197](https://github.com/arjanvlek/libtado/issues/197)) ([27b5e44](https://github.com/arjanvlek/libtado/commit/27b5e44488d9e12b1e874e1535614ef6e8fd4f5d))
* **api:** Specify Content-Type on put requests ([#9](https://github.com/arjanvlek/libtado/issues/9)) ([77b80df](https://github.com/arjanvlek/libtado/commit/77b80df2dc60563f29523d7e58058b22dfcaf9f3))
* Bump release version ([872de5c](https://github.com/arjanvlek/libtado/commit/872de5c22d5e88e18fc57c6262c8aa1d6d073369))
* Bump release version ([1260b7a](https://github.com/arjanvlek/libtado/commit/1260b7ade7847f1546ad92ff6232389c3ae5ed3b))
* Bump release version ([fd88a19](https://github.com/arjanvlek/libtado/commit/fd88a19f91c326c9e294cd1cbcf01845b64f8bfd))
* **ci:** Publish on PyPi ([#12](https://github.com/arjanvlek/libtado/issues/12)) ([b051efe](https://github.com/arjanvlek/libtado/commit/b051efe8edea17fb6138ab336082ef85c198082f))
* **ci:** publish to pypi with poetry ([#429](https://github.com/arjanvlek/libtado/issues/429)) ([7e55e71](https://github.com/arjanvlek/libtado/commit/7e55e71ee460c66198a6868eb6e29d663ec4db36))
* **cli:** Extend device list with Smart AC ([#253](https://github.com/arjanvlek/libtado/issues/253)) ([86fafaf](https://github.com/arjanvlek/libtado/commit/86fafafbd8d7b004bb880f7b4b9ecf9846b159dc))
* **cli:** Fix KeyError that occurs when libtado encounters a Hot Water zone ([#31](https://github.com/arjanvlek/libtado/issues/31)) ([2e9dfaf](https://github.com/arjanvlek/libtado/commit/2e9dfafee7e84ac8790edf56d5be080dedd221c5))
* **deps:** Update package with up-to-date deps ([dd330a5](https://github.com/arjanvlek/libtado/commit/dd330a58b101f918e7e95d91c1748209a13db509))
* **devices:** Add devices SU02 and BR02 on tado devices command ([#32](https://github.com/arjanvlek/libtado/issues/32)) ([667fffd](https://github.com/arjanvlek/libtado/commit/667fffd56b8648eed73ddea4f97fb48d99cbd879))
* **login:** Add library name in UserAgent on Tado requests ([#300](https://github.com/arjanvlek/libtado/issues/300)) ([2e3fb7f](https://github.com/arjanvlek/libtado/commit/2e3fb7ffc3905f6d194809751adebcca7702afaa))
* **login:** Update creds for API v2 nowadays ([21212fc](https://github.com/arjanvlek/libtado/commit/21212fcf18bb8595c1667fce82169313adb3770a))
* **login:** Update login and token refresh, optimize requests ([#47](https://github.com/arjanvlek/libtado/issues/47)) ([a122bf0](https://github.com/arjanvlek/libtado/commit/a122bf002e1b548d148cc16a45efebbb2563d677))
* refresh flow was not DST compliant ([#484](https://github.com/arjanvlek/libtado/issues/484)) ([683abf6](https://github.com/arjanvlek/libtado/commit/683abf678be0082addd0a7954be68454fa340cc0))
* Release version 3.7.14 ([#384](https://github.com/arjanvlek/libtado/issues/384)) ([334862c](https://github.com/arjanvlek/libtado/commit/334862cb77d70a8a69feeb5070868bf03bf58f67))
* **security:** Bump security fixes in dependencies ([#609](https://github.com/arjanvlek/libtado/issues/609)) ([6304ecf](https://github.com/arjanvlek/libtado/commit/6304ecfdd0fdd453e0015f28ed4b37f08afdc05b))
* Trigger security release ([#566](https://github.com/arjanvlek/libtado/issues/566)) ([5d1974a](https://github.com/arjanvlek/libtado/commit/5d1974aa92da935adca17c42392e0be30ed0efa5))
* **version:** Deploy next version ([87b776d](https://github.com/arjanvlek/libtado/commit/87b776d818010024c7fd9f42a05518d7bdc7e8e6))

## [4.3.1](https://github.com/germainlefebvre4/libtado/compare/4.3.0...4.3.1) (2026-10-13)


### Bugfix

* **security:** Bump security fixes in dependencies ([#609](https://github.com/germainlefebvre4/libtado/issues/609)) ([6304ecf](https://github.com/germainlefebvre4/libtado/commit/6304ecfdd0fdd453e0015f28ed4b37f08afdc05b))
