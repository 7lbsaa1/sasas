# sky7

واجهة اجتماعية عربية RTL متخصصة في صور السماء والطبيعة، مبنية بـ Vanilla HTML/CSS/JavaScript وFirebase Web SDK.

## التشغيل

```bash
python3 -m http.server 4173 --bind 0.0.0.0
```

`index.html` هو مدخل تسجيل الدخول. إعدادات Firebase في `js/firebase.js`. الواجهة تتضمن Demo feed حتى قبل وجود بيانات في قاعدة البيانات، وتحوّل auth إلى Firebase عند توفر إعدادات المشروع.
