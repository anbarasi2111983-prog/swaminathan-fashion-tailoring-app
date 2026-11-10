SWAMINATHAN FASHION TAILORING - Android Studio Project

முக்கிய குறிப்பு:
இந்த ZIP source project + GitHub Actions cloud build workflow. இது நேரடியாக APK அல்ல.
இந்த சூழலில் Android SDK / Gradle build environment இல்லாததால் APK-ஐ நேரடியாக compile செய்து வழங்க முடியவில்லை.

மொபைல் மட்டும் இருந்தால் APK உருவாக்கும் வழி (GitHub cloud build):
1. GitHub account உருவாக்கவும் / உள்நுழையவும்.
2. இந்த ZIP-ஐ extract செய்து, உள்ளே உள்ள project files-ஐ GitHub-ல் புதிய repository-க்கு upload செய்ய வேண்டும். .github folder உட்பட எல்லா files-யும் upload ஆக வேண்டும்.
3. Repository பெயர் SwaminathanTailoring என வைக்கலாம்.
4. GitHub repository-யில் Actions tab திறக்கவும்.
5. "Build Swaminathan Tailoring APK" workflow-ஐத் தேர்ந்தெடுத்து Run workflow அழுத்தவும்.
6. Build முடிந்ததும் workflow run பக்கத்தின் Artifacts பகுதியில் "Swaminathan-Tailoring-APK" ZIP download செய்யவும்.
7. ZIP-ஐ extract செய்து app-debug.apk-ஐத் திறந்து install செய்யவும். Android கேட்கும்போது அந்த browser/file manager-க்கு Install unknown apps அனுமதி கொடுக்கவும்.

கவனம்:
- GitHub web interface-ல் project-இன் எல்லா files-யும் (hidden .github folder உட்பட) upload செய்ய வேண்டும். Mobile browser-ல் hidden files upload செய்வது சிரமமாக இருக்கலாம்; GitHub Desktop/PC இருந்தால் எளிது.
- இது debug APK; தனிப்பட்ட பயன்பாட்டுக்கான install build. Public Play Store வெளியீட்டுக்கு release signing மற்றும் கூடுதல் சோதனை தேவை.
- Android 10 (API 29) அல்லது அதற்கு மேல்.
- Order data இந்த device-ன் WebView LocalStorage-ல் சேமிக்கப்படும்; cloud sync இல்லை.
- PDF/Excel library-கள் CDN-ல் இருந்து load ஆகுவதால் அந்த வசதிகளுக்கு internet தேவை.
- Excel backup spreadsheet-ல் order, items, measurements சேரும்; uploaded photos spreadsheet backup-ல் சேராது.
- Browser storage அளவு வரம்புடையது. நிறைய புகைப்படங்களை சேமித்தால் இடம் நிரம்பலாம்; Excel backup-ஐ அடிக்கடி எடுக்கவும்.
