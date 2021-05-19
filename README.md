# xamarin-reminder

## Xamarin iOS

### How to list all iOS code signin key
```bash
security find-identity -v -p codesigning
```
## How to not panic when ios code signing key not found in keychain
- Be sure that your signing key is the keychain with [this](###how-to-list-all-iOS-code-signin-key)
- Visual Studio need to be run as administrator
