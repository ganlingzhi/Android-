# Android-![2021022113594852](https://user-images.githubusercontent.com/55912832/200491605-8411f219-940b-435e-aeba-0647024d5a60.jpeg)


onCreate:Activity第一次运行时调用，可用于加载布局，获取控件命名空间等一些初始化工作
onRestart:当Activity被重新启动时，调用此方法
onStart:表示Activity正在被启动，已经从不可见到可见状态(不是指用户可见，指Activity在后台运行，没有出现在前台)，但还是无法与用户交互
onResume:Activity已经变为可见状态了，并且出现在前台工作了，也就是用户可见了
onPause:表示Activity正在暂停，但Activity依然可见，可以执行一些轻量级操作，但一般不会进行太多操作，因为这样会影响用户体验
onStop:表示Actiivty即将暂停，此时Activity工作在后台，已经不可见了，可以与onPause方法一样做一些轻量化操作，但依然不能太耗时。
onDestroy:活动即将被销毁
