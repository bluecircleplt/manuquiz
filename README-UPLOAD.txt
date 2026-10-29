MANULIFE INVESTING PERSONALITY QUIZ - WEBSITE PACKAGE
Built for: https://manuquiz.tmediatechnology.com/
=====================================================
Upload EVERYTHING in this folder to the root of manuquiz.tmediatechnology.com.
Keep the folder structure as it is:

  index.html          the quiz
  assets/             artwork used by the quiz
  share/              the images guests can save to their device
  og/                 the preview pictures Facebook shows when a result is shared
  result/             the public result page (one per character) that gets shared
  CNAME               only needed if hosting on GitHub Pages (harmless otherwise)

Before going live:
  1. In index.html find   SCRIPT_URL: ""   and put your Google Apps Script link between the quotes.
  2. The site must open with https:// (Facebook requires it).

After going live, test each result link in Facebook's Sharing Debugger:
  https://developers.facebook.com/tools/debug/
  https://manuquiz.tmediatechnology.com/result/oyen.html
  https://manuquiz.tmediatechnology.com/result/bina.html
  https://manuquiz.tmediatechnology.com/result/rimba.html
