2025-09-22 01:52:44.529 [info] [main] Log level: Info
2025-09-22 01:52:44.529 [info] [main] Validating found git in: "/usr/local/bin/git"
2025-09-22 01:52:44.681 [info] [main] Using git "2.43.0" from "/usr/local/bin/git"
2025-09-22 01:52:44.681 [info] [Model][doInitialScan] Initial repository scan started
2025-09-22 01:52:44.734 [info] > git rev-parse --show-toplevel [48ms]
2025-09-22 01:52:44.734 [info] fatal: not a git repository (or any of the parent directories): .git
2025-09-22 01:52:44.774 [info] > git rev-parse --show-toplevel [39ms]
2025-09-22 01:52:44.774 [info] fatal: not a git repository (or any of the parent directories): .git
2025-09-22 01:52:44.775 [info] [Model][doInitialScan] Initial repository scan completed - repositories (0), closed repositories (0), parent repositories (0), unsafe repositories (0)
2025-09-22 01:52:45.507 [info] > git rev-parse --show-toplevel [50ms]
2025-09-22 01:52:45.507 [info] fatal: not a git repository (or any of the parent directories): .git
2025-09-22 01:52:58.300 [info] > git init -b main [91ms]
2025-09-22 01:52:58.340 [info] > git rev-parse --show-toplevel [38ms]
2025-09-22 01:52:58.379 [info] > git rev-parse --git-dir --git-common-dir [37ms]
2025-09-22 01:52:58.384 [info] [Model][openRepository] Opened repository: /Users/samarthverulkar/Downloads/BlockNinja
2025-09-22 01:52:58.388 [info] [Git][getRemotes] No remotes found in the git config file
2025-09-22 01:52:58.448 [info] > git config --get commit.template [61ms]
2025-09-22 01:52:58.450 [info] > git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) --ignore-case refs/heads/main refs/remotes/main [62ms]
2025-09-22 01:52:58.450 [warning] [Git][getBranch] No such branch: main
2025-09-22 01:52:58.505 [info] > git for-each-ref --sort -committerdate --format %(refname) %(objectname) %(*objectname) [52ms]
2025-09-22 01:52:58.506 [info] > git status -z -uall [55ms]
2025-09-22 01:52:58.513 [info] [Git][getRemotes] No remotes found in the git config file
2025-09-22 01:52:58.584 [info] > git config --get commit.template [72ms]
2025-09-22 01:52:58.586 [info] > git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) --ignore-case refs/heads/main refs/remotes/main [73ms]
2025-09-22 01:52:58.586 [warning] [Git][getBranch] No such branch: main
2025-09-22 01:52:58.589 [info] > git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) --ignore-case refs/heads/main refs/remotes/main [79ms]
2025-09-22 01:52:58.589 [warning] [Git][getBranch] No such branch: main
2025-09-22 01:52:58.589 [error] [GitHistoryProvider][resolveHEADMergeBase] Failed to resolve merge base for main: Error: No such branch: main.
2025-09-22 01:52:58.638 [info] > git log --format=%H%n%aN%n%aE%n%at%n%ct%n%P%n%D%n%B -z --shortstat --diff-merges=first-parent -n50 --skip=0 --topo-order --decorate=full --stdin [47ms]
2025-09-22 01:52:58.638 [info] fatal: bad revision 'refs/heads/main'
2025-09-22 01:52:58.638 [error] [GitHistoryProvider][provideHistoryItems] Failed to get history items with options '{"historyItemRefs":["refs/heads/main"],"limit":50,"skip":0}': Failed to execute git {
  "exitCode": 128,
  "gitCommand": "log",
  "stdout": "",
  "stderr": "fatal: bad revision 'refs/heads/main'\n"
}
2025-09-22 01:52:58.638 [info] > git status -z -uall [51ms]
2025-09-22 01:52:58.640 [info] > git for-each-ref --sort -committerdate --format %(refname) %(objectname) %(*objectname) [51ms]
2025-09-22 01:52:59.216 [info] > git check-ignore -v -z --stdin [68ms]
2025-09-22 01:53:01.172 [info] > git check-ignore -v -z --stdin [73ms]
2025-09-22 01:53:12.905 [info] > git add -A -- . [104ms]
2025-09-22 01:53:15.305 [info] > git show --textconv :.git/COMMIT_EDITMSG [50ms]
2025-09-22 01:53:15.306 [info] > git ls-files --stage -- /Users/samarthverulkar/Downloads/BlockNinja/.git/COMMIT_EDITMSG [49ms]
2025-09-22 01:53:15.348 [info] > git hash-object -t tree /dev/null [41ms]
2025-09-22 01:53:15.348 [warning] [GitFileSystemProvider][stat] File not found - git:/Users/samarthverulkar/Downloads/BlockNinja/.git/COMMIT_EDITMSG.git?%7B%22path%22%3A%22%2FUsers%2Fsamarthverulkar%2FDownloads%2FBlockNinja%2F.git%2FCOMMIT_EDITMSG%22%2C%22ref%22%3A%22%22%7D
2025-09-22 01:53:15.349 [info] > git hash-object -t tree /dev/null [43ms]
2025-09-22 01:53:15.349 [warning] [GitFileSystemProvider][readFile] File not found - git:/Users/samarthverulkar/Downloads/BlockNinja/.git/COMMIT_EDITMSG.git?%7B%22path%22%3A%22%2FUsers%2Fsamarthverulkar%2FDownloads%2FBlockNinja%2F.git%2FCOMMIT_EDITMSG%22%2C%22ref%22%3A%22%22%7D
2025-09-22 01:53:15.663 [info] > git check-ignore -v -z --stdin [73ms]
2025-09-22 01:56:08.621 [info] > git -c user.useConfigOnly=true commit --quiet [175714ms]
2025-09-22 01:56:08.626 [info] [Git][getRemotes] No remotes found in the git config file
2025-09-22 01:56:08.668 [info] > git config --get commit.template [44ms]
2025-09-22 01:56:08.671 [info] > git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) --ignore-case refs/heads/main refs/remotes/main [45ms]
2025-09-22 01:56:08.718 [info] > git for-each-ref --sort -committerdate --format %(refname) %(objectname) %(*objectname) [44ms]
2025-09-22 01:56:08.723 [info] > git status -z -uall [51ms]
2025-09-22 01:56:08.768 [info] [Git][getRemotes] No remotes found in the git config file
2025-09-22 01:56:08.821 [info] > git config --get commit.template [54ms]
2025-09-22 01:56:08.821 [info] > git log --format=%H%n%aN%n%aE%n%at%n%ct%n%P%n%D%n%B -z --shortstat --diff-merges=first-parent -n50 --skip=0 --topo-order --decorate=full --stdin [80ms]
2025-09-22 01:56:08.824 [info] > git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) --ignore-case refs/heads/main refs/remotes/main [56ms]
2025-09-22 01:56:08.888 [info] > git for-each-ref --sort -committerdate --format %(refname) %(objectname) %(*objectname) [62ms]
2025-09-22 01:56:08.888 [info] > git status -z -uall [63ms]
2025-09-22 01:57:18.287 [info] > git check-ignore -v -z --stdin [906ms]
2025-09-22 01:57:21.830 [info] > git ls-files --stage -- /Users/samarthverulkar/Downloads/BlockNinja/README.md [153ms]
2025-09-22 01:57:21.837 [info] > git show --textconv :README.md [162ms]
2025-09-22 01:57:21.903 [info] > git cat-file -s 437f897ba49891000d572d2f4766dfad30f6078f [71ms]
2025-09-22 01:57:50.638 [info] > git ls-files --stage -- /Users/samarthverulkar/Downloads/BlockNinja/index.js [519ms]
2025-09-22 01:57:50.659 [info] > git show --textconv :index.js [544ms]
2025-09-22 01:57:50.728 [info] > git cat-file -s 950d9153e6511173055f9e983b74220676bc0afc [87ms]
2025-09-22 01:59:10.994 [info] > git check-ignore -v -z --stdin [919ms]
2025-09-22 01:59:23.612 [info] [Git][getRemotes] No remotes found in the git config file
2025-09-22 01:59:23.812 [info] > git config --get commit.template [209ms]
2025-09-22 01:59:23.834 [info] > git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) --ignore-case refs/heads/main refs/remotes/main [223ms]
2025-09-22 01:59:23.893 [info] > git for-each-ref --sort -committerdate --format %(refname) %(objectname) %(*objectname) [55ms]
2025-09-22 01:59:23.896 [info] > git status -z -uall [60ms]
2025-09-22 01:59:28.771 [info] > git log --format=%H%n%aN%n%aE%n%at%n%ct%n%P%n%D%n%B -z --shortstat --diff-merges=first-parent -n50 --skip=0 --topo-order --decorate=full --stdin [69ms]
2025-09-22 01:59:28.909 [info] [Git][getRemotes] No remotes found in the git config file
2025-09-22 01:59:28.955 [info] > git config --get commit.template [47ms]
2025-09-22 01:59:28.956 [info] > git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) --ignore-case refs/heads/main refs/remotes/main [47ms]
2025-09-22 01:59:29.007 [info] > git status -z -uall [49ms]
2025-09-22 01:59:29.007 [info] > git for-each-ref --sort -committerdate --format %(refname) %(objectname) %(*objectname) [48ms]
2025-09-22 01:59:35.121 [info] [Git][getRemotes] No remotes found in the git config file
2025-09-22 01:59:35.189 [info] > git config --get commit.template [69ms]
2025-09-22 01:59:35.191 [info] > git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) --ignore-case refs/heads/main refs/remotes/main [67ms]
2025-09-22 01:59:35.290 [info] > git status -z -uall [98ms]
2025-09-22 01:59:35.290 [info] > git for-each-ref --sort -committerdate --format %(refname) %(objectname) %(*objectname) [97ms]
2025-09-22 01:59:57.216 [info] > git remote add main https://github.com/samarth641/CryptoSlayer.git [1043ms]
2025-09-22 01:59:57.265 [info] > git config --get commit.template [42ms]
2025-09-22 01:59:57.275 [info] > git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) --ignore-case refs/heads/main refs/remotes/main [51ms]
2025-09-22 01:59:57.326 [info] > git for-each-ref --sort -committerdate --format %(refname) %(objectname) %(*objectname) [48ms]
2025-09-22 01:59:57.328 [info] > git status -z -uall [52ms]
2025-09-22 01:59:58.714 [info] > git ls-files --stage -- /Users/samarthverulkar/Downloads/BlockNinja/index.js [75ms]
2025-09-22 01:59:58.759 [info] > git cat-file -s 950d9153e6511173055f9e983b74220676bc0afc [43ms]
2025-09-22 01:59:58.803 [info] > git show --textconv :index.js [42ms]
2025-09-22 01:59:59.955 [info] > git fetch main [2624ms]
2025-09-22 01:59:59.955 [info] From https://github.com/samarth641/CryptoSlayer
 * [new branch]      main       -> main/main
