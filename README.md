# RemovePermissionGrant:

The patch file is used to remove permission grant process of `android-11.0.0_r27`.

## Features:
1. auto grant permission.
2. remove the annoying message: This app was built for an older version of Android and may not work properly. Try checking for updates or contact the developer.
3. bypass these use WindowManager.LayoutParams.FLAG_SECURE to prevent taking snapshot.

## TODO:

| # |  Folder   | Status |
| ---- |  :----:  | :----: |
|1| 1 | - |

## Howto: 

1. follow the instruction of `https://mirrors.tuna.tsinghua.edu.cn/help/AOSP/`, use branch `android-11.0.0_r27`, e.g., `repo init -u http://mirrors.tuna.tsinghua.edu.cn/git/AOSP/platform/manifest -b android-11.0.0_r27`

2. apply the patch `android-11.0.0_r27.diff` or modify the source follows `android-11.0.0_r27.diff`.
