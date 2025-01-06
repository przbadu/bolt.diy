# 🚀 Release v0.0.6

## What's Changed 🌟

### 🎉 First Release

Exciting times! This marks our first release. Thanks to everyone who contributed! 🙌

### ✨ Features

* add login (d2b36e8) by @d3lm
* use tailwind-compat (2c1f32c) by @d3lm
* refactor layout and introduce workspace panel and fix some bugs (ab9d59a) by @d3lm
* add first version of workbench, increase token limit, improve system prompt (621b880) by @d3lm
* improve prompt, add ability to abort streaming, improve message parser (012b5ba) by @d3lm
* add file tree and hook up editor (a7d8693) by @d3lm
* add support for message continuation ([#1](https://github.com/przbadu/bolt.diy/pull/1)) by @przbadu
* chat autoscroll ([#6](https://github.com/przbadu/bolt.diy/pull/6))
* sync file changes back to webcontainer ([#5](https://github.com/przbadu/bolt.diy/pull/5))
* add simple api error handling ([#9](https://github.com/przbadu/bolt.diy/pull/9))
* initial persistence ([#3](https://github.com/przbadu/bolt.diy/pull/3))
* submit file changes to the llm ([#11](https://github.com/przbadu/bolt.diy/pull/11))
* add 'Open in StackBlitz' button to header ([#10](https://github.com/przbadu/bolt.diy/pull/10))
* add terminal and simple shortcut system ([#16](https://github.com/przbadu/bolt.diy/pull/16))
* use artifact id in urls, store metadata in history ([#15](https://github.com/przbadu/bolt.diy/pull/15))
* oauth-based login ([#7](https://github.com/przbadu/bolt.diy/pull/7))
* allow to disable auth during development ([#21](https://github.com/przbadu/bolt.diy/pull/21))
* allow to open up to three terminals ([#22](https://github.com/przbadu/bolt.diy/pull/22))
* tweak ui for redirect screen ([#23](https://github.com/przbadu/bolt.diy/pull/23))
* adjust system prompt ([#24](https://github.com/przbadu/bolt.diy/pull/24))
* initial chat history ui ([#25](https://github.com/przbadu/bolt.diy/pull/25))
* style sidebar and landing page ([#27](https://github.com/przbadu/bolt.diy/pull/27))
* add ability to change preview URL ([#26](https://github.com/przbadu/bolt.diy/pull/26))
* implement light and dark theme ([#30](https://github.com/przbadu/bolt.diy/pull/30))
* show tooltip when the editor is read-only ([#34](https://github.com/przbadu/bolt.diy/pull/34))
* add basic analytics ([#29](https://github.com/przbadu/bolt.diy/pull/29))
* allow to minimize chat ([#35](https://github.com/przbadu/bolt.diy/pull/35))
* send analytics event for token usage ([#37](https://github.com/przbadu/bolt.diy/pull/37))
* encrypt data and fix renewal ([#38](https://github.com/przbadu/bolt.diy/pull/38))
* add dropdown to select preview port ([#17](https://github.com/przbadu/bolt.diy/pull/17))
* add file tree breadcrumb ([#40](https://github.com/przbadu/bolt.diy/pull/40))
* rework ux for deleting chats ([#46](https://github.com/przbadu/bolt.diy/pull/46))
* navigate away when deleting current chat ([#44](https://github.com/przbadu/bolt.diy/pull/44))
* add avatar ([#47](https://github.com/przbadu/bolt.diy/pull/47))
* sanitize user messages ([#42](https://github.com/przbadu/bolt.diy/pull/42))
* remove authentication ([#1](https://github.com/przbadu/bolt.diy/pull/1)) by @przbadu
* add readme image ([#4](https://github.com/przbadu/bolt.diy/pull/4))
* added sync files to selected local folder function is created.Yarn package manager fixes, styling fixes. Sass module fix. Added Claude model for open router. ([#30](https://github.com/przbadu/bolt.diy/pull/30))
* added support for xAI Grok Beta ([#196](https://github.com/przbadu/bolt.diy/pull/196))
* set numCtx = 32768 for Ollama models ([#209](https://github.com/przbadu/bolt.diy/pull/209))
* add ability to enter API keys in the UI ([#101](https://github.com/przbadu/bolt.diy/pull/101))
* added the latest Sonnet 3.5 and Haiku 3.5 ([#205](https://github.com/przbadu/bolt.diy/pull/205))
* lm studio integration ([#104](https://github.com/przbadu/bolt.diy/pull/104))
* added dedicated bolt terminal, and attached to workbench ([#228](https://github.com/przbadu/bolt.diy/pull/228))
* added code streaming to editor while AI is writing files ([#213](https://github.com/przbadu/bolt.diy/pull/213))
* refactor/standardise model providers code + add "get provider key" ([#251](https://github.com/przbadu/bolt.diy/pull/251))
* [UX] click shortcut in chat to go to source file in workbench ([#330](https://github.com/przbadu/bolt.diy/pull/330))
* better prompt enhancement ([#428](https://github.com/przbadu/bolt.diy/pull/428))
* Added Together AI Dynamic Models ([#513](https://github.com/przbadu/bolt.diy/pull/513))
* added artifact bundling for custom long artifacts like uploading folder ([#504](https://github.com/przbadu/bolt.diy/pull/504))
* Git Repository Integration ([#421](https://github.com/przbadu/bolt.diy/pull/421))
* Added a tabbed setting modal ([#580](https://github.com/przbadu/bolt.diy/pull/580))
* Connections Tabs ([#607](https://github.com/przbadu/bolt.diy/pull/607))
* added ray effects for the UI as decorative elements ([#282](https://github.com/przbadu/bolt.diy/pull/282))
* Optimize LLM Context Management and File Handling ([#578](https://github.com/przbadu/bolt.diy/pull/578))
* added perplexity model ([#715](https://github.com/przbadu/bolt.diy/pull/715))
* Show token usage on LLM call assistant message ([#769](https://github.com/przbadu/bolt.diy/pull/769))
* Add Configurable System Prompts Feature ([#744](https://github.com/przbadu/bolt.diy/pull/744))
* feat:Added backdrop and loading screen in Git clone from Url  ([#597](https://github.com/przbadu/bolt.diy/pull/597))
* Improved GitHub connection ([#757](https://github.com/przbadu/bolt.diy/pull/757))


### 🐛 Bug Fixes

* buttons after switching to tailwind-compat reset (5fa2ee5) by @d3lm
* update system prompt (637ad2b) by @d3lm
* do not use path mapping for worker function (8613e39) by @d3lm
* make file tree scrollable ([#14](https://github.com/przbadu/bolt.diy/pull/14))
* always parse all assistant messages ([#13](https://github.com/przbadu/bolt.diy/pull/13))
* issue with generating a new url id every time ([#18](https://github.com/przbadu/bolt.diy/pull/18))
* use jose for cloudflare compatibility ([#20](https://github.com/przbadu/bolt.diy/pull/20))
* typo in example prompt (9aca292) by @d3lm
* hidden file patterns ([#31](https://github.com/przbadu/bolt.diy/pull/31))
* adjust system prompt ([#32](https://github.com/przbadu/bolt.diy/pull/32))
* update dependencies to fix type validation error ([#33](https://github.com/przbadu/bolt.diy/pull/33))
* correctly sort file tree ([#36](https://github.com/przbadu/bolt.diy/pull/36))
* user avatar ([#51](https://github.com/przbadu/bolt.diy/pull/51))
* remove monorepo (6fb59d2) by @samdenty
* add issue templates ([#2](https://github.com/przbadu/bolt.diy/pull/2))
* update repo name (ff8d59c) by @samdenty
* rename template (2aa10ee) by @samdenty
* rename template (579556c) by @samdenty
* add license (ff8cd57) by @samdenty
* typo (1ceca49) by @samdenty
* remove duplicated bug_report template (fc84501) by @samdenty
* update links (e4c7294) by @samdenty
* add screen recordings section to bug_report.yml (b17d6a5) by @samdenty
* don't render directly in body (50885b0) by @samdenty
* remove logout button ([#130](https://github.com/przbadu/bolt.diy/pull/130))
* typo in README.md ([#117](https://github.com/przbadu/bolt.diy/pull/117))
* typo in README.md ([#151](https://github.com/przbadu/bolt.diy/pull/151))
* fix hanging shells ([#153](https://github.com/przbadu/bolt.diy/pull/153))
* show issue page ([#157](https://github.com/przbadu/bolt.diy/pull/157))
* fix hanging shells ([#159](https://github.com/przbadu/bolt.diy/pull/159))
* typos in CONTRIBUTING.md ([#165](https://github.com/przbadu/bolt.diy/pull/165))
* further enhance Docker and docker-comose support with staged, --target and --profile support, plus Coolify Deployment Support ([#71](https://github.com/przbadu/bolt.diy/pull/71))
* respect provider choice from UI ([#188](https://github.com/przbadu/bolt.diy/pull/188))
* bug  #245 ([#254](https://github.com/przbadu/bolt.diy/pull/254))
* adds missing -t for dockerbuild:prod command in package.json ([#247](https://github.com/przbadu/bolt.diy/pull/247))
* gemini create model error ([#158](https://github.com/przbadu/bolt.diy/pull/158))
* added scroll fix for file browser ([#304](https://github.com/przbadu/bolt.diy/pull/304))
* execution order is fix, this fixes the inconsistency on project reload ([#309](https://github.com/przbadu/bolt.diy/pull/309))
* enhance prompt "Invalid or missing provider" bad request error ([#347](https://github.com/przbadu/bolt.diy/pull/347))
* mobile friendly ([#361](https://github.com/przbadu/bolt.diy/pull/361))
* silent eslint issues ([#414](https://github.com/przbadu/bolt.diy/pull/414))
* prettier issue ([#411](https://github.com/przbadu/bolt.diy/pull/411))
* typo in docker-compose.yaml ([#471](https://github.com/przbadu/bolt.diy/pull/471))
* header gradient, textarea border, prompt buttons ([#368](https://github.com/przbadu/bolt.diy/pull/368))
* artifact bugfix ([#569](https://github.com/przbadu/bolt.diy/pull/569))
* artifact loop fix ([#571](https://github.com/przbadu/bolt.diy/pull/571))
* grammar/typos in system prompt ([#654](https://github.com/przbadu/bolt.diy/pull/654))
* Settings bug fix, provider automatically turns on after opening the settings  ([#662](https://github.com/przbadu/bolt.diy/pull/662))
* dev command ([#682](https://github.com/przbadu/bolt.diy/pull/682))
* added default value to true for provider setting in initial  ([#683](https://github.com/przbadu/bolt.diy/pull/683))
* the creds issue in workflow ([#690](https://github.com/przbadu/bolt.diy/pull/690))
* auto select model on provider disabled ([#684](https://github.com/przbadu/bolt.diy/pull/684))
* commit-file-ignore (0c899e4) by @dustinwloring1988
* lm studio fix (1d64a15) by @dustinwloring1988
* start new chat icon (d1fa70f) by @dustinwloring1988
* removed context optimization temporarily, to be moved to optional ([#713](https://github.com/przbadu/bolt.diy/pull/713))
* Add Code Streaming Sampling for Performance Optimization ([#655](https://github.com/przbadu/bolt.diy/pull/655))
* handle conflicts between input method engine and enter key in chatbox ([#679](https://github.com/przbadu/bolt.diy/pull/679))
* warn Constants Failed  ([#753](https://github.com/przbadu/bolt.diy/pull/753))
* update vite.config.ts ([#751](https://github.com/przbadu/bolt.diy/pull/751))
* Added auto detect branch name and version tag for Debug Tab ([#755](https://github.com/przbadu/bolt.diy/pull/755))
* UI bug debug tab : System Information  ([#760](https://github.com/przbadu/bolt.diy/pull/760))
* Application  fails to load on Safari ([#771](https://github.com/przbadu/bolt.diy/pull/771))
* prompt enhance patch ([#784](https://github.com/przbadu/bolt.diy/pull/784))
* chat title character restriction (e064803) by @dustinwloring1988
* fixed model not loading/working, even after baseUrl set in .env file ([#816](https://github.com/przbadu/bolt.diy/pull/816))


### 📚 Documentation

* fix typo in CONTRIBUTING.md ([#158](https://github.com/przbadu/bolt.diy/pull/158))
* fix typos in README.md ([#164](https://github.com/przbadu/bolt.diy/pull/164))
* update README.md changed .env to .env.local ([#178](https://github.com/przbadu/bolt.diy/pull/178))
* added documentation creation framework ([#445](https://github.com/przbadu/bolt.diy/pull/445))
* Removed Ollama Modelfile Section ([#605](https://github.com/przbadu/bolt.diy/pull/605))
* add link to bolt.new issue tracker ([#665](https://github.com/przbadu/bolt.diy/pull/665))
* added socials ([#697](https://github.com/przbadu/bolt.diy/pull/697))
* miniflare error knowledge (282beb9) by @dustinwloring1988
* simplified setup ([#817](https://github.com/przbadu/bolt.diy/pull/817))


### ♻️ Code Refactoring

* workbench store and move logic into action runner ([#4](https://github.com/przbadu/bolt.diy/pull/4))
* remove settings button (2b1bf0f) by @d3lm
* add slider to switch between code or preview ([#12](https://github.com/przbadu/bolt.diy/pull/12))
* refactor(SettingWindow):Updated Settings Tab Styling ([#600](https://github.com/przbadu/bolt.diy/pull/600))
* refactored Setting component, added useSettings Hook to get settings details from one single place ([#645](https://github.com/przbadu/bolt.diy/pull/645))


### ⚙️ CI

* use correct versions ([#2](https://github.com/przbadu/bolt.diy/pull/2))
* deploy to cloudflare ([#19](https://github.com/przbadu/bolt.diy/pull/19))
* remove deployment workflow (849880e) by @d3lm


### 🔍 Other Changes

* disable eslint (46c083c) by @apai4
* Added the ability to use practically any LLM you can dream of within Bolt.new (90a206f) by @coleam00
* Added the OpenRouter provider and a few models from OpenRouter (easily extendable to include more!) (4f7a06f) by @coleam00
* Add provider filtering on model list ([#1](https://github.com/przbadu/bolt.diy/pull/1)) by @przbadu
* Added Google Generative AI (gemini) integration ([#2](https://github.com/przbadu/bolt.diy/pull/2))
* let the ollama models be auto generated from ollama api ([#5](https://github.com/przbadu/bolt.diy/pull/5))
* added download button to downloade generated code in a zip file ([#6](https://github.com/przbadu/bolt.diy/pull/6))
* Fixing up codebase after merging pull requests (d7bda6f) by @coleam00
* Updated README with new providers and a running list of features to add to the fork (8c4933d) by @coleam00
* Adding together to the list of integration requests (cd4ddfd) by @coleam00
* More feature requests!! (121ea7e) by @coleam00
* Sync with stackblitz upstream ([#7](https://github.com/przbadu/bolt.diy/pull/7))
* Update README.md ([#28](https://github.com/przbadu/bolt.diy/pull/28))
* Update README.md ([#8](https://github.com/przbadu/bolt.diy/pull/8))
* Adding CONTRIBUTING.md specifically for this fork. (8ac7931) by @coleam00
* [Prompt] Add structured planning step to improve response quality ([#11](https://github.com/przbadu/bolt.diy/pull/11))
* Fix for llama 3.1 models ([#12](https://github.com/przbadu/bolt.diy/pull/12))
* Docker Additions ([#23](https://github.com/przbadu/bolt.diy/pull/23))
* Added GitHub push functionality ([#24](https://github.com/przbadu/bolt.diy/pull/24))
* Add mistral models. ([#36](https://github.com/przbadu/bolt.diy/pull/36))
* Enhance Ollama Model Integration and Type Definitions ([#44](https://github.com/przbadu/bolt.diy/pull/44))
* Adding Deepseek coder + Deepseek chat with the Deepseek API. ([#51](https://github.com/przbadu/bolt.diy/pull/51))
* Further changes to support OLLAMA_API_BASE_URL with ollama models ([#64](https://github.com/przbadu/bolt.diy/pull/64))
* Cleanup and fixing Ollama models not showing up after merging changes (8ab8e67) by @coleam00
* Updating README with finished implementations and reorder the list of priorities (7b28a75) by @coleam00
* Update constants.ts ([#70](https://github.com/przbadu/bolt.diy/pull/70))
* Added DEEPSEEK_API_KEY to .env.example (065be0f) by @coleam00
* More feature requests! Will look at pull requests soon (2feeb18) by @coleam00
* Added more detailed instructions ([#55](https://github.com/przbadu/bolt.diy/pull/55))
* Fixing up Docker Compose to work with hot reloads in development and environment variables (22ae9d8) by @coleam00
* Fixing up setup + installation instructions in README (7fe66ae) by @coleam00
* Small mention of hot reloading even when running in container (64e95a0) by @coleam00
* Instructions on making Ollama models work well (e7ce257) by @coleam00
* Making Ollama work within the Docker container, very important fix (a6d81b1) by @coleam00
* Fixing merge conflicts in BaseChat.tsx (b3fe207) by @coleam00
* Noting that API key will still work if set in .env file (13b1321) by @coleam00
* Update README.md (848c697) by @coleam00
* removing GitHub action workflow github-build-push.yml ([#242](https://github.com/przbadu/bolt.diy/pull/242))
* Temporarily removing semantic-pr.yaml ([#261](https://github.com/przbadu/bolt.diy/pull/261))
* Update README.md ([#285](https://github.com/przbadu/bolt.diy/pull/285))
* Fix/provider consolelog ([#296](https://github.com/przbadu/bolt.diy/pull/296))
* olama local add  ([#118](https://github.com/przbadu/bolt.diy/pull/118))
* Should not provide hard-coded OLLAMA_API_BASE_URL value in .env.example ([#321](https://github.com/przbadu/bolt.diy/pull/321))
* Huggingface Models Integrated ([#314](https://github.com/przbadu/bolt.diy/pull/314))
* (Ready for review and merge) Add Chat Rewind, Duplicate, and Fork Features ([#305](https://github.com/przbadu/bolt.diy/pull/305))
* Update the Google Gemini models list ([#338](https://github.com/przbadu/bolt.diy/pull/338))
* Updating README with new features and a link to our community (50de8d0) by @coleam00
* (Ready for review) - Small visual fix. Add background for chat window(currently transparent and looks ugly) ([#350](https://github.com/przbadu/bolt.diy/pull/350))
* Cohere support added ([#351](https://github.com/przbadu/bolt.diy/pull/351))
* Created DEFAULT_NUM_CTX VAR with a default of 32768 ([#328](https://github.com/przbadu/bolt.diy/pull/328))
* Update to Gemini exp-1121 ([#371](https://github.com/przbadu/bolt.diy/pull/371))
* Added 3 new models to Huggingface ([#380](https://github.com/przbadu/bolt.diy/pull/380))
* Linting ([#367](https://github.com/przbadu/bolt.diy/pull/367))
* (Ready for review) Import and Export Individual Chats ([#372](https://github.com/przbadu/bolt.diy/pull/372))
* Small-cleanup-of-base-chat-component ([#412](https://github.com/przbadu/bolt.diy/pull/412))
* Created FAQ at bottom of README (23df7ae) by @coleam00
* Added roadmap to README FAQ (66ef47c) by @coleam00
* Force local linting ([#378](https://github.com/przbadu/bolt.diy/pull/378))
* Feat/improve sidebar ([#422](https://github.com/przbadu/bolt.diy/pull/422))
* (Ready for Review) Start chat with Folder Import ([#413](https://github.com/przbadu/bolt.diy/pull/413))
* Bump the npm_and_yarn group across 1 directory with 9 updates ([#456](https://github.com/przbadu/bolt.diy/pull/456))
* Socail Image - Filesize and Image size ([#455](https://github.com/przbadu/bolt.diy/pull/455))
* Ollama not respecting model selection ([#460](https://github.com/przbadu/bolt.diy/pull/460))
* Add search chats support ([#440](https://github.com/przbadu/bolt.diy/pull/440))
* shell commands execution failure on app reload ([#427](https://github.com/przbadu/bolt.diy/pull/427))
* GitHub action fix for docs ([#488](https://github.com/przbadu/bolt.diy/pull/488))
* Stable additions ([#491](https://github.com/przbadu/bolt.diy/pull/491))
* Updated features being developed in README (c8b4eee) by @coleam00
* UI glow and Prompt Caching ([#493](https://github.com/przbadu/bolt.diy/pull/493))
* combind-merge ([#498](https://github.com/przbadu/bolt.diy/pull/498))
* Create main.yml (455684a) by @dustinwloring1988
* Fixed v3_lazyRouteDiscovery flag warn ([#505](https://github.com/przbadu/bolt.diy/pull/505))
* Update README.md ([#506](https://github.com/przbadu/bolt.diy/pull/506))
* Update and rename main.yml to stale.yml (115dcbb) by @dustinwloring1988
* Docs Link added to readme ([#508](https://github.com/przbadu/bolt.diy/pull/508))
* Update stale.yml (320575d) by @dustinwloring1988
* Update linting-failed-message in pre-commit ([#512](https://github.com/przbadu/bolt.diy/pull/512))
* (Ready for review) Improve start command on windows ([#316](https://github.com/przbadu/bolt.diy/pull/316))
* Issue Template Update ([#520](https://github.com/przbadu/bolt.diy/pull/520))
* Implement chat description editing in sidebar and header, add… ([#483](https://github.com/przbadu/bolt.diy/pull/483))
* HIGH PRIORITY - Attach images to prompts ([#332](https://github.com/przbadu/bolt.diy/pull/332))
* Updating README now that image attaching is merged, changing order of items in README list. (67862d4) by @coleam00
* Voice input with fixes ([#537](https://github.com/przbadu/bolt.diy/pull/537))
* Added Fullscreen and Resizing to Preview ([#550](https://github.com/przbadu/bolt.diy/pull/550))
* (ready for review)Harcode together ai api url as fallback ([#533](https://github.com/przbadu/bolt.diy/pull/533))
* Update the model collapse button ([#565](https://github.com/przbadu/bolt.diy/pull/565))
* Refinement of folder import ([#426](https://github.com/przbadu/bolt.diy/pull/426))
* Add command detection to git import flow ([#589](https://github.com/przbadu/bolt.diy/pull/589))
* Git import from url ([#585](https://github.com/przbadu/bolt.diy/pull/585))
* ui/settings style ([#592](https://github.com/przbadu/bolt.diy/pull/592))
* add vue support for codemirror ([#581](https://github.com/przbadu/bolt.diy/pull/581))
* Update to Gemini exp-1206 ([#573](https://github.com/przbadu/bolt.diy/pull/573))
* Update FAQ.md ([#606](https://github.com/przbadu/bolt.diy/pull/606))
* Fix Features Toggle ([#610](https://github.com/przbadu/bolt.diy/pull/610))
* Updated logo in header ([#625](https://github.com/przbadu/bolt.diy/pull/625))
* Replaced images to match new style ([#629](https://github.com/przbadu/bolt.diy/pull/629))
* Updating name to Bolt.diy in README (1d5ad99) by @coleam00
* Updating git clone url in README. (fa526a6) by @coleam00
* Fixing typo. (1145c4e) by @coleam00
* Merge branch 'main' of https://github.com/stackblitz-labs/bolt.diy (7d202a4) by @coleam00
* Updating documentation link in README. (3bdf091) by @coleam00
* Merge branch 'main' of https://github.com/stackblitz-labs/bolt.diy (62bc87b) by @coleam00
* Update SettingsWindow.tsx ([#635](https://github.com/przbadu/bolt.diy/pull/635))
* updated docs with new name ([#637](https://github.com/przbadu/bolt.diy/pull/637))
* fix docs Title ([#639](https://github.com/przbadu/bolt.diy/pull/639))
* Changed Docs URL In Settings ([#638](https://github.com/przbadu/bolt.diy/pull/638))
* Remove other oTToDev mentions ([#648](https://github.com/przbadu/bolt.diy/pull/648))
* Add gemini flash 2.0 ([#649](https://github.com/przbadu/bolt.diy/pull/649))
* added start message for dev server ([#668](https://github.com/przbadu/bolt.diy/pull/668))
* update README.md (eeafc12) by @dustinwloring1988
* Added some small UI enhancements to the Settings and Sidebar ([#676](https://github.com/przbadu/bolt.diy/pull/676))
* Fix/UI enhancements ([#708](https://github.com/przbadu/bolt.diy/pull/708))
* added support for private github repo through github connections ([#670](https://github.com/przbadu/bolt.diy/pull/670))
* groq-llama3.3-70b (eb53146) by @dustinwloring1988
* Add Screenshot Capture and Management Features to Chat and Workbench Components ([#582](https://github.com/przbadu/bolt.diy/pull/582))
* Update readme ([#722](https://github.com/przbadu/bolt.diy/pull/722))
* Groq Llama 3.2 90B Vision Preview (ece0213) by @dustinwloring1988
* Basic file tree context menu ([#602](https://github.com/przbadu/bolt.diy/pull/602))
* README, FAQ, CONTRIBUTING branding updates ([#728](https://github.com/przbadu/bolt.diy/pull/728))
* Setting-Menu (7c3a3bb) by @dustinwloring1988
* prompt-enhanced-toast (d936c01) by @dustinwloring1988
* Features Tab Changes ([#726](https://github.com/przbadu/bolt.diy/pull/726))
* fix-perplexity-icon (23346f6) by @dustinwloring1988
* perplexity-provider-icon (9cd9ee9) by @dustinwloring1988
* README-formatting (87a9071) by @dustinwloring1988
* update-Bolt-to-bolt (e223e9b) by @dustinwloring1988
* debug-tab (4016f54) by @dustinwloring1988
* favicon-ico (1e7c3a4) by @dustinwloring1988
* mkdoc-update-names (d22b32a) by @dustinwloring1988
* mkdoc-docs-styled (d9b2801) by @dustinwloring1988
* new section heading (0157fdd) by @dustinwloring1988
* fix clickable links docs (810cc81) by @dustinwloring1988
* default-provider-image (6ba9397) by @dustinwloring1988
* Check the render method of SlotClone. #432 ([#433](https://github.com/przbadu/bolt.diy/pull/433))
* feat(url-prompt) added prompt url params ([#669](https://github.com/przbadu/bolt.diy/pull/669))
* Fixed theming of Copy Code button ([#774](https://github.com/przbadu/bolt.diy/pull/774))
* Bugfix for stable ([#776](https://github.com/przbadu/bolt.diy/pull/776))
* pull latest commit ([#1](https://github.com/przbadu/bolt.diy/pull/1)) by @przbadu


## ✨ First-time Contributors

A huge thank you to our amazing new contributors! Your first contribution marks the start of an exciting journey! 🌟

* 🌟 [@apai4](https://github.com/apai4)
* 🌟 [@coleam00](https://github.com/coleam00)
* 🌟 [@dustinwloring1988](https://github.com/dustinwloring1988)
* 🌟 [@przbadu](https://github.com/przbadu)
* 🌟 [@samdenty](https://github.com/samdenty)

