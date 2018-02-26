One time setup on all PCs:  
1. change the group policy (`gpedit.msc`)
2. in gpedit: `User Config > Admin Templates > Desktop > Desktop`
3. in desktop menu, enable the policy for `Desktop Wallpaper`
4. edit the policy, in wallpaper name put `YI-1-51K0T92\commIT\wallpaper.jpg`
5. wallpaper style: Fill

After that, you just need to change the `wallpaper.jpg` in `C:\Windows\commIT\` in `YI-1-51K0T92`, which is YIH 01 PC, the one on the left on the supervisor desk in YIH. 

Make sure that the wallpaper has the setting of:
- Format: .jpg
- Dimensions: 1920 x 1080

Note:
- Loggin in with local account (e.g. quickprint acc, pcadminxxx, etc.) instead of domain account (e.g. nusstu\xxx, nusstf\xxx) will result in no wallpaper due to different credentials
