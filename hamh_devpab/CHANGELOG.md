## 3.0.0-alpha.61 (2025-01-08)

### 🚀 Features

- Use device area if available for entities that have no area directly set ([#403](https://github.com/t0bst4r/home-assistant-matter-hub/pull/403))

### 🩹 Fixes

- add extra logging when a device cannot be created ([fc0a2f0](https://github.com/t0bst4r/home-assistant-matter-hub/commit/fc0a2f0))
- **basic-information:** ensure variables are actually strings ([dc5f700](https://github.com/t0bst4r/home-assistant-matter-hub/commit/dc5f700))

### ❤️ Thank You

- Ricardo Hermida Ruiz @rhruiz
- Tobias Glatthar @t0bst4r

## 3.0.0-alpha.60 (2025-01-07)

### 🩹 Fixes

- **basic-information:** prevent empty values to fail initialization ([73185d5](https://github.com/t0bst4r/home-assistant-matter-hub/commit/73185d5))
- **cover:** use compatible cover types for tilt only or both ([a28ee12](https://github.com/t0bst4r/home-assistant-matter-hub/commit/a28ee12))
- **lights:** proper boundaries for color temperature ([784f186](https://github.com/t0bst4r/home-assistant-matter-hub/commit/784f186))
- **media_player:** set default input when no input could be determined ([0830f18](https://github.com/t0bst4r/home-assistant-matter-hub/commit/0830f18))

### ❤️ Thank You

- Tobias Glatthar @t0bst4r

## 3.0.0-alpha.59 (2025-01-06)

### 🚀 Features

- add descriptions for docker-compose ([7b304fd](https://github.com/t0bst4r/home-assistant-matter-hub/commit/7b304fd))
- allow filtering by entity_category ([fc83505](https://github.com/t0bst4r/home-assistant-matter-hub/commit/fc83505))
- **cover:** allow covers to mimic HA behaviors ([5e2907a](https://github.com/t0bst4r/home-assistant-matter-hub/commit/5e2907a))
- **media_player:** source selection, mute and volume fixes ([#363](https://github.com/t0bst4r/home-assistant-matter-hub/pull/363))

### 🩹 Fixes

- **basic-information:** use proper device information instead of mocked values ([d33c6e8](https://github.com/t0bst4r/home-assistant-matter-hub/commit/d33c6e8))
- **colorControl:** validate min and max mireds to stay in bounds ([2e10106](https://github.com/t0bst4r/home-assistant-matter-hub/commit/2e10106))
- **input_button:** turn the matter device 'on' for a short time ([57465a6](https://github.com/t0bst4r/home-assistant-matter-hub/commit/57465a6))

### ❤️ Thank You

- Kenny Levinsen @kennylevinsen
- Ricardo Hermida Ruiz @rhruiz
- Tobias Glatthar @t0bst4r

## 3.0.0-alpha.58 (2024-12-28)

### 🚀 Features

- **cover:** allow tilt feature ([9506263](https://github.com/t0bst4r/home-assistant-matter-hub/commit/9506263))

### 🩹 Fixes

- automatically retry home assistant connection on startup ([47979d9](https://github.com/t0bst4r/home-assistant-matter-hub/commit/47979d9))
- **lights:** auto adjust min and max mireds when value is out of bounds ([83a6fa0](https://github.com/t0bst4r/home-assistant-matter-hub/commit/83a6fa0))
- **thermostat:** consider the default unit of measurements from home assistant for temperatures ([e9aeb1a](https://github.com/t0bst4r/home-assistant-matter-hub/commit/e9aeb1a))

### ❤️ Thank You

- Tobias Glatthar @t0bst4r

## 3.0.0-alpha.57 (2024-12-20)

### 🚀 Features

- ⚠️  Taking a Holiday Break – See You in the New Year! ([86bea0a](https://github.com/t0bst4r/home-assistant-matter-hub/commit/86bea0a))

### 🩹 Fixes

- **light:** allow adjusting min and max level if value is out of bounds ([a95dbda](https://github.com/t0bst4r/home-assistant-matter-hub/commit/a95dbda))
- **script, automation, scene:** explicit call the right commands to activate scripts, automations, and scenes ([66f41cd](https://github.com/t0bst4r/home-assistant-matter-hub/commit/66f41cd))

### ⚠️  Breaking Changes

- As the holiday season approaches and my main job keeps me busy, I haven’t been able to dedicate as much time to this project as I’d like. Over the holidays, I’ll be taking a well-deserved break to recharge. That said, if an opportunity arises, I’ll try to answer a few questions or review a pull request via my phone. I’m looking forward to returning refreshed and motivated in the new year. Thank you for your understanding and continued support! Happy holidays!

### ❤️ Thank You

- Tobias Glatthar @t0bst4r

## 3.0.0-alpha.56 (2024-12-19)

### 🚀 Features

- allow include and exclude by area ([a3ef4a6](https://github.com/t0bst4r/home-assistant-matter-hub/commit/a3ef4a6))
- **basic-information:** add serial number to devices ([7c37dc1](https://github.com/t0bst4r/home-assistant-matter-hub/commit/7c37dc1))
- **input_button:** add support for input_button entities ([7b38ad9](https://github.com/t0bst4r/home-assistant-matter-hub/commit/7b38ad9))

### 🩹 Fixes

- **lights:** enable features for on/off and level control ([e89cb67](https://github.com/t0bst4r/home-assistant-matter-hub/commit/e89cb67))
- **on-off:** allow sending on and off commands, when already on or off ([898ba0d](https://github.com/t0bst4r/home-assistant-matter-hub/commit/898ba0d))

### ❤️ Thank You

- Timo Christeleit
- Tobias Glatthar @t0bst4r

## 3.0.0-alpha.55 (2024-12-15)

### 🩹 Fixes

- add debug logging when home assistant actions fail ([d77826e](https://github.com/t0bst4r/home-assistant-matter-hub/commit/d77826e))
- ⚠️  **thermostat:** refactor how states are synchronized ([551da69](https://github.com/t0bst4r/home-assistant-matter-hub/commit/551da69))

### ⚠️  Breaking Changes

- **thermostat:** Auto mode from Home Assistant is no longer supported for climates / thermostats. It just doesn't fit into the Matter specification.

### ❤️ Thank You

- Tobias Glatthar @t0bst4r

## 3.0.0-alpha.54 (2024-12-09)

### 🩹 Fixes

- **fan-control:** always set fan mode sequence ([57803ca](https://github.com/t0bst4r/home-assistant-matter-hub/commit/57803ca))

### ❤️ Thank You

- Tobias Glatthar @t0bst4r

## 3.0.0-alpha.53 (2024-12-09)

### 🚀 Features

- **fan-control:** Implement fan control cluster ([#258](https://github.com/t0bst4r/home-assistant-matter-hub/pull/258))

### ❤️ Thank You

- Kenny Levinsen @kennylevinsen

## 3.0.0-alpha.52 (2024-12-07)

### 🩹 Fixes

- **basic-information:** add vendor id and names to all devices ([d3e4703](https://github.com/t0bst4r/home-assistant-matter-hub/commit/d3e4703))
- **thermostat:** set thermostatRunningState more explicit ([8617c88](https://github.com/t0bst4r/home-assistant-matter-hub/commit/8617c88))

### ❤️ Thank You

- Tobias Glatthar @t0bst4r

## 3.0.0-alpha.51 (2024-12-04)

### 🩹 Fixes

- **color-control:** Propagate colorMode ([ce5ced4](https://github.com/t0bst4r/home-assistant-matter-hub/commit/ce5ced4))
- **frontend:** Add second Samsung vendor ID ([#256](https://github.com/t0bst4r/home-assistant-matter-hub/pull/256))
- **thermostat:** Compare setpoint with target temperature ([#254](https://github.com/t0bst4r/home-assistant-matter-hub/pull/254))
- **thermostat:** Skip temp commands if state is unavailable ([#255](https://github.com/t0bst4r/home-assistant-matter-hub/pull/255))

### ❤️ Thank You

- Kenny Levinsen @kennylevinsen

## 3.0.0-alpha.50 (2024-12-03)

### 🚀 Features

- **frontend:** add details how to connect multiple fabrics ([1b717ac](https://github.com/t0bst4r/home-assistant-matter-hub/commit/1b717ac))

### 🩹 Fixes

- **frontend:** add explicit main page to not prevent history-back ([ed13eb8](https://github.com/t0bst4r/home-assistant-matter-hub/commit/ed13eb8))
- **matter:** finish transaction before calling home assistant services ([f66372c](https://github.com/t0bst4r/home-assistant-matter-hub/commit/f66372c))

### ❤️ Thank You

- Tobias Glatthar @t0bst4r

## 3.0.0-alpha.49 (2024-11-30)

### 🚀 Features

- **frontend:** replace brand icons and add samsung ([b3991e2](https://github.com/t0bst4r/home-assistant-matter-hub/commit/b3991e2))

### 🩹 Fixes

- **deps:** update matter.js to v0.11.8 ([8fe9509](https://github.com/t0bst4r/home-assistant-matter-hub/commit/8fe9509))
- **frontend:** Add Amazon and Apple vendor IDs ([a244855](https://github.com/t0bst4r/home-assistant-matter-hub/commit/a244855))
- **lights:** preserve last level control state ([6991d9b](https://github.com/t0bst4r/home-assistant-matter-hub/commit/6991d9b))

### ❤️ Thank You

- Kenny Levinsen @kennylevinsen
- Tobias Glatthar @t0bst4r

## 3.0.0-alpha.48 (2024-11-30)

### 🩹 Fixes

- **cover:** add AbsolutePosition feature to position aware covers and fake PositionAware feature for non position aware covers ([7fb8a01](https://github.com/t0bst4r/home-assistant-matter-hub/commit/7fb8a01))
- **docker:** remove environment variables from dockerfile ([24adece](https://github.com/t0bst4r/home-assistant-matter-hub/commit/24adece))

### ❤️ Thank You

- Tobias Glatthar @t0bst4r

## 3.0.0-alpha.47 (2024-11-30)

### 🚀 Features

- ⚠️  add IP whitelisting to prevent unauthorized access ([916b3ae](https://github.com/t0bst4r/home-assistant-matter-hub/commit/916b3ae))

### ⚠️  Breaking Changes

- The native addon (HAOS) will use Home Assistant ingress from now on. Direct access via the port will no longer be possible.

### ❤️ Thank You

- Tobias Glatthar @t0bst4r

## 3.0.0-alpha.46 (2024-11-30)

### 🚀 Features

- adjust proxy request handling and update documentation ([f6bdd20](https://github.com/t0bst4r/home-assistant-matter-hub/commit/f6bdd20))

### ❤️ Thank You

- Tobias Glatthar @t0bst4r

## 3.0.0-alpha.45 (2024-11-29)

### 🩹 Fixes

- **frontend:** adjust base url to prevent broken urls ([370d25b](https://github.com/t0bst4r/home-assistant-matter-hub/commit/370d25b))

### ❤️ Thank You

- Tobias Glatthar @t0bst4r

## 3.0.0-alpha.44 (2024-11-29)

### 🚀 Features

- add base url and proxy detection ([bbce762](https://github.com/t0bst4r/home-assistant-matter-hub/commit/bbce762))
- **cli:** allow explicit whitelisting of ip addresses for http ([dee117e](https://github.com/t0bst4r/home-assistant-matter-hub/commit/dee117e))

### 🩹 Fixes

- prevent edge cases where storage gets deleted ([3bdc6ee](https://github.com/t0bst4r/home-assistant-matter-hub/commit/3bdc6ee))
- built clean update mechanism to prevent devices to get re-created ([26dc0be](https://github.com/t0bst4r/home-assistant-matter-hub/commit/26dc0be))
- **frontend:** add base to index.html ([75137fe](https://github.com/t0bst4r/home-assistant-matter-hub/commit/75137fe))

### ❤️ Thank You

- Tobias Glatthar @t0bst4r

## 3.0.0-alpha.43 (2024-11-28)

### 🩹 Fixes

- **scene:** default to off state to be able to turn it on ([1af9513](https://github.com/t0bst4r/home-assistant-matter-hub/commit/1af9513))

### ❤️ Thank You

- Tobias Glatthar @t0bst4r

## 3.0.0-alpha.42 (2024-11-28)

### 🚀 Features

- **frontend:** New form-based bridge configuration ([#197](https://github.com/t0bst4r/home-assistant-matter-hub/pull/197))
- **media_player:** expose media_player as speaker device if feature flag is activated ([#156](https://github.com/t0bst4r/home-assistant-matter-hub/pull/156))

### 🩹 Fixes

- prevent race conditions when home assistant responds faster than matter ([#211](https://github.com/t0bst4r/home-assistant-matter-hub/pull/211))
- **frontend:** add copy-to-clipboard action to cluster states ([f79ef69](https://github.com/t0bst4r/home-assistant-matter-hub/commit/f79ef69))

### ❤️ Thank You

- adrisg
- Kenny Levinsen @kennylevinsen
- Maxime Flamant @maximeflamant
- Tobias Glatthar @t0bst4r

## 3.0.0-alpha.41 (2024-11-27)

### 🚀 Features

- add a customized app logo ([#202](https://github.com/t0bst4r/home-assistant-matter-hub/pull/202))
- **frontend:** add app logo to header ([f9d8021](https://github.com/t0bst4r/home-assistant-matter-hub/commit/f9d8021))

### 🩹 Fixes

- add more details when home assistant connection fails ([963d3b2](https://github.com/t0bst4r/home-assistant-matter-hub/commit/963d3b2))
- **frontend:** add margin to the commissioning qr-code ([#198](https://github.com/t0bst4r/home-assistant-matter-hub/pull/198))

### ❤️ Thank You

- adrisg
- Tobias Glatthar @t0bst4r

## 3.0.0-alpha.40 (2024-11-23)

### 🩹 Fixes

- trigger new release ([d00b83f](https://github.com/t0bst4r/home-assistant-matter-hub/commit/d00b83f))
- revert matter.js and cleanup dependencies ([89507ce](https://github.com/t0bst4r/home-assistant-matter-hub/commit/89507ce))

### ❤️  Thank You

- t0bst4r @t0bst4r

## 3.0.0-alpha.39 (2024-11-23)

### 🩹 Fixes

- revert matter.js to 0.11.5-alpha.0-20241121-c31bc6998 ([a52a66e](https://github.com/t0bst4r/home-assistant-matter-hub/commit/a52a66e))

### ❤️  Thank You

- t0bst4r @t0bst4r

## 3.0.0-alpha.38 (2024-11-23)

### 🩹 Fixes

- only hash labels larger than max length ([3e71fb3](https://github.com/t0bst4r/home-assistant-matter-hub/commit/3e71fb3))
- change fallthrough matcher after migrating to express@5 ([620eddd](https://github.com/t0bst4r/home-assistant-matter-hub/commit/620eddd))
- **cover:** remove absolute position and add operational status ([5e37273](https://github.com/t0bst4r/home-assistant-matter-hub/commit/5e37273))

### ❤️  Thank You

- Avi Miller @Djelibeybi
- t0bst4r @t0bst4r

## 3.0.0-alpha.37 (2024-11-22)

### 🚀 Features

- prepare configurations per domainm, entity and compatibility mode ([cb0b599](https://github.com/t0bst4r/home-assistant-matter-hub/commit/cb0b599))
- **nx-cloud:** setup nx cloud workspace ([2919527](https://github.com/t0bst4r/home-assistant-matter-hub/commit/2919527))

### 🩹 Fixes

- **climate:** do not set the target position when device is off ([b828295](https://github.com/t0bst4r/home-assistant-matter-hub/commit/b828295))
- **climate:** only add humidity sensor if available at all ([948a34a](https://github.com/t0bst4r/home-assistant-matter-hub/commit/948a34a))
- **deps:** update dependency ajv to v8 ([e73e5c5](https://github.com/t0bst4r/home-assistant-matter-hub/commit/e73e5c5))

### ❤️  Thank You

- t0bst4r @t0bst4r
- Tobias Glatthar @t0bst4r

## 3.0.0-alpha.36 (2024-11-16)

### 🩹 Fixes

- **binary_sensor:** made config of boolean state cluster optional ([0710d89](https://github.com/t0bst4r/home-assistant-matter-hub/commit/0710d89))

### ❤️  Thank You

- Tobias Glatthar @t0bst4r

## 3.0.0-alpha.35 (2024-11-16)

### 🚀 Features

- **binary_sensor:** add support for water leak detector ([2f8707a](https://github.com/t0bst4r/home-assistant-matter-hub/commit/2f8707a))

### 🩹 Fixes

- **ci:** add repository to repository_dispatch ([28d34b0](https://github.com/t0bst4r/home-assistant-matter-hub/commit/28d34b0))
- **cover:** remove unallowed properties from covers without positions ([241206c](https://github.com/t0bst4r/home-assistant-matter-hub/commit/241206c))

### ❤️  Thank You

- t0bst4r @t0bst4r

## 3.0.0-alpha.34 (2024-11-16)

### 🚀 Features

- **humidifer:** add support for humidifiers mapped to PlugInUnits ([dd7fe69](https://github.com/t0bst4r/home-assistant-matter-hub/commit/dd7fe69))
- **media_player:** add support for media_players as OnOffPluginUnits ([59f081c](https://github.com/t0bst4r/home-assistant-matter-hub/commit/59f081c))

### 🩹 Fixes

- **ci:** automatic releases for the addon repository including changelog ([4559883](https://github.com/t0bst4r/home-assistant-matter-hub/commit/4559883))
- **cover:** allow covers to be not position aware ([7af0298](https://github.com/t0bst4r/home-assistant-matter-hub/commit/7af0298))

### ❤️  Thank You

- t0bst4r @t0bst4r

## 3.0.0-alpha.33 (2024-11-16)

### 🩹 Fixes

- **climate:** remove optional temperature cluster ([#147](https://github.com/t0bst4r/home-assistant-matter-hub/pull/147))
- **cover:** do not use configStatus to control lift directions ([de7aae8](https://github.com/t0bst4r/home-assistant-matter-hub/commit/de7aae8))

### ❤️  Thank You

- Guillaume S @KipK
- t0bst4r @t0bst4r

## 3.0.0-alpha.32 (2024-11-15)

### 🩹 Fixes

- **lights:** remove old and wrong properties from lights ([0c02a6c](https://github.com/t0bst4r/home-assistant-matter-hub/commit/0c02a6c))

### ❤️  Thank You

- t0bst4r @t0bst4r

## 3.0.0-alpha.31 (2024-11-14)

### 🩹 Fixes

- disable matter environment parsing ([effe5a4](https://github.com/t0bst4r/home-assistant-matter-hub/commit/effe5a4))
- **light:** default hue and saturation to 0 when not available ([306bf5a](https://github.com/t0bst4r/home-assistant-matter-hub/commit/306bf5a))

### ❤️  Thank You

- t0bst4r @t0bst4r

## 3.0.0-alpha.30 (2024-11-14)

### 🩹 Fixes

- minor patch in state management ([cb7607e](https://github.com/t0bst4r/home-assistant-matter-hub/commit/cb7607e))

### ❤️  Thank You

- t0bst4r @t0bst4r

## 3.0.0-alpha.29 (2024-11-14)

### 🩹 Fixes

- refactor all clusters to use reactTo and pessimistic state changes ([cd00915](https://github.com/t0bst4r/home-assistant-matter-hub/commit/cd00915))

### ❤️  Thank You

- t0bst4r @t0bst4r

## 3.0.0-alpha.28 (2024-11-12)

### 🩹 Fixes

- another try to properly react to state events ([04ba690](https://github.com/t0bst4r/home-assistant-matter-hub/commit/04ba690))

### ❤️  Thank You

- t0bst4r @t0bst4r

## 3.0.0-alpha.27 (2024-11-12)

### 🚀 Features

- **basicInformation:** add change detection and reachable check to all devices ([d48c9b6](https://github.com/t0bst4r/home-assistant-matter-hub/commit/d48c9b6))
- **cli:** added a config-option to provide a configuration file instead of CLI arguments ([b5325d6](https://github.com/t0bst4r/home-assistant-matter-hub/commit/b5325d6))

### 🩹 Fixes

- **basicInformation:** reduce the hash for long names to 4 chars ([1212ad3](https://github.com/t0bst4r/home-assistant-matter-hub/commit/1212ad3))
- **basicInformation:** use the entity_id as name, if name is missing ([d4baf5c](https://github.com/t0bst4r/home-assistant-matter-hub/commit/d4baf5c))

### ❤️  Thank You

- t0bst4r @t0bst4r

## 3.0.0-alpha.26 (2024-11-10)

### 🩹 Fixes

- **climate:** use entity state value as fallback for all status reports ([20483e8](https://github.com/t0bst4r/home-assistant-matter-hub/commit/20483e8))

### ❤️  Thank You

- t0bst4r @t0bst4r

## 3.0.0-alpha.25 (2024-11-10)

### 🩹 Fixes

- **bridge:** enable flex wrapping for filter chips in BridgeDetails ([#95](https://github.com/t0bst4r/home-assistant-matter-hub/pull/95))
- **climate:** map all neccessary properties from climate to thermostat ([72ab81e](https://github.com/t0bst4r/home-assistant-matter-hub/commit/72ab81e))
- **light:** only round min and max values properly ([50394f6](https://github.com/t0bst4r/home-assistant-matter-hub/commit/50394f6))
- **sensor:** fix temperature conversion ([59c17d8](https://github.com/t0bst4r/home-assistant-matter-hub/commit/59c17d8))

### ❤️  Thank You

- Jeroen Hof @Metal-Eagle
- t0bst4r @t0bst4r

## 3.0.0-alpha.24 (2024-11-09)

### 🚀 Features

- **climate:** add thermostatRunningMode only for autoMode ([c928ca5](https://github.com/t0bst4r/home-assistant-matter-hub/commit/c928ca5))

### ❤️  Thank You

- t0bst4r @t0bst4r

## 3.0.0-alpha.23 (2024-11-09)

### 🚀 Features

- **climate:** add temperature measurement and humidity sensor ([3b44979](https://github.com/t0bst4r/home-assistant-matter-hub/commit/3b44979))

### 🩹 Fixes

- refactor thermostat server to a single behavior with feature flags ([a939600](https://github.com/t0bst4r/home-assistant-matter-hub/commit/a939600))
- **light:** round values after converting kelvin and mireds ([e4ad137](https://github.com/t0bst4r/home-assistant-matter-hub/commit/e4ad137))

### ❤️  Thank You

- t0bst4r @t0bst4r

## 3.0.0-alpha.22 (2024-11-08)

### 🩹 Fixes

- **binary_sensor:** safe access the config from the state ([b703cc7](https://github.com/t0bst4r/home-assistant-matter-hub/commit/b703cc7))
- **ci:** remove typo which prevented the release workflow ([7330d8d](https://github.com/t0bst4r/home-assistant-matter-hub/commit/7330d8d))
- **deps:** update all npm dependencies ([690abbc](https://github.com/t0bst4r/home-assistant-matter-hub/commit/690abbc))

### ❤️  Thank You

- t0bst4r @t0bst4r

## 3.0.0-alpha.21 (2024-11-07)

### 🩹 Fixes

- prevent bridge edit screen from automatically changing the port ([415fada](https://github.com/t0bst4r/home-assistant-matter-hub/commit/415fada))

### ❤️  Thank You

- t0bst4r @t0bst4r

## 3.0.0-alpha.20 (2024-11-07)

### 🚀 Features

- extracted bridge creation to it's own page, allow editing an existing bridge ([38287af](https://github.com/t0bst4r/home-assistant-matter-hub/commit/38287af))

### ❤️  Thank You

- t0bst4r @t0bst4r

## 3.0.0-alpha.19 (2024-11-06)

### 🩹 Fixes

- add silly logs for entity exclusion ([e635f91](https://github.com/t0bst4r/home-assistant-matter-hub/commit/e635f91))

### ❤️  Thank You

- t0bst4r @t0bst4r

## 3.0.0-alpha.18 (2024-11-05)

### 🚀 Features

- use custom homeAssistantBehavior for better state management ([6e0f862](https://github.com/t0bst4r/home-assistant-matter-hub/commit/6e0f862))

### ❤️  Thank You

- t0bst4r @t0bst4r

## 3.0.0-alpha.17 (2024-11-03)

### 🩹 Fixes

- **climate:** use cooling and heating together with auto mode ([6193a40](https://github.com/t0bst4r/home-assistant-matter-hub/commit/6193a40))

### ❤️  Thank You

- t0bst4r @t0bst4r

## 3.0.0-alpha.16 (2024-11-03)

### 🩹 Fixes

- add hash to state subscription to prevent reuses when entity filter is changed ([1162dce](https://github.com/t0bst4r/home-assistant-matter-hub/commit/1162dce))
- **climate:** allow auto-mode only ([7bb1f68](https://github.com/t0bst4r/home-assistant-matter-hub/commit/7bb1f68))

### ❤️  Thank You

- t0bst4r @t0bst4r

## 3.0.0-alpha.15 (2024-11-01)

### 🩹 Fixes

- **level-control:** configure minimal transition time ([e754974](https://github.com/t0bst4r/home-assistant-matter-hub/commit/e754974))

### ❤️  Thank You

- t0bst4r @t0bst4r

## 3.0.0-alpha.14 (2024-11-01)

### 🩹 Fixes

- **light:** use correct device type for color temp only devices ([4b57edf](https://github.com/t0bst4r/home-assistant-matter-hub/commit/4b57edf))
- **light:** do not set out-of-bounds color temperatures ([a22ae25](https://github.com/t0bst4r/home-assistant-matter-hub/commit/a22ae25))

### ❤️  Thank You

- t0bst4r @t0bst4r

## 3.0.0-alpha.13 (2024-11-01)

### 🩹 Fixes

- implement moveToLevelWithOnOff for all levelControls ([93ab431](https://github.com/t0bst4r/home-assistant-matter-hub/commit/93ab431))

### ❤️  Thank You

- t0bst4r @t0bst4r

## 3.0.0-alpha.12 (2024-10-31)

### 🚀 Features

- allow configuring the mdns-interface ([441c99b](https://github.com/t0bst4r/home-assistant-matter-hub/commit/441c99b))
- show version number in app title ([70bdca8](https://github.com/t0bst4r/home-assistant-matter-hub/commit/70bdca8))

### 🩹 Fixes

- add explicit icon for google vendor id ([0afbd42](https://github.com/t0bst4r/home-assistant-matter-hub/commit/0afbd42))

### ❤️  Thank You

- t0bst4r @t0bst4r

## 3.0.0-alpha.11 (2024-10-29)

### 🩹 Fixes

- support pattern matching ([8107a8b](https://github.com/t0bst4r/home-assistant-matter-hub/commit/8107a8b))
- **light:** add fallback-transition time to level- and color-control ([b0ed5a8](https://github.com/t0bst4r/home-assistant-matter-hub/commit/b0ed5a8))

### ❤️  Thank You

- t0bst4r @t0bst4r

## 3.0.0-alpha.10 (2024-10-29)

### 🩹 Fixes

- ignore entities by their hidden and disabled state ([9e7b641](https://github.com/t0bst4r/home-assistant-matter-hub/commit/9e7b641))

### ❤️  Thank You

- t0bst4r @t0bst4r

## 3.0.0-alpha.9 (2024-10-29)

### 🚀 Features

- add support for input_boolean, scene, automation, script ([e63a955](https://github.com/t0bst4r/home-assistant-matter-hub/commit/e63a955))

### 🩹 Fixes

- add fallback mechanism for empty json files ([035a0bd](https://github.com/t0bst4r/home-assistant-matter-hub/commit/035a0bd))
- remove all entities which don't have a state ([cb7b76c](https://github.com/t0bst4r/home-assistant-matter-hub/commit/cb7b76c))
- **climate:** set controlSequenceOfOperation as a required property ([4816273](https://github.com/t0bst4r/home-assistant-matter-hub/commit/4816273))

### ❤️  Thank You

- t0bst4r @t0bst4r

## 3.0.0-alpha.8 (2024-10-28)

### 🩹 Fixes

- **basic-information:** consider maxLength of device properties ([627aea5](https://github.com/t0bst4r/home-assistant-matter-hub/commit/627aea5))

### ❤️  Thank You

- t0bst4r @t0bst4r

## 3.0.0-alpha.7 (2024-10-27)

### 🩹 Fixes

- add more configuration details ([7c95b3c](https://github.com/t0bst4r/home-assistant-matter-hub/commit/7c95b3c))

### ❤️  Thank You

- t0bst4r @t0bst4r

## 3.0.0-alpha.6 (2024-10-27)

### 🩹 Fixes

- use fallback dirname for node:18 ([bbe0903](https://github.com/t0bst4r/home-assistant-matter-hub/commit/bbe0903))

### ❤️  Thank You

- t0bst4r @t0bst4r

## 3.0.0-alpha.5 (2024-10-27)

### 🩹 Fixes

- add missing token to generate github releases ([dd3479f](https://github.com/t0bst4r/home-assistant-matter-hub/commit/dd3479f))

### ❤️  Thank You

- t0bst4r @t0bst4r

## 3.0.0-alpha.4 (2024-10-27)

### 🩹 Fixes

- remove first-release flag ([3b90bfe](https://github.com/t0bst4r/home-assistant-matter-hub/commit/3b90bfe))

### ❤️  Thank You

- t0bst4r @t0bst4r

## 3.0.0-alpha.3 (2024-10-27)

### 🩹 Fixes

- **docs:** change the addon repository to be added in home assistant ([4aedf2e](https://github.com/t0bst4r/home-assistant-matter-hub/commit/4aedf2e))

### ❤️  Thank You

- t0bst4r @t0bst4r

## 3.0.0-alpha.2 (2024-10-27)

### 🚀 Features

- project setup and complete migration ([51301ac](https://github.com/t0bst4r/home-assistant-matter-hub/commit/51301ac))

### ❤️  Thank You

- t0bst4r @t0bst4r