To add this tap to brew:

    brew tap jcgay/jcgay

# Maven deluxe

A Maven installation with nice additions:

 - [maven-color](https://github.com/jcgay/maven-color), add colors to maven console output.
 - [maven-notifier](https://github.com/jcgay/maven-notifier), add desktop notifications for your build.
 - [maven-profiler](https://github.com/jcgay/maven-profiler), measure build time.
 
If maven is already installed:

    brew unlink maven 
 
then:

    brew install maven-deluxe
    
# [Send-Notification](https://github.com/jcgay/send-notification)

A CLI to send desktop notifications backed by various implementations (Growl, notify-send, Snarl, OS X notification center, etc)

    brew install send-notification

# [chtignore](https://github.com/jcgay/chtignore)

Print `.gitignore` template from [https://github.com/github/gitignore](https://github.com/github/gitignore) in standard output.

    brew install chtignore

# [notify.sh](https://github.com/jcgay/notify.sh)

Send desktop notification when a command finishes.

    brew install notify-sh