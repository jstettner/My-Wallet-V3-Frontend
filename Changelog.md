__Blockchain HD Frontend__

_Recent changes_

#   (2015-09-24)



---

## Bug Fixes

- **Addresses:** show either fiat or btc but not both in Address view
  ([39fc0f80](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/39fc0f80515099dab98028d832cde85c21176777))
- **CSP:**
  - switch to ui-select fork to avoid unsafe-inline
  ([b366db87](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/b366db8709559e7cb5950a6d20b002d3dc841f52))
  - frame-src is depricated, setting child-src to non
  ([aebd8d45](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/aebd8d45e4756b25715f5c4883970032b8914b55))
  - added media-src: blob: for Chrome 45.
  ([f465acd9](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/f465acd9415484232de88ad625fcd47068253fc6))
- **Send:** pasted watch only address sticks
  ([017735b5](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/017735b5a059c665ee893185641363daa4ea13e4))
- **UI:**
  - don't wrap on login button, hide hand icon on small devices
  ([c46f62eb](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/c46f62ebe739db80dd45c79fb70d6964ecf22637))
  - use CSS to override dynamic class name rendering in AF
  ([a6bd2dcd](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/a6bd2dcd81716e1178ebe1fe392be45d9c25c6de))
  - align two-step icons to bottom
  ([445084aa](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/445084aa39ff4f30025b1873a173999d2549a2fc))
  - refactor back button using icon instead of png
  ([42bd9b2e](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/42bd9b2e09c0bc0d15d1aad6eba22ff20a33e4c5))
  - take out auto centering for IE
  ([38558928](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/38558928bbc34fec444358a5716b5be028f46043))
  - qr scanner should flow below in Send modal
  ([dc811b3a](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/dc811b3a4335cce2615955a1f42b6c31b42fcd9c))
  - give setting views breathing room at bottom
  ([dfaa96d8](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/dfaa96d80e7eb935f50acf0bea94ce8ee545a4e6))
  - receive modal input widths auto sizing issues
  ([a6123cf7](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/a6123cf7602a660a51b0a19218175bc8797ec84e))
  - hide input spinners on -webkit, change class name on bc-async-input (padding only necessary)
  ([e9f1a11c](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/e9f1a11cff5046992c02aa45621598e1b06581ed))
  - normalize search fields so they match transactions screen, make sure buttons don't break
  ([aed74541](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/aed745416be573cffbb2e0853235ced0ab129122))
  - use some creative css to make sure sections don't overlap across various screen sizes in the home page
  ([0958dd07](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/0958dd0753f50ac0cf12bbd5ac12ee6c5aa5d540))
  - move alerts in app to top right, fix authorization success msg, fix helper text widths on smaller screens, give max-height to advanced send modals
  ([d7f6e623](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/d7f6e623937415ca61e3b77e352d4bd395597b9f))
  - remove auto margin so that IE can flex correctly
  ([0931d56b](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/0931d56b1173fbc40caa774743b8223d23150987))
  - simplify navbar logo/menu CSS
  ([5098145b](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/5098145bac3fe58c1de4a5b614e0df303189cd95))
  - rm .form-group class from directive
  ([94bb3a6c](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/94bb3a6cef9c4ef7e8f210bb427a499d41b5496b))
- **addresses:** prevent user from generating HD address after upgrade before sync is complete
  ([86e8cd8c](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/86e8cd8c17ecfd05d28bfe0f19f9d507ad984587))
- **admin:** show results of activating in modal
  ([d81ebb1d](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/d81ebb1d3cc2309fcea44eba479f345ffc3db8b8))
- **alerts:** Modals have their own alert contexts
  ([1f12b51b](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/1f12b51b67c05114ffcf71bf73421a7c4fc03b63))
- **bc-async-input:** cancel after submit no longer undoes the previous change
  ([4d38ad77](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/4d38ad77f20e6f2cae32b1fc002b6aba61d253cd))
- **contextualMessage:** add missing 0 to balance check
  ([120e947b](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/120e947b1b13ae97ce6f3fd24ec5bbc188a0858a))
- **copy:** swap out from/to
  ([2b7d728b](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/2b7d728b4c4b197201e712cb4e252b0291ee5f1b))
- **dyk:** translate strings in view rather than in service
  ([db5f06c3](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/db5f06c3d10557b4a5054dc24cbf71ff7452e3d0))
- **empty-state:** remove unnecessary check which was causing it not to appear correctly
  ([b654f796](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/b654f796729aea088e359399b398d4bec4b4a1eb))
- **inline-styles:** remove inline style from directive template
  ([a6367f29](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/a6367f29ceb031fff409b9a45c923d46cd86ff46))
