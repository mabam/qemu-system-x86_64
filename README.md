### About
This Homebrew Tap will install QEMU for virtualising qemu-system-x86_64 only.

### Installation

```
brew tap mabam/qemu-system-x86 https://github.com/mabam/qemu-x86_64

brew install qemu-x86
```

### De-Installation
qemu-x86 cannot co-exist with regular QEMU. If you want to have QEMU virtualise/emulate platforms other than X86_64, install regular QEMU after uninstalling this Tap first:
```
brew uninstall qemu-x86

brew untap mabam/qemu-system-x86
