# Changelog

## [0.26.1](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.26.0...v0.26.1) (2024-04-10)


### Bug Fixes

* bug fix ([dd839c4](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/dd839c406833efd8d2d12ad73458b8ee9be7d6e2))

## [0.26.0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.25.1...v0.26.0) (2024-04-10)


### Features

* Add an option to var - Database name for a specific privileges use ([ed1cd95](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/ed1cd95b27a1bd71fa10c5a806b77b74ad470a2a))

## [0.25.1](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.25.0...v0.25.1) (2024-01-30)


### Bug Fixes

* add retention var to api gateway logs ([d6a0ca6](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/d6a0ca63ecc40ddeba5c456cbbc25ff7ddd37e2f))

## [0.25.0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.24.2...v0.25.0) (2024-01-18)


### Features

* expose cognito user pool configurations. ([dd7ba4d](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/dd7ba4d851c468d728fac0c1cdd499220c657a0f))


### Bug Fixes

* line error ([9275220](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/9275220a728af978404ae6ca74d63e897ee0874d))
* var error ([25d777a](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/25d777acafcb00022cb58752d31a33da6eb00801))

## [0.24.2](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.24.1...v0.24.2) (2024-01-11)


### Bug Fixes

* fix bug for atlas-project ([17a8642](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/17a8642ec2f24bac26ad4685f56516818f1617df))

## [0.24.1](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.24.0...v0.24.1) (2024-01-11)


### Bug Fixes

* change env ([2fa72da](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/2fa72da2c14fa78d51cfdd402637485356e0d623))

## [0.24.0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.23.0...v0.24.0) (2024-01-11)


### Features

* fix env var ([df10d21](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/df10d21d68d4887b4e990bf9c7cd52a475d0064b))


### Bug Fixes

* fix env.hcl var ([e5500e1](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/e5500e12156658df35b3cad321ea62392415f49c))

## [0.23.0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.22.0...v0.23.0) (2023-08-29)


### Features

