## 上马自动签到 [![Run Auto Sign](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml/badge.svg)](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml)

### 基于 Node.js + GitHub Action 实现上海马拉松官网每日签到

### Use 使用

1. Fork本项目（顺手点Star以示鼓励～🥳）
2. 在Repo的Setting页面，添加名为上马官网的用户名：`SM_USERNAME`和密码：`SM_PASSWORD`的Secret 
3. 手动测试运行
<img width="1444" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/695683c9-fbc2-4cab-9ef8-41e2ddf59b78">
在控制台应该能看到 `签到成功/请勿重复签到` 的提示
<img width="990" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/399e89f7-2ad6-486e-9e67-8953564ec528">


### 关于Job执行时间
签到Job执行时间是**UTC时间0点**，也就是**北京时间8点**执行，**不过由于GitHub的负载比较重**，真正签到时间可能延后一段时间，一般是几十分钟，这个延迟时间取决于GitHub Action的负载。

### 申明
- 本项目仅做学习交流, 禁止用于各种非法途径
- Auto Sign-in run successful on Fri Sep 13 06:46:04 UTC 2024
- Auto Sign-in run successful on Sat Sep 14 00:42:53 UTC 2024
- Auto Sign-in run successful on Sun Sep 15 00:49:58 UTC 2024
- Auto Sign-in run successful on Mon Sep 16 00:46:55 UTC 2024
- Auto Sign-in run successful on Tue Sep 17 00:36:34 UTC 2024
- Auto Sign-in run successful on Wed Sep 18 00:43:25 UTC 2024
- Auto Sign-in run successful on Thu Sep 19 00:44:07 UTC 2024
- Auto Sign-in run successful on Thu Sep 19 08:19:06 UTC 2024
- Auto Sign-in run successful on Fri Sep 20 00:20:30 UTC 2024
- Auto Sign-in run successful on Sat Sep 21 00:19:54 UTC 2024
- Auto Sign-in run successful on Sun Sep 22 00:22:44 UTC 2024
- Auto Sign-in run successful on Mon Sep 23 00:21:16 UTC 2024
- Auto Sign-in run successful on Tue Sep 24 00:20:48 UTC 2024
- Auto Sign-in run successful on Tue Sep 24 06:58:53 UTC 2024
- Auto Sign-in run successful on Wed Sep 25 00:20:52 UTC 2024
- Auto Sign-in run successful on Thu Sep 26 00:20:31 UTC 2024
- Auto Sign-in run successful on Fri Sep 27 00:20:54 UTC 2024
- Auto Sign-in run successful on Sat Sep 28 00:20:36 UTC 2024
- Auto Sign-in run successful on Sun Sep 29 00:23:31 UTC 2024
- Auto Sign-in run successful on Mon Sep 30 00:21:52 UTC 2024
- Auto Sign-in run successful on Tue Oct  1 00:23:30 UTC 2024
- Auto Sign-in run successful on Wed Oct  2 00:20:47 UTC 2024
- Auto Sign-in run successful on Thu Oct  3 00:20:51 UTC 2024
- Auto Sign-in run successful on Fri Oct  4 00:20:49 UTC 2024
- Auto Sign-in run successful on Sat Oct  5 00:20:38 UTC 2024
- Auto Sign-in run successful on Sun Oct  6 00:22:54 UTC 2024
- Auto Sign-in run successful on Mon Oct  7 00:22:08 UTC 2024
- Auto Sign-in run successful on Tue Oct  8 00:20:39 UTC 2024
- Auto Sign-in run successful on Wed Oct  9 00:24:23 UTC 2024
- Auto Sign-in run successful on Thu Oct 10 00:20:42 UTC 2024
- Auto Sign-in run successful on Fri Oct 11 00:20:50 UTC 2024
- Auto Sign-in run successful on Sat Oct 12 00:20:12 UTC 2024
- Auto Sign-in run successful on Sun Oct 13 00:22:43 UTC 2024
- Auto Sign-in run successful on Mon Oct 14 00:22:06 UTC 2024
- Auto Sign-in run successful on Tue Oct 15 00:21:06 UTC 2024
- Auto Sign-in run successful on Wed Oct 16 00:21:09 UTC 2024
- Auto Sign-in run successful on Thu Oct 17 00:21:10 UTC 2024
- Auto Sign-in run successful on Fri Oct 18 00:20:55 UTC 2024
- Auto Sign-in run successful on Sat Oct 19 00:20:47 UTC 2024
- Auto Sign-in run successful on Sun Oct 20 00:23:09 UTC 2024
- Auto Sign-in run successful on Mon Oct 21 00:22:04 UTC 2024
- Auto Sign-in run successful on Tue Oct 22 00:21:16 UTC 2024
- Auto Sign-in run successful on Wed Oct 23 00:21:10 UTC 2024
- Auto Sign-in run successful on Thu Oct 24 00:21:07 UTC 2024
- Auto Sign-in run successful on Fri Oct 25 00:21:17 UTC 2024
- Auto Sign-in run successful on Sat Oct 26 00:20:38 UTC 2024
- Auto Sign-in run successful on Sun Oct 27 00:23:09 UTC 2024
- Auto Sign-in run successful on Mon Oct 28 00:22:47 UTC 2024
- Auto Sign-in run successful on Tue Oct 29 00:21:35 UTC 2024
- Auto Sign-in run successful on Wed Oct 30 00:21:25 UTC 2024
- Auto Sign-in run successful on Thu Oct 31 00:21:28 UTC 2024
- Auto Sign-in run successful on Fri Nov  1 00:23:46 UTC 2024
- Auto Sign-in run successful on Sat Nov  2 00:20:50 UTC 2024
- Auto Sign-in run successful on Sun Nov  3 00:23:28 UTC 2024
- Auto Sign-in run successful on Mon Nov  4 00:22:14 UTC 2024
- Auto Sign-in run successful on Tue Nov  5 00:21:01 UTC 2024
- Auto Sign-in run successful on Wed Nov  6 00:20:50 UTC 2024
- Auto Sign-in run successful on Thu Nov  7 00:21:01 UTC 2024
- Auto Sign-in run successful on Fri Nov  8 00:20:52 UTC 2024
- Auto Sign-in run successful on Sat Nov  9 00:20:29 UTC 2024
- Auto Sign-in run successful on Sun Nov 10 00:22:32 UTC 2024
- Auto Sign-in run successful on Mon Nov 11 00:21:55 UTC 2024
- Auto Sign-in run successful on Tue Nov 12 00:20:43 UTC 2024
- Auto Sign-in run successful on Wed Nov 13 00:21:11 UTC 2024
- Auto Sign-in run successful on Thu Nov 14 00:20:59 UTC 2024
- Auto Sign-in run successful on Fri Nov 15 00:22:22 UTC 2024
- Auto Sign-in run successful on Sat Nov 16 00:22:10 UTC 2024
- Auto Sign-in run successful on Sun Nov 17 00:24:01 UTC 2024
- Auto Sign-in run successful on Mon Nov 18 00:23:29 UTC 2024
- Auto Sign-in run successful on Tue Nov 19 00:22:16 UTC 2024
- Auto Sign-in run successful on Wed Nov 20 00:22:08 UTC 2024
- Auto Sign-in run successful on Thu Nov 21 00:22:19 UTC 2024
- Auto Sign-in run successful on Fri Nov 22 00:22:53 UTC 2024
- Auto Sign-in run successful on Sat Nov 23 00:21:48 UTC 2024
- Auto Sign-in run successful on Sun Nov 24 00:24:07 UTC 2024
- Auto Sign-in run successful on Mon Nov 25 00:23:04 UTC 2024
- Auto Sign-in run successful on Tue Nov 26 00:22:40 UTC 2024
- Auto Sign-in run successful on Wed Nov 27 00:22:44 UTC 2024
- Auto Sign-in run successful on Thu Nov 28 00:22:42 UTC 2024
- Auto Sign-in run successful on Fri Nov 29 00:22:42 UTC 2024
- Auto Sign-in run successful on Sat Nov 30 00:22:14 UTC 2024
- Auto Sign-in run successful on Sun Dec  1 00:27:33 UTC 2024
- Auto Sign-in run successful on Mon Dec  2 00:24:01 UTC 2024
- Auto Sign-in run successful on Tue Dec  3 00:24:06 UTC 2024
- Auto Sign-in run successful on Wed Dec  4 00:23:18 UTC 2024
- Auto Sign-in run successful on Thu Dec  5 00:23:16 UTC 2024
- Auto Sign-in run successful on Fri Dec  6 00:23:12 UTC 2024
- Auto Sign-in run successful on Sat Dec  7 00:22:49 UTC 2024
- Auto Sign-in run successful on Sun Dec  8 00:25:13 UTC 2024
- Auto Sign-in run successful on Mon Dec  9 00:24:19 UTC 2024
- Auto Sign-in run successful on Tue Dec 10 00:23:34 UTC 2024
- Auto Sign-in run successful on Wed Dec 11 00:23:25 UTC 2024
- Auto Sign-in run successful on Thu Dec 12 00:23:17 UTC 2024
- Auto Sign-in run successful on Fri Dec 13 00:23:25 UTC 2024
- Auto Sign-in run successful on Sat Dec 14 00:22:29 UTC 2024
- Auto Sign-in run successful on Sun Dec 15 00:25:30 UTC 2024
- Auto Sign-in run successful on Mon Dec 16 00:24:18 UTC 2024
- Auto Sign-in run successful on Tue Dec 17 00:23:10 UTC 2024
- Auto Sign-in run successful on Wed Dec 18 00:22:21 UTC 2024
- Auto Sign-in run successful on Thu Dec 19 00:22:34 UTC 2024
- Auto Sign-in run successful on Fri Dec 20 00:21:30 UTC 2024
- Auto Sign-in run successful on Sat Dec 21 00:20:52 UTC 2024
- Auto Sign-in run successful on Sun Dec 22 00:23:30 UTC 2024
- Auto Sign-in run successful on Mon Dec 23 00:22:34 UTC 2024
- Auto Sign-in run successful on Tue Dec 24 00:21:32 UTC 2024
- Auto Sign-in run successful on Wed Dec 25 00:21:13 UTC 2024
- Auto Sign-in run successful on Thu Dec 26 01:20:31 UTC 2024
- Auto Sign-in run successful on Fri Dec 27 01:21:04 UTC 2024
- Auto Sign-in run successful on Sat Dec 28 01:19:37 UTC 2024
- Auto Sign-in run successful on Sun Dec 29 01:34:49 UTC 2024
- Auto Sign-in run successful on Mon Dec 30 01:23:17 UTC 2024
- Auto Sign-in run successful on Tue Dec 31 01:20:51 UTC 2024
- Auto Sign-in run successful on Wed Jan  1 01:27:30 UTC 2025
- Auto Sign-in run successful on Thu Jan  2 01:20:43 UTC 2025
- Auto Sign-in run successful on Fri Jan  3 01:21:28 UTC 2025
- Auto Sign-in run successful on Sat Jan  4 01:19:53 UTC 2025
- Auto Sign-in run successful on Sun Jan  5 01:27:24 UTC 2025
- Auto Sign-in run successful on Mon Jan  6 01:24:53 UTC 2025
- Auto Sign-in run successful on Tue Jan  7 01:21:57 UTC 2025
