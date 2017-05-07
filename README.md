# RtlViewPager
ViewPager that displays items from right to left for RTL locales and behaves like a regular ViewPager otherwise. Forked version of <a href="https://github.com/diego-gomez-olvera/RtlViewPager">RtlViewPager</a> and it inculudes some fixes.

[ ![Download](https://api.bintray.com/packages/farukcankaya/maven/RtlViewPager/images/download.svg) ](https://bintray.com/farukcankaya/maven/RtlViewPager/_latestVersion)

# Showcase

<div align="center">
	<img src="demos/RtlViewPager.gif" width="360" height="600" />
</div>

# Usage

### Add dependecy

```java
dependencies {
    ...
    compile 'com.farukcankaya.rtlviewpager:1.0.3'
}
```

### Add RtlViewPager to layout

```xml
<com.farukcankaya.rtlviewpager.RtlViewPager
        android:id="@+id/pager"
        android:layout_width="match_parent"
        android:layout_height="match_parent" />
```

thats all!
