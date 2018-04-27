# dotfiles

> Joseph's Ansible-powered dotfiles (currently only for macOS)

## Setup

```bash
./install.sh
```

## Todo

- [ ] Set keyboard hold repeat interval (https://apple.stackexchange.com/a/83923)
- [ ] Set trackpad acceleration `defaults write -g com.apple.trackpad.scaling 1`
- [ ] Enable trackpad "tap to click" `defaults write -g com.apple.AppleMultitouchTrackpad.Clicking 1`
- [ ] Enable trackpad "three finger drag" `defaults write -g com.apple.AppleMultitouchTrackpad.TrackpadThreeFingerDrag 1`
- [ ] Disable siri
- [ ] Finder settings: 
```
com.apple.finder._FXSortFoldersFirst 1
com.apple.finder.ShowExternalHardDrivesOnDesktop 0
com.apple.finder.ShowHardDrivesOnDesktop 0
com.apple.finder.ShowMountedServersOnDesktop 0
com.apple.finder.ShowRemovableMediaOnDesktop 0
com.apple.finder.NewWindowTarget "PfHm"
com.apple.finder.NewWindowTargetPath "file:///Users/jsphpl/"
``` 
- [ ] Disable siri
```
"com.apple.siricore.fides.DES Lottery Win Override Enabled" 0
"com.apple.siricore.fides.DES Recording Enabled" 0
com.apple.Siri.StatusMenuVisible 0
}
```
