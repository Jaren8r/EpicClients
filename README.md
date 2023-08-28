# Auth Clients
Every application (e.g. game, website) that utilises Epic's official services is issued an auth client that is used to identify requests sent to Epic, as well as to set boundaries to what a certain application can access.

## List of Auth Clients
| Name | ID | Secret | Enabled | EOS | Service | Redirect URL | Grant Types | Allowed Scopes | Features |
| ---- | -- | ------ | ------- | --- | ------- | ------------ | ----------- | -------------- | -------- |
| [epicgamesWebsiteClient](permissions/007c0bfe154c4f5396648f013c641dcf.md) | `007c0bfe154c4f5396648f013c641dcf` | `Unknown` | ✅ | ❔ | `Unknown` | `https://epicgames-stage.ol.epicgames.net/exchange` | `Unknown` | `None` | `None` |
| [utClient](permissions/1252412dc7704a9690f6ea4611bc81ee.md) | `1252412dc7704a9690f6ea4611bc81ee` | `2ca0c925b4674852bff92b26f8322434` | ✅ | ❌ | `ut` | `None` | `authorization_code`,&nbsp;`client_credentials`,&nbsp;`continuation_token`,&nbsp;`device_auth`,&nbsp;`device_code`,&nbsp;`exchange_code`,&nbsp;`external_auth`,&nbsp;`password`,&nbsp;`refresh_token` | `None` | `None` |
| [orionLivePCGameClient](permissions/1483ba7d6c0247828c26cc8a74a9a183.md) | `1483ba7d6c0247828c26cc8a74a9a183` | `78facc4029ed4d66801a5402adad79c8` | ✅ | ❌ | `orionLive` | `None` | `client_credentials` | `None` | `None` |
| [androidPortal](permissions/1ea8131a415347f49ca78a6a81e2b66f.md) | `1ea8131a415347f49ca78a6a81e2b66f` | `69c9500c-91bf-4975-bf05-cc932af46efd` | ✅ | ❌ | `androidportal` | `None` | `authorization_code`,&nbsp;`client_credentials`,&nbsp;`continuation_token`,&nbsp;`device_auth`,&nbsp;`device_code`,&nbsp;`exchange_code`,&nbsp;`external_auth`,&nbsp;`password`,&nbsp;`refresh_token` | `None` | `None` |
| [launcherWebClient](permissions/24a1bff3f90749efbfcbc576c626a282.md) | `24a1bff3f90749efbfcbc576c626a282` | `Unknown` | ✅ | ❔ | `Unknown` | `https://launcher-stage.ol.epicgames.net/exchange` | `Unknown` | `None` | `None` |
| [paymentWebClient](permissions/29cee42e711746e1bbcafb62929e48fd.md) | `29cee42e711746e1bbcafb62929e48fd` | `Unknown` | ✅ | ❔ | `Unknown` | `https://payment-stage.ol.epicgames.net/exchange` | `Unknown` | `None` | `None` |
| [fortniteGameClient](permissions/300d79839c914445948e3c1100f211db.md) | `300d79839c914445948e3c1100f211db` | `Unknown` | ❌ | ❔ | `Unknown` | `None` | `Unknown` | `None` | `None` |
| [fortniteIOSGameClient](permissions/3446cd72694c4a4485d81b77adbb2141.md) | `3446cd72694c4a4485d81b77adbb2141` | `9209d4a5e25a457fb9b07489d313b41a` | ✅ | ✅ | `a5289801b5584029a35f1af1e49fe718` | `com.epicgames.fortnite://fnauth/` | `authorization_code`,&nbsp;`client_credentials`,&nbsp;`continuation_token`,&nbsp;`device_auth`,&nbsp;`device_code`,&nbsp;`exchange_code`,&nbsp;`external_auth`,&nbsp;`password`,&nbsp;`refresh_token` | `None` | `None` |
| [launcherAppClient2](permissions/34a02cf8f4414e29b15921876da36f9a.md) | `34a02cf8f4414e29b15921876da36f9a` | `daafbccc737745039dffe53d94fc76cf` | ✅ | ❌ | `launcher` | `https://localhost/launcher/authorized` | `client_credentials` | `None` | `None` |
| [unrealissues](permissions/3adb22b897e24666971f9a273b1c15e8.md) | `3adb22b897e24666971f9a273b1c15e8` | `Unknown` | ❌ | ❔ | `Unknown` | `None` | `Unknown` | `None` | `None` |
| [unrealComClient](permissions/43e2dea89b054198a703f6199bee6d5b.md) | `43e2dea89b054198a703f6199bee6d5b` | `Unknown` | ✅ | ❔ | `Unknown` | `https://partial-epicgames.cs95.force.com/CommunitySSO` | `Unknown` | `None` | `None` |
| [ocean_web](permissions/4b6c700c72c44e178b12070f2719af1a.md) | `4b6c700c72c44e178b12070f2719af1a` | `Unknown` | ✅ | ❔ | `Unknown` | `https://epicgames-stage.ol.epicgames.net/spyjinx/exchange` | `Unknown` | `None` | `None` |
| [fortniteSwitchGameClient](permissions/5229dcd3ac3845208b496649092f251b.md) | `5229dcd3ac3845208b496649092f251b` | `e3bd2d3e-bf8c-4857-9e7d-f3d947d220c7` | ✅ | ✅ | `a5289801b5584029a35f1af1e49fe718` | `https://accounts.epicgames.com/fnauth` | `client_credentials`,&nbsp;`device_auth`,&nbsp;`device_code`,&nbsp;`external_auth`,&nbsp;`refresh_token` | `None` | `None` |
| [RealIdWeb](permissions/52aff4e66d4d45548180ccf65ce12d3e.md) | `52aff4e66d4d45548180ccf65ce12d3e` | `Unknown` | ✅ | ❔ | `Unknown` | `https://epicgames-stage.ol.epicgames.net/realid/exchange` | `Unknown` | `None` | `None` |
| [orionLivePS4USGameClient](permissions/63f198487c8646f192a59be02ce0d14c.md) | `63f198487c8646f192a59be02ce0d14c` | `73f1d7b9e7124c3b8538e8d67d7c4e68` | ✅ | ❌ | `orionLive` | `None` | `client_credentials` | `None` | `None` |
| [utDedicatedServer](permissions/6ff43e743edc4d1dbac3594877b4bed9.md) | `6ff43e743edc4d1dbac3594877b4bed9` | `54619d6f84d443e195200b54ab649a53` | ✅ | ❌ | `ut` | `None` | `client_credentials` | `None` | `None` |
| [fortniteAndroidGameClient-deprecated](permissions/72f83226ab664739b635b1e318a635bc.md) | `72f83226ab664739b635b1e318a635bc` | `2f298cd32c6641fab2b0ceaa5bc9c92f` | ❌ | ❔ | `Unknown` | `None` | `Unknown` | `None` | `None` |
| [fortnitePS4EUGameClient](permissions/79a931b375334570ac369234f5da05ec.md) | `79a931b375334570ac369234f5da05ec` | `Unknown` | ✅ | ❔ | `Unknown` | `https://accounts.epicgames-stage.ol.epicgames.net/fnauth` | `Unknown` | `None` | `None` |
| [UEFN](permissions/8c99c65484304ba493a2bc1220656e80.md) | `8c99c65484304ba493a2bc1220656e80` | `0375eb2fe2644c0daf083e2f251a4648` | ✅ | ❌ | `uefn` | `None` | `authorization_code`,&nbsp;`client_credentials`,&nbsp;`device_auth`,&nbsp;`device_code`,&nbsp;`exchange_code`,&nbsp;`external_auth`,&nbsp;`password`,&nbsp;`refresh_token`,&nbsp;`token_to_token` | `None` | `None` |
| [viper_web](permissions/8df415b848c74affb682907405f7a52b.md) | `8df415b848c74affb682907405f7a52b` | `Unknown` | ✅ | ❔ | `Unknown` | `https://epicgames-stage.ol.epicgames.net/shadowcomplex/exchange` | `Unknown` | `None` | `None` |
| [battlebreakers_web](permissions/8e873617d81d4caf89bae28a4b74bbfe.md) | `8e873617d81d4caf89bae28a4b74bbfe` | `Unknown` | ✅ | ❔ | `Unknown` | `https://epicgames-stage.ol.epicgames.net/battlebreakers/exchange` | `Unknown` | `None` | `None` |
| [launcherPaymentClient2](permissions/8e889dadbfaf4145b3a806f51d1e3fee.md) | `8e889dadbfaf4145b3a806f51d1e3fee` | `2c6040b846404160abf5229c565d6ef7` | ✅ | ❔ | `launcher` | `None` | `password` | `None` | `None` |
| [orionLivePS4GameClient](permissions/9fe4a9e4584c43a0bca6bd22a52f2f40.md) | `9fe4a9e4584c43a0bca6bd22a52f2f40` | `3bc094a9bab74dcdb8bb74c836758d48` | ✅ | ❌ | `orionLive` | `None` | `client_credentials`,&nbsp;`password` | `None` | `None` |
| [orionLivePS4EUGameClient](permissions/a510a43d1fcc4636bc9c99a46a7cd50c.md) | `a510a43d1fcc4636bc9c99a46a7cd50c` | `2bd23b2e603d46c4939fcbf9d2b2f46a` | ✅ | ❌ | `orionLive` | `None` | `client_credentials`,&nbsp;`password` | `None` | `None` |
| [utDedicatedServerEpicTrusted](permissions/ad8def9ae6b84360b6c9b358aba06262.md) | `ad8def9ae6b84360b6c9b358aba06262` | `Unknown` | ✅ | ❔ | `Unknown` | `None` | `Unknown` | `None` | `None` |
| [Diesel - Dauntless](permissions/b070f20729f84693b5d621c904fc5bc2.md) | `b070f20729f84693b5d621c904fc5bc2` | `HG@XE&TGCxEJsgT#&_p2]=aRo#~>=>+c6PhR)zXP` | ✅ | ❌ | `egp_dauntless` | `https://www.playdauntless.com` | `authorization_code`,&nbsp;`client_credentials`,&nbsp;`device_auth`,&nbsp;`exchange_code`,&nbsp;`external_auth`,&nbsp;`password`,&nbsp;`refresh_token` | `None` | `None` |
| [fulfillmentClient](permissions/b3a0d1d6558b788e27a8c044083375ef.md) | `b3a0d1d6558b788e27a8c044083375ef` | `Unknown` | ✅ | ❔ | `Unknown` | `None` | `Unknown` | `None` | `None` |
| [fortniteHKGameClient](permissions/bb69d1e9bedb4c04a9e64a63a40aa2a4.md) | `bb69d1e9bedb4c04a9e64a63a40aa2a4` | `Unknown` | ❌ | ❔ | `Unknown` | `None` | `Unknown` | `None` | `None` |
| [udnClient](permissions/bc742d26f8314469aa997373f39c876e.md) | `bc742d26f8314469aa997373f39c876e` | `Unknown` | ✅ | ❔ | `Unknown` | `https://staging.udn.unrealengine.com/oauth/authorized` | `Unknown` | `None` | `None` |
| [adminportal](permissions/be806bc37c6f4bb9874430ebb11a6eaa.md) | `be806bc37c6f4bb9874430ebb11a6eaa` | `Unknown` | ✅ | ❔ | `Unknown` | `None` | `Unknown` | `None` | `None` |
| [ue4answerhub](permissions/c4c02c7c99e94ed9870a9dbeafab2c3f.md) | `c4c02c7c99e94ed9870a9dbeafab2c3f` | `Unknown` | ✅ | ❔ | `Unknown` | `https://answers.epicgames-stage.ol.epicgames.com/oauth/authorized` | `Unknown` | `None` | `None` |
| [content-service-stage-web](permissions/c7d5e728807d464ab81aed3746d1c831.md) | `c7d5e728807d464ab81aed3746d1c831` | `Unknown` | ✅ | ❔ | `content-service` | `https://content-service-stage.bfda.live.use1a.on.epicgames.com/oauth/v1/token-exchange` | `Unknown` | `None` | `None` |
| [fortniteComClient](permissions/cd2b7c19c9734a2ab98dc251868d7724.md) | `cd2b7c19c9734a2ab98dc251868d7724` | `Unknown` | ✅ | ❔ | `Unknown` | `https://epicgames-stage.ol.epicgames.net/fortnite/exchange` | `Unknown` | `None` | `None` |
| [fortniteXboxGameClient](permissions/cfaa14c4bf8744e3a5ef9a5d6c34558d.md) | `cfaa14c4bf8744e3a5ef9a5d6c34558d` | `Unknown` | ✅ | ❔ | `Unknown` | `https://accounts.epicgames-stage.ol.epicgames.net/fnauth` | `Unknown` | `None` | `None` |
| [fortnitePS4USGameClient](permissions/d8566f2e7f5c48f89683173eb529fee1.md) | `d8566f2e7f5c48f89683173eb529fee1` | `Unknown` | ✅ | ❔ | `Unknown` | `https://accounts.epicgames-stage.ol.epicgames.net/fnauth` | `Unknown` | `None` | `None` |
| [utDedicatedServerEpicHosted](permissions/e0aca23dfb7348d6bad648bbe175a6e6.md) | `e0aca23dfb7348d6bad648bbe175a6e6` | `Unknown` | ✅ | ❔ | `Unknown` | `None` | `Unknown` | `None` | `None` |
| [utvbulletin](permissions/e7d1a3ee19ac4173b80a53006dc53be3.md) | `e7d1a3ee19ac4173b80a53006dc53be3` | `Unknown` | ✅ | ❔ | `Unknown` | `https://forums.unrealtournament-stage.ol.epicgames.net/authorize.php` | `Unknown` | `None` | `None` |
| [fortnitePCGameClient](permissions/ec684b8c687f479fadea3cb2ad83f5c6.md) | `ec684b8c687f479fadea3cb2ad83f5c6` | `e1f31c211f28413186262d37a13fc84d` | ✅ | ✅ | `a5289801b5584029a35f1af1e49fe718` | `None` | `authorization_code`,&nbsp;`client_credentials`,&nbsp;`device_auth`,&nbsp;`device_code`,&nbsp;`exchange_code`,&nbsp;`external_auth`,&nbsp;`refresh_token` | `None` | `None` |
| [utcomClient](permissions/f0b883ba7d3646bba4aa11bf1d71c071.md) | `f0b883ba7d3646bba4aa11bf1d71c071` | `Unknown` | ✅ | ❔ | `Unknown` | `https://epicgames-stage.ol.epicgames.net/unrealtournament/exchange` | `Unknown` | `None` | `None` |
| [publicClient](permissions/f2f868d1259e4b128e5b7e8a3732cb1a.md) | `f2f868d1259e4b128e5b7e8a3732cb1a` | `Unknown` | ✅ | ❔ | `all` | `None` | `Unknown` | `None` | `None` |
| [launcherServiceClient](permissions/f3e80378aed4462498774a7951cd263f.md) | `f3e80378aed4462498774a7951cd263f` | `Unknown` | ✅ | ❔ | `Unknown` | `https://localhost/launcher/authorized` | `Unknown` | `None` | `None` |
| [ue4vbulletin](permissions/f65082b48b504eb88f73961b0131cda7.md) | `f65082b48b504eb88f73961b0131cda7` | `Unknown` | ✅ | ❔ | `Unknown` | `https://forums.unrealengine-stage.ol.epicgames.net/authorize.php` | `Unknown` | `None` | `None` |
| [wexpClient](permissions/f8eac541a1c241939f76d26cf2a673a6.md) | `f8eac541a1c241939f76d26cf2a673a6` | `80f5551f151840ca9f52e2e14581a742` | ✅ | ❌ | `wexp` | `None` | `client_credentials` | `None` | `None` |