- **mobile-safari:** change header css so icons align nicely, remove unnecessary padding and margin + old css
  ([0a6d1b04](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/0a6d1b04a18677a1c3210a0f733f536eb927e223))
- **mock:** typo in payment mock
  ([26ff983a](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/26ff983af6f81b520266c929e98eed87c99cc9f7))
- **recovery:** set working to false on error
  ([2e32e2e2](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/2e32e2e236a96e5518b1d42f60bc8cd48235db8a))
- **responsiveUI:**
  - use flex on header, position fix body viewport
  ([ff635ec6](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/ff635ec6882715cdf3ba3a6932f870ceeb427b73))
  - go with a less is more approach on mobile, add some spacing to tx-addrs on tablet sized resolutions
  ([d0621e31](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/d0621e3168cad0138be09f669de55c4682435c6f))
- **secondPasswordCtrl:** Change second password cancel message
  ([768c2c92](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/768c2c92f34cc7d8fb7a7e8738ce4efc8762c32e))
- **send:**
  - make sure all fields are set and rebuild payment before trying to send
  ([84ca8dae](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/84ca8dae66e52d3723180fece9ca93ef751fcb66))
  - force payment fee when changing to advanced send
  ([b6378ab5](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/b6378ab573d1bbf80e84363ac73f0ed6bd827623))
  - take custom fee into account when validating amount
  ([77327c5e](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/77327c5e7cea647b4702d5465f7eb3a43e481d6b))
  - from field label stays static when fee changes
  ([182578fc](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/182578fce5d7472e33c64baecd45cb597d1022e9))
  - to label displays correctly depending on the destinations
  ([c53ad049](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/c53ad049eb337e0f242257c29d2b1210e19dcb99))
- **sendCtrl:**
  - check and make sure no destinations are null
  ([58eb4ce6](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/58eb4ce63aa1af2a167dc6a8e47da2df53edae92))
  - update payment when usd value changes or address is pasted
  ([56cd7c19](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/56cd7c19772a01fba33191f30ef67d267ba11005))
  - set to and amount in case of payment request
  ([b90e069a](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/b90e069a29fcff3f7cce4ae980d6582ac78c2ad9))
  - allow saving public note
  ([6d61aef7](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/6d61aef7c6eb57854b12667f8cbf92cd556f4e89))
  - fixes ui-select dropdown after pasting
  ([62b01308](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/62b013080ce1caba1caf303c9019efe348a983a6))
- **transactions-feed:** watch the account index and fetch more tx's for that account, update test suite with mocked up MyWallet
  ([5ede55fa](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/5ede55fa3bf2d9879c94decf61abea2105a3044e))
- **translateMock:** Add .instant to mock
  ([b609f186](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/b609f18690afe9097631547f51410a0fb0726d5e))
- **upgrade:** Insist on 2nd password more clearly. Show spinner.
  ([8f0e7acb](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/8f0e7acb014477c6294535018b01140b0925108f))
- **verify-mobile-number:**
  - link for resending verification code
  ([4b9e8d14](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/4b9e8d14727339c0a585d0560d4d4ec86cc8e6bb))
  - reset verification code and error message on completion
  ([17e047fc](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/17e047fc1db68d9c3a18524fe23cb27f7d9f3eb1))


## Features

- **<noscript>:** Tell user to enable JavaScript
  ([4e5b06f0](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/4e5b06f0feb570e2e5a4dd0554db58a589748d4a))
- **Accounts:** reveal account xpub
  ([114e5d1f](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/114e5d1fd60073659f52145096625ed645d1a1d7))
- **Home:**
  - comment out legacy addresses for now, minor ui tweaks
  ([bf8d96ee](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/bf8d96ee6e8e41dcf9f7a45efb5e194bc87ecd99))
  - show legacy only if there's value, fix test
  ([969467f1](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/969467f1178d336d02529a9e3c3626de8d50c4c2))
  - add tabular account balance data, rm related tests
  ([8df1e934](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/8df1e934f30e8b93acc19936ee6978ac66cdd6fd))
- **UI:**
  - inline to rows in modals, right align labels
  ([1723c432](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/1723c432979d23dd1d5c1a53900d317c7ba54779))
  - make wallet navigation on mobile take up entire height of screen, shift toggle menu to right hand side
  ([a6c369a0](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/a6c369a0f4a2174855db21bf9161142d5bcae64a))
- **Xpub:** display warning to user before revealing Xpub
  ([cced1ffd](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/cced1ffdf9822c91ff451932f3b3f6f2f6b63097))
- **browser:** drop support for Safari 3, 4 & 5
  ([97c26809](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/97c2680916b84735e461e9412eaefafa095c09f2))