2025-09-22 01:59:59.996 [info] > git config --get commit.template [40ms]
2025-09-22 02:00:00.000 [info] > git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) --ignore-case refs/heads/main refs/remotes/main [41ms]
2025-09-22 02:00:00.066 [info] > git status -z -uall [65ms]
2025-09-22 02:00:00.066 [info] > git for-each-ref --sort -committerdate --format %(refname) %(objectname) %(*objectname) [64ms]
2025-09-22 02:00:00.121 [info] > git log --format=%H%n%aN%n%aE%n%at%n%ct%n%P%n%D%n%B -z --shortstat --diff-merges=first-parent -n50 --skip=0 --topo-order --decorate=full --stdin [51ms]
2025-09-22 02:00:01.170 [info] > git ls-files --stage -- /Users/samarthverulkar/Downloads/BlockNinja/index.js [50ms]
2025-09-22 02:00:01.214 [info] > git cat-file -s 950d9153e6511173055f9e983b74220676bc0afc [43ms]
2025-09-22 02:00:01.258 [info] > git show --textconv :index.js [42ms]
2025-09-22 02:00:37.695 [info] > git blame --root --incremental 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c -- /Users/samarthverulkar/Downloads/BlockNinja/index.js [923ms]
2025-09-22 02:01:04.327 [info] > git diff-tree -r --name-status -z --diff-filter=ADMR --find-renames=50% 4b825dc642cb6eb9a060e54bf8d69288fbee4904 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c [291ms]
2025-09-22 02:01:04.548 [info] > git show --textconv 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c:images/bomb.jpg [197ms]
2025-09-22 02:01:04.549 [info] > git show --textconv 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c:images/bombs.jpeg [195ms]
2025-09-22 02:01:04.571 [info] > git show --textconv 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c:README.md [220ms]
2025-09-22 02:01:04.573 [info] > git show --textconv 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c:.DS_Store [224ms]
2025-09-22 02:01:04.604 [info] > git show --textconv 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c:images/bomb.png [251ms]
2025-09-22 02:01:04.626 [info] > git ls-tree -l 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c -- /Users/samarthverulkar/Downloads/BlockNinja/images/btc.png [235ms]
2025-09-22 02:01:04.635 [info] > git ls-tree -l 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c -- /Users/samarthverulkar/Downloads/BlockNinja/images/doge.png [238ms]
2025-09-22 02:01:04.636 [info] > git show --textconv 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c:images/btc.png [280ms]
2025-09-22 02:01:04.636 [info] > git show --textconv 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c:index.js [268ms]
2025-09-22 02:01:04.653 [info] > git show --textconv 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c:styles.css [279ms]
2025-09-22 02:01:04.653 [info] > git ls-tree -l 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c -- /Users/samarthverulkar/Downloads/BlockNinja/README.md [273ms]
2025-09-22 02:01:04.654 [info] > git ls-tree -l 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c -- /Users/samarthverulkar/Downloads/BlockNinja/images/cardano.png [260ms]
2025-09-22 02:01:04.654 [info] > git ls-tree -l 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c -- /Users/samarthverulkar/Downloads/BlockNinja/.DS_Store [277ms]
2025-09-22 02:01:04.654 [info] > git ls-tree -l 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c -- /Users/samarthverulkar/Downloads/BlockNinja/images/bombs.jpeg [266ms]
2025-09-22 02:01:04.654 [info] > git ls-tree -l 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c -- /Users/samarthverulkar/Downloads/BlockNinja/images/bomb.jpg [272ms]
2025-09-22 02:01:04.658 [info] > git show --textconv 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c:index.html [293ms]
2025-09-22 02:01:04.662 [info] > git ls-tree -l 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c -- /Users/samarthverulkar/Downloads/BlockNinja/images/bomb.png [278ms]
2025-09-22 02:01:04.663 [info] > git ls-tree -l 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c -- /Users/samarthverulkar/Downloads/BlockNinja/index.html [262ms]
2025-09-22 02:01:04.664 [info] > git ls-tree -l 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c -- /Users/samarthverulkar/Downloads/BlockNinja/styles.css [257ms]
2025-09-22 02:01:04.666 [info] > git show --textconv 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c:images/cardano.png [308ms]
2025-09-22 02:01:04.668 [info] > git ls-tree -l 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c -- /Users/samarthverulkar/Downloads/BlockNinja/images/eth.png [270ms]
2025-09-22 02:01:04.743 [info] > git ls-tree -l 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c -- /Users/samarthverulkar/Downloads/BlockNinja/index.js [339ms]
2025-09-22 02:01:04.753 [info] > git show --textconv 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c:images/eth.png [390ms]
2025-09-22 02:01:04.753 [info] > git show --textconv 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c:images/doge.png [392ms]
2025-09-22 02:01:04.999 [info] > git check-ignore -v -z --stdin [76ms]
2025-09-22 02:20:13.937 [info] > git ls-tree -l 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c -- /Users/samarthverulkar/Downloads/BlockNinja/README.md [1310ms]
2025-09-22 02:20:13.938 [info] > git ls-tree -l 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c -- /Users/samarthverulkar/Downloads/BlockNinja/index.html [1324ms]
2025-09-22 02:20:13.939 [info] > git ls-tree -l 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c -- /Users/samarthverulkar/Downloads/BlockNinja/styles.css [1318ms]
2025-09-22 02:20:13.939 [info] > git ls-tree -l 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c -- /Users/samarthverulkar/Downloads/BlockNinja/index.js [1334ms]
2025-09-22 02:20:25.814 [info] > git log --format=%H%n%aN%n%aE%n%at%n%ct%n%P%n%D%n%B -z --shortstat --diff-merges=first-parent -n50 --skip=0 --topo-order --decorate=full --stdin [81ms]
2025-09-22 02:20:31.430 [info] > git push -u main main [2688ms]
2025-09-22 02:20:31.430 [info] To https://github.com/samarth641/CryptoSlayer.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/samarth641/CryptoSlayer.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. If you want to integrate the remote changes,
hint: use 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
2025-09-22 02:20:31.477 [info] > git config --get commit.template [40ms]
2025-09-22 02:20:31.479 [info] > git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) --ignore-case refs/heads/main refs/remotes/main [41ms]
2025-09-22 02:20:31.522 [info] > git for-each-ref --sort -committerdate --format %(refname) %(objectname) %(*objectname) [41ms]
2025-09-22 02:20:31.525 [info] > git status -z -uall [44ms]
2025-09-22 02:21:04.494 [info] > git config --get commit.template [85ms]
2025-09-22 02:21:04.499 [info] > git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) --ignore-case refs/heads/main refs/remotes/main [87ms]
2025-09-22 02:21:04.590 [info] > git for-each-ref --sort -committerdate --format %(refname) %(objectname) %(*objectname) [89ms]
2025-09-22 02:21:04.593 [info] > git status -z -uall [93ms]
2025-09-22 02:21:20.041 [info] > git ls-tree -l 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c -- /Users/samarthverulkar/Downloads/BlockNinja/index.html [1440ms]
2025-09-22 02:21:20.042 [info] > git ls-tree -l 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c -- /Users/samarthverulkar/Downloads/BlockNinja/README.md [1435ms]
2025-09-22 02:21:20.042 [info] > git ls-tree -l 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c -- /Users/samarthverulkar/Downloads/BlockNinja/index.js [1449ms]
2025-09-22 02:21:20.043 [info] > git ls-tree -l 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c -- /Users/samarthverulkar/Downloads/BlockNinja/styles.css [1440ms]
2025-09-22 02:21:31.753 [info] > git ls-tree -l 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c -- /Users/samarthverulkar/Downloads/BlockNinja/index.html [274ms]
2025-09-22 02:21:31.754 [info] > git ls-tree -l 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c -- /Users/samarthverulkar/Downloads/BlockNinja/README.md [268ms]
2025-09-22 02:21:31.754 [info] > git ls-tree -l 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c -- /Users/samarthverulkar/Downloads/BlockNinja/styles.css [271ms]
2025-09-22 02:21:31.754 [info] > git ls-tree -l 27c2c7cc1af7b2db87b1485a6d2dc5444fee4c9c -- /Users/samarthverulkar/Downloads/BlockNinja/index.js [279ms]
