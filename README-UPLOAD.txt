MANULIFE INVESTING PERSONALITY QUIZ - WEBSITE PACKAGE
Built for: https://manuquiz.tmediatechnology.com/
=====================================================
Upload EVERYTHING in this folder (keep the folders as they are):
  index.html   the quiz        | assets/ artwork   | share/ saveable result images
  og/          Facebook preview pictures            | result/ public shared result pages
  CNAME        only for GitHub Pages

HOW THE RULES WORK
  * Adviser ID code: compulsory ONLY on 7 Jan 2027 (00:00 to 23:59, Malaysia time). Hidden on all other days.
    Judged by the website's own clock, so a guest's wrong phone clock does not matter.
  * To TEST the Adviser ID screen before the event, open the quiz with  ?adviser=on  on the end of the address:
    https://manuquiz.tmediatechnology.com/?adviser=on
  * Result page: Save image + Share to Facebook first. Once the guest has done both, the buttons change to
    Start over + Explore Manulife Investments. (A small "Skip" link lets anyone move on. To remove it, in index.html
    change  ALLOW_SKIP: true  to  ALLOW_SKIP: false )

BEFORE GOING LIVE
  1. The Google Sheet link is already inside index.html.
  2. The site must open with https://
  3. Test each result link at https://developers.facebook.com/tools/debug/ (click "Scrape Again"):
     https://manuquiz.tmediatechnology.com/result/oyen.html
     https://manuquiz.tmediatechnology.com/result/bina.html
     https://manuquiz.tmediatechnology.com/result/rimba.html

DESKTOP BACKGROUND
  On desktop-size screens (wide, 900px and over) the quiz and the shared result pages sit on
  assets/bg_desktop.jpg. Phones, tablets in portrait and the 1080x1920 standee are unchanged.