- **design:**
  - add @media query for better responsive behavior in scrolling & left menu
  ([7cb3ee44](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/7cb3ee448f26f6181463386895c9368211f0f617))
  - add "be your own bank"/branding
  ([b855be43](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/b855be430d86b6443bb098bf21e050efc7f9607d))
- **ladda-spinner:** remove gif, use a pure CSS3 spinner instead
  ([ecabaad2](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/ecabaad2c0e71a738d00c0845ca49bc4137e4356))
- **no script:** cross browser CSS to center the msg
  ([7d9fcd5a](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/7d9fcd5ad7c6b57581bcc43124fab4a4132ea664))
- **payment:** create wrapper for wallet-payment.js
  ([529f9ed4](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/529f9ed4cf1e751f20c8c253af4ca3574509789b))
- **recovery:** Recover funds markup and controller
  ([4693eee7](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/4693eee7f74d89118d3b02cae34a32bf16aea612))
- **security-center:** set default score > 0 for new wallet creation
  ([a4cc21d9](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/a4cc21d9d61311a83ede809f093e5a60c5731372))
- **signup:** remove email verification step
  ([32df37c9](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/32df37c9f6fa7b115beba0489f6fa7dd2db8e058))
- **walletRecovery:** add styles, ux, & references to new files
  ([d0cb2b0a](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/d0cb2b0a1daf5a2b1c2bbffd424a40e1b46761ff))
- **xpub:** touch up modal UI
  ([8f038d43](https://github.com/blockchain/My-Wallet-HD-Frontend/commit/8f038d4319140325514d4fe9b0a333b15a6cb06b))


## Refactor

- delete unused navigation_ctrl methods
- **CSP:** unsafe-inline CSS
- **CSS:** remove unnecessary modal-open css
- **Charts:** remove references of angular-charts and its dependencies
- **DidYouKnow:** move tests to pending until better translateFilter is created to test directive
- **Performance:** remove unused Bootstrap CSS modules
- **SecondPassword:** add bc-modal css class to center modal
- **TopCtrl:** simplified reference to Wallet.total
- **UI:**
  - remove unused CSP css
  - use utility classes, normalize typography
  - remove unused PNG's, delete unused CSS and references to it
  - normalize all settings UI to have labels if it's enable/disabled, remove references to old bootstrap buttons, deletes unused css
  - left align typography in receive modal & home page, reduce line-height
  - audit hex values and replace them with scss variable names, cleanup old css along the way
  - remove unused bootstrap references, add padding to textarea in send modal
  - align cols to baseline in home, less clunky first-time modal
  - update note ux, center modals, redo send confirm screen, update ladda spinner
- **advancedSettings:** Clean up validation functions, make sure fee-per-kb cannot exceed 0.01 btc
- **app:**
  - replace remaining walletApp uses
  - use angular module lookup rather than global app variable
- **importAddress:** replace wallet-spender with payment.js
- **sendCtrl:** implement payment.js module
- **signin:** move out of modals for sign up, get rid of registration ctrl & test
- **signup:**
  - more cleanup inside signup markup + css, rm reference to registration ctrl
  - move register html into signup, controller refactored, delete unused css


## Chore

- delete unused jade file
- **CSP:** provide script hash for browser detection
- **README:** change HD references to V3
- **Travis:** fix NodeJS version at 0.12
- **app:** use correct reference to Spender
- **changelog:**
  - add to grunt dist task
  - configured git-changelog
- **css:** bring in Bootstrap modal CSS into app so we have more control
- **did-you-know:** add test coverage to the directive, rm un-necessary translate filter in jade file
- **es6:**
  - Send Controller
  - fixed and converted function returns in ConfirmRecoverPhraseCtrl
  - fixed return statements in modalInstance resolve segments
  - converted FirstTimeCtrl
  - converted SecondPasswordCtrl
  - converted LoginCtrl
  - converted SignupCtrl
  - converted ModalNotificationCtrl
  - converted NavigationCtrl
  - converted OpenLinkCtrl
  - converted SecurityCenterCtrl
  - converted AppCtrl
  - converted FeedbackCtrl
  - converted ConfirmRecoverPhraseCtrl
  - converted ClaimCtrl
  - converted AccountFormCtrl
  - Added support and converted some controllers
  - converted TopCtrl
- **grunt:** reuse build task and remove debug tasks
- **homeCtrl:** make es6 code more concise
- **readme:** remove Spender part of README
- **sendCtrl:** Remove unused scope functions
- **spender:** remove MyWalletSpender from frontend
- **walletRecovery:** hide wallet recovery option



---
<sub><sup>*Generated with [git-changelog](https://github.com/rafinskipg/git-changelog). If you have any problem or suggestion, create an issue.* :) **Thanks** </sub></sup>