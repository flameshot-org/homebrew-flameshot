# Flameshot-org Tap

This tap exists as an easy way to install Flameshot on MacOS. The main brew repository requires app's be notarized by Apple. However, Apple charges $100 per year and requires a government ID and I am unwilling to do either of these things. Instead, I will happily provide this tap as a convenient way to install Flameshot. 

To use this tap:

```
brew tap flameshot-org/flameshot
brew trust --cask flameshot-org/flameshot/flameshot-org-flameshot
brew install  flameshot-org-flameshot
```