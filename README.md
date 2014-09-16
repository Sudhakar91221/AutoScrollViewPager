Android Auto Scroll ViewPager
==============================

## Usage
- include this library, use

``` xml
<cn.trinea.android.view.autoscrollviewpager.AutoScrollViewPager
	android:id="@+id/view_pager"
	android:layout_width="match_parent"
	android:layout_height="wrap_content" />
```
replace
``` xml
<android.support.v4.view.ViewPager
	android:id="@+id/view_pager"
	android:layout_width="match_parent"
	android:layout_height="wrap_content" />
```
- `startAutoScroll()` start auto scroll, delay time is `getInterval()`.
- `startAutoScroll(int)` start auto scroll delayed.
- `stopAutoScroll()` stop auto scroll.
