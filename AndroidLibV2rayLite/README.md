# AndroidLibV2rayLite

进入`AndroidLibV2rayLite`文件夹

```
go mod download
```



编译aar

```
$ go install golang.org/x/mobile/cmd/gomobile@latest
$ gomobile init

export PATH="${PATH}:/Users/zz/go/bin/"
gomobile bind -v -o android.aar -target=android ./
export ANDROID_HOME="/Users/zz/Library/Android/sdk"
export ANDROID_NDK_HOME="/Users/zz/Library/Android/sdk/ndk/23.0.7196353"
export ANDROID_NDK_HOME="/Users/zz/Library/Android/sdk/ndk/21.3.6528147"
```

