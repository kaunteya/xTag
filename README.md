# xTag

Automatic version updater for Xcode projects
It does following
- Updates Version based on parameters
- Increments build number by one
- Commits the change to git
- Applies the tag to the commit 

## Install
You can install `xTag` using 

### curl

```
curl -L https://raw.githubusercontent.com/kaunteya/xTag/master/installer.sh | sudo sh
```

### Manual
```
make install
```

## Usage
Run this command in your repo
```
xtag Info.plist p
```

## License
`xTag` is released under the MIT license. See LICENSE for details.
