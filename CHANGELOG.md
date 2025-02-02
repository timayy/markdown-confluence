# Changelog

## [4.9.0](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v4.8.0...obsidian-confluence-root-v4.9.0) (2023-04-30)


### Features

* Add support for "index.md" as a folder file ([f598074](https://github.com/markdown-confluence/markdown-confluence/commit/f5980740cb99f0fa04cd0c66c6f5dba6ea78c288))


### Bug Fixes

* Bash to shell language map ([28ae75e](https://github.com/markdown-confluence/markdown-confluence/commit/28ae75ed118d86841a00797d6f1bd12225551cc3))

## [4.8.0](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v4.7.5...obsidian-confluence-root-v4.8.0) (2023-04-30)


### Features

* Add new setting to allow you to use the first heading as the page title. ([ec4e426](https://github.com/markdown-confluence/markdown-confluence/commit/ec4e426700d241c29f84ac25b28893f28f20a555))

## [4.7.5](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v4.7.4...obsidian-confluence-root-v4.7.5) (2023-04-30)


### Bug Fixes

* Handle #hash links better for names that have spaces and handle internal links ([7ad345a](https://github.com/markdown-confluence/markdown-confluence/commit/7ad345af210e346517535faa7a08d801b1660ded))

## [4.7.4](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v4.7.3...obsidian-confluence-root-v4.7.4) (2023-04-29)


### Bug Fixes

* Check for duplicate page titles not file names. ([540b1f9](https://github.com/markdown-confluence/markdown-confluence/commit/540b1f93cd20784f9c7c8f14895221667fe5f3f5))

## [4.7.3](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v4.7.2...obsidian-confluence-root-v4.7.3) (2023-04-29)


### Bug Fixes

* Replace spaces in hashFragment not linkToPage ([ed446e8](https://github.com/markdown-confluence/markdown-confluence/commit/ed446e87a1a12d7014efeff37ae39e161b558e0c))

## [4.7.2](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v4.7.1...obsidian-confluence-root-v4.7.2) (2023-04-28)


### Bug Fixes

* Don't specify default for contentRoot on CommandLineArgumentSettingsLoader. ([ec8c338](https://github.com/markdown-confluence/markdown-confluence/commit/ec8c3387dc4d324acf49853917f5ee8c95442e7e))

## [4.7.1](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v4.7.0...obsidian-confluence-root-v4.7.1) (2023-04-28)


### Bug Fixes

* Update the common path to include parent ([076effd](https://github.com/markdown-confluence/markdown-confluence/commit/076effdab718709df8c0a57faca917d3d152a41b))

## [4.7.0](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v4.6.4...obsidian-confluence-root-v4.7.0) (2023-04-28)


### Features

* Add links to updated pages on Completed Dialog ([65c1a42](https://github.com/markdown-confluence/markdown-confluence/commit/65c1a42b7b039512d5582b055f8adfb4f25333c8))


### Bug Fixes

* fmt ([91ff4e9](https://github.com/markdown-confluence/markdown-confluence/commit/91ff4e99135b90709ab3f185873b98ce94eb7242))
* Replace spaces with `-` to match what confluence uses. ([92b9d2d](https://github.com/markdown-confluence/markdown-confluence/commit/92b9d2d9266ac777cc8ae4cbcd665f591a17b636))
* Wrap check for file in try catch to report the errors better ([3fabce0](https://github.com/markdown-confluence/markdown-confluence/commit/3fabce0fb09573106552a37586bc1caf3883da6a))


### Documentation

* Update repo and org names to match new names ([404a85b](https://github.com/markdown-confluence/markdown-confluence/commit/404a85b206704873d57c233131ba4f564c4ccd86))

## [4.6.4](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v4.6.3...obsidian-confluence-root-v4.6.4) (2023-04-28)


### Bug Fixes

* Don't load settings when first initialising Publisher. Fixes issue when no settings available in set up situation. ([ceb21e7](https://github.com/markdown-confluence/markdown-confluence/commit/ceb21e7c193752394003545438d583323c0bccc6))
* My bad ([1acc9b8](https://github.com/markdown-confluence/markdown-confluence/commit/1acc9b8303948da962b0da614d74f8daf67eabff))
* Remove debug console.logs ([f89e617](https://github.com/markdown-confluence/markdown-confluence/commit/f89e6178f63e42a85c0e25bfe180fea270b82bba))

## [4.6.3](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v4.6.2...obsidian-confluence-root-v4.6.3) (2023-04-28)


### Bug Fixes

* Wrong Ordering of AutoSettingsLoader Loaders ([4b1dc22](https://github.com/markdown-confluence/markdown-confluence/commit/4b1dc22895001646b638997536706053bda7cbf2))

## [4.6.2](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v4.6.1...obsidian-confluence-root-v4.6.2) (2023-04-28)


### Bug Fixes

* More debugging ([215ff9b](https://github.com/markdown-confluence/markdown-confluence/commit/215ff9b619fa2adc2669a76c67a40ddb4f71fd93))

## [4.6.1](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v4.6.0...obsidian-confluence-root-v4.6.1) (2023-04-28)


### Bug Fixes

* Temp hack to show all files to be published ([d3539e9](https://github.com/markdown-confluence/markdown-confluence/commit/d3539e9e503d16dd8277847f28214d8a7552d51f))

## [4.6.0](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v4.5.0...obsidian-confluence-root-v4.6.0) (2023-04-28)


### Features

* Add "." option to folderToPublish to allow publishing whole contentRoot ([54c53ac](https://github.com/markdown-confluence/markdown-confluence/commit/54c53ac6860b06a3d3f8e8e278b01be5d3ea333c))

## [4.5.0](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v4.4.0...obsidian-confluence-root-v4.5.0) (2023-04-28)


### Features

* Enable SourceMaps in Docker ([5f13f52](https://github.com/markdown-confluence/markdown-confluence/commit/5f13f526ec1dc3326d3517a6080139d047c6e9ca))

## [4.4.0](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v4.3.0...obsidian-confluence-root-v4.4.0) (2023-04-27)


### Features

* Allow ConfigFile path to be provided as env var "CONFLUENCE_CONFIG_FILE" ([1311a93](https://github.com/markdown-confluence/markdown-confluence/commit/1311a930c09963f932146e482d444ea9df8bd553))

## [4.3.0](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v4.2.8...obsidian-confluence-root-v4.3.0) (2023-04-27)


### Features

* Allow setting content root for FilesystemAdaptor ([d008f29](https://github.com/markdown-confluence/markdown-confluence/commit/d008f294170561cec8ebfc7aa54352fb34c8cc44))


### Bug Fixes

* Add new projects to dependabot ([1d63186](https://github.com/markdown-confluence/markdown-confluence/commit/1d63186fb5de78b129fec7bc9b02b2ccdbc959ee))
* If environment variable is empty or "" then don't use. ([b0b7684](https://github.com/markdown-confluence/markdown-confluence/commit/b0b7684f42906710929833f5883aab31fefc8e10))
* Pin puppeteer Docker container ([d9d5f11](https://github.com/markdown-confluence/markdown-confluence/commit/d9d5f11516582ec80a51cf0f137ba30d0a15ef8e))
* Trim and add back the contentRoot ([c48a9c0](https://github.com/markdown-confluence/markdown-confluence/commit/c48a9c0171bf34655ac5b3826ae0b35fdb4085f1))


### Dependencies

* adf-utils for Obsidian ([3784f95](https://github.com/markdown-confluence/markdown-confluence/commit/3784f9536f642092330ca12f67fdf8047c7c88d3))
* **deps:** bump @atlaskit/adf-utils in /packages/lib ([3b5ae81](https://github.com/markdown-confluence/markdown-confluence/commit/3b5ae81d740f9519581e42b7e56896ad874bf7f2))
* **deps:** bump @atlaskit/editor-json-transformer from 8.8.3 to 8.8.4 ([b9a4496](https://github.com/markdown-confluence/markdown-confluence/commit/b9a4496c9963b8da44dc89a602865077fa912028))
* **deps:** bump @atlaskit/renderer from 107.3.2 to 107.3.3 ([252f911](https://github.com/markdown-confluence/markdown-confluence/commit/252f911d42bcdeee1febadfbd6e90e226416b990))
* **deps:** bump docker/build-push-action ([5c99424](https://github.com/markdown-confluence/markdown-confluence/commit/5c99424d647625c7ea5f6d16147b87584faa315b))
* **deps:** bump docker/login-action ([c7fde60](https://github.com/markdown-confluence/markdown-confluence/commit/c7fde60cd2ec87561cff55c155eb03789734ddf3))
* **deps:** bump docker/metadata-action ([289e598](https://github.com/markdown-confluence/markdown-confluence/commit/289e59832bfc2429a105f5ab23384cd54b294d3b))
* **deps:** bump github/codeql-action from 2.3.0 to 2.3.1 ([378c2b7](https://github.com/markdown-confluence/markdown-confluence/commit/378c2b74bc41794ab263d00fcef5f4a45d82908a))
* **deps:** bump puppeteer/puppeteer in /packages/cli ([07eeca7](https://github.com/markdown-confluence/markdown-confluence/commit/07eeca733ab5104397afcbe620015da91b13dfff))
* Update lint-staged to resolve vuln ([4ba7926](https://github.com/markdown-confluence/markdown-confluence/commit/4ba7926a1d8a8a3334eeabafcf6dac43ed39c37d))


### Documentation

* Add link direct to Report a vuln ([61ce80a](https://github.com/markdown-confluence/markdown-confluence/commit/61ce80a43356d5353b8a7705bd5bc6f026abc79d))
* Add Snyk badge ([15f8382](https://github.com/markdown-confluence/markdown-confluence/commit/15f8382e62c5bbfaccf51afc30ba76d3f5c1e758))
* Docs moved to https://github.com/markdown-confluence/docs-obsidian-confluence ([442d353](https://github.com/markdown-confluence/markdown-confluence/commit/442d3534b63c538c5a9ab2e8ab1a82e81717995d))
* Fix OpenSSF Scorecard Link ([16ca266](https://github.com/markdown-confluence/markdown-confluence/commit/16ca266abacc64dbb3eb33c716dcf33f1a65d4d1))

## [4.2.8](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v4.2.7...obsidian-confluence-root-v4.2.8) (2023-04-26)


### Bug Fixes

* Commit to the right repo ([1cf7b40](https://github.com/markdown-confluence/markdown-confluence/commit/1cf7b405a97156c611f00298e268994f677f75d2))

## [4.2.7](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v4.2.6...obsidian-confluence-root-v4.2.7) (2023-04-26)


### Bug Fixes

* Clean out obsidian-integration repo before copying in latest files ([02b3887](https://github.com/markdown-confluence/markdown-confluence/commit/02b38872133ddb685e804901b97adbaa20d4283f))

## [4.2.6](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v4.2.5...obsidian-confluence-root-v4.2.6) (2023-04-26)


### Bug Fixes

* Copy contents of obsidian folder not the folder as well ([abb3618](https://github.com/markdown-confluence/markdown-confluence/commit/abb361873c0793ff515837044a2e079be855f4b8))

## [4.2.5](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v4.2.4...obsidian-confluence-root-v4.2.5) (2023-04-26)


### Bug Fixes

* git add for all files ([614f13c](https://github.com/markdown-confluence/markdown-confluence/commit/614f13c0a74b750d76cd1f2a7b8374e84251b835))

## [4.2.4](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v4.2.3...obsidian-confluence-root-v4.2.4) (2023-04-26)


### Bug Fixes

* Include README for Obsidian repo and copy obsidian package source into repo to be stamped with release tag ([0ac4de3](https://github.com/markdown-confluence/markdown-confluence/commit/0ac4de3f2d37609c49dab043f47a51a83dd594f8))

## [4.2.3](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v4.2.2...obsidian-confluence-root-v4.2.3) (2023-04-26)


### Bug Fixes

* Bump version ([f22975a](https://github.com/markdown-confluence/markdown-confluence/commit/f22975a0899fa895b06f6ec3be6046d7958e08d5))

## [4.2.2](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v4.2.1...obsidian-confluence-root-v4.2.2) (2023-04-26)


### Bug Fixes

* Fix upload-release-assets.sh git config ([6ce1b84](https://github.com/markdown-confluence/markdown-confluence/commit/6ce1b84f0cd6544f0aac048e831fd822d236e321))
* Rename links to align with repo rename ([742e98c](https://github.com/markdown-confluence/markdown-confluence/commit/742e98c3b6d29caab074e7a09d744120069b2d99))

## [4.2.1](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v4.2.0...obsidian-confluence-root-v4.2.1) (2023-04-26)


### Bug Fixes

* Add new manifest.json to allow new commit for release to be tagged against ([f35d0a4](https://github.com/markdown-confluence/markdown-confluence/commit/f35d0a445531c413f52f40f7c57d2db80dd7c455))


### Dependencies

* **deps:** bump puppeteer from 19.11.0 to 19.11.1 ([2be4945](https://github.com/markdown-confluence/markdown-confluence/commit/2be4945c2682109f5742fdb8b8d5d3b32c7b0edc))

## [4.2.0](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v4.1.1...obsidian-confluence-root-v4.2.0) (2023-04-26)


### Features

* Update to publish to obsidian-integration repo ([c1b7b98](https://github.com/markdown-confluence/markdown-confluence/commit/c1b7b983c6aeb7773d2e5b2ff77857682b250a1b))

## [4.1.1](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v4.1.0...obsidian-confluence-root-v4.1.1) (2023-04-26)


### Bug Fixes

* Correct step name ([6721f30](https://github.com/markdown-confluence/markdown-confluence/commit/6721f30ebd1ea168642a88d5eb880cce25ff36a8))

## [4.1.0](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v4.0.4...obsidian-confluence-root-v4.1.0) (2023-04-26)


### Features

* Tag docker with extra tags for Major and Major.Minor ([6ef7b65](https://github.com/markdown-confluence/markdown-confluence/commit/6ef7b652105cc609d6023f8fa4243dade8d863a2))

## [4.0.4](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v4.0.3...obsidian-confluence-root-v4.0.4) (2023-04-26)


### Bug Fixes

* id not name ([b7d5797](https://github.com/markdown-confluence/markdown-confluence/commit/b7d579712f22ffecf9a634313823cd7f8659878c))
* Tag docker with correct version ([bb47286](https://github.com/markdown-confluence/markdown-confluence/commit/bb4728631adaf9196da793a7e8c23f658154cb90))

## [4.0.3](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v4.0.2...obsidian-confluence-root-v4.0.3) (2023-04-26)


### Bug Fixes

* Update Token to support packages ([73d3b54](https://github.com/markdown-confluence/markdown-confluence/commit/73d3b544781c927cf847dfe34e839201cb5b92d2))

## [4.0.2](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v4.0.1...obsidian-confluence-root-v4.0.2) (2023-04-26)


### Bug Fixes

* Missing components ([f495464](https://github.com/markdown-confluence/markdown-confluence/commit/f4954649b6e770940076e9c390e1c78e8e6a0083))

## [4.0.1](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v4.0.0...obsidian-confluence-root-v4.0.1) (2023-04-26)


### Bug Fixes

* Only build and release docker when release is created ([fe26002](https://github.com/markdown-confluence/markdown-confluence/commit/fe260026267fa1974b712bd425238c9e1b347766))
* package-lock.json out of date ([1468cb1](https://github.com/markdown-confluence/markdown-confluence/commit/1468cb1a28050808def376531a26c8fd9968ca9c))

## [4.0.0](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v3.7.0...obsidian-confluence-root-v4.0.0) (2023-04-26)


### ⚠ BREAKING CHANGES

* No longer bundling the lib package to help with tree shaking and code navigation

### Features

* Add docker CLI ([e8f930f](https://github.com/markdown-confluence/markdown-confluence/commit/e8f930fbeb612152cf19f5b387fb322b4c82bc5e))
* Initial CLI version ([85b4aff](https://github.com/markdown-confluence/markdown-confluence/commit/85b4aff13921accf6dd376e18929f3a19087757e))


### Bug Fixes

* Path in docs ([486bc74](https://github.com/markdown-confluence/markdown-confluence/commit/486bc74e11a0f1a1292933e0684a22288906d57d))


### Documentation

* Fix links on Thanks page ([96c4953](https://github.com/markdown-confluence/markdown-confluence/commit/96c4953f0251595ff17ec92f950bded255b0b0a1))


### Dependencies

* **deps:** bump github/codeql-action from 2.2.12 to 2.3.0 ([2c4d081](https://github.com/markdown-confluence/markdown-confluence/commit/2c4d081a3733ff527b993663662698cace53887f))

## [3.7.0](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v3.6.1...obsidian-confluence-root-v3.7.0) (2023-04-24)


### Features

* [StepSecurity] Apply security best practices ([#136](https://github.com/markdown-confluence/markdown-confluence/issues/136)) ([b7b38a4](https://github.com/markdown-confluence/markdown-confluence/commit/b7b38a42b2c21f91725f44f97ec1e98473e724a0))
* Add PAT for Branch Protection Check ([b44a52e](https://github.com/markdown-confluence/markdown-confluence/commit/b44a52e2ce41dc1c826957f9bad52b55a31d0ea0))
* Create CODEOWNERS ([a507ff9](https://github.com/markdown-confluence/markdown-confluence/commit/a507ff96284384720d826fbf2446e359517aedf6))
* Create SECURITY.md ([06f8ba7](https://github.com/markdown-confluence/markdown-confluence/commit/06f8ba7b9cdbc0938fd312609ed6e82877f108a4))
* Dependancy review comment with summary ([76597ac](https://github.com/markdown-confluence/markdown-confluence/commit/76597acd6bd883eec1dee87b9d490b0b462de095))
* Ignore comments when comparing pages to see if page has changed ([8cedbed](https://github.com/markdown-confluence/markdown-confluence/commit/8cedbedeaac229a2ceec31a11d7494c35845064b))
* Make ADF the same as what Confluence returns. ([a223c72](https://github.com/markdown-confluence/markdown-confluence/commit/a223c72057fe154f3a47916fb97e1c92830bdf7c))
* Map Inline Comments with best effort ([b1d8db3](https://github.com/markdown-confluence/markdown-confluence/commit/b1d8db3eb1d68ebc06c614052ea41693f47842e2))


### Bug Fixes

* Add category when uploading Sarif file ([3fb888b](https://github.com/markdown-confluence/markdown-confluence/commit/3fb888b9600aea095892c50dc210779df709c240))
* dependabot config to be consistent ([4933c62](https://github.com/markdown-confluence/markdown-confluence/commit/4933c6246e1db4c2996419ff3a1c8988667c9570))
* Fix permissions syntax ([b7e585b](https://github.com/markdown-confluence/markdown-confluence/commit/b7e585b5a46bb9bf8b2ca7af0bccdf1dff95063a))
* Ignore error under eslint due to not being an issue ([e784c6c](https://github.com/markdown-confluence/markdown-confluence/commit/e784c6ca1d2a6e2cae19c695cf8488ee60ce7056))
* Ignore vuln not being used ([619daca](https://github.com/markdown-confluence/markdown-confluence/commit/619daca0e1adb8c24f5768abf9f3c412757f6c8a))
* Root permissions all read as per https://github.com/ossf/scorecard/blob/376f465c111c39c6a5ad7408e8896cd790cb5219/docs/checks.md#token-permissions ([4560446](https://github.com/markdown-confluence/markdown-confluence/commit/45604462575d96e9ac085c15eb45c9207fd1c232))

## [3.6.1](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v3.6.0...obsidian-confluence-root-v3.6.1) (2023-04-21)


### Bug Fixes

* Upload the right signed file ([ef7b176](https://github.com/markdown-confluence/markdown-confluence/commit/ef7b17638f40c52e8cb23c4e09d538d2285ca1f3))

## [3.6.0](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v3.5.0...obsidian-confluence-root-v3.6.0) (2023-04-21)


### Features

* Add step-security/harden-runner to GHA ([f49c627](https://github.com/markdown-confluence/markdown-confluence/commit/f49c6273b984120ad53f8b32b28f47cc5cd65a73))


### Bug Fixes

* Upload release assets ([95b5c61](https://github.com/markdown-confluence/markdown-confluence/commit/95b5c61bf197441b556df630f3fc0837e9952ed4))

## [3.5.0](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v3.4.1...obsidian-confluence-root-v3.5.0) (2023-04-21)


### Features

* Add OSSF Badge to README.md ([b6f5bf2](https://github.com/markdown-confluence/markdown-confluence/commit/b6f5bf25295befee11e04362fd18d23a0d1350a5))
* Add OSSF Scorecard Scan ([f29c630](https://github.com/markdown-confluence/markdown-confluence/commit/f29c630fc361718ef02d675feb79be73cc034057))
* Add snyk monitor ([e829018](https://github.com/markdown-confluence/markdown-confluence/commit/e829018c728dbdaf68206a9292ee42c2ea689fa0))
* Custom ADF via Codeblock and adf language ([8e91630](https://github.com/markdown-confluence/markdown-confluence/commit/8e916307b14654da4bc54bc71579e2a0283b365f))
* Scan code with snyk ([#128](https://github.com/markdown-confluence/markdown-confluence/issues/128)) ([118e46a](https://github.com/markdown-confluence/markdown-confluence/commit/118e46ad413c9819d6c9f0f2076f9915a6667c80))
* Sign releases ([06ddd88](https://github.com/markdown-confluence/markdown-confluence/commit/06ddd887e493d00d7e009252334d194e9a6527fb))


### Bug Fixes

* Add GHA Perms ([#130](https://github.com/markdown-confluence/markdown-confluence/issues/130)) ([2e35b30](https://github.com/markdown-confluence/markdown-confluence/commit/2e35b30689b6b329585b0102ee4ddf1eafcd49dd))
* Add missing homepage and bugs to package.json ([c920345](https://github.com/markdown-confluence/markdown-confluence/commit/c92034563ce2f8d11a40ed2c68b104807eace3be))
* Add permissions to root of all workflows ([a430221](https://github.com/markdown-confluence/markdown-confluence/commit/a430221f89fb4af5290e5a54264375f59065dfb5))
* Fix .eslintrc to resolve CodeQL error ([f27dd85](https://github.com/markdown-confluence/markdown-confluence/commit/f27dd854e13a0af9b087fe6801bf070158141a96))
* Remove wrong switch ([6528836](https://github.com/markdown-confluence/markdown-confluence/commit/65288361aad87f1bd941fec58c227be49eb9dfd7))
* Run snyk on Dependabot PRs ([b16e2b1](https://github.com/markdown-confluence/markdown-confluence/commit/b16e2b1aeb28310b5ca0d15e260518eda7f3ff38))

## [3.4.1](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v3.4.0...obsidian-confluence-root-v3.4.1) (2023-04-20)


### Bug Fixes

* Add repository information for providence ([362e025](https://github.com/markdown-confluence/markdown-confluence/commit/362e0252bd24440f6311286e2b4446ffcf458dc4))

## [3.4.0](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v3.3.0...obsidian-confluence-root-v3.4.0) (2023-04-20)


### Features

* Add npm provenance ([ee76005](https://github.com/markdown-confluence/markdown-confluence/commit/ee760054c80d9e385f559c18111b379f30fd3da0))
* **blog:** Blog support. ([e0bdc24](https://github.com/markdown-confluence/markdown-confluence/commit/e0bdc248c9845f4a609f7d9f9c7de388ea183b12))
* Update Confluence Page Settings Command ([a7d395e](https://github.com/markdown-confluence/markdown-confluence/commit/a7d395e5a2ddc9323a683bc9c877f8878740422a))
* Write `connie-publish: true` to all files that have been published to ensure even if you move the files they still will be published. ([a7d395e](https://github.com/markdown-confluence/markdown-confluence/commit/a7d395e5a2ddc9323a683bc9c877f8878740422a))


### Dependencies

* Clean up mermaid-electron-renderer package.json ([8137934](https://github.com/markdown-confluence/markdown-confluence/commit/81379341178e28046174ceadcb74f271ac0dd10b))

## [3.3.0](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v3.2.0...obsidian-confluence-root-v3.3.0) (2023-04-18)


### Features

* Update a page when you are the last modifier ([5c42d77](https://github.com/markdown-confluence/markdown-confluence/commit/5c42d7787cf4c53098759ac221a81369e033df3d))


### Bug Fixes

* npm fmt ([206269c](https://github.com/markdown-confluence/markdown-confluence/commit/206269cc887eb75659dd77673318715eb3db1457))
* Updates requested https://github.com/obsidianmd/obsidian-releases/pull/1867#issuecomment-1512710718 ([47c4bf9](https://github.com/markdown-confluence/markdown-confluence/commit/47c4bf9d6ba2efb70e2ae62d59623f13f5db9183))

## [3.2.0](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v3.1.0...obsidian-confluence-root-v3.2.0) (2023-04-18)


### Features

* Publish `mermaid-electron-renderer` ([351d78d](https://github.com/markdown-confluence/markdown-confluence/commit/351d78d4cc9a9e06c2216a0dbfa60988bc76abf2))


### Bug Fixes

* Speed up builds ([fa77fc3](https://github.com/markdown-confluence/markdown-confluence/commit/fa77fc336032a761a760d30998939f052e815b5a))

## [3.1.0](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v3.0.2...obsidian-confluence-root-v3.1.0) (2023-04-18)


### Features

* Create manual release to align with Obsidian requirements ([a9b90e5](https://github.com/markdown-confluence/markdown-confluence/commit/a9b90e5cb1ad61fe56d33c5e8a6c0288c7f111a6))


### Bug Fixes

* Add manual component names ([9514e2f](https://github.com/markdown-confluence/markdown-confluence/commit/9514e2f9344dbf9cea866902226a85aab339a4d2))
* Bump version ([a798554](https://github.com/markdown-confluence/markdown-confluence/commit/a798554d470e880ab53f689412b0c6aeab269d2c))

## [3.0.2](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v3.0.1...obsidian-confluence-root-v3.0.2) (2023-04-18)


### Bug Fixes

* NPM Access to Public ([74be60d](https://github.com/markdown-confluence/markdown-confluence/commit/74be60d2db7eb106cb55202006b9afa1cb4fea2d))
* Start work towards manual release ([3439f99](https://github.com/markdown-confluence/markdown-confluence/commit/3439f997b0959a8471d224963fba8b650f6f529a))
* Test my local plugin ([c7f7d30](https://github.com/markdown-confluence/markdown-confluence/commit/c7f7d30a1b3b6b32774c61c55452c9da95d2ab17))

## [3.0.1](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v3.0.0...obsidian-confluence-root-v3.0.1) (2023-04-18)


### Bug Fixes

* noEmit for Obsidian package ([7a36a92](https://github.com/markdown-confluence/markdown-confluence/commit/7a36a924f8bd8b97b53d6bdaf8132e8f36191192))

## [3.0.0](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-root-v3.0.4...obsidian-confluence-root-v3.0.0) (2023-04-18)


### Features

* Add NPM publish after release is created ([2979a11](https://github.com/markdown-confluence/markdown-confluence/commit/2979a11507c140436ce0ca236e86aca70991bfb9))
* **AdfEqual:** Updates to make the ADF closer to what Confluence returns ([348f00e](https://github.com/markdown-confluence/markdown-confluence/commit/348f00e3d98bf6843f886310eeadf75ca86be1e3))
* **AdfPreview:** Make local files render correctly in ADF Preview ([860bfb8](https://github.com/markdown-confluence/markdown-confluence/commit/860bfb8e5cf1f094231abd2f4b4e7ae6bc91e7fd))
* **build:** Add `mermaidRendererPlugin.js` ([a64a176](https://github.com/markdown-confluence/markdown-confluence/commit/a64a1763c8c440e8d826b8f4a8bc6aa304eafc38))
* **build:** Minify outputs to save size in main.js file ([c879d5d](https://github.com/markdown-confluence/markdown-confluence/commit/c879d5ddb3f40376fea7b2ce903818865bcac175))
* **ci:** Add initial google-github-actions/release-please-action@v3 ([39cc200](https://github.com/markdown-confluence/markdown-confluence/commit/39cc2001113f6f846dddc56bc8ba75f5ff7ce026))
* **ci:** Export meta.json from esbuild ([c27ca7d](https://github.com/markdown-confluence/markdown-confluence/commit/c27ca7d67230a5aa051c94407a69745dbcf83f81))
* **eslint:** Add checks to GH Actions ([e786154](https://github.com/markdown-confluence/markdown-confluence/commit/e7861542f9dbe99bbc81bb0cecfee00f32ae5c5a))
* Include stats/expanded file names on publish ([d618b66](https://github.com/markdown-confluence/markdown-confluence/commit/d618b665521364ebfbea05a2713ff70f74630b91))
* Lots of changes to enable better testing ([0ce560c](https://github.com/markdown-confluence/markdown-confluence/commit/0ce560c3fb2c60edd4509d31ed99f52f500e2f13))
* **PageId:** Specify PageId when page published to Confluence ([c545009](https://github.com/markdown-confluence/markdown-confluence/commit/c5450092bb8abdf106d80d5a12b4a075dbd61130))
* **PublishDialog:** Add more detail to publish completed / failed dialog ([ddce9fc](https://github.com/markdown-confluence/markdown-confluence/commit/ddce9fc483edd724f608e0d37f62030588da1d09))
* **SinglePage:** Publish updates for 1 page only ([41e5ac4](https://github.com/markdown-confluence/markdown-confluence/commit/41e5ac4f6dee96fd51531fe6200c9f34dd571261))
* **tests:** Add initial unit tests and GH Actions to ensure they pass ([b7f636e](https://github.com/markdown-confluence/markdown-confluence/commit/b7f636e2fb8e8a99c06cd60d227e38ae9e8d2873))
* **Wikilinks:** First pass at supporting Wikilinks Syntax ([57e9f65](https://github.com/markdown-confluence/markdown-confluence/commit/57e9f65da1ddb4beb21d997bdf8652a6eed29720))
* **Wikilinks:** Support smart links and pages in multiple spaces ([20656f4](https://github.com/markdown-confluence/markdown-confluence/commit/20656f489d32a50ebd70587f25ca0d167c721cf0))


### Bug Fixes

* Add `@markdown-confluence/lib` to `markdown-electron-renderer` ([886556a](https://github.com/markdown-confluence/markdown-confluence/commit/886556abfb0c2f297c032577b9ce55ed89213d14))
* Add root component to `linked-versions` ([f2e1541](https://github.com/markdown-confluence/markdown-confluence/commit/f2e1541ed97292a13b4493c905fef89b69b140fc))
* Add version for root package ([afea12d](https://github.com/markdown-confluence/markdown-confluence/commit/afea12d202e15be39e89542c8cba8a58aaf952f3))
* Attempt 10,000 fixing releases ([60d875a](https://github.com/markdown-confluence/markdown-confluence/commit/60d875a134d16b2a7ef707d2ff4163657e27ad6a))
* Bump lib ([18c4d27](https://github.com/markdown-confluence/markdown-confluence/commit/18c4d27b07d21ed793bbb8492d83109afde1356d))
* Bump obsidian version ([c42e0d2](https://github.com/markdown-confluence/markdown-confluence/commit/c42e0d2335c52a4beddcb0273e17ad287b9166ea))
* Bump version I hope ([39b93eb](https://github.com/markdown-confluence/markdown-confluence/commit/39b93eba447f2a1f706ff6e65e7e8cabea08bf75))
* **ci:** Add support to bundle up files for plugin ([250984b](https://github.com/markdown-confluence/markdown-confluence/commit/250984b2baf462266d7cafc5a6eb7b82b0fd2dbb))
* **ci:** Fix errors ([ffeea5c](https://github.com/markdown-confluence/markdown-confluence/commit/ffeea5c80bde3c5674716059e450b8c6963f8e9d))
* **ci:** Learn to check ([a494231](https://github.com/markdown-confluence/markdown-confluence/commit/a494231840544e19cc8ac7bc090be6f327bc68dc))
* **ci:** List files uploaded to GitHub ([7612bcd](https://github.com/markdown-confluence/markdown-confluence/commit/7612bcd6b67c8ba712611e553dff985f8cae38bd))
* **ci:** Move manifest to root of repo to align with Obsidian requirements ([78d09e4](https://github.com/markdown-confluence/markdown-confluence/commit/78d09e43daad45aa0cf51f5f1ca874fa5b13e8e1))
* **ci:** Remove component from tag ([362b07e](https://github.com/markdown-confluence/markdown-confluence/commit/362b07e58af2420eb37a7fcabdfa1f9161a6c954))
* **ci:** Remove extra comment in manifest.json ([05d9657](https://github.com/markdown-confluence/markdown-confluence/commit/05d965738ac77b951acc39348bb7e4a64c627b1f))
* **ci:** Remove Sourcemap to save size ([0a1398b](https://github.com/markdown-confluence/markdown-confluence/commit/0a1398bb880c3201598ec860c68c1b82b016fa4a))
* **ci:** Remove v from github release ([3d3c07e](https://github.com/markdown-confluence/markdown-confluence/commit/3d3c07ef3b96c6f73561f5cd2aa0e44e7f6034c9))
* **ci:** Remove v from version number ([2a024bd](https://github.com/markdown-confluence/markdown-confluence/commit/2a024bdf2d640749561f41a24f79343005066d13))
* **ci:** Run Release Please via PAT to allow GHA checks to run ([adb0708](https://github.com/markdown-confluence/markdown-confluence/commit/adb07085f4bd026f994b5c8201abe0782e9b3828))
* **ci:** Use manifest over gh actions auto config ([3dc8d2b](https://github.com/markdown-confluence/markdown-confluence/commit/3dc8d2bbe5a25c844cda5c224ab0da7c465a5622))
* **cli:** Build error ([8d2698b](https://github.com/markdown-confluence/markdown-confluence/commit/8d2698b47c6244fe2304b44b78b557358dfe5797))
* Dir path for copy ([0f499da](https://github.com/markdown-confluence/markdown-confluence/commit/0f499dae4252a4053bde8de749ace04da69454dd))
* Don't publish till release created ([861ae0a](https://github.com/markdown-confluence/markdown-confluence/commit/861ae0a0b12e649c2b0385ea417cdda81e1eae82))
* Enable merge due to not having `linked-versions` ([8850884](https://github.com/markdown-confluence/markdown-confluence/commit/8850884803b8168de9031de1d09cb56da2e6c11e))
* **eslint:** Fix eslint issues ([cbaa567](https://github.com/markdown-confluence/markdown-confluence/commit/cbaa5671bb7e16c1b79b636cb06ed930298b29a6))
* Flip plugins order again ([3003b70](https://github.com/markdown-confluence/markdown-confluence/commit/3003b704f9378cf180aaaaabe95feba3ea740b22))
* Force rename mdToADF to MdToADF ([9d0d483](https://github.com/markdown-confluence/markdown-confluence/commit/9d0d4839b8540b423d794ab3d93d4ba071ede6dd))
* Group name ([cec80c5](https://github.com/markdown-confluence/markdown-confluence/commit/cec80c50da2432477e033f3635f8fb27de246245))
* **images:** Fix for image upload ([6b973f2](https://github.com/markdown-confluence/markdown-confluence/commit/6b973f2fc2a97b299c1abb61708407c097a80706))
* Manifest ([b87659e](https://github.com/markdown-confluence/markdown-confluence/commit/b87659e8c780a77092b0c5de616feda20f9dcefa))
* **Mermaid:** Remove extra console.log ([cfbddd5](https://github.com/markdown-confluence/markdown-confluence/commit/cfbddd531d4b79e3bd2447e39299db19b6393014))
* Move "." to the bottom ([e3a68ce](https://github.com/markdown-confluence/markdown-confluence/commit/e3a68cee680ac1f65f49577f537937a2ae502cfd))
* **Obsidian:** Update to match recommendations from https://github.com/obsidianmd/obsidian-releases/blob/master/plugin-review.md ([a038a46](https://github.com/markdown-confluence/markdown-confluence/commit/a038a46c08fb363d46a3f80ba431d165a507ca64))
* Only remove component from tag name for Obsidian ([84c6628](https://github.com/markdown-confluence/markdown-confluence/commit/84c662823f550906e7764127d8a3782cea308c43))
* **ReleasePlease:** Fix to use a different name for package due to the actual obsidian package ([3f94f7e](https://github.com/markdown-confluence/markdown-confluence/commit/3f94f7e15745139f7530ae1f86b0334f7d6ff184))
* Rename `MainSettingTab` to `ConfluenceSettingTab` ([29ef8f2](https://github.com/markdown-confluence/markdown-confluence/commit/29ef8f256305a13d520fc65c7a49064ed90aa296))
* Rename `MyPlugin` to `ConfluencePlugin` ([2298e27](https://github.com/markdown-confluence/markdown-confluence/commit/2298e2787b29c5ca9ce030cbd3bee7b8698326a6))
* Rename `MyPluginSettings` to `ConfluenceSettings` ([25bdb97](https://github.com/markdown-confluence/markdown-confluence/commit/25bdb97c85e79284c42bf89bd5b3a0cff1ebc10a))
* Rename frontmatter-to-publish to connie-frontmatter-to-publish ([d18d209](https://github.com/markdown-confluence/markdown-confluence/commit/d18d20998fdd686a2aefe2aefbda33a4c2b86341))
* **settings:** SaveSettings before Init ([64c4e41](https://github.com/markdown-confluence/markdown-confluence/commit/64c4e41565364525bfb2b53480630d30c875b91d))
* **stringifyObject:** Replacing stringify-object with JSON.stringify ([0297b44](https://github.com/markdown-confluence/markdown-confluence/commit/0297b44b42af151e88d9a942a814b6dffabe5f20))
* **test:** Extend test timeout ([ee38491](https://github.com/markdown-confluence/markdown-confluence/commit/ee38491e4bb3073890cf6d7650356c31bab03063))
* **test:** Fix snapshot test to test passing all tests ([8e26790](https://github.com/markdown-confluence/markdown-confluence/commit/8e26790ff219105ccfd54078239515164369b0b6))
* Try adding the component to PR title ([0b07269](https://github.com/markdown-confluence/markdown-confluence/commit/0b0726960a6771be367d897916eb0820f7dcb02d))
* Try reordering plugins ([42706d9](https://github.com/markdown-confluence/markdown-confluence/commit/42706d9f167fbdeb125477ac167326d8e939166a))
* Update config to be simpler ([6fff68e](https://github.com/markdown-confluence/markdown-confluence/commit/6fff68ecc7b97119735e3c94878f4455e42c5bd0))
* Update package-lock.json ([66cf8cf](https://github.com/markdown-confluence/markdown-confluence/commit/66cf8cf5d87eae7371ab1d473329cb921d8c064f))
* Use package names not short names ([f851af4](https://github.com/markdown-confluence/markdown-confluence/commit/f851af442df0d5986ae218248c229c5daec42220))
* Work around bug in release-please ([b740114](https://github.com/markdown-confluence/markdown-confluence/commit/b74011475d85c5ca4551aba998b1ea3b8627a025))
* Wrong path for manifest.json ([8444d3f](https://github.com/markdown-confluence/markdown-confluence/commit/8444d3f7f571e37e42565bddc403ac1dbd943eb7))


### Dependencies

* **deps:** bump @atlaskit/renderer from 107.2.0 to 107.3.2 ([7ae7a58](https://github.com/markdown-confluence/markdown-confluence/commit/7ae7a58ebdca4a516eba61504ef3299d4c42f6ce))
* Remove unused deps ([2bfd5c4](https://github.com/markdown-confluence/markdown-confluence/commit/2bfd5c4741202f4d18639254758ac9f914ec8eab))


### Documentation

* Add BRAT installation instructions ([a46cd23](https://github.com/markdown-confluence/markdown-confluence/commit/a46cd23023426153405aef6e9d7c413a9c4bda01))
* Add brat to readme.md ([9d8efb0](https://github.com/markdown-confluence/markdown-confluence/commit/9d8efb076b3dc43c787c684456559f8347c71c66))
* Add Installation BRAT to side nav ([5d87192](https://github.com/markdown-confluence/markdown-confluence/commit/5d871924fa93eceffc8be6817c61b42f70f9404f))
* Add reference to https://github.com/LostPaul/obsidian-folder-notes/tree/main ([d783f1b](https://github.com/markdown-confluence/markdown-confluence/commit/d783f1b0b60f0864f07bac7a8eaeeafbac7e6101))
* Add Wikilinks example ([92a979f](https://github.com/markdown-confluence/markdown-confluence/commit/92a979ffd496e1993d36be26422bf341c0a58b72))
* Fix book.toml ([985561a](https://github.com/markdown-confluence/markdown-confluence/commit/985561a25f9a801f6570c368941792fb24abfc64))
* Minor documentation changes from jvsteiner ([f2d3b47](https://github.com/markdown-confluence/markdown-confluence/commit/f2d3b474474d80bd05ff589a3654e4400e05265d))


### Miscellaneous Chores

* release 2.0.0 ([a9eae0c](https://github.com/markdown-confluence/markdown-confluence/commit/a9eae0cf43f20e3eb57096792c78f7215e6f2dd0))
* release 3.0.0 ([cc12c74](https://github.com/markdown-confluence/markdown-confluence/commit/cc12c74227dd7f6f0ed2d52b5120d7b727aa37a1))

## [3.0.4](https://github.com/markdown-confluence/markdown-confluence/compare/3.0.3...3.0.4) (2023-04-18)


### Bug Fixes

* Enable merge due to not having `linked-versions` ([8850884](https://github.com/markdown-confluence/markdown-confluence/commit/8850884803b8168de9031de1d09cb56da2e6c11e))

## [3.0.3](https://github.com/markdown-confluence/markdown-confluence/compare/3.0.2...3.0.3) (2023-04-18)


### Bug Fixes

* Bump lib ([18c4d27](https://github.com/markdown-confluence/markdown-confluence/commit/18c4d27b07d21ed793bbb8492d83109afde1356d))
* Bump obsidian version ([c42e0d2](https://github.com/markdown-confluence/markdown-confluence/commit/c42e0d2335c52a4beddcb0273e17ad287b9166ea))
* Flip plugins order again ([3003b70](https://github.com/markdown-confluence/markdown-confluence/commit/3003b704f9378cf180aaaaabe95feba3ea740b22))
* Move "." to the bottom ([e3a68ce](https://github.com/markdown-confluence/markdown-confluence/commit/e3a68cee680ac1f65f49577f537937a2ae502cfd))

## [3.0.2](https://github.com/markdown-confluence/markdown-confluence/compare/3.0.1...3.0.2) (2023-04-18)


### Bug Fixes

* Bump version I hope ([39b93eb](https://github.com/markdown-confluence/markdown-confluence/commit/39b93eba447f2a1f706ff6e65e7e8cabea08bf75))

## [3.0.1](https://github.com/markdown-confluence/markdown-confluence/compare/3.0.0...3.0.1) (2023-04-18)


### Bug Fixes

* Dir path for copy ([0f499da](https://github.com/markdown-confluence/markdown-confluence/commit/0f499dae4252a4053bde8de749ace04da69454dd))
* Don't publish till release created ([861ae0a](https://github.com/markdown-confluence/markdown-confluence/commit/861ae0a0b12e649c2b0385ea417cdda81e1eae82))
* Group name ([cec80c5](https://github.com/markdown-confluence/markdown-confluence/commit/cec80c50da2432477e033f3635f8fb27de246245))
* Try reordering plugins ([42706d9](https://github.com/markdown-confluence/markdown-confluence/commit/42706d9f167fbdeb125477ac167326d8e939166a))
* Work around bug in release-please ([b740114](https://github.com/markdown-confluence/markdown-confluence/commit/b74011475d85c5ca4551aba998b1ea3b8627a025))

## [3.0.0](https://github.com/markdown-confluence/markdown-confluence/compare/2.1.1...3.0.0) (2023-04-18)


### Features

* Add NPM publish after release is created ([2979a11](https://github.com/markdown-confluence/markdown-confluence/commit/2979a11507c140436ce0ca236e86aca70991bfb9))
* **AdfEqual:** Updates to make the ADF closer to what Confluence returns ([348f00e](https://github.com/markdown-confluence/markdown-confluence/commit/348f00e3d98bf6843f886310eeadf75ca86be1e3))
* **build:** Add `mermaidRendererPlugin.js` ([a64a176](https://github.com/markdown-confluence/markdown-confluence/commit/a64a1763c8c440e8d826b8f4a8bc6aa304eafc38))
* Include stats/expanded file names on publish ([d618b66](https://github.com/markdown-confluence/markdown-confluence/commit/d618b665521364ebfbea05a2713ff70f74630b91))
* Lots of changes to enable better testing ([0ce560c](https://github.com/markdown-confluence/markdown-confluence/commit/0ce560c3fb2c60edd4509d31ed99f52f500e2f13))


### Bug Fixes

* Add `@markdown-confluence/lib` to `markdown-electron-renderer` ([886556a](https://github.com/markdown-confluence/markdown-confluence/commit/886556abfb0c2f297c032577b9ce55ed89213d14))
* Add root component to `linked-versions` ([f2e1541](https://github.com/markdown-confluence/markdown-confluence/commit/f2e1541ed97292a13b4493c905fef89b69b140fc))
* Add version for root package ([afea12d](https://github.com/markdown-confluence/markdown-confluence/commit/afea12d202e15be39e89542c8cba8a58aaf952f3))
* Attempt 10,000 fixing releases ([60d875a](https://github.com/markdown-confluence/markdown-confluence/commit/60d875a134d16b2a7ef707d2ff4163657e27ad6a))
* Force rename mdToADF to MdToADF ([9d0d483](https://github.com/markdown-confluence/markdown-confluence/commit/9d0d4839b8540b423d794ab3d93d4ba071ede6dd))
* Manifest ([b87659e](https://github.com/markdown-confluence/markdown-confluence/commit/b87659e8c780a77092b0c5de616feda20f9dcefa))
* **ReleasePlease:** Fix to use a different name for package due to the actual obsidian package ([3f94f7e](https://github.com/markdown-confluence/markdown-confluence/commit/3f94f7e15745139f7530ae1f86b0334f7d6ff184))
* Rename `MainSettingTab` to `ConfluenceSettingTab` ([29ef8f2](https://github.com/markdown-confluence/markdown-confluence/commit/29ef8f256305a13d520fc65c7a49064ed90aa296))
* Rename `MyPlugin` to `ConfluencePlugin` ([2298e27](https://github.com/markdown-confluence/markdown-confluence/commit/2298e2787b29c5ca9ce030cbd3bee7b8698326a6))
* Rename `MyPluginSettings` to `ConfluenceSettings` ([25bdb97](https://github.com/markdown-confluence/markdown-confluence/commit/25bdb97c85e79284c42bf89bd5b3a0cff1ebc10a))
* **test:** Extend test timeout ([ee38491](https://github.com/markdown-confluence/markdown-confluence/commit/ee38491e4bb3073890cf6d7650356c31bab03063))
* Try adding the component to PR title ([0b07269](https://github.com/markdown-confluence/markdown-confluence/commit/0b0726960a6771be367d897916eb0820f7dcb02d))
* Update config to be simpler ([6fff68e](https://github.com/markdown-confluence/markdown-confluence/commit/6fff68ecc7b97119735e3c94878f4455e42c5bd0))
* Update package-lock.json ([66cf8cf](https://github.com/markdown-confluence/markdown-confluence/commit/66cf8cf5d87eae7371ab1d473329cb921d8c064f))
* Use package names not short names ([f851af4](https://github.com/markdown-confluence/markdown-confluence/commit/f851af442df0d5986ae218248c229c5daec42220))
* Wrong path for manifest.json ([8444d3f](https://github.com/markdown-confluence/markdown-confluence/commit/8444d3f7f571e37e42565bddc403ac1dbd943eb7))


### Documentation

* Add BRAT installation instructions ([a46cd23](https://github.com/markdown-confluence/markdown-confluence/commit/a46cd23023426153405aef6e9d7c413a9c4bda01))
* Add brat to readme.md ([9d8efb0](https://github.com/markdown-confluence/markdown-confluence/commit/9d8efb076b3dc43c787c684456559f8347c71c66))
* Add Installation BRAT to side nav ([5d87192](https://github.com/markdown-confluence/markdown-confluence/commit/5d871924fa93eceffc8be6817c61b42f70f9404f))
* Add reference to https://github.com/LostPaul/obsidian-folder-notes/tree/main ([d783f1b](https://github.com/markdown-confluence/markdown-confluence/commit/d783f1b0b60f0864f07bac7a8eaeeafbac7e6101))
* Add Wikilinks example ([92a979f](https://github.com/markdown-confluence/markdown-confluence/commit/92a979ffd496e1993d36be26422bf341c0a58b72))
* Fix book.toml ([985561a](https://github.com/markdown-confluence/markdown-confluence/commit/985561a25f9a801f6570c368941792fb24abfc64))
* Minor documentation changes from jvsteiner ([f2d3b47](https://github.com/markdown-confluence/markdown-confluence/commit/f2d3b474474d80bd05ff589a3654e4400e05265d))


### Miscellaneous Chores

* release 3.0.0 ([cc12c74](https://github.com/markdown-confluence/markdown-confluence/commit/cc12c74227dd7f6f0ed2d52b5120d7b727aa37a1))

## [2.1.1](https://github.com/markdown-confluence/markdown-confluence/compare/2.1.0...2.1.1) (2023-04-14)


### Bug Fixes

* Rename frontmatter-to-publish to connie-frontmatter-to-publish ([d18d209](https://github.com/markdown-confluence/markdown-confluence/commit/d18d20998fdd686a2aefe2aefbda33a4c2b86341))
* **stringifyObject:** Replacing stringify-object with JSON.stringify ([0297b44](https://github.com/markdown-confluence/markdown-confluence/commit/0297b44b42af151e88d9a942a814b6dffabe5f20))


### Dependencies

* Remove unused deps ([2bfd5c4](https://github.com/markdown-confluence/markdown-confluence/commit/2bfd5c4741202f4d18639254758ac9f914ec8eab))

## [2.1.0](https://github.com/markdown-confluence/markdown-confluence/compare/2.0.1...2.1.0) (2023-04-14)


### Features

* **build:** Minify outputs to save size in main.js file ([c879d5d](https://github.com/markdown-confluence/markdown-confluence/commit/c879d5ddb3f40376fea7b2ce903818865bcac175))
* **ci:** Export meta.json from esbuild ([c27ca7d](https://github.com/markdown-confluence/markdown-confluence/commit/c27ca7d67230a5aa051c94407a69745dbcf83f81))
* **tests:** Add initial unit tests and GH Actions to ensure they pass ([b7f636e](https://github.com/markdown-confluence/markdown-confluence/commit/b7f636e2fb8e8a99c06cd60d227e38ae9e8d2873))


### Bug Fixes

* **ci:** Fix errors ([ffeea5c](https://github.com/markdown-confluence/markdown-confluence/commit/ffeea5c80bde3c5674716059e450b8c6963f8e9d))
* **ci:** Learn to check ([a494231](https://github.com/markdown-confluence/markdown-confluence/commit/a494231840544e19cc8ac7bc090be6f327bc68dc))
* **ci:** Run Release Please via PAT to allow GHA checks to run ([adb0708](https://github.com/markdown-confluence/markdown-confluence/commit/adb07085f4bd026f994b5c8201abe0782e9b3828))
* **test:** Fix snapshot test to test passing all tests ([8e26790](https://github.com/markdown-confluence/markdown-confluence/commit/8e26790ff219105ccfd54078239515164369b0b6))


### Dependencies

* **deps:** bump @atlaskit/renderer from 107.2.0 to 107.3.2 ([7ae7a58](https://github.com/markdown-confluence/markdown-confluence/commit/7ae7a58ebdca4a516eba61504ef3299d4c42f6ce))

## [2.0.1](https://github.com/markdown-confluence/markdown-confluence/compare/2.0.0...2.0.1) (2023-04-13)


### Bug Fixes

* **images:** Fix for image upload ([6b973f2](https://github.com/markdown-confluence/markdown-confluence/commit/6b973f2fc2a97b299c1abb61708407c097a80706))

## [2.0.0](https://github.com/markdown-confluence/markdown-confluence/compare/1.4.0...2.0.0) (2023-04-12)


### Bug Fixes

* **Obsidian:** Update to match recommendations from https://github.com/obsidianmd/obsidian-releases/blob/master/plugin-review.md ([a038a46](https://github.com/markdown-confluence/markdown-confluence/commit/a038a46c08fb363d46a3f80ba431d165a507ca64))


### Miscellaneous Chores

* release 2.0.0 ([a9eae0c](https://github.com/markdown-confluence/markdown-confluence/commit/a9eae0cf43f20e3eb57096792c78f7215e6f2dd0))

## [1.4.0](https://github.com/markdown-confluence/markdown-confluence/compare/1.3.0...1.4.0) (2023-04-11)


### Features

* **PublishDialog:** Add more detail to publish completed / failed dialog ([ddce9fc](https://github.com/markdown-confluence/markdown-confluence/commit/ddce9fc483edd724f608e0d37f62030588da1d09))
* **SinglePage:** Publish updates for 1 page only ([41e5ac4](https://github.com/markdown-confluence/markdown-confluence/commit/41e5ac4f6dee96fd51531fe6200c9f34dd571261))
* **Wikilinks:** First pass at supporting Wikilinks Syntax ([57e9f65](https://github.com/markdown-confluence/markdown-confluence/commit/57e9f65da1ddb4beb21d997bdf8652a6eed29720))
* **Wikilinks:** Support smart links and pages in multiple spaces ([20656f4](https://github.com/markdown-confluence/markdown-confluence/commit/20656f489d32a50ebd70587f25ca0d167c721cf0))

## [1.3.0](https://github.com/markdown-confluence/markdown-confluence/compare/1.2.4...1.3.0) (2023-04-11)


### Features

* **AdfPreview:** Make local files render correctly in ADF Preview ([860bfb8](https://github.com/markdown-confluence/markdown-confluence/commit/860bfb8e5cf1f094231abd2f4b4e7ae6bc91e7fd))
* **eslint:** Add checks to GH Actions ([e786154](https://github.com/markdown-confluence/markdown-confluence/commit/e7861542f9dbe99bbc81bb0cecfee00f32ae5c5a))
* **PageId:** Specify PageId when page published to Confluence ([c545009](https://github.com/markdown-confluence/markdown-confluence/commit/c5450092bb8abdf106d80d5a12b4a075dbd61130))


### Bug Fixes

* **cli:** Build error ([8d2698b](https://github.com/markdown-confluence/markdown-confluence/commit/8d2698b47c6244fe2304b44b78b557358dfe5797))
* **eslint:** Fix eslint issues ([cbaa567](https://github.com/markdown-confluence/markdown-confluence/commit/cbaa5671bb7e16c1b79b636cb06ed930298b29a6))

## [1.2.4](https://github.com/markdown-confluence/markdown-confluence/compare/1.2.3...1.2.4) (2023-04-07)


### Bug Fixes

* **settings:** SaveSettings before Init ([64c4e41](https://github.com/markdown-confluence/markdown-confluence/commit/64c4e41565364525bfb2b53480630d30c875b91d))

## [1.2.3](https://github.com/markdown-confluence/markdown-confluence/compare/1.2.2...1.2.3) (2023-04-06)


### Bug Fixes

* **ci:** Remove extra comment in manifest.json ([05d9657](https://github.com/markdown-confluence/markdown-confluence/commit/05d965738ac77b951acc39348bb7e4a64c627b1f))

## [1.2.2](https://github.com/markdown-confluence/markdown-confluence/compare/1.2.1...1.2.2) (2023-04-06)


### Bug Fixes

* **ci:** Move manifest to root of repo to align with Obsidian requirements ([78d09e4](https://github.com/markdown-confluence/markdown-confluence/commit/78d09e43daad45aa0cf51f5f1ca874fa5b13e8e1))

## [1.2.1](https://github.com/markdown-confluence/markdown-confluence/compare/1.2.0...1.2.1) (2023-04-06)


### Bug Fixes

* **ci:** Remove v from github release ([3d3c07e](https://github.com/markdown-confluence/markdown-confluence/commit/3d3c07ef3b96c6f73561f5cd2aa0e44e7f6034c9))

## [1.2.0](https://github.com/markdown-confluence/markdown-confluence/compare/v1.1.0...1.2.0) (2023-04-06)


### Features

* **ci:** Add initial google-github-actions/release-please-action@v3 ([39cc200](https://github.com/markdown-confluence/markdown-confluence/commit/39cc2001113f6f846dddc56bc8ba75f5ff7ce026))


### Bug Fixes

* **ci:** Add support to bundle up files for plugin ([250984b](https://github.com/markdown-confluence/markdown-confluence/commit/250984b2baf462266d7cafc5a6eb7b82b0fd2dbb))
* **ci:** List files uploaded to GitHub ([7612bcd](https://github.com/markdown-confluence/markdown-confluence/commit/7612bcd6b67c8ba712611e553dff985f8cae38bd))
* **ci:** Remove component from tag ([362b07e](https://github.com/markdown-confluence/markdown-confluence/commit/362b07e58af2420eb37a7fcabdfa1f9161a6c954))
* **ci:** Remove Sourcemap to save size ([0a1398b](https://github.com/markdown-confluence/markdown-confluence/commit/0a1398bb880c3201598ec860c68c1b82b016fa4a))
* **ci:** Remove v from version number ([2a024bd](https://github.com/markdown-confluence/markdown-confluence/commit/2a024bdf2d640749561f41a24f79343005066d13))
* **ci:** Use manifest over gh actions auto config ([3dc8d2b](https://github.com/markdown-confluence/markdown-confluence/commit/3dc8d2bbe5a25c844cda5c224ab0da7c465a5622))
* **Mermaid:** Remove extra console.log ([cfbddd5](https://github.com/markdown-confluence/markdown-confluence/commit/cfbddd531d4b79e3bd2447e39299db19b6393014))

## [1.1.0](https://github.com/markdown-confluence/markdown-confluence/compare/obsidian-confluence-v1.0.4...obsidian-confluence-1.1.0) (2023-04-06)


### Features

* **ci:** Add initial google-github-actions/release-please-action@v3 ([39cc200](https://github.com/markdown-confluence/markdown-confluence/commit/39cc2001113f6f846dddc56bc8ba75f5ff7ce026))


### Bug Fixes

* **ci:** Add support to bundle up files for plugin ([250984b](https://github.com/markdown-confluence/markdown-confluence/commit/250984b2baf462266d7cafc5a6eb7b82b0fd2dbb))
* **ci:** List files uploaded to GitHub ([7612bcd](https://github.com/markdown-confluence/markdown-confluence/commit/7612bcd6b67c8ba712611e553dff985f8cae38bd))
* **ci:** Remove Sourcemap to save size ([0a1398b](https://github.com/markdown-confluence/markdown-confluence/commit/0a1398bb880c3201598ec860c68c1b82b016fa4a))
* **ci:** Remove v from version number ([2a024bd](https://github.com/markdown-confluence/markdown-confluence/commit/2a024bdf2d640749561f41a24f79343005066d13))
* **ci:** Use manifest over gh actions auto config ([3dc8d2b](https://github.com/markdown-confluence/markdown-confluence/commit/3dc8d2bbe5a25c844cda5c224ab0da7c465a5622))
* **Mermaid:** Remove extra console.log ([cfbddd5](https://github.com/markdown-confluence/markdown-confluence/commit/cfbddd531d4b79e3bd2447e39299db19b6393014))

## [1.0.4](https://github.com/markdown-confluence/markdown-confluence/compare/v1.0.3...v1.0.4) (2023-04-06)


### Bug Fixes

* **ci:** Remove v from version number ([2a024bd](https://github.com/markdown-confluence/markdown-confluence/commit/2a024bdf2d640749561f41a24f79343005066d13))

## [1.0.3](https://github.com/markdown-confluence/markdown-confluence/compare/v1.0.2...v1.0.3) (2023-04-06)


### Bug Fixes

* **Mermaid:** Remove extra console.log ([cfbddd5](https://github.com/markdown-confluence/markdown-confluence/commit/cfbddd531d4b79e3bd2447e39299db19b6393014))

## [1.0.2](https://github.com/markdown-confluence/markdown-confluence/compare/v1.0.1...v1.0.2) (2023-04-05)


### Bug Fixes

* **ci:** List files uploaded to GitHub ([7612bcd](https://github.com/markdown-confluence/markdown-confluence/commit/7612bcd6b67c8ba712611e553dff985f8cae38bd))
* **ci:** Remove Sourcemap to save size ([0a1398b](https://github.com/markdown-confluence/markdown-confluence/commit/0a1398bb880c3201598ec860c68c1b82b016fa4a))

## [1.0.1](https://github.com/markdown-confluence/markdown-confluence/compare/v1.0.0...v1.0.1) (2023-04-05)


### Bug Fixes

* **ci:** Add support to bundle up files for plugin ([250984b](https://github.com/markdown-confluence/markdown-confluence/commit/250984b2baf462266d7cafc5a6eb7b82b0fd2dbb))

## 1.0.0 (2023-04-05)


### Features

* **ci:** Add initial google-github-actions/release-please-action@v3 ([39cc200](https://github.com/markdown-confluence/markdown-confluence/commit/39cc2001113f6f846dddc56bc8ba75f5ff7ce026))
