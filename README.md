# bluetoothLockScreen
linux 扫描蓝牙自动锁屏和解锁  手机或者手环靠近电脑自动解锁

依靠Bluelog工具来扫描蓝牙设备
https://github.com/MS3FGX/Bluelog

打开脚本填写自己要绑定的蓝牙MAC地址
$myBluetoothCode = "xxxxxxxxx";

默认锁屏解锁命令为
loginctl lock-session
loginctl unlock-session
