# mykeys

My ([@colinbrislawn](https://github.com/colinbrislawn)'s) ssh keys.

## 📥 How to give me access to your compuer via ssh

-- idk, call me

## 📤 Once I'm in, how can I access my own secure GitHub repos?

-- 🔐➡️📋 Make new ssh keys, copy it to clipboard ([example gist](https://gist.github.com/stormpython/9517102))

```sh
ssh-keygen -t rsa
# press enter 3x times

cat ~/.ssh/id_rsa.pub
# copy the new key
# if there's one key, just triple-click > copy
```

-- 📋➡️ :octocat: Open [GitHub > Keys](https://github.com/settings/keys) > New SSH Key 🟢 > 📋 Paste > Add Key ✅
