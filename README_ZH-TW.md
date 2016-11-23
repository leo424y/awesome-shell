# Awesome Shell [![Awesome][awesome-badge]][awesome-link]

這是一份非常棒的命令列框架、工具包、指南、以及小玩意兒組織清單。由 awesome-php 獲得靈感。該 awesome 收集在 [Unix-Shell.ZEEF.com](https://unix-shell.zeef.com/caleb.xu) 上也可用。

- [命令列效率](#命令列效率)
- [定製](#定製)
- [針對開發者](#針對開發者)
- [系統工具](#系統工具)
- [下載與服務](#下載與服務)
- [多媒體與檔案格式](#多媒體與檔案格式)
- [應用程式](#應用程式)
- [遊戲](#遊戲)
- [Shell 包管理](#shell-包管理)
- [Shell 指令碼開發](#shell-指令碼開發)
- [指南](#指南)
- [**Awesome Zsh**][awesome-zsh]&nbsp; [![Awesome][awesome-badge]][awesome-zsh]
- [**Awesome Fish**][awesome-fish] [![Awesome][awesome-badge]][awesome-fish]
- [其它 Awesome 清單](#其它-awesome-清單)

## 命令列效率

*使你的終端體驗更有效率的搜尋、書籤、多路複用、以及其它工具。*

* [ag](https://github.com/ggreer/the_silver_searcher) - 在層級目錄中超快的搜尋字元串
* [aliases](https://github.com/sebglazebrook/aliases) - 針對 bash 的上下文動態組織別名
* [aliasme](https://github.com/Jintin/aliasme) - 用來快速更改目錄的 alias 輔助程式
* [autoenv](https://github.com/kennethreitz/autoenv) - 基於目錄的環境
* [autojump](https://github.com/wting/autojump) - 自帶學習功能的 cd 命令，從命令列輕易地導航目錄
* [bashhub](https://github.com/rcaloras/bashhub-client) - :cloud: 在雲中的 bash 歷史，已索引且可搜尋。
* [bashmarks](https://github.com/huyng/bashmarks) - 適用於 shell 的目錄書籤
* [bd](https://github.com/vigneshwaranr/bd) - 迅速回到父目錄
* [boilr](https://github.com/tmrts/boilr) - 從 boilerplate 模板建立項目的超快命令列工具
* [boom](https://github.com/holman/boom) - 在命令列中儲存連結及片斷
* [borg](https://github.com/ok-borg/borg) - 基於終端的 bash 命令搜尋引擎
* [byobu](http://byobu.co/) - 基於文字的視窗管理器及終端多路複用器
* [commacd](https://github.com/shyiko/commacd) - 在 Bash 中更快速的移動方式
* [desk](https://github.com/jamesob/desk) - 適用於 shell 的輕量級工作區管理器
* [direnv](https://github.com/direnv/direnv) - 針對 shell 的環境切換工具（利用 autoenv 比較）
* [enhancd](https://github.com/b4b4r07/enhancd) - :rocket: 具有互動式過濾功能的下一代 cd 命令
* [fasd](https://github.com/clvv/fasd) - 命令列效率提升器，提供快速訪問檔案及目錄
* [foxy](https://github.com/s-p-k/foxy) - 適合 Firefox 及 Surf 瀏覽器的無格式文字書籤
* [fzf](https://github.com/junegunn/fzf) - 命令列下的模糊搜尋器
* [hhighlighter](https://github.com/paoloantinori/hhighlighter) - 在命令輸出中給單詞著色
* [hr](https://github.com/LuRsT/hr) - 適用於終端的 `<hr />`
* [hstr](https://github.com/dvorka/hstr) - Bash 歷史建議框
* [k](https://github.com/supercrabtree/k) - k 是一個使目錄列表更可讀的 Zsh 指令碼，它增添了 Git 狀態、檔案顏色、以及腐朽的日期
* [k alias](https://github.com/lingtalfi/k) - 獲得用於單行的酷 alias
* [marker](https://github.com/pindexis/marker) - 將你的 shell 命令加到書籤
* [parallel](http://www.gnu.org/software/parallel/) - 以並行化方式從標準輸入構造並執行 shell 命令列
* [pathpicker](https://github.com/facebook/PathPicker) - 允許將 grep、搜尋、git 等的輸出結果作為輸入，並提供友好的選擇介面，以便開啟或作為命令的參數
* [percol](https://github.com/mooz/percol) - 為傳統的 UNIX shell 管道新增互動式的過濾
* [qfc](https://github.com/pindexis/qfc) - 針對 Bash 和 Zsh 的檔案補全 widget
* [SHML](https://github.com/odb/shml) - 適用於終端的樣式框架 (Shell 標記語言)
* [slugify](https://github.com/benlinton/slugify) - 將檔名及目錄轉換為 web 友好的格式
* [sman](https://github.com/tokozedg/sman) - :bug: 命令列下的片斷管理器
* [spark](https://github.com/holman/spark) - ▁▂▃▅▂▇ 在你的 shell 中
* [Shark](https://github.com/fisherman/shark) - ▁▂▃▅ Sparkline 生成器
* [sheet](https://github.com/oscardelben/sheet) -  用於命令列的文字片斷
* [spot](https://github.com/rauchg/spot) - 微型的檔案搜尋工具
* [snips](https://github.com/srijanshetty/snips) - 管理程式碼片斷的命令列工具
* [sshfs](https://github.com/osxfuse/sshfs) - 通過 SSH 掛載遠端檔案系統的工具
* [sshrc](https://github.com/Russell91/sshrc) - SSH 時帶上你的 .bashrc、.vimrc 等
* [sudocabulary](https://github.com/badarsh2/Sudocabulary) - 從終端學習英語詞彙
* [thefuck](https://github.com/nvbn/thefuck) - 通過使用容易記住的命令修正常見的 shell 錯誤
* [tmux](http://tmux.github.io/) - 很棒的終端複用器
* [up](https://github.com/shannonmoeller/up) - 按名稱或計數升序排列目錄，支援 bash 和 zsh
* [v](https://github.com/rupa/v) - 適用於 Vim 的 z
* [wemux](https://github.com/zolrath/wemux) - 多使用者使用 Tmux 變得更容易
* [z](https://github.com/rupa/z) - z 是新的 j

## 定製

*定製提示符、顏色主題等。*

* [base16-shell](https://github.com/chriskempson/base16-shell) - 適用於 shell 的 Base16
* [bash-full-of-colors](https://github.com/slomkowski/bash-full-of-colors) - 超強的命令列提示（含 screen、tmux、git 等支援）
* [bash-git-prompt](https://github.com/magicmonty/bash-git-prompt) - 針對 Git 使用者的資訊及夢幻提示符
* [bash-powerline](https://github.com/riobard/bash-powerline) - Powerline 風格的 Bash 提示符，純 Bash 指令碼
* [bashstrap](https://github.com/barryclark/bashstrap) - 美化 OS X 終端的快速方法
* [bullet-train-oh-my-zsh-theme](https://github.com/caiogondim/bullet-train-oh-my-zsh-theme) - :bullettrain_side: 基於 Powerline Vim 外掛的 oh-my-zsh shell 主題
* [emojify](https://github.com/mrowa44/emojify) - 適用於命令列的表情 :scream:
* [flatui-terminal-theme](https://dribbble.com/shots/1021755-Flat-UI-Terminal-Theme) - 很好的終端顏色主題
* [git-prompt](https://github.com/lvv/git-prompt) - 包含 Git、SVN 及 HG 模組的 Bash 提示符
* [gittify](https://github.com/momeni/gittify) - 彩色的 Bash 提示符及定製的 Git 別名
* [Gogh - Color Scheme](https://github.com/Mayccoll/Gogh) - 適用於 GNOME 終端的顏色主題
* [liquidprompt](https://github.com/nojhan/liquidprompt) - 針對 Bash 和 Zsh 的全功能及用心設計的自適應提示符
* [mysql-colorize](https://github.com/horosgrisa/mysql-colorize.bash) -  彩色的 MySQL 命令列客戶端
* [oh-my-git](https://github.com/arialdomartini/oh-my-git) - 針對 Bash 和 Zsh 的自用 Git 提示符
* [sexy-bash-prompt](https://github.com/twolfson/sexy-bash-prompt) - 包含顏色、Git 狀態及 Git 分支的 Bash 提示符

## 針對開發者

*命令列開發、版本控制、以及部署。*

* [bocker](https://github.com/p8952/bocker) - 使用百行 bash 實現的 Docker
* [cloc](https://github.com/AlDanial/cloc) - 統計程式碼行數
* [dokku](https://github.com/dokku/dokku) - 百行 Bash 打造的 Docker 迷你 Heroku
* [getopts](https://github.com/fisherman/getopts) - 適用於 fish 的命令列解析器
* [git-extra-commands](https://github.com/unixorn/git-extra-commands) - 很多 Git 擴充套件工具，包括 churn、cut-branch、improved-merge 等
* [git-extras](https://github.com/tj/git-extras) - Git 工具，包括倉庫摘要、repl、更改日誌人數、作者提交百分比等
* [git-open](https://github.com/paulirish/git-open) - 輸入 `git open` 在瀏覽器中開啟 GitHub 頁面或倉庫網站
* [git-semver](https://github.com/markchalloner/git-semver) - 用來方便的語義化版本及更改日誌驗證的 Git 外掛
* [git-sh](https://github.com/rtomayko/git-sh) - 適合 Git 工作的定製 Bash 環境
* [git-up](https://github.com/aanand/git-up) - 自動變基進來的更改代替合併，優雅！
* [hub](https://github.com/github/hub) - 更易使用 GitHub 的命令列工具
* [mr](https://github.com/joeyh/myrepos) - 多倉庫管理工具
* [overcommit](https://github.com/brigade/overcommit) - 完全可配置且可擴充套件的 Git hook 管理器
* [pre-commit](http://pre-commit.com) - 用於管理及維護多語言 pre-commit hooks 的框架
* [repren](https://github.com/jlevy/repren) - 命令列搜尋與替換及檔案重新命名的瑞士軍刀式工具
* [slap](https://github.com/slap-editor/slap) - 執行在 Node.js 上的基於終端的類 Sublime 文字編輯器
* [shipit](https://github.com/sapegin/shipit) - 極簡 SSH 部署

## 系統工具

*作業系統相關工具，包括系統管理、系統偵錯、及檔案和程序管理。*

* [atop](http://www.atoptool.nl) - 能夠報告所有程序活動的 ASCII 全屏效能監視器
* [cv](https://github.com/Xfennec/progress) - 顯示 cp、rm、dd 等命令進度的 Linux 工具
* [glances](https://github.com/nicolargo/glances) - 系統監視之眼
* [goaccess](https://github.com/allinurl/goaccess) - 執行於 \*nix 系統終端中的實時 web 日誌分析器及互動式檢視器
* [histstat](https://github.com/vesche/histstat) - 適用於 netstat 的歷史
* [htop](https://github.com/hishamhm/htop) - 基於 ncurses 的互動式程序檢視器，其目標是比 `top` 更好
* [lnav](http://lnav.org) - 小型的高階日誌檔案檢視器
* [lsp](https://github.com/dborzov/lsp) - 改進的 `ls`，包含無格式語言的檔案說明及智慧的檔案分組
* [mtr](https://github.com/traviscross/mtr) - traceroute 和 ping 功能合二為一的網路診斷工具
* [ncdu](https://dev.yorhel.nl/ncdu) - NCurses 磁碟佔用統計
* [powertop](https://github.com/fenrus75/powertop) - 電池/電源佔用及裝置狀態監視命令列工具，包含調整選項
* [procdog](https://github.com/jlevy/procdog) - 輕量級的命令列控制類似伺服器的長實時程序
* [quick-secure](https://github.com/marshyski/quick-secure) - 快速的安全並加固 UNIX/Linux 系統

## 下載與服務

*使用 shell 指令碼編寫的自架、輕量級伺服器與網路工具。*

* [aria2](https://github.com/aria2/aria2) - aria2 是一款在命令列中操作的輕量級多協議、多來源、及跨平臺下載工具，它支援 HTTP/HTTPS、FTP、BitTorrent 及 Metalink
* [balls](https://github.com/jneen/balls) - Bash on Balls，全功能的 web 平臺
* [bashttpd](https://github.com/avleen/bashttpd) - 使用 Bash 編寫的 web 伺服器
* [bitpocket](https://github.com/sickill/bitpocket) - "DIY Dropbox" 或 "雙向目錄同步（含正確刪除）"
* [Dropbox-Uploader](https://github.com/andreafabrizi/Dropbox-Uploader) - Dropbox Uploader 是用來從 Dropbox 上傳、下載、列出或刪除檔案的 Bash 指令碼
* [httpie](https://github.com/jkbrzt/httpie) - HTTPie 是一個命令列 HTTP 客戶端，使用者友好的 cURL 替代品
* [ngincat](https://github.com/jaburns/ngincat) - 使用 netcat 的微型 Bash HTTP 伺服器
* [resty](https://github.com/micha/resty) - 你可以在管道中使用的小型命令列 REST 客戶端
* [youtube-dl](https://github.com/rg3/youtube-dl) - 從 YouTube.com 及其它視訊站點下載視訊的小命令列程式

## 多媒體與檔案格式

*用於處理視訊及音訊檔案的工具。*

* [adb-export](https://github.com/sromku/adb-export) - 匯出 Android 內容提供商為 CSV 格式
* [Android-Kitchen](https://github.com/dsixda/Android-Kitchen) - 基於文字的 Android ROM 定製 kitchen，使用 shell 指令碼並支援 Cygwin/OS X/Linux
* [Beets](https://github.com/beetbox/beets) - 音樂庫管理器及 MusicBrainz 標籤工具
* [cmus](https://github.com/cmus/cmus) - 跨平臺的命令列音樂播放器
* [gifgen](https://github.com/lukechilds/gifgen) - 簡單高質量的 GIF 編碼
* [image-scraper](https://github.com/sananth12/ImageScraper) - 包含諸多特性的酷命令列影象 scraper
* [jq](https://github.com/stedolan/jq) - 針對 json 資料的 Sed，你可以使用它分片、過濾、對映及變換結構化資料
* [mplayer](http://www.mplayerhq.hu/design7/news.html) - 讓你在 shell 中播放主流的音訊及視訊格式（使用 ASCII 字元）
* [nehm](https://github.com/bogem/nehm) - 下載、設定 IDv3 標籤、並新增到 iTunes 的控制檯工具
* [PiCAST](https://github.com/lanceseidman/PiCAST) - PiCAST 將你的 35 刀 Raspberry Pi 變成類 Chromecast 裝置
* [sejda](https://github.com/torakiki/sejda/) - 命令列下的 PDF 文件處理工具（分割、合併、旋轉、轉換為 jpg、提取文字等）
* [xmlstarlet](http://xmlstar.sourceforge.net/) - 古老而強大的命令列 XML 格式化、過濾及處理工具

## 應用程式

*基於命令列的應用程式或從命令列訪問現有服務。*

* [ansiweather](https://github.com/fcambus/ansiweather) - 終端中的天氣預報，包含 ANSI 顏色及 Unicode 符號
* [bashblog](https://github.com/cfenollosa/bashblog) - 處理 blog 投遞的 Bash 指令碼
* [choosealicense-cli](https://github.com/lord63/choosealicense-cli) - 把 http://choosealicense.com 帶到你的終端
* [facy](https://github.com/huydx/facy) - 命令列下的 Facebook 客戶端
* [fanyi](https://github.com/afc163/fanyi) - 翻譯英文為中文的命令列工具
* [geeknote](https://github.com/VitaliyRodnenko/geeknote) - 命令列的 Evernote 客戶端
* [haxor-news](https://github.com/donnemartin/haxor-news) - 像黑客一樣瀏覽 Hacker News
* [hn-cli](https://github.com/rafaelrinaldi/hn-cli) - 從終端舒服的瀏覽 Hacker News
* [iponmap](https://github.com/nogizhopaboroda/iponmap) - 利用 IP 地址在世界地圖上繪點
* [isitup](https://github.com/lord63/isitup) - 檢查一個網站是否正常上線
* [jrnl](https://github.com/maebert/jrnl) - 使用無格式文字檔案儲存日記的簡單命令列程式
* [ledger](https://github.com/ledger/ledger) - 命令列記賬
* [licen](https://github.com/lord63/licen) - 生成項目 license
* [moviemon](https://github.com/iCHAIT/moviemon) - 有關在命令列下看電影的每樣東東
* [pushblast](https://github.com/alebcay/pushblast) - 當 shell 程式退出時獲得 PushBullet 通知
* [pushbullet-bash](https://github.com/Red5d/pushbullet-bash) - PushBullet API 的 Bash 介面
* [Reddit Terminal Viewer](https://github.com/michael-lazar/rtv) - 從終端瀏覽 Reddit
* [SAWS](https://github.com/donnemartin/saws) - 超強的 AWS 命令列介面
* [transfer.sh](https://transfer.sh/) — 從 shell 快速上傳並分享檔案
* [vl](https://github.com/ellisonleao/vl) - 針對文字文件的 URL 連結檢查器
* [wego](https://github.com/schachmat/wego) - 適用於終端的天氣預報應用
* [whereami](https://github.com/rafaelrinaldi/whereami) - 從命令列獲得你的地理位置資訊

## 遊戲

*只顧工作而不玩玩是一種糟糕的度日方式。*

* [bash2048](https://github.com/mydzor/bash2048) - 2048 遊戲的 Bash 實現
* [minesweeper](https://github.com/feherke/Bash-script/tree/master/minesweeper) - 掃雷的 Bash 實現
* [sedtris](https://github.com/uuner/sedtris) - 使用 sed 實現的俄羅斯方塊
* [sed-scripts](https://github.com/aureliojargas/sed-scripts) - 使用 sed 編寫的 Arkanoid 和 Sokoban

## Shell 包管理

*用於管理多個 shell 配置的工具。對於特定的 zsh 工具，參閱 Zsh 節。*

* [bash-it](https://github.com/Bash-it/bash-it) - 社羣化的 Bash 框架
* [basher](https://github.com/basherpm/basher) - 針對 shell 指令碼的包管理器
* [bpkg](http://www.bpkg.io/) - JavaScript 有 npm、Ruby 有 Gems、Python 有 pip，現在 Shell 有 bpkg
* [dotfiler](https://github.com/svetlyak40wt/dotfiler) – 使用 Python 編寫的基於 Git 的 Shell dotfiles 管理器
* [fresh](https://github.com/freshshell/fresh) - 使你的 dotfiles 保持更新
* [homeshick](https://github.com/andsens/homeshick) - 使用 Bash 編寫的 Git dotfile 同步器
* [vcsh](https://github.com/RichiH/vcsh) - 基於 Git 的配置管理器
* [shundle](https://github.com/chilicuil/shundle) - 適用於 shell 指令碼的外掛管理器

## Shell 指令碼開發

*用於編寫、改進、及管理 Bash 或其它 shell 指令碼的工具。*

* [ansi](https://github.com/fidian/ansi) - 使用純 Bash 實現的 ANSI 轉義碼，包括更改文字顏色、定位游標等等
* [assert.sh](https://github.com/lehmannro/assert.sh) - Bash 單元測試框架
* [bashful](https://github.com/jmcantrell/bashful) - 簡化編寫 Bash 指令碼的庫收集
* [bashmanager](https://github.com/lingtalfi/bashmanager) - 用來建立命令列工具的微型 Bash 框架
* [bats](https://github.com/sstephenson/bats) - Bash 自動化測試系統
* [Fishtape](https://github.com/fisherman/fishtape) - 適用於 fish 的 TAP 產生器及測試工具
* [composure](https://github.com/erichs/composure) - 撰寫、文件、版本、及組織你的 shell 函數
* [dispatch](https://github.com/Mosai/workshop/blob/master/doc/dispatch.md) - 使用 50 行可移植 shell 指令碼寫成的命令列參數解析器
* [is.sh](https://github.com/qzb/is.sh) - 內建 test 命令的替代品，使 "if" 語句更漂亮
* [mo](https://github.com/tests-always-included/mo) - 使用純 Bash 實現的 Mustache 模板
* [optparse](https://github.com/nk412/optparse) - 針對 getopts 的 BASH wrapper，用於簡單的命令列參數
* [rerun](https://github.com/rerun/rerun) - 用來管理保留指令碼的模組化 shell 自動化框架
* [semver_bash](https://github.com/cloudflare/semver_bash) - 使用 Bash 實現的語義化版本
* [sh-semver] (https://github.com/qzb/sh-semver) - 適用於 bash 的 Semver 工具，匹配指定規則來查詢版本
* [shellcheck](https://github.com/koalaman/shellcheck) - 針對 shell 指令碼的靜態化分析工具
* [shellfire](https://github.com/shellfire-dev/shellfire) - 名稱空間倉庫，可寫 shell (bash、sh 及 dash) 函數庫
* [shpec](https://github.com/rylnd/shpec) - shell 測試框架
* [sub](https://github.com/basecamp/sub) - 以美味之道來管理程式
* [ts](https://github.com/thinkerbot/ts) - shell 測試指令碼
* [shunit2](https://github.com/kward/shunit2) - 適用於 Bash 指令碼的單元測試框架（具有 JUnit/PyUnit 風味）
* [rebash](https://github.com/jandob/rebash) - 指令碼庫/框架，包含 imports、exceptions、doc-tests 等功能


# 指南

* [Bash 黑客的維基](http://wiki.bash-hackers.org/)
* [Greg Wooledge（又名 "greycat"）的維基](http://mywiki.wooledge.org)：尤其是 [Bash 指南](http://mywiki.wooledge.org/BashGuide)、[Bash 疑難問答](http://mywiki.wooledge.org/BashFAQ) 及 [Bash 陷阱](http://mywiki.wooledge.org/BashPitfalls)
* [Google 的 Shell 風格指南](https://google.github.io/styleguide/shell.xml)
* [Linux 文件項目: Bash 程式設計 - 簡介/如何做](http://tldp.org/HOWTO/Bash-Prog-Intro-HOWTO.html#toc)
* [Linux 文件項目: 高階 Bash 指令碼指南](http://www.tldp.org/LDP/abs/html/)
* [WikiBooks: Bash Shell 指令碼](https://en.wikibooks.org/wiki/Bash_Shell_Scripting)
* [使用非官方的 Bash 嚴格模式 (除非你愛偵錯)](http://redsymbol.net/articles/unofficial-bash-strict-mode/)
* [命令列的藝術](https://github.com/jlevy/the-art-of-command-line)
* [學會成為命令列殺手](https://www.learnenough.com/command-line-tutorial)


# 其它 Awesome 清單

其它很棒的 awesome 清單可在 [awesome-awesome](https://github.com/emijrp/awesome-awesome) 和 [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) 找到。


[awesome-zsh]: https://github.com/unixorn/awesome-zsh-plugins
[awesome-fish]: https://github.com/fisherman/awesome-fish
[awesome-link]: https://github.com/sindresorhus/awesome
[awesome-badge]: https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg
