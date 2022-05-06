# xamarin-reminder

## Xamarin Android

## Filter device log

```bash
adb logcat | findstr com.example.package
```

## Xamarin iOS

### How to list all iOS code signin key

```bash
security find-identity -v -p codesigning
```

## How to not panic when ios code signing key not found in keychain

- Be sure that your signing key is the keychain with [this](###how-to-list-all-iOS-code-signin-key)
- Visual Studio need to be run as administrator

## ipa file is no more generated and 'Build iTunes Package Archive' is checked

In Visual Studio, you must target 'Remove Device' and not 'Local Device'
![image](https://user-images.githubusercontent.com/50547935/118830237-11b0dd00-b8bf-11eb-859b-5be30d94db7b.png)