* expose domain name unique ([#849](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/849)) ([ae57d8a](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/ae57d8a3e01a4c719a7d8f055e3876a0efcb739d))

## [0.22.0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.21.0...v0.22.0) (2023-08-29)


### Features

* expose cognito user pool name ([#847](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/847)) ([f7bd61f](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/f7bd61f2657bcbf1451f575f3f5801ca6098fffb))

## [0.21.0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.20.2...v0.21.0) (2023-07-19)


### Features

* Support variable for database version ([#835](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/835)) ([5e5d49d](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/5e5d49da557d2040f34d59a7a89ccb47a36066fc))

## [0.20.2](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.20.1...v0.20.2) (2023-06-20)


### Bug Fixes

* update version constrain for waf ([#817](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/817)) ([c8cc982](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/c8cc9820a14b444ac5f67b2e007ec53c8e5d6f05))

## [0.20.1](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.20.0...v0.20.1) (2023-06-20)


### Bug Fixes

* adding api gateway name by stage ([#815](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/815)) ([e757b2a](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/e757b2afafabba6626dda2e2f81c423e88890a10))

## [0.20.0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.19.0...v0.20.0) (2023-05-27)


### Features

* change the way we pass sg for elb ([#804](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/804)) ([609a81d](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/609a81db54afdae7b08317824f2facc0fe8f6eee))

## [0.19.0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.18.2...v0.19.0) (2023-05-25)


### Features

* add option to change load balancer subnet ([#802](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/802)) ([4dc7cbb](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/4dc7cbb891f0b1bf8365fb633d87fabd28852c09))

## [0.18.2](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.18.1...v0.18.2) (2023-05-24)


### Bug Fixes

* change names ([#799](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/799)) ([3770285](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/3770285b8f46ddd5b4b56df3d1cc47b016f4b1d3))

## [0.18.0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.17.1...v0.18.0) (2023-05-24)


### Features

* adding docs ([#796](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/796)) ([2290435](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/22904350618309690f75469fd604fa7dc638b950))

## [0.17.1](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.17.0...v0.17.1) (2023-05-22)


### Bug Fixes

* add variable ([#793](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/793)) ([885d421](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/885d4218fde5be1200826e486da99d594cbdbd15))
* remove workflow ([3f07785](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/3f077855dae5ebf7513cbc403089b37aad78bbe6))

## [0.17.0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.16.10...v0.17.0) (2023-05-22)


### Features

* **api-gateway:** Allow custom headers for method & integration request execution ([#672](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/672)) ([8bcf148](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/8bcf148dce9ca211a7ad6ff6efc961d36c2c5965))
* update version of flow logs ([#789](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/789)) ([948b213](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/948b2133089681f57c15697b1536dbce5defd6d3))


### Bug Fixes

* bump @aws-sdk/client-secrets-manager in /server ([#582](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/582)) ([ad52d13](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/ad52d13a33783e21d1d49508e80e65e3cb274958))
* bump @aws-sdk/client-secrets-manager in /server ([#586](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/586)) ([8611a3c](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/8611a3cd8843cca794a9942f6faac25b11983027))
* bump @aws-sdk/client-secrets-manager in /server ([#592](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/592)) ([9d4d0da](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/9d4d0daccc898061b55f6f6a17eae5854828f1a4))
* bump @aws-sdk/client-secrets-manager in /server ([#597](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/597)) ([c7f5224](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/c7f52243e7723fe8618ed1d7c76be12d0c7dc417))
* bump @aws-sdk/client-secrets-manager in /server ([#601](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/601)) ([89af03c](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/89af03c8a85c6334ec61f7d22cca68749b1360a5))
* bump @aws-sdk/client-secrets-manager in /server ([#605](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/605)) ([9c05114](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/9c05114cdaa2f8ba504da5d0d9a3f132c1ace0ad))
* bump @aws-sdk/client-secrets-manager in /server ([#609](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/609)) ([6857866](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/6857866123f04f38476bf20c1094c4ae29424899))
* bump @aws-sdk/client-secrets-manager in /server ([#613](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/613)) ([65e2b3e](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/65e2b3e1e3b334a16b8e8ac46d610680e09dda36))
* bump @aws-sdk/client-secrets-manager in /server ([#621](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/621)) ([b98a24e](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/b98a24e1c6cac3414d8b0a1145a7b739c5fe4fb3))
* bump @aws-sdk/client-secrets-manager in /server ([#623](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/623)) ([59393ff](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/59393ff3131fbfe942377e320f5df9f3c839020c))
* bump @aws-sdk/client-secrets-manager in /server ([#628](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/628)) ([ae205d6](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/ae205d6f48019afdec5c4f98191a0ce4c7492562))
* bump @aws-sdk/client-secrets-manager in /server ([#634](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/634)) ([d826313](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/d826313f7f97d1adfb7090744fa7f11319ba63f7))
* bump @aws-sdk/client-secrets-manager in /server ([#636](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/636)) ([0bbd620](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/0bbd620d548c1f90ddf6d980826a17aecb68078d))
* bump @aws-sdk/client-secrets-manager in /server ([#638](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/638)) ([1290d88](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/1290d88f13c0a841f4281fb340277279b082736d))
* bump @aws-sdk/client-secrets-manager in /server ([#640](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/640)) ([a011b9d](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/a011b9d00b9083c8b7dd9110e5d1e1fe157f9b93))
* bump @aws-sdk/client-secrets-manager in /server ([#649](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/649)) ([f9eb084](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/f9eb0840098098ba9bd20cb47148b239f8cc78f7))
* bump @aws-sdk/client-secrets-manager in /server ([#652](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/652)) ([4da2989](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/4da298905de8012ce2596b96f0fa45470442ac8c))
* bump @aws-sdk/client-secrets-manager in /server ([#655](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/655)) ([7878f72](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/7878f720a57ff20396508f955ffd344c7647a954))
* bump @aws-sdk/client-secrets-manager in /server ([#658](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/658)) ([2e2d901](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/2e2d901a10fd665fe299e95a9b594f2f16b006a4))
* bump @aws-sdk/client-secrets-manager in /server ([#666](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/666)) ([b311886](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/b31188695faffe66714c2a1e0c25d0d18e166b01))
* bump @aws-sdk/client-secrets-manager in /server ([#668](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/668)) ([3fc981f](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/3fc981fe55db52187d378633c87bdd200fc2774f))
* bump @aws-sdk/client-secrets-manager in /server ([#671](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/671)) ([254be20](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/254be207b3982838ff89bcbd28a70856e8e0e15d))
* bump @aws-sdk/client-secrets-manager in /server ([#674](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/674)) ([7a0e104](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/7a0e10497b9885ba5b6ed5831d7592eca9609a31))
* bump @aws-sdk/client-secrets-manager in /server ([#677](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/677)) ([f04393d](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/f04393d5a32a1f772c973b846790ee617408bc14))
* bump @aws-sdk/client-secrets-manager in /server ([#680](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/680)) ([d91d5b0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/d91d5b0f8f8228ba77f59d13848f08e77654df0b))
* bump @aws-sdk/client-secrets-manager in /server ([#683](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/683)) ([8430cdf](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/8430cdf9aa111eabdf326faf24b8fc60347f82ec))
* bump @aws-sdk/client-secrets-manager in /server ([#687](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/687)) ([6ec72d9](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/6ec72d95529527782e0d585c69018a015f9c1c21))
* bump @aws-sdk/client-secrets-manager in /server ([#689](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/689)) ([35d0676](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/35d0676dbd0e29a01b883263db27c8ea5d714a3d))
* bump @aws-sdk/client-secrets-manager in /server ([#692](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/692)) ([590e72c](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/590e72cf3a3f1cead796423797312d66a7746396))
* bump @aws-sdk/client-secrets-manager in /server ([#697](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/697)) ([8ac97c5](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/8ac97c57a91a6b0a53cdbde8411627a3fd54a44a))
* bump @aws-sdk/client-secrets-manager in /server ([#706](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/706)) ([eff63c1](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/eff63c1004da519cc31a3ff5f70761fba80c80b4))
* bump @aws-sdk/client-secrets-manager in /server ([#712](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/712)) ([3381363](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/33813632835d92bd56fd75e040dec63b024b3aef))
* bump @aws-sdk/client-secrets-manager in /server ([#714](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/714)) ([523d163](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/523d163de9b0bf4df317b6384b7c9b5993fa3968))
* bump @aws-sdk/client-secrets-manager in /server ([#719](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/719)) ([f211d7c](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/f211d7cf3263090fcd7a4e35120787fc1c7ba2bd))
* bump @aws-sdk/client-secrets-manager in /server ([#722](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/722)) ([b159ae8](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/b159ae8fab480337677b60980b5f598a8debb559))
* bump @aws-sdk/client-secrets-manager in /server ([#727](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/727)) ([fed1715](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/fed1715713e4eb1bbc33f501534432893519bd75))
* bump @aws-sdk/client-secrets-manager in /server ([#731](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/731)) ([22744a8](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/22744a8e48c4b5c70ff0e17a79f59689802a64bc))
* bump @aws-sdk/client-secrets-manager in /server ([#734](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/734)) ([3f97672](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/3f97672adb0a988e6592ff2defa5b93248c961fb))
* bump @aws-sdk/client-secrets-manager in /server ([#739](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/739)) ([59d14c0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/59d14c01b96d7470ff267f0762192058f6bc5da5))
* bump @aws-sdk/client-secrets-manager in /server ([#747](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/747)) ([40045a6](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/40045a6d85dbbee5d4e5bd0aa976d2e905d48975))
* bump @aws-sdk/client-secrets-manager in /server ([#751](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/751)) ([6db5733](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/6db5733457c009fa87dbe9ff4b989ed2ea2b034c))
* bump @aws-sdk/client-secrets-manager in /server ([#753](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/753)) ([9dd4d1a](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/9dd4d1a9a9bb140f1761bfa0eac46ce190d2b575))
* Bump @aws-sdk/client-secrets-manager in /server ([#761](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/761)) ([36f6500](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/36f6500ac5b61ac0372bd4a4ee6ac2223b6a2e05))
* Bump @aws-sdk/client-secrets-manager in /server ([#765](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/765)) ([1c48d2a](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/1c48d2a126ae2d2edbad4e573f1858c0bff61423))
* Bump @aws-sdk/client-secrets-manager in /server ([#770](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/770)) ([7eae36f](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/7eae36f760539641bbb731b84469bba804cee84d))
* Bump @aws-sdk/client-secrets-manager in /server ([#778](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/778)) ([11787d3](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/11787d379c57149a1609c31a8867cefc0526a8c2))
* Bump @aws-sdk/client-secrets-manager in /server ([#785](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/785)) ([49a1e6d](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/49a1e6db020bb0f29af6c1bf6fe663ef91b997dc))
* bump @sideway/formula from 3.0.0 to 3.0.1 in /client ([#611](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/611)) ([4d1e77a](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/4d1e77a2af2be4d7e8bd00fc6e3b3737f17851ae))
* bump @testing-library/react from 13.4.0 to 14.0.0 in /client ([#624](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/624)) ([19861c7](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/19861c743618bd42f4830bd52b26fb36bd6070a3))
* bump @types/jest from 29.2.6 to 29.4.0 in /client ([#581](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/581)) ([c352b9c](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/c352b9ce72292ea905b6455ea03b0e420b6e490d))
* bump @types/jest from 29.4.0 to 29.4.1 in /client ([#656](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/656)) ([ddb5bbe](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/ddb5bbe9739a8dd9e487ad4c513fe7056b73acfe))
* bump @types/jest from 29.4.1 to 29.4.2 in /client ([#663](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/663)) ([848ff99](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/848ff99129e6d25404172b978593acb38dddda40))
* bump @types/jest from 29.4.2 to 29.4.4 in /client ([#665](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/665)) ([1009569](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/100956975c5af4c8ad13ba1b8c5b40303a67dda3))
* bump @types/jest from 29.4.4 to 29.5.0 in /client ([#670](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/670)) ([b01d3a8](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/b01d3a85723f3ff9f504aa41673a79b1ae8933d6))
* bump @types/jest from 29.5.0 to 29.5.1 in /client ([#728](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/728)) ([71d79cc](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/71d79cc8f9a2e395aa10786748e165d39d1ab2b9))
* bump @types/node from 18.11.18 to 18.11.19 in /client ([#602](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/602)) ([b2cf077](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/b2cf07705c61a37784b3a5adf42f86b42f6578a2))
* bump @types/node from 18.11.19 to 18.13.0 in /client ([#608](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/608)) ([9178d4b](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/9178d4bee1d5ecc1f6813277f193dcd8141cbb4b))
* bump @types/node from 18.13.0 to 18.14.0 in /client ([#626](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/626)) ([6371499](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/6371499e157aafbe6af120f349a3a66755acf0f8))
* bump @types/node from 18.14.0 to 18.14.1 in /client ([#631](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/631)) ([4609c66](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/4609c66dc7e7421ea3ee180a430b4b32d9f5692b))
* bump @types/node from 18.14.1 to 18.14.2 in /client ([#635](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/635)) ([0180c82](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/0180c823b6b605cb53d135475fcec3fc8812c62f))
* bump @types/node from 18.14.2 to 18.14.3 in /client ([#639](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/639)) ([133392e](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/133392e6fcc2f33d694d3dcc0fe68b9316d9aac8))
* bump @types/node from 18.14.3 to 18.14.5 in /client ([#642](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/642)) ([06f0327](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/06f0327c83f10215641713871d5fdf61345cff00))
* bump @types/node from 18.14.5 to 18.14.6 in /client ([#643](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/643)) ([1da88bf](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/1da88bfc0487c732c2c1625249b3b0703834d6af))
* bump @types/node from 18.14.6 to 18.15.0 in /client ([#650](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/650)) ([d404b98](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/d404b98ef4eecf02cc84063491789584e22c7d0e))
* bump @types/node from 18.15.0 to 18.15.1 in /client ([#653](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/653)) ([de4e47a](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/de4e47a40eb996ac13d1b6bcfe0ad233fd429335))
* bump @types/node from 18.15.1 to 18.15.3 in /client ([#660](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/660)) ([b2933af](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/b2933afe998c4d61ef582503b4692e53c20855f6))
* bump @types/node from 18.15.10 to 18.15.11 in /client ([#693](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/693)) ([38e2b1c](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/38e2b1ce10db5f8ab82fb2a45fc7f68a480ba042))
* bump @types/node from 18.15.11 to 18.15.12 in /client ([#724](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/724)) ([faeeeea](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/faeeeeaa20e097e22e822d472983814b8016f57d))
* bump @types/node from 18.15.12 to 18.15.13 in /client ([#729](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/729)) ([96c3d53](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/96c3d531d149276f880d681546efa7c5d0900e26))
* bump @types/node from 18.15.13 to 18.16.0 in /client ([#733](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/733)) ([9ccee2a](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/9ccee2aa2545f746c821d4b81c50d3d93c7e1aeb))
* bump @types/node from 18.15.3 to 18.15.5 in /client ([#673](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/673)) ([b93d548](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/b93d54809f2be4a4a5d1cd8a35c14947c2aa1678))
* bump @types/node from 18.15.5 to 18.15.6 in /client ([#684](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/684)) ([55f96c6](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/55f96c641d94a679642b01858c2912a03727584a))
* bump @types/node from 18.15.6 to 18.15.10 in /client ([#685](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/685)) ([7dbc167](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/7dbc1678ca27c0c70473343aeb04d3aa1e036999))
* bump @types/node from 18.16.0 to 18.16.1 in /client ([#736](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/736)) ([ec5b18e](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/ec5b18e1bcb02c5ace9deb7b8cfe946dc9ae3007))
* bump @types/node from 18.16.1 to 18.16.2 in /client ([#743](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/743)) ([46e717d](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/46e717d97326a23e2998dcbf1080b913c11962a4))
* bump @types/node from 18.16.2 to 18.16.3 in /client ([#745](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/745)) ([146baed](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/146baed78aacfc8146d5960cf2f5eb267268cfef))
* Bump @types/node from 18.16.3 to 20.1.0 in /client ([#757](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/757)) ([80df8fb](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/80df8fbf2f6ab3224f5e58170b373bcb05342eaf))
* Bump @types/node from 20.1.0 to 20.1.1 in /client ([#764](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/764)) ([2dd7d8d](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/2dd7d8dfecc36b1f8fe378698b5b419e0b610217))
* Bump @types/node from 20.1.1 to 20.1.2 in /client ([#768](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/768)) ([f2286cc](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/f2286cc8e8e20b9eb558c6dd247935437503b6b7))
* Bump @types/node from 20.1.2 to 20.1.3 in /client ([#772](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/772)) ([6e4363a](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/6e4363aaa40bf6fab3bb73347b1f02de5ef10621))
* Bump @types/node from 20.1.3 to 20.1.4 in /client ([#774](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/774)) ([565ee01](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/565ee018b5c5a2ad3d40921f8a00f2b7d3b189d3))
* Bump @types/node from 20.1.4 to 20.1.5 in /client ([#775](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/775)) ([9fdcc51](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/9fdcc515ff9939bea271fb58798fc663e6ac018c))
* Bump @types/node from 20.1.5 to 20.1.7 in /client ([#779](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/779)) ([2524d4e](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/2524d4e6ea8868a8af75dc2c9f63258bb9407c55))
* Bump @types/node from 20.1.7 to 20.2.0 in /client ([#782](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/782)) ([ee16cdb](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/ee16cdb6bbeea40174597bd692347b2eaab8072f))
* Bump @types/node from 20.2.0 to 20.2.1 in /client ([#786](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/786)) ([a44452d](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/a44452d695a06311779a7e43e678dccc1503c1d6))
* Bump @types/node from 20.2.1 to 20.2.3 in /client ([#787](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/787)) ([ec072fe](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/ec072febd30acf8d7611bc59d8e846e41f4bff46))
* bump @types/react from 18.0.27 to 18.0.28 in /client ([#616](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/616)) ([7d47e3e](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/7d47e3e8eb3a25210ae97aacc50d1413a664dd51))
* bump @types/react from 18.0.28 to 18.0.29 in /client ([#686](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/686)) ([f6d1667](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/f6d1667f9b764d3b1c6b3ae168fb15215de968b0))
* bump @types/react from 18.0.29 to 18.0.30 in /client ([#688](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/688)) ([c5a5cb0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/c5a5cb061f6e799b5bda0630716b0e4cd62b097c))
* bump @types/react from 18.0.30 to 18.0.31 in /client ([#694](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/694)) ([d51b5ec](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/d51b5ec47de31147d821f119e2a0e139dfa2117f))
* bump @types/react from 18.0.31 to 18.0.32 in /client ([#700](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/700)) ([0e84b71](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/0e84b713530b08bd0721eed5e59c124f3d8ee82f))
* bump @types/react from 18.0.32 to 18.0.33 in /client ([#702](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/702)) ([d3fa3d5](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/d3fa3d5a3949197c6bcb14dc12ebd2a2d0bec8c1))
* bump @types/react from 18.0.33 to 18.0.34 in /client ([#713](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/713)) ([9ffcb15](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/9ffcb15a542fbcb59d22906f6b02aec2f0c24c86))
* bump @types/react from 18.0.34 to 18.0.35 in /client ([#717](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/717)) ([63f2c8e](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/63f2c8e1cd8e97fc2118a8b11bdb4494759ab1a6))
* bump @types/react from 18.0.35 to 18.0.37 in /client ([#721](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/721)) ([f3905ad](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/f3905ad6cd9d371a36e03db3952a395cbf5fb484))
* bump @types/react from 18.0.37 to 18.0.38 in /client ([#732](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/732)) ([54c63c8](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/54c63c897b76af6fd84182a93e6257c178c47f10))
* bump @types/react from 18.0.38 to 18.2.0 in /client ([#738](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/738)) ([0556947](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/0556947d490e88577da103a3c7bc259cbfc5e095))
* bump @types/react from 18.2.0 to 18.2.3 in /client ([#750](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/750)) ([86ceed4](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/86ceed4d13f0942df90bd3d6e6ab27546bbc1d6f))
* bump @types/react from 18.2.3 to 18.2.5 in /client ([#752](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/752)) ([dfdd7de](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/dfdd7dea2aa85c55dc3783b88d534559987e1d64))
* Bump @types/react from 18.2.5 to 18.2.6 in /client ([#763](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/763)) ([62a1b16](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/62a1b1631902de1accd69ba57f60917b8fd96c9f))
* bump @types/react-dom from 18.0.10 to 18.0.11 in /client ([#619](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/619)) ([8a3d406](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/8a3d406e83fd23feea34a8231aabf23e0a0613ec))
* bump @types/react-dom from 18.0.11 to 18.2.1 in /client ([#737](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/737)) ([a46cfa3](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/a46cfa39c154802255a7706a2051955761f02133))
* bump @types/react-dom from 18.2.1 to 18.2.3 in /client ([#749](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/749)) ([ceff7a5](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/ceff7a56dd6507867a12344cdb59b24cdee548c2))
* Bump @types/react-dom from 18.2.3 to 18.2.4 in /client ([#760](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/760)) ([a637d34](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/a637d34ada51c15a292168ca457aec012e56b7de))
* bump axios from 1.2.4 to 1.2.5 in /client ([#584](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/584)) ([a0631c1](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/a0631c1061412e1506a419f044a2dab9b149c7dd))
* bump axios from 1.2.4 to 1.2.5 in /server ([#585](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/585)) ([db88f91](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/db88f917ef362d0eefde539f6ca3ab5d4c297fea))
* bump axios from 1.2.5 to 1.2.6 in /client ([#587](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/587)) ([e8ca00d](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/e8ca00d114df2a9eff9d7973bed1cd257dfe35a2))
* bump axios from 1.2.5 to 1.2.6 in /server ([#588](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/588)) ([adda39f](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/adda39f10980376a762b461b2e8d23cf2dbc915f))
* bump axios from 1.2.6 to 1.3.0 in /client ([#594](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/594)) ([b79854a](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/b79854adb85210bae6de12fac8882e2ee1f54c0e))
* bump axios from 1.2.6 to 1.3.0 in /server ([#596](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/596)) ([c4b4142](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/c4b4142a48911d2c8de16caa6ac6b0218f161c92))
* bump axios from 1.3.0 to 1.3.1 in /client ([#599](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/599)) ([a0abcfe](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/a0abcfef85bef34176b3cd5dd31e5bf9a7c72c45))
* bump axios from 1.3.0 to 1.3.1 in /server ([#598](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/598)) ([5b0272c](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/5b0272cad7b6297556978dca982c41a56cfff41a))
* bump axios from 1.3.1 to 1.3.2 in /client ([#603](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/603)) ([9e64358](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/9e64358727ace096b05235a5ac281dcb7c973b3b))
* bump axios from 1.3.1 to 1.3.2 in /server ([#604](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/604)) ([c7498bd](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/c7498bd1cf4592ff0ac10af2a8b2c08cea74024e))
* bump axios from 1.3.2 to 1.3.3 in /client ([#617](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/617)) ([8d83cfd](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/8d83cfd374f3c5cac6136a959cbca60814c668f3))
* bump axios from 1.3.2 to 1.3.3 in /server ([#618](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/618)) ([92f129e](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/92f129e52285b97678f09ce310541ad7ffe7f3d2))
* bump axios from 1.3.3 to 1.3.4 in /client ([#629](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/629)) ([5f06b78](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/5f06b78de9c37563b9c0d9c5ac88e7b251641de3))
* bump axios from 1.3.3 to 1.3.4 in /server ([#630](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/630)) ([3f8c02b](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/3f8c02baee6a2bd63d7791b85fbb2a8bfc60ad9a))
* bump axios from 1.3.4 to 1.3.5 in /client ([#709](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/709)) ([a12f582](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/a12f58276ba0da1f37898075c1ea1b66f3e97b24))
* bump axios from 1.3.4 to 1.3.5 in /server ([#708](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/708)) ([8be2869](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/8be286971eb61c00ad4a1b46ffaa5d4f8e91877c))
* bump axios from 1.3.5 to 1.3.6 in /client ([#725](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/725)) ([1fd567a](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/1fd567a392e235e535d06664f9f19a1315ff766d))
* bump axios from 1.3.5 to 1.3.6 in /server ([#726](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/726)) ([bcd34f3](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/bcd34f375e4e7ea52dc2f349fdb509e950513f52))
* bump axios from 1.3.6 to 1.4.0 in /client ([#742](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/742)) ([0e6d421](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/0e6d421f14d6809bbd07c6c704b71ddc5e7a7a52))
* bump axios from 1.3.6 to 1.4.0 in /server ([#740](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/740)) ([84fcd30](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/84fcd30815580060646ab4b4ed530072967d30d2))
* bump dns-packet from 5.3.1 to 5.4.0 in /client ([#641](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/641)) ([ad0d6ce](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/ad0d6ce272c72c1a8fc092a96775870b1cef1f17))
* bump mongodb from 4.13.0 to 5.0.0 in /server ([#595](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/595)) ([97a0f74](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/97a0f74e0f044ad6aaa3a13ef27b7e6d6ad0a6e8))
* bump mongodb from 5.0.0 to 5.1.0 in /server ([#633](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/633)) ([6ea2bdc](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/6ea2bdc2af6139334d5a0bd635303e829bba52b4))
* bump mongodb from 5.1.0 to 5.2.0 in /server ([#704](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/704)) ([9008ecc](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/9008ecc3e460f3f97019e95fa5c5ec913350458b))
* bump mongodb from 5.2.0 to 5.3.0 in /server ([#723](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/723)) ([9c5f31b](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/9c5f31b20ab3d08212e2b0226c6551c15acf29fd))
* bump mongodb from 5.3.0 to 5.4.0 in /server ([#754](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/754)) ([25c9b1a](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/25c9b1add3c5c8680b21a970017b2883aa1b3661))
* Bump mongodb from 5.4.0 to 5.5.0 in /server ([#769](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/769)) ([117b376](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/117b376d66de6b7e52fbe38241b2075a9b8177ed))
* bump typescript from 4.9.4 to 4.9.5 in /client ([#589](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/589)) ([0d2cc92](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/0d2cc921942fb56e6d442ddca191b964f750a84b))
* bump web-vitals from 3.1.1 to 3.3.0 in /client ([#651](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/651)) ([266e62f](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/266e62f90a7ff58d2a7e5dd152e52e399efa2afe))
* bump web-vitals from 3.3.0 to 3.3.1 in /client ([#705](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/705)) ([ac33e34](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/ac33e3465e162bbebc760eda54e553e2958ebb10))
* bump webpack from 5.72.1 to 5.76.1 in /client ([#661](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/661)) ([688ca8a](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/688ca8a3bde389eb36b140193d1a323dd5f1c56c))

## [0.16.10](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.16.9...v0.16.10) (2023-01-25)


### Bug Fixes

* bump @aws-sdk/client-secrets-manager in /server ([#573](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/573)) ([4a0a2f5](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/4a0a2f5455ce072db2c973bfed5b5f9ff999d046))
* bump @aws-sdk/client-secrets-manager in /server ([#574](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/574)) ([8576900](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/85769009ac3be69b6ee0c9e94f652d4f97206d3a))
* bump @aws-sdk/client-secrets-manager in /server ([#578](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/578)) ([87f0cd3](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/87f0cd3712ed2731e5b41e5e3ac068b4afeebca2))
* bump @types/jest from 29.2.5 to 29.2.6 in /client ([#570](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/570)) ([17574bb](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/17574bb31bcf42c6478109da946bd5b853c48ec2))
* bump @types/react from 18.0.26 to 18.0.27 in /client ([#571](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/571)) ([0a783a1](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/0a783a15af51a7c75592d21fc7c321d9cc8b0788))
* bump axios from 1.2.2 to 1.2.3 in /client ([#567](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/567)) ([1195713](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/119571311254a2af24a8ceebeec8e217975added))
* bump axios from 1.2.2 to 1.2.3 in /server ([#569](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/569)) ([c671511](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/c67151172938bc1de82bb4420b3163cfb2f1eda7))
* bump axios from 1.2.3 to 1.2.4 in /client ([#577](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/577)) ([df580cb](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/df580cbdf96dd97322683da1913be60e8d7013cd))
* bump axios from 1.2.3 to 1.2.4 in /server ([#576](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/576)) ([c34fea7](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/c34fea73bd4c72cb23e7d14e437ef11c10f4e704))

## [0.16.9](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.16.8...v0.16.9) (2023-01-14)


### Bug Fixes

* bump json5 from 1.0.1 to 1.0.2 in /client ([#555](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/555)) ([0fbd55f](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/0fbd55fce8cebcbd079ccdc01f0fcebb423d2a93))
* bump web-vitals from 3.1.0 to 3.1.1 in /client ([#559](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/559)) ([74b5a8c](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/74b5a8c0491caf48d992bcbf9d076f384cb9ad5e))

## [0.16.8](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.16.7...v0.16.8) (2023-01-02)


### Bug Fixes

* added "admin_create_user_config" variable ([#551](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/551)) ([912a680](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/912a680d7757781daa5479e7b422daa40bde426e))

## [0.16.7](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.16.6...v0.16.7) (2023-01-02)


### Bug Fixes

* added verification template variable ([#549](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/549)) ([2670b56](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/2670b56b06cea431dce71aa4defeac87e2a8203a))
* bump @types/jest from 29.2.4 to 29.2.5 in /client ([#548](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/548)) ([03f34a7](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/03f34a7e48f513399ff02f8c6c1f18bfbe804f96))
* bump axios from 1.2.1 to 1.2.2 in /client ([#545](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/545)) ([659febd](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/659febd7deac1552630366d2e73391ae196ef78c))
* bump axios from 1.2.1 to 1.2.2 in /server ([#547](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/547)) ([3e17af5](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/3e17af5cb40142bb2b9316187c200b5bffb093d7))

## [0.16.6](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.16.5...v0.16.6) (2022-12-29)


### Bug Fixes

* bump @types/node from 18.11.17 to 18.11.18 in /client ([#540](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/540)) ([8267f29](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/8267f29925b6a0224d48d37197f9d3e7f4f42221))
* bump @types/react-dom from 18.0.6 to 18.0.10 in /client ([#538](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/538)) ([4ac3585](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/4ac358584ee55ce2e5f54790f63012fe569f2992))

## [0.16.5](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.16.4...v0.16.5) (2022-12-20)


### Bug Fixes

* bump @types/node from 18.11.15 to 18.11.17 in /client ([#526](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/526)) ([f908568](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/f908568dc6edb38d7d6ad4749c5af0d7ad3a242d))
* bump mongodb from 4.12.1 to 4.13.0 in /server ([#527](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/527)) ([47a6205](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/47a6205725cd34f49424f6a1ff8a79bb341f3796))

## [0.16.4](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.16.3...v0.16.4) (2022-12-15)


### Bug Fixes

* bump @types/node from 18.11.14 to 18.11.15 in /client ([#519](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/519)) ([a197851](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/a197851b51d6073d19a0144e7ab164f3e8f8378b))

## [0.16.3](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.16.2...v0.16.3) (2022-12-13)


### Bug Fixes

* bump @types/node from 18.11.12 to 18.11.13 in /client ([#512](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/512)) ([bb7aa1f](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/bb7aa1f94378943a41c5181be5b741082c61a86d))
* bump @types/node from 18.11.13 to 18.11.14 in /client ([#516](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/516)) ([ac4d429](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/ac4d429f097667ac0681ffb513adedc15382188c))

## [0.16.2](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.16.1...v0.16.2) (2022-12-11)


### Bug Fixes

* bump @types/node from 18.11.11 to 18.11.12 in /client ([#508](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/508)) ([21196f0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/21196f0ca05eda0bc8cdc2a220fbd15bedcd01ba))

## [0.16.1](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.16.0...v0.16.1) (2022-12-08)


### Bug Fixes

* bump @aws-sdk/client-secrets-manager in /server ([#504](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/504)) ([8adc694](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/8adc694a3345f1a0c7605d99729dadd98e6ebd7d))
* bump typescript from 4.9.3 to 4.9.4 in /client ([#503](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/503)) ([daf8089](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/daf80897892dce1d194a1361b8e57eab174a5c89))

## [0.16.0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.15.6...v0.16.0) (2022-12-07)


### Features

* **elastic beanstalk:** set aws_elastic_beanstalk_solution_stack as variable ([#500](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/500)) ([6006a9a](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/6006a9ae8476d5ba673427b46ed254eefe06b95f))


### Bug Fixes

* bump @aws-sdk/client-secrets-manager in /server ([#488](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/488)) ([3b900eb](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/3b900eb49810912f0555b998278f7a89f1d1059e))
* bump @aws-sdk/client-secrets-manager in /server ([#494](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/494)) ([13b0259](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/13b025937bf05996c28b6d8e999c64542b6bf8f6))
* bump @types/jest from 29.2.3 to 29.2.4 in /client ([#492](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/492)) ([0cbb833](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/0cbb833b596e912a2b517e14ee3927f8fc7b890e))
* bump @types/node from 18.11.10 to 18.11.11 in /client ([#490](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/490)) ([c13ae98](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/c13ae9895238cd2285ff9a8dd23e3bc65e0842b3))
* bump @types/node from 18.11.3 to 18.11.10 in /client ([#487](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/487)) ([eb6bd77](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/eb6bd77bd8b1165fa7a52bbceb45a04933eaf84a))
* bump @types/react from 18.0.21 to 18.0.26 in /client ([#497](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/497)) ([68e8d7e](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/68e8d7ed28d8934d7b84c108d11768f44e529290))
* bump axios from 1.2.0 to 1.2.1 in /client ([#491](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/491)) ([be86129](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/be8612915020bc5e60b8ef7f9c91a8eb8f81e82a))
* bump axios from 1.2.0 to 1.2.1 in /server ([#493](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/493)) ([5390213](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/5390213cc4f3bf4be47b39807684d9907b14f80f))
* bump decode-uri-component from 0.2.0 to 0.2.2 in /client ([#489](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/489)) ([a92bb1d](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/a92bb1d60470cff6d8fcc468eea0405beb538cc2))

## [0.15.6](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.15.5...v0.15.6) (2022-11-25)


### Bug Fixes

* bump mongodb from 4.11.0 to 4.12.1 in /server ([#481](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/481)) ([a761df4](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/a761df4e934ffb57db4ce325bb996431ca14ce1b))

## [0.15.5](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.15.4...v0.15.5) (2022-11-23)


### Bug Fixes

* bump @aws-sdk/client-secrets-manager in /server ([#472](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/472)) ([583e331](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/583e33109389481d79fc9321fd0c72e344c364dc))
* bump @aws-sdk/client-secrets-manager in /server ([#477](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/477)) ([d494c68](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/d494c689b43073044ca0347c256abaf118196860))
* bump @types/jest from 29.2.0 to 29.2.3 in /client ([#470](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/470)) ([5c5048e](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/5c5048e9c5a9b5b4ec42a32d08b07a98d9ea59f8))
* bump axios from 1.1.3 to 1.2.0 in /client ([#475](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/475)) ([8166e8f](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/8166e8f54d1b417997df6fb6035f9f71cae7b3fc))
* bump axios from 1.1.3 to 1.2.0 in /server ([#478](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/478)) ([3701571](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/3701571995b9992303bdfbbd6747b3a8bbba7d62))
* bump typescript from 4.8.4 to 4.9.3 in /client ([#468](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/468)) ([aa04893](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/aa048937e703ec6e36a0b59e593e913cd2b19bbd))
* bump web-vitals from 3.0.4 to 3.1.0 in /client ([#469](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/469)) ([efe292b](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/efe292b9b3e4daad090a19ae03e011e603ee1499))

## [0.15.4](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.15.3...v0.15.4) (2022-11-19)


### Bug Fixes

* bump @aws-sdk/client-secrets-manager in /server ([#463](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/463)) ([4b7bcfd](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/4b7bcfd2fe3046e314dbc89725e1b668b361aa04))

## [0.15.3](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.15.2...v0.15.3) (2022-11-17)


### Bug Fixes

* bump minimatch and recursive-readdir in /client ([#461](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/461)) ([6570db1](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/6570db151464dbcbcfb96875ea7c5ab9018204c0))
* linter warnings in splant operator (*) ([#459](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/459)) ([f94ad27](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/f94ad279a99c51df718e145145346481a569dde1))

## [0.15.2](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.15.1...v0.15.2) (2022-11-17)


### Bug Fixes

* bump @aws-amplify/ui-react from 3.5.8 to 3.5.9 in /client ([#395](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/395)) ([a2a3a64](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/a2a3a649e551991112f76304c14e6a84f5606fa3))
* bump @aws-sdk/client-secrets-manager in /server ([#399](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/399)) ([56739d9](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/56739d979c76371b8858f5986d45d0839c47c764))
* bump @aws-sdk/client-secrets-manager in /server ([#401](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/401)) ([07ef891](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/07ef891302f645a634ac70c12f9cf81376e311e3))
* bump @types/jest from 29.1.2 to 29.2.0 in /client ([#394](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/394)) ([bcb2a00](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/bcb2a00d3eaa3fe0c562dd16750963f3f3635e75))
* bump @types/node from 18.11.0 to 18.11.2 in /client ([#396](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/396)) ([e9f74f6](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/e9f74f61b2bb3df2f30ddce48a246f0d1c5bbcc0))
* bump @types/node from 18.11.2 to 18.11.3 in /client ([#400](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/400)) ([d428ee7](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/d428ee77d589b445953e4f5748527c2d0ccafc83))
* bump mongodb from 4.10.0 to 4.11.0 in /server ([#398](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/398)) ([f0dd7aa](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/f0dd7aaeb8dcc3c77cec271d3ee4768116558b1f))
* bump web-vitals from 3.0.3 to 3.0.4 in /client ([#393](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/393)) ([5bda311](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/5bda311b830226d1019441411bb1fd71b549171d))

## [0.15.1](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.15.0...v0.15.1) (2022-10-18)


### Bug Fixes

* bump @aws-amplify/ui-react from 3.5.7 to 3.5.8 in /client ([#383](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/383)) ([b0c5309](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/b0c53097d15072e7fc5996d54283f015afdd0e52))
* bump @aws-sdk/client-secrets-manager in /server ([#384](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/384)) ([ef4c4ef](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/ef4c4ef0f7fa9f89c5d83a8ec1e8cd8467827082))
* bump @aws-sdk/client-secrets-manager in /server ([#390](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/390)) ([315e202](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/315e2025d5a55c18e0622174a1324ea3a55283a6))
* bump @types/node from 18.8.5 to 18.11.0 in /client ([#387](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/387)) ([762cccd](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/762cccd718b6d493825c90b1707ad17380b5cbe6))
* bump aws-amplify from 4.3.37 to 4.3.38 in /client ([#382](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/382)) ([1a5a1c4](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/1a5a1c438e8550c144062f5d7925bbc47484816b))
* bump aws-amplify from 4.3.38 to 4.3.39 in /client ([#385](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/385)) ([6b0e640](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/6b0e640956c576f8618892fcff4cc9680022f7d7))
* bump axios from 1.1.2 to 1.1.3 in /client ([#386](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/386)) ([fee473d](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/fee473d43f24b933fcae205a4b093c96017b2363))
* bump axios from 1.1.2 to 1.1.3 in /server ([#388](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/388)) ([bb0bee2](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/bb0bee21c7b963b04ca2f6eebad6a0f06bfeb4b4))
* union the secrets for project ([#391](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/391)) ([d511e29](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/d511e297a44302405885ab8e6a751a5e5e26e30a))

## [0.15.0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.14.1...v0.15.0) (2022-10-05)


### Features

* **api-gateway:** adding support to binary files ([#368](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/368)) ([a8ff60d](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/a8ff60db2fab5bf3f4e0fbfdaa2bb71cb1fe99e2))

## [0.14.1](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.14.0...v0.14.1) (2022-10-05)


### Bug Fixes

* bump @aws-amplify/ui-react from 3.5.4 to 3.5.6 in /client ([#362](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/362)) ([43bc143](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/43bc143e34775c830b381dc99c3f0b79c2679f61))
* bump @types/node from 18.8.1 to 18.8.2 in /client ([#365](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/365)) ([04f5fcc](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/04f5fcc2d9d77a5a5b8ccab8680d500c7b1eb800))
* bump axios from 0.27.2 to 1.0.0 in /client ([#363](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/363)) ([f1baa0d](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/f1baa0d6531ac8837264f82a896304e345d88326))
* bump axios from 0.27.2 to 1.0.0 in /server ([#366](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/366)) ([4fea0a7](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/4fea0a70eb21c05b8911a3032001434bfc63dbb4))
* bump web-vitals from 3.0.2 to 3.0.3 in /client ([#364](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/364)) ([403e73c](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/403e73c29522be03e8826155663ade364669cea7))

## [0.14.0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.13.0...v0.14.0) (2022-10-04)


### Features

* **mongodb:** fetch secrets from aws secrets management ([#358](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/358)) ([98b2594](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/98b2594734278d3a6999a8fc9ca85ef712af9298))

## [0.13.0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.12.0...v0.13.0) (2022-10-04)


### Features

* **cognito:** adding the ability to disable cognito auth on api gateway ([#339](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/339)) ([f3a53de](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/f3a53def918b75cadeaf8e469d05d4a3b4a1c267))


### Bug Fixes

* adding sensitive keyword to mongodb password db ([#357](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/357)) ([67ed69e](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/67ed69e3615e3bbdf83bd3e67e587fda6ae49985))
* bump @aws-sdk/client-secrets-manager in /server ([#335](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/335)) ([beface1](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/beface13a824eb03061f6f10579279fc7d4dac11))
* bump @aws-sdk/client-secrets-manager in /server ([#338](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/338)) ([095e0e9](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/095e0e972f031597cf46530c929d67d34b426145))
* bump @aws-sdk/client-secrets-manager in /server ([#342](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/342)) ([af00b85](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/af00b85973ecd639ef7f2cb4ec61e1a99a642205))
* bump @aws-sdk/client-secrets-manager in /server ([#346](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/346)) ([b2737d5](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/b2737d562469d462ee157fdb5c0978daf61c9f15))
* bump @aws-sdk/client-secrets-manager in /server ([#356](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/356)) ([4e252cb](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/4e252cbfb23edc83fc77b1d753370b974cbc7ef0))
* bump @types/jest from 29.0.3 to 29.1.0 in /client ([#343](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/343)) ([5e1acb7](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/5e1acb74f7cedcd95a95959d600f1f5787639f28))
* bump @types/jest from 29.1.0 to 29.1.1 in /client ([#345](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/345)) ([2078d8e](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/2078d8e80f047b936a9fb5cee4454b962485d1a2))
* bump @types/node from 18.7.18 to 18.7.21 in /client ([#334](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/334)) ([190e765](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/190e7653d870bf34ed972c51d7090a9be294b855))
* bump @types/node from 18.7.21 to 18.7.23 in /client ([#336](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/336)) ([fd37fc0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/fd37fc01d7daa49bf20986be966ff907f60ce745))
* bump @types/node from 18.7.23 to 18.8.0 in /client ([#349](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/349)) ([6ce0cdc](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/6ce0cdc4cccc623faf56b9dee4260483d7c7bdf5))
* bump @types/node from 18.8.0 to 18.8.1 in /client ([#351](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/351)) ([139d949](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/139d949ecdac2b6d5533114eee4d25be07b0f4d1))
* bump aws-amplify from 4.3.36 to 4.3.37 in /client ([#348](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/348)) ([13bce68](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/13bce681ba0b9f821804efd13e116a1bd6a503f5))
* bump typescript from 4.8.3 to 4.8.4 in /client ([#341](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/341)) ([5d34605](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/5d346054fb6c76382d15b2b37ab74daa36fe822d))

## [0.12.0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.11.2...v0.12.0) (2022-09-25)


### Features

* **elastic beanstalk:** adding iam policy for ec2 ([#332](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/332)) ([d190135](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/d1901351a2aa8d4d1f4cf113d69f6edad215a2ba))

## [0.11.2](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.11.1...v0.11.2) (2022-09-23)


### Bug Fixes

* **build env:** adding the ability to pass variable to code build ([#330](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/330)) ([37e390b](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/37e390b83e73e9228d93b8412e6620e7ca7cc7a0))
* bump @aws-amplify/ui-react from 3.4.1 to 3.5.0 in /client ([#287](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/287)) ([56ca4e0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/56ca4e0253f7baf52628c4f201353413782b53a8))
* bump @aws-amplify/ui-react from 3.5.0 to 3.5.1 in /client ([#300](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/300)) ([c505df8](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/c505df8d1bf4fab5b9f4a714674b27d44c1f3b21))
* bump @aws-amplify/ui-react from 3.5.1 to 3.5.2 in /client ([#320](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/320)) ([9ff80e0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/9ff80e0d4546c44a1f121b3c7cfc99adf8275a2b))
* bump @aws-amplify/ui-react from 3.5.2 to 3.5.4 in /client ([#325](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/325)) ([9f4a423](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/9f4a4233d716f246a112110ef8cccee3ab32e6ad))
* bump @aws-sdk/client-secrets-manager in /server ([#289](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/289)) ([5e53b97](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/5e53b973701da89b544effde360259696d2fb5d6))
* bump @aws-sdk/client-secrets-manager in /server ([#294](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/294)) ([af69574](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/af695742727fab43ac2c8a5f279ef59949d09c95))
* bump @aws-sdk/client-secrets-manager in /server ([#296](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/296)) ([9b9cb56](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/9b9cb56cb6f60e33a73c7de5f6990677a1852833))
* bump @aws-sdk/client-secrets-manager in /server ([#301](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/301)) ([a642229](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/a6422292acad65be14144cd9906267c2374fc489))
* bump @aws-sdk/client-secrets-manager in /server ([#307](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/307)) ([9d576da](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/9d576da49c130212afd267254f5ffc5064c03b72))
* bump @aws-sdk/client-secrets-manager in /server ([#309](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/309)) ([0384a27](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/0384a274811a93bca60740358792bfb54815d7e6))
* bump @aws-sdk/client-secrets-manager in /server ([#317](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/317)) ([171c5d1](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/171c5d1e1e10583f20f17d63e236b25814bb6bd9))
* bump @aws-sdk/client-secrets-manager in /server ([#319](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/319)) ([9e745a0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/9e745a0eb3dd5c7f01c39dc10be8d9f332c02473))
* bump @testing-library/react from 13.3.0 to 13.4.0 in /client ([#297](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/297)) ([8fb231c](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/8fb231c68aacadc2c1e8413dd329954491e18958))
* bump @types/jest from 29.0.0 to 29.0.1 in /client ([#306](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/306)) ([db0c299](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/db0c299810760fc878247b8e79702ef464f41e7e))
* bump @types/jest from 29.0.1 to 29.0.2 in /client ([#315](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/315)) ([99bd13f](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/99bd13f72ca022c7e5cd827197e650d6097b6d7c))
* bump @types/jest from 29.0.2 to 29.0.3 in /client ([#321](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/321)) ([0e6589b](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/0e6589b09954c95817dbc9bdda52610d81de9789))
* bump @types/node from 18.7.14 to 18.7.15 in /client ([#298](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/298)) ([0a797a5](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/0a797a549540cafe37e66e581a3f86f9f8709558))
* bump @types/node from 18.7.15 to 18.7.16 in /client ([#302](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/302)) ([7c206c0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/7c206c05debbb20df59bd231463d2ffcab7d6e29))
* bump @types/node from 18.7.16 to 18.7.17 in /client ([#308](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/308)) ([842e64f](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/842e64fd92b90a551a2a84c87fda6a437032c24e))
* bump @types/node from 18.7.17 to 18.7.18 in /client ([#314](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/314)) ([93895a5](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/93895a5953d5c92ad1b1da9ef29541dd16905c2c))
* bump @types/react from 18.0.17 to 18.0.18 in /client ([#288](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/288)) ([c42d406](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/c42d406754e4d16e36143a4e4e2e8abd536d36c1))
* bump @types/react from 18.0.18 to 18.0.19 in /client ([#305](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/305)) ([6d94a8d](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/6d94a8d977dc3009150871548254a7fc82084802))
* bump @types/react from 18.0.19 to 18.0.20 in /client ([#313](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/313)) ([dafae9b](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/dafae9bf824fad69b77c2a65c32cd945861682c0))
* bump @types/react from 18.0.20 to 18.0.21 in /client ([#329](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/329)) ([8cc12c0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/8cc12c0d03d8522dd724e83471d737f1287e1e6a))
* bump aws-amplify from 4.3.33 to 4.3.34 in /client ([#295](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/295)) ([f39a64c](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/f39a64ce576c185c0993019c3019d2fb5045017d))
* bump aws-amplify from 4.3.34 to 4.3.35 in /client ([#303](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/303)) ([b6fc250](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/b6fc250a53ff5234fff49784b3ba865f6e105da0))
* bump aws-amplify from 4.3.35 to 4.3.36 in /client ([#326](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/326)) ([a00b63a](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/a00b63a492730efe9441d1fc89d61ad7fc87c0f2))
* bump mongodb from 4.9.0 to 4.9.1 in /server ([#292](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/292)) ([03ddc6b](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/03ddc6ba1fb93abfcdb2d3452c550bbecdf2e394))
* bump mongodb from 4.9.1 to 4.10.0 in /server ([#324](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/324)) ([3a35b2c](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/3a35b2cf8bb5e9ebbe82cf206060d9aefa9ccc1d))
* bump typescript from 4.8.2 to 4.8.3 in /client ([#304](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/304)) ([194be60](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/194be60fb93c1e8a171015f305dd299019c4e842))
* bump web-vitals from 3.0.0 to 3.0.1 in /client ([#290](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/290)) ([b85a8ae](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/b85a8ae53cf4a3ef2ef097d51904d2b0fedc69e0))
* bump web-vitals from 3.0.1 to 3.0.2 in /client ([#322](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/322)) ([6ec72fc](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/6ec72fcc1952e104e9e2d094e58daf22a0d9c1fe))

## [0.11.1](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.11.0...v0.11.1) (2022-08-30)


### Bug Fixes

* bump @aws-sdk/client-secrets-manager in /server ([#281](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/281)) ([a9e330f](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/a9e330f5d3c06534e222be8955f5da75e75b5889))
* bump @aws-sdk/client-secrets-manager in /server ([#284](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/284)) ([c372730](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/c37273094d20fef20888085ac7b5644b63cca972))
* bump @types/jest from 28.1.8 to 29.0.0 in /client ([#282](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/282)) ([369992d](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/369992d8d901939f6c8652e2a3e25260f32f7027))
* bump @types/node from 18.7.13 to 18.7.14 in /client ([#283](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/283)) ([6c47c12](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/6c47c129a540268e1611dc0e88ce57003c8fe08f))

## [0.11.0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.10.0...v0.11.0) (2022-08-28)


### Features

* **cognito:** username case insensitive ([#277](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/277)) ([fc2db46](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/fc2db46d8f9eb5d0b212d63f313d85faa40906b1))


### Bug Fixes

* bump @types/jest from 28.1.7 to 28.1.8 in /client ([#273](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/273)) ([7c26046](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/7c26046bb1800f294eeed84cddc95a0f395d79f7))
* bump @types/node from 18.7.11 to 18.7.12 in /client ([#268](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/268)) ([a1493f6](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/a1493f66ec383b7571923e0d1ff4d1fd09f52fa8))
* bump @types/node from 18.7.12 to 18.7.13 in /client ([#271](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/271)) ([f5c482c](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/f5c482c3e29ef231e60380f37de621f8045d8c05))
* bump @types/node from 18.7.9 to 18.7.11 in /client ([#267](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/267)) ([9578cb9](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/9578cb9f3592a036daedd78b2331bfdebe29d62a))
* bump aws-amplify from 4.3.32 to 4.3.33 in /client ([#269](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/269)) ([904ea77](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/904ea776182c35ec782038137af6874c425103a6))
* bump typescript from 4.7.4 to 4.8.2 in /client ([#274](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/274)) ([80c2751](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/80c2751c4dbac1fb2d6a4606133a254f22665457))
* bump web-vitals from 2.1.4 to 3.0.0 in /client ([#272](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/272)) ([448447b](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/448447bedebbbdfdf0e066bbbf0ec69fc676dca5))

## [0.10.0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.9.0...v0.10.0) (2022-08-22)


### Features

* **cicd:** support passing environment to build stage ([#266](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/266)) ([013134e](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/013134ec99cf2b3098aaf55e8579a9071f9a059d))


### Bug Fixes

* bump @aws-amplify/ui-react from 3.1.0 to 3.2.1 in /client ([#213](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/213)) ([d5599ab](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/d5599ab8c05e4e61a857b7f937d4af78b5daecc1))
* bump @aws-amplify/ui-react from 3.2.1 to 3.3.0 in /client ([#229](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/229)) ([139a96f](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/139a96f5e7e666a10eecc4ff9bec36316c76befb))
* bump @aws-amplify/ui-react from 3.3.0 to 3.4.0 in /client ([#247](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/247)) ([cd6cc0d](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/cd6cc0d2e0f1330f291f865d5f10b4df30b22437))
* bump @aws-amplify/ui-react from 3.4.0 to 3.4.1 in /client ([#259](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/259)) ([1818cc8](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/1818cc8b29c0d2670673a3fabc8911da2a6723a6))
* bump @aws-sdk/client-secrets-manager in /server ([#206](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/206)) ([ce7267b](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/ce7267b6395c18cc0461829ba32ed55497fd7f20))
* bump @aws-sdk/client-secrets-manager in /server ([#214](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/214)) ([d19a3b9](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/d19a3b92495c41d46f7e76184bfafca7838e5d55))
* bump @aws-sdk/client-secrets-manager in /server ([#239](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/239)) ([f311aca](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/f311acac7a3f1dca12fcd40f4291878ee7606bea))
* bump @aws-sdk/client-secrets-manager in /server ([#257](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/257)) ([303e111](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/303e11155f4bedd15b009115371bc2ee54408291))
* bump @aws-sdk/client-secrets-manager in /server ([#262](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/262)) ([4229154](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/4229154e1739e3fd5cf5048ae675e73f25c0559f))
* bump @aws-sdk/client-secrets-manager in /server ([#265](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/265)) ([a2d319d](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/a2d319d5f77520b649d6f16450c37f1ce25ffb92))
* bump @testing-library/jest-dom from 5.16.4 to 5.16.5 in /client ([#233](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/233)) ([0c03816](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/0c03816b7644647eae1d7f6a152ad1d40609e183))
* bump @testing-library/user-event from 14.2.3 to 14.4.3 in /client ([#240](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/240)) ([350ca38](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/350ca3827e25c71468aefecc6a14c591bfdcbf94))
* bump @types/jest from 28.1.4 to 28.1.5 in /client ([#193](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/193)) ([b758384](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/b75838436f3df6117b79145bf8debff09520b083))
* bump @types/jest from 28.1.5 to 28.1.7 in /client ([#255](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/255)) ([7c2eccf](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/7c2eccf5841692b9f27fd862005765f16cb5c46c))
* bump @types/node from 18.0.4 to 18.6.1 in /client ([#211](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/211)) ([0d31af8](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/0d31af86ce29cfdad928090ff3d39341d32b125f))
* bump @types/node from 18.6.1 to 18.6.5 in /client ([#238](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/238)) ([a7f1a2d](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/a7f1a2dd4d170779162611b8b889e0116117730e))
* bump @types/node from 18.6.5 to 18.7.1 in /client ([#244](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/244)) ([289ff5f](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/289ff5fd48b5e5ab828a72d9f23c4281782a3937))
* bump @types/node from 18.7.1 to 18.7.3 in /client ([#250](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/250)) ([e14f3b9](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/e14f3b9e817f8c0cbcc4b56e88d6e87acee39ec0))
* bump @types/node from 18.7.3 to 18.7.5 in /client ([#253](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/253)) ([b62c768](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/b62c768a6d216b9b9233896f41b09e63478b7de4))
* bump @types/node from 18.7.5 to 18.7.6 in /client ([#258](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/258)) ([e0a3e43](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/e0a3e439e4291e96b1260e841bd590b812dc3d27))
* bump @types/node from 18.7.6 to 18.7.9 in /client ([#264](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/264)) ([3f26809](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/3f2680910484d3ebcb9f94b0c6ed2f7943ceaf26))
* bump @types/react from 18.0.15 to 18.0.17 in /client ([#245](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/245)) ([8d7047a](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/8d7047a26b09762d2447f2fd5ac098f8341c4625))
* bump aws-amplify from 4.3.27 to 4.3.30 in /client ([#223](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/223)) ([0505c0a](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/0505c0aa66be8f9378849b2f1040ddc7cbb7eff6))
* bump aws-amplify from 4.3.30 to 4.3.31 in /client ([#254](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/254)) ([c3ad3ed](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/c3ad3edf63470754c3b12d6289a8fe70a46a5a43))
* bump aws-amplify from 4.3.31 to 4.3.32 in /client ([#261](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/261)) ([40ec497](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/40ec497b00dad6181c36c47ab916d1dc2acb41f6))
* bump mongodb from 4.8.0 to 4.8.1 in /server ([#215](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/215)) ([7ae5726](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/7ae572644d704b788311562e3af6fd02d4224d92))
* bump mongodb from 4.8.1 to 4.9.0 in /server ([#263](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/263)) ([cbe6254](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/cbe62541c0be83db493abc783412dd53d9238337))
* bump terser from 5.13.1 to 5.14.2 in /client ([#210](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/210)) ([77684bc](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/77684bc02fe42dc4b3402c2baf54b95d62d3252e))
* pre commit warning ([#237](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/237)) ([8bf9513](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/8bf951360fd4b0b9fdb472a6cd72cc78a32f1725))

## [0.9.0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.8.3...v0.9.0) (2022-07-15)


### Features

* Codestar connection Github v2 ([#201](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/201)) ([df1e9ee](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/df1e9eeef2f7b1af3e4058748bc83d244ddc9602))


### Bug Fixes

* bump @aws-amplify/ui-react from 3.0.4 to 3.1.0 in /client ([#194](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/194)) ([d79dca6](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/d79dca6d61afec551f7d094dbf6e9ae403916f26))
* bump @aws-sdk/client-secrets-manager in /server ([#195](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/195)) ([f9079e9](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/f9079e94e36a6854c4a49f4c74dde7f9d7ee5fb3))
* bump @aws-sdk/client-secrets-manager in /server ([#200](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/200)) ([61f59ea](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/61f59eab584bda99ae4a93b2db4348172de0a0f4))
* bump @testing-library/user-event from 14.2.1 to 14.2.3 in /client ([#199](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/199)) ([1030ab9](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/1030ab9b28272c30564a9925cefd6071b50ea26d))
* bump @types/node from 18.0.3 to 18.0.4 in /client ([#196](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/196)) ([8885aee](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/8885aee64ea8b0d54dc1a366137233887c74f01b))
* bump mongodb from 4.7.0 to 4.8.0 in /server ([#197](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/197)) ([52b603b](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/52b603b5fc4359397837ca70895e010175375421))

## [0.8.3](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.8.2...v0.8.3) (2022-07-10)


### Bug Fixes

* bump @aws-amplify/ui-react from 3.0.3 to 3.0.4 in /client ([#188](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/188)) ([a3c4ca4](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/a3c4ca4e41f16de1ab34cdd603cf833950a9f655))
* bump @aws-sdk/client-secrets-manager in /server ([#184](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/184)) ([73cdb92](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/73cdb9249db44eb3f20e055ddfd2df711323c7d3))
* bump @types/node from 18.0.0 to 18.0.1 in /client ([#182](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/182)) ([9f324d8](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/9f324d8546048a116dc0bc700e18bab0079e66d1))
* bump @types/node from 18.0.1 to 18.0.3 in /client ([#187](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/187)) ([3c7a3f8](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/3c7a3f8e3a9a049bab85acefe29ea4389bf736d0))
* bump @types/react from 18.0.14 to 18.0.15 in /client ([#186](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/186)) ([a85fffb](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/a85fffb63028824fa99c8f690b263c01fcec1a70))
* bump @types/react-dom from 18.0.5 to 18.0.6 in /client ([#189](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/189)) ([44bff1d](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/44bff1db4a3047eb49926c624556a29d3c186766))
* bump aws-amplify from 4.3.26 to 4.3.27 in /client ([#190](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/190)) ([0c04a09](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/0c04a09412cdf5b171f92a1707b42235e5f1ff00))

## [0.8.2](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.8.1...v0.8.2) (2022-07-02)


### Bug Fixes

* bump @aws-amplify/ui-react from 3.0.2 to 3.0.3 in /client ([#179](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/179)) ([54d3e97](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/54d3e97cdb61587ebf95adc890136b512b0fcedb))
* bump @aws-sdk/client-secrets-manager in /server ([#173](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/173)) ([a3456d6](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/a3456d6a1acd1498edcb450ed168978d7bf360af))
* bump @aws-sdk/client-secrets-manager in /server ([#178](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/178)) ([34a57c8](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/34a57c8dc96110dbc75216697e46cd389fec0dfc))
* bump @types/jest from 28.1.3 to 28.1.4 in /client ([#180](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/180)) ([20e3ef7](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/20e3ef74209d0e1f3c3ae4f098841fa74a2a9341))
* **lambda:** Add Environment ([#181](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/181)) ([d326938](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/d326938046e3c7a084eacf3785153c4a98a53ede))

## [0.8.1](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.8.0...v0.8.1) (2022-06-27)


### Bug Fixes

* bump @aws-amplify/ui-react from 2.19.1 to 3.0.0 in /client ([#162](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/162)) ([18ff6a1](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/18ff6a13c67c43b5d2bf2dca7b9ae6d364b89764))
* bump @aws-amplify/ui-react from 3.0.0 to 3.0.1 in /client ([#167](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/167)) ([23344cb](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/23344cb9d3e6445366d94426c761ea42a0f45b7f))
* bump @aws-amplify/ui-react from 3.0.1 to 3.0.2 in /client ([#169](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/169)) ([89cdb98](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/89cdb986faaf95813c9af1811eaac666e4a865eb))
* bump @aws-sdk/client-secrets-manager in /server ([#147](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/147)) ([fefbfac](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/fefbfac68611f61711a7cdd1afd96f1a4a634435))
* bump @aws-sdk/client-secrets-manager in /server ([#150](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/150)) ([f4290d2](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/f4290d2d190f8ab61531d858c83e29c48d3686af))
* bump @aws-sdk/client-secrets-manager in /server ([#159](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/159)) ([b3b7bb8](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/b3b7bb8818c8025cfeeb72ca9b144b3d150bd38e))
* bump @testing-library/user-event from 14.2.0 to 14.2.1 in /client ([#161](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/161)) ([323616a](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/323616ac38b824c8028cf0d3a66a03cc8b40327c))
* bump @types/jest from 28.1.1 to 28.1.3 in /client ([#166](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/166)) ([56b3e90](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/56b3e9016bbb5f4255373f0034cf53650af28dc0))
* bump @types/node from 17.0.41 to 17.0.42 in /client ([#146](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/146)) ([a04e5a8](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/a04e5a8cf474266ce0da8b5fee0549966f35159e))
* bump @types/node from 17.0.42 to 18.0.0 in /client ([#157](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/157)) ([e257e44](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/e257e446019c399b0f895bc5a1c79bc68f1384a3))
* bump aws-amplify from 4.3.23 to 4.3.26 in /client ([#160](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/160)) ([a025c5e](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/a025c5e1db961a4829413b63a43d777230bfa9f7))
* bump mongodb from 4.6.0 to 4.7.0 in /server ([#148](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/148)) ([95a9da7](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/95a9da71a26dda1799a1a422f20396135ea8b74d))
* bump react and @types/react in /client ([#164](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/164)) ([0b2baee](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/0b2baee6246afc556f3970dcb473327f8762d8b9))
* bump react-dom from 18.1.0 to 18.2.0 in /client ([#168](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/168)) ([d4aa144](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/d4aa144866717637f106bad661a0df9da5d846fc))
* bump typescript from 4.7.3 to 4.7.4 in /client ([#163](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/163)) ([e943720](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/e943720eabc6567a62c24f02b1367c8cdcc59852))
* upgrade aws-amplify from 4.3.23 to 4.3.24 ([#155](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/155)) ([38f8a08](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/38f8a0827a0fffa7554d67d609434dbdfa4c1890))

## [0.8.0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.7.1...v0.8.0) (2022-06-11)


### Features

* removing security base line from module added as a side module ([#144](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/144)) ([768f842](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/768f842992711d05533107e680703956ff5dbe24))

## [0.7.1](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.7.0...v0.7.1) (2022-06-11)


### Bug Fixes

* Change the way we implement white list ip's. now if enable the `… ([#132](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/132)) ([683851b](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/683851b8eb571a40f3ef4231cdf728df068bf51f))

## [0.7.0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.6.0...v0.7.0) (2022-06-11)


### Features

* adding env variable for server build ([#141](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/141)) ([c290371](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/c2903711e40b06d9beed341fe0ca8eabab58cd6d))

## [0.6.0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.5.2...v0.6.0) (2022-06-10)


### Features

* adding support for NX env file ([#140](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/140)) ([967ef5b](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/967ef5b5b366360c60943c7e1709feb0c5ba689e))


### Bug Fixes

* bump @aws-amplify/ui-react from 2.19.0 to 2.19.1 in /client ([#138](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/138)) ([b9e1539](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/b9e1539b913eb0a03eee248e275052afc5614b20))
* bump @aws-sdk/client-secrets-manager in /server ([#135](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/135)) ([1be967e](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/1be967ecaffec5c69863ec30f2b0b1b7206d9d59))
* bump @types/jest from 28.1.0 to 28.1.1 in /client ([#126](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/126)) ([8384866](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/83848668e293a4780f6a431f56ec85ca435be354))
* bump @types/node from 17.0.38 to 17.0.40 in /client ([#127](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/127)) ([9187975](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/9187975ca1627ef2817e3ce0d398d76f10ef501c))
* bump @types/node from 17.0.40 to 17.0.41 in /client ([#137](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/137)) ([054d4d2](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/054d4d2c2ca76436ea6ca7d4d7036435f9e2798c))
* bump @types/react from 18.0.10 to 18.0.12 in /client ([#125](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/125)) ([030774e](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/030774ed48e0cff83a27d4ced95d972b35abf8cf))
* bump mongodb from 4.6.0 to 4.7.0 in /server ([#136](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/136)) ([69a9e30](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/69a9e307ac401212b8839934520db745e767eeb3))
* bump typescript from 4.7.2 to 4.7.3 in /client ([#124](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/124)) ([c3c7a91](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/c3c7a91f0e941a6947e08130d3d4bd0490f37acd))

## [0.5.2](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.5.1...v0.5.2) (2022-06-06)


### Bug Fixes

* update paramter name in vpc module ([#130](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/130)) ([3baa484](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/3baa48415210313f6a2fc55fb00b4b92910c5f4f))

## [0.5.1](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.5.0...v0.5.1) (2022-06-04)


### Bug Fixes

* bump @aws-amplify/ui-react from 2.18.3 to 2.19.0 in /client ([#116](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/116)) ([6be0c44](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/6be0c440077e74366417f9ec52237c8aa811d2c4))
* remove the check only for a specific rule ([#121](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/121)) ([d73c722](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/d73c722ebe3e3add34e1d2663001fa3ecd39108e))

## [0.5.0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.4.0...v0.5.0) (2022-06-02)


### Features

* adding default encryption in all account ebs ([#115](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/115)) ([fc6483a](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/fc6483ae98f4351187abdc0639b212b2556399da))
* adding scaling group as a prameter ([#113](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/113)) ([b667020](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/b6670201336090ae29dfc96af6de38091490d9cb))

## [0.4.0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.3.0...v0.4.0) (2022-06-02)


### Features

* adding full path for buildspec.yml file for server and client ([#112](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/112)) ([f74f2c6](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/f74f2c60deb1490c7193dc07825362c5bc7dfb74))


### Bug Fixes

* bump @types/jest from 27.5.1 to 28.1.0 in /client ([#110](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/110)) ([f48c26e](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/f48c26e805beaef9857c1a2dc7a879db54096da0))
* bump @types/node from 17.0.36 to 17.0.38 in /client ([#105](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/105)) ([ae5c1cd](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/ae5c1cd4dc5eb1f3d33dcb589fd23faa288b20ee))
* bump @types/react from 18.0.9 to 18.0.10 in /client ([#106](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/106)) ([8de04a4](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/8de04a454c00220ea7571297b557b4da8983fb70))
* change default atlas instance name ([#111](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/111)) ([26edc36](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/26edc36073e397d265d6a06130cb70bdd1a94d94))

## [0.3.0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.2.2...v0.3.0) (2022-05-31)


### Features

* Adding mongodb cluster type as a parameter, by default will use… ([#103](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/103)) ([7a1234a](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/7a1234a51feaa2767f98a6fba548efe9a087a9ce))


### Bug Fixes

* bump @testing-library/react from 13.2.0 to 13.3.0 in /client ([#99](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/99)) ([d242d21](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/d242d215c8c3078350d8093bfa579f3e1588b8e0))

### [0.2.2](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.2.1...v0.2.2) (2022-05-28)


### Bug Fixes

* bump @testing-library/user-event from 14.1.1 to 14.2.0 in /client ([#94](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/94)) ([be7de14](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/be7de1414e978028ed7700b955bda733cb40a9f2))
* bump @types/jest from 27.4.1 to 27.5.1 in /client ([#93](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/93)) ([900a1d9](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/900a1d9d9de30eb55f5cd3ede19e296f906662a7))
* bump @types/node from 17.0.31 to 17.0.35 in /client ([#72](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/72)) ([0de1c29](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/0de1c29a9375174dd42a78f59db1d29cc148c671))
* bump @types/node from 17.0.31 to 17.0.36 in /client ([#97](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/97)) ([5a924f2](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/5a924f23b8dc06c8e7c8433d605b73e393f7b771))
* bump @types/react-dom from 18.0.3 to 18.0.5 in /client ([#92](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/92)) ([2262422](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/22624228f3fa26fb0a334b62c418cf76a58e740f))
* bump typescript from 4.6.4 to 4.7.2 in /client ([#95](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/95)) ([44291c2](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/44291c26c8c2d01dea916074b68004f0e7298a32))

### [0.2.1](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.2.0...v0.2.1) (2022-05-28)


### Bug Fixes

* bump @aws-amplify/ui-react from 2.15.8 to 2.18.3 in /client ([#86](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/86)) ([22d24ae](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/22d24ae8390029c5ab0f74e26cbb2eb74436369e))
* bump @aws-sdk/client-secrets-manager in /server ([#87](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/87)) ([cec5e0f](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/cec5e0ff6d239825e607ecfe1f1432f53b5c1fe8))
* bump aws-amplify from 4.3.20 to 4.3.23 in /client ([#84](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/84)) ([7e71367](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/7e71367e992cd894d9618029ba6abdf99f5d76f0))
* upgrade @testing-library/react from 13.1.1 to 13.2.0 ([#82](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/82)) ([7f432db](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/7f432dbd731b939d79701a4d8a304b2d15434c0a))
* upgrade @types/jest from 27.4.1 to 27.5.0 ([#78](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/78)) ([7186cfe](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/7186cfec81c13ab19a84e3c94598e76eb32d1137))
* upgrade @types/react from 18.0.8 to 18.0.9 ([#88](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/88)) ([1c9735a](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/1c9735abb50bff26c243146cb34a61b79043a19d))

## [0.2.0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.1.8...v0.2.0) (2022-05-28)


### Features

* adding client and server ci on github action ([#89](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/89)) ([844fadd](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/844fadd6f5f7e4825e51b84bd0303d483a4e676a))

### [0.1.8](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.1.7...v0.1.8) (2022-05-14)


### Bug Fixes

* Adding missing libs amplify ([#52](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/52)) ([f88834e](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/f88834ef0ea4a52f7679e215d62def4f0c94883c))

### [0.1.7](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.1.6...v0.1.7) (2022-05-14)


### Bug Fixes

* Add missing lib ([#50](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/50)) ([c88b514](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/c88b514a5e412c4b63b0cc4cf143f620a9a441e5))

### [0.1.6](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.1.5...v0.1.6) (2022-05-14)


### Bug Fixes

* change versions in react to succeed complete the build in aws codebuild ([#48](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/48)) ([02ce9b3](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/02ce9b36688619392a520214fa63f9dd0122cb3a))

### [0.1.5](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.1.4...v0.1.5) (2022-05-14)


### Bug Fixes

* codebuild node version 18 not supported ([#46](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/46)) ([e3f6479](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/e3f6479f67c666fec0cc3298b2fe45e78bac2971))

### [0.1.4](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.1.3...v0.1.4) (2022-05-14)


### Bug Fixes

* change react version ([#44](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/44)) ([1a31943](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/1a31943c56c577285110713743b01b7993006fd4))

### [0.1.3](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.1.2...v0.1.3) (2022-05-14)


### Bug Fixes

* codebuild node version changeing ([#42](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/42)) ([56cc507](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/56cc507576efb25d6f39080d369b29dd1db5dd99))

### [0.1.2](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.1.1...v0.1.2) (2022-05-13)


### Bug Fixes

* description ([0977165](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/09771657a2157f5fd187036279c21bffcc0a81c2))

### [0.1.1](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/v0.1.0...v0.1.1) (2022-05-13)


### Bug Fixes

* syntax error in yml file ([#34](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/34)) ([32346c3](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/32346c3bcebccfefb4bafcd413641f524b7d8946))

## [0.1.0](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/compare/0.0.4...v0.1.0) (2022-05-13)


### Features

* ([#21](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/issues/21)) ([87bba94](https://github.com/MoveoTech/terraform-aws-rest-api-architecture/commit/87bba942dffd208e1116c4dbcc46df17af8d0471))
