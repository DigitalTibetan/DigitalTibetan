# Tibetan and mobile devices

| Mobile device | Displays Tibetan | Tibetan input method | Apps | Support | Comment |
| :--------- | :---: | :---: | :---: | :---: | ----------------------------|
| [Google Android](configuration_android.md) | + + | + + | + + + | + + | Full Tibetan support since Android 6.0 (2015) |
| [Apple iPhone, iPad](configuration_ios.md) | + + | +[^1] | + | - - | Full Tibetan support since iOS 4.21 (2010), slowly breaking |
| Amazon Kindle | - -[^2] | - - | - - - | - - | Amazon Kindle support for Tibetan is broken since Kindle OS version 5.9.6 |

## I want to get a new mobile, what's best for Tibetan?

Since both major platforms, Google's Android and Apple's iOS fully support Tibetan, it's mostly a matter of taste which platform is preferred.

- Generally **[Android](configuration_android.md) is more open** and easier to customize to more complex applications. If you plan to have maximum possibilities, go with Android. There are significantly more Tibetan apps available for Android than for the other platforms. The language-rendering parts of Android are open-source, and problems are usually fixed efficiently.
- Slightly **easier** to use for some people are Apple iOS devices ([**iPhone, iPad**](configuration_ios.md)). This comes at the cost of fewer degrees of freedom: Installing your own content, fonts and cross-application interoperability is considerably hampered when compared to Android. Apple's support process for low resource languages is simply non-existing: so in case of technical problems, you're on your own.

For most people, the actual **differences** between Android and iOS **do not matter**: just check both app stores for the applications you might want to use. Generally, power-users that want to access all technical possibilities, including extension and development are better off with Android, in terms of ease-of-use iOS has advantages for some.

Unfortunately most **e-ink ebook readers** are not particularly well suited for Tibetan. Amazon Kindle has completely **broken Tibetan** support, so those cannot be used. Amazon support was unable to track and fix the problem.

Some ebook manufacturers (e.g. PocketBook) offer some degree of Tibetan support, but it is still rather limited when compared with Android or iOS devices. Not recommended.

## How do I work with Tibetan on my mobile device?

Setup, fonts and Tibetan keyboard:

* [Apple iOS configuration](configuration_ios.md)
* [Android configuration](configuration_android.md)

## Apps

Dictionaries, tools and other apps:

* [Apple iOS apps for Tibetan](apps_ios.md)
* [Android apps for Tibetan](apps_android.md)


[^1]: iOS currently has a bug that sometimes duplicates stacked Tibetan letters during input with Apple's implementation of the Wylie import method with iOS hardware keyboards (e.g. Apple magic keyboard for iPad). The duplicate letters vanish as soon as a complete syllable is entered. Apple has so far been unable to fix this.
[^2]: Older kindle models (before operating system update 5.9.6) did correctly display Tibetan script. Current version have broken the support for Tibetan. Amazon has so far been unable to fix this.
