# RemovePermissionGrant

The patch file is used to remove permission grant process of `android-10.0.0_r35`.

## Features:
1. auto grant permission.
2. remove the annoying message: This app was built for an older version of Android and may not work properly. Try checking for updates or contact the developer.
3. bypass these use WindowManager.LayoutParams.FLAG_SECURE to prevent taking snapshot.

## Howto 

1. follow the instruction of `https://mirrors.tuna.tsinghua.edu.cn/help/AOSP/`, use branch `android-10.0.0_r35`, e.g., `repo init -u http://mirrors.tuna.tsinghua.edu.cn/git/AOSP/platform/manifest -b android-10.0.0_r35`

2. apply the patch `android-10.0.0_r35.diff` or modify the source follows `android-10.0.0_r35.diff`.
