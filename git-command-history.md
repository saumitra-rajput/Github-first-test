  21  cd gh/
   22  git clonegit@github.com:saumitra-rajput/gh-master.git
   23  git clone git@github.com:saumitra-rajput/gh-master.git
   24  ls
   25  cd gh-master/
   26  ls
   27  git config --global user.anme
   28  git config --global --list
   29  git config global --list
   30  git config --list
   31  git config global | grep user
   32  git user
   33  git config
   34  git config --global
   35  git config --global -l
   36  ls
   37  git pull
   38  git push
   39  git fetch
   40  git configt --global | grep user
   41  git config --global | grep user
   42  git config user.name
   43  git config -l
   44  git config --global user.name "Saumitra Rajput"
   45  git config --global user.email "saumitrarajput3jan@gmail.com"
   46  ls
   47  git config --list
   48  ls
   49  cd gh-notes/
   50  ls
   51  cat readme.md
   52  cd
   53  ls
   54  cd gh/
   55  ls
   56  git clone git@github.com:saumitra-rajput/bash-scripting.git
   57  ls
   58  cd bash-scripting/
   59  git config --list
   60  ls
   61  cd ..
   62  git gh-master/
   63  ls
   64  cd gh-master/
   65  ls
   66  clear
   67  ls
   68  git status
   69  git checkout -b dev
   70  ls
   71  git status
   72  git log --online
   73  git log --oneline
   74  git push origin dev
   75  git status
   76  ls
   77  mkdir local
   78  cd local/
   79  ls
   80  vim git-commands.md
   81  cd ..
   82  ls
   83  git status
   84  ls
   85  git add .
   86  git commit -m "Added a local file on devlocal"
   87  git push origin dev
   88  git status
   89  git fetch
   90  ls
   91  git loa
   92  git local/
   93  ls
   94  cd local/
   95  ls
   96  cat git-commands.md
   97  git status
   98  git pull
   99  git pull origin dev
  100  git log -oneline
  101  git log --oneline
  102  cd ..
  103  l
  104  cd ..
  105  ls
  106  git clone git@github.com:saumitra-rajput/my-linux.git
  107  ls
  108  git clone git@github.com:saumitra-rajput/Github-first-test.git
  109  ls
  110  cd Github-first-test/
  111  ls
  112  git status
  113  git checkout -feature-login
  114  git checkout -b feature-login
  115  ls
  116  git status
  117  git log --onelinde
  118  git log --oneline
  119  clear
  120  ls
  121  touch test.txt
  122  touch second.txt
  123  ls
  124  git status
  125  git add .
  126  l
  127  git status
  128  git commit -m "Added txt file on feature b"
  129  ls
  130  git log --oneline
  131  ls
  132  touch third.txt
  133  git add third.txt
  134  git commit -m "Added third file in feature b"
  135  touch four.txt
  136  git add for
  137  git add four.txt
  138  ls
  139  git status
  140  git commit -m "Added four txt in feature"
  141  git status --oneline
  142  git log --oneline
  143  git checkout main
  144  ls
  145  git log  --oneline
  146  clear
  147  ls
  148  git checkout feature-login
  149  git log --oneline
  150  git checkout main
  151  git log --oneline
  152  git merge feature-login
  153  git log --oneline
  154  git status
  155  git checkout -b feature-signup
  156  ls
  157  touch signup.txt
  158  git add .
  159  git commit -m "Add signup in signup b"
  160  git checkout main
  161  touch main.txt
  162  git add main.txt
  163  git commit "Added main in main b"
  164  git commit -m"Added main in main b"
  165  git log --oneline
  166  git checkout feature-signup
  167  git log --oneline
  168  git checkout  main
  169  git merge feature-signup
  170  git status
  171  git log --oneline
  172  ls
  173  git status
  174  git checkout -b feature-profile
  175  touch fp1.txt
  176  git add  .
  177  git commit -m "Added fp1 in feature P b"
  178  touch fp2.txt
  179  git add  .
  180  git commit -m "Added fp2 in feature P b"
  181  touch fp3.txt
  182  git add  .
  183  git commit -m "Added fp3 in feature P b"
  184  touch fp4.txt
  185  git commit -m "Added fp3 in feature P b"
  186  git add  .
  187  git commit -m "Added fp4 in feature P b"
  188  git log --oneline
  189  git checkout main
  190  git log --oneline
  191  git merge --squash feature-profile
  192  git log --oneline
  193  git checkout -b feature-settings
  194  touch fs1.txt
  195  git add .
  196  git commit -m "Added fs1 in fs b"
  197  touch fs2.txt
  198  git add .
  199  git commit -m "Added fs2 in fs b"
  200  touch fs3.txt
  201  git add .
  202  git commit -m "Added fs3 in fs b"
  203  touch fs4.txt
  204  git add .
  205  git commit -m "Added fs4 in fs b"
  206  git log --oneline
  207  git checkout main
  208  git log --oneline
  209  git status
  210  git merge feature-settings
  211  git log --oneline
  212  Trade-offs (What you lose)
  213  Loss of granular history
  214  Individual commits (bug fixes, experiments, progress) are gone
  215  Harder debugging
  216  You can’t easily pinpoint which exact commit introduced a bug
  217  Reduced traceability
  218  Less visibility into development process (who did what, step-by-step)
  219  Collaboration issues (sometimes)
  220  If others depend on commit history, rewriting it (via rebase + squash) can cause conflicts
  221  git status
  222  git push
  223  git branch
  224  git checkout feature-login
  225  git push
  226  git push origin feature-login
  227  git checkout feature-profile
  228  git push origin feature-profile
  229  git checkout feature-settings
  230  git push origin feature-settings
  231  git checkout feature-signup
  232  git push origin feature-signup
  233  git checkout main
  234  git branch
  235  ls
  236  history
