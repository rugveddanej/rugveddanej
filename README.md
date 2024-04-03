### Upload Folders Via Termux

- Open your project in the termux
```
cd /sdcard/Projects/
```

- Add your account name in the termux
```
git config --global user.name "rugveddanej"
```

- Add your account email in the termux
```
git config --global user.email "rugveddanej.code@gmail.com"
```

- Initialize your project
```
git init
```

- Config directory for github
```
git config --global --add safe.directory /storage/emulated/0/Download/rugveddanej
```

- Add Directory to github
```
git add *
```

- Commit in your repository
```
git commit -m "Uploading files via Termux"
```

- Add repository where to upload files
```
git remote add origin https://github.com/rugveddanej/_.git
```

- Push files to repository
```
git push origin master
```

- Put Username
```
rugveddanej
```

- Put Token from https://github/settings/tokens
