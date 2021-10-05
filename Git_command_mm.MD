Git Commands
============
#Myanmar Version

### Git Project အသစ်တစ်ခု စတင်ပြုလုပ်ခြင်း

| Command | ဖော်ပြချက် |
| ------- | ----------- |
| `git init` | folder ကို Git folder အဖြစ်သတ်မှတ်ခြင်း  |
| `git clone ssh://git@github.com/[username]/[repository-name].git` | ရှိပြီးသား git folder တစ်ခုအား local PJ folder အဖြစ်သတ်မှတ်ခြင်း |

### အခြေခံလုပ်ဆောင်ချက်များ

| Command | ဖော်ပြချက် |
| ------- | ----------- |
| `git status` | Git folder ထဲမှာ ရှိတဲ့ file တွေဖော်ပြခြင်း |
| `git add [file-name.txt]` | file အသစ်ထည့်ခြင်း |
| `git add .` | file အားလုံးပေါင်းထည့်ခြင်း |
| `git commit -m "[commit message]"` | version မှတ်တမ်းသတ်မှတ်ခြင်း |
| `git commit -am "[commit message]"` | add ပြီးသား file ကို version သတ်မှတ်ခြင်း/update လုပ်ခြင်း |
| `git rm -r [file-name.txt]` | file အား git folder မှဖယ်ရှားခြင်း |

### Branch ခွဲထွက်ခြင်း နှင့် ပေါင်းစပ်ခြင်း

| Command | ဖော်ပြချက် |
| ------- | ----------- |
| `git branch` | git folder အတွင်းတွင်ရှိသော Branches များအားကြည့်ရှုခြင်း |
| `git branch [branch name]` | Branch အသစ်တစ်ခုပြုလုပ်ခြင်း |
| `git branch -d [branch name]` | Branch ဖျက်သိမ်းခြင်း |
| `git push origin --delete [branch name]` | ဆက်သွယ်ထားသော Git folder မှ branch အားဖျက်သိမ်းခြင်း |
| `git checkout -b [branch name]` | Branch အသစ်တစ်ခုပြုလုပ်ပြီး ၎င်း branch ထဲသို့ ကူးပြောင်းစေခြင်း |
| `git checkout -b [branch name] origin/[branch name]` | တခြား Git folder မှ branch အား ပုံတူကူးပြီး  ၎င်း branch ထဲသို့ ကူးပြောင်းစေခြင်း  |
| `git branch -m [old branch name] [new branch name]` | branch နာမည်ပြင်ဆင်ခြင်း |
| `git checkout [branch name]` | branch ကူးပြောင်းခြင်း |
| `git checkout -` | မူလ branch သို့ ပြန်လည်ကူးပြောင်းခြင်း |
| `git checkout -- [file-name.txt]` | file ၏ပြောင်းလဲမှုများကို ဖျက်သိမ်းခြင်း |
| `git merge [branch name]` | ‌ရောက်ရှိနေသော branch နှင့် ပေါင်းစပ်ခြင်း |
| `git merge [source branch] [target branch]` | branch နှစ်ခုပေါင်းစပ်ခြင်း |
| `git stash` | Stash changes in a dirty working directory |
| `git stash clear` | Remove all stashed entries |

### မျှဝေခြင်း နှင့် ပြန်လည်ပြင်ဆင်ခြင်း

| Command | ဖော်ပြချက် |
| ------- | ----------- |
| `git push origin [branch name]` | ချိတ်ဆက်မှုပြုလုပ်ထားသော Git Folder သို့ branch တစ်ခု ပို့ခြင်း |
| `git push -u origin [branch name]` | ချိတ်ဆက်မှုပြုလုပ်ထားသော Git Folder သို့ branch တစ်ခု ပို့ပြီး ၎င်း branch အားအသုံးပြုခြင်း |
| `git push` | ချိတ်ဆက်မှုပြုလုပ်ထားသော Git Folder သို့ branch တစ်ခု ပို့ပြီး ၎င်း branch အားအသုံးပြုခြင်း |
| `git push origin --delete [branch name]` | ချိတ်ဆက်မှုပြုလုပ်ထားသော Git Folder မှ branch တစ်ခု အားဖျက်သိမ်းခြင်း |
| `git pull` | local folder သို့ ချိတ်ဆက်မှုပြုလုပ်ထားသော git folder မှ Version များယူခြင်း |
| `git pull origin [branch name]` | local folder သို့ ချိတ်ဆက်မှုပြုလုပ်ထားသော git folder မှ Version များယူခြင်း |
| `git remote add origin ssh://git@github.com/[username]/[repository-name].git` | တခြား Git folder တစ်ခုအားချိတ်ဆက်ခြင်း |
| `git remote set-url origin ssh://git@github.com/[username]/[repository-name].git` | Set a repository's origin branch to SSH |

### စစ်ဆေးခြင်း နှင့် နှိုင်းယှဥ်ခြင်း

| Command | ဖော်ပြချက် |
| ------- | ----------- |
| `git log` | version မှတ်တမ်းပြန်ကြည့်ခြင်း |
| `git log --summary` | version မှတ်တမ်းများအား အသေးစိတ်ပြန်လည်ကြည့်ရှုခြင်း |
| `git log --pretty=oneline` |  version မှတ်တမ်းအားတစ်ကြောင်းချင်းစီဖော်ပြခြင်း |
| `git diff [source branch] [target branch]` | ပေါင်းစပ်မှု မပြုလုပ်ခင် ပြောင်းလဲမှုများ အား ပြန်လည်ကြည့်ရှုခြင်း |
