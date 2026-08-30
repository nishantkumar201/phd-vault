*Summary of using said tool*
## JDK version
Use JDK 11, not 17 — JDK 17 throws `InaccessibleObjectException` on this app. (source: [[2026-09#N1- 2026-08-30 - Setting up OpenSim|N1]])

### Setup
```bash
brew install openjdk@11
sudo nano ".../opensim.conf"
# set: jdkhome="/opt/homebrew/opt/openjdk@11/libexec/openjdk.jdk/Contents/Home"
```