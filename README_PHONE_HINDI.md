# MyReel — Phone se Cloud APK Build (Starter)

Yeh Android-first Flutter UI starter hai. Ismein Home, Reels, Create, Chat, Profile ke demo screens aur GitHub Actions cloud build workflow hai.

## Zaroori sach
- Yeh abhi **demo/starter** hai; live login, OTP, backend, media upload, calls, moderation aur monetization connected nahi hain.
- Is project se APK build karne ke liye apne phone se GitHub par repository banana/upload karna hoga.
- OTP, password, Firebase private credentials kisi ko chat mein na dein.

## Android phone se APK banane ka tareeqa
1. GitHub app ya browser mein GitHub account banaye/sign in karein.
2. New repository banayein, naam `myreel` rakhein. Public ya Private aap choose kar sakte hain.
3. ZIP ko phone mein extract karein. Repository mein project files upload karein, folders bhi upload hon: `lib`, `.github/workflows`.
4. GitHub repository kholein → **Actions** tab → `Build MyReel Android APK`.
5. **Run workflow** dabayein. Build complete hone ka wait karein.
6. Workflow run ke neeche **Artifacts** mein `MyReel-Android-APK` download karein.
7. ZIP artifact extract karein; usmein `app-release.apk` hoga. Android par install karte waqt browser/file manager se install permission maangi ja sakti hai.

## Agar Actions tab ya Run workflow na dikhe
Repository Settings → Actions mein GitHub Actions enable karein. Phir main branch par workflow file maujood honi chahiye.

## Agla development
- Firebase project aur Android app registration
- 18+ age gate and secure authentication
- Firestore security rules + user/post schema
- Firebase Storage / video storage
- Real upload, likes, comments, follows, chat
- Reporting, blocking, admin review
- Privacy policy, terms, account deletion
- Production testing and Play Store release

## User age and safety
MyReel ko intended 18+ service ke liye age verification/age gate design karna hoga. Sirf birth date field ko strong age verification na samjhein. Platform policies and local laws check karein.
