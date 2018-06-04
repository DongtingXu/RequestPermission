# RequestPermission
让主Activity继承RequestPermission，然后调用requestPermission(String[] permissions, int requestCode)接口即可，自动判断编译版本是否大于M，
M以下系统返回true，用户拒绝权限授予后会弹出提示框提示用户到设置里面授予权限，否则无法正常使用app。
