============================================================
  ADHYAYAN EDUTECH — SYSTEME.IO SETUP GUIDE
  READ THIS FIRST before pasting any sections
============================================================

FILES IN THIS FOLDER:
─────────────────────
  00_GLOBAL_CSS.css     → Paste into Page Custom CSS (do this FIRST)
  01_NAV.html           → Navigation bar
  02_HERO.html          → Hero / banner section
  03_CERT_STRIP.html    → Certifications strip (orange bar)
  04_COURSES.html       → All 9 courses grid
  05_WHY_US.html        → Why Choose Us (8 cards, dark bg)
  06_COMBO_COURSES.html → Combo offers with discount badges
  07_STATS_BAR.html     → Stats bar (500+ students, 10+ courses...)
  08_GALLERY.html       → Photo gallery (you add your own images)
  09_CONTACT.html       → Contact form + branch addresses
  10_FOOTER.html        → Footer


STEP 1 — ADD GLOBAL CSS (do this once)
───────────────────────────────────────
1. In your Systeme.io page editor, click the ⚙ gear icon (Page Settings)
2. Find "Custom CSS" or "Head Code" section
3. Open 00_GLOBAL_CSS.css and paste the entire contents there
4. Save


STEP 2 — BUILD THE PAGE SECTIONS
──────────────────────────────────
For each section (01 through 10), do this:

  a. In the Systeme.io editor, drag a new SECTION onto the page
  b. Inside the section, drag a ROW
  c. Inside the row, drag an HTML element (it looks like "</>")
  d. Click the HTML element to open the code editor
  e. Paste the contents of the corresponding .html file
  f. Click Save / Apply

Repeat for each section in order (01 → 10).


SECTION BACKGROUND COLORS:
────────────────────────────
Set these in the Section settings → Background color:

  01_NAV.html           → #ffffff  (white)
  02_HERO.html          → #0d1b40  (dark navy)
  03_CERT_STRIP.html    → #e85d1a  (orange)
  04_COURSES.html       → #ffffff  (white)
  05_WHY_US.html        → #0d1b40  (dark navy)
  06_COMBO_COURSES.html → #f8f6f2  (light gray)
  07_STATS_BAR.html     → #ffffff  (white)
  08_GALLERY.html       → #ffffff  (white)
  09_CONTACT.html       → #0d1b40  (dark navy)
  10_FOOTER.html        → #080f22  (near black)


SECTION PADDING:
────────────────
  For each section in Systeme.io settings, set:
  Top padding: 0px  |  Bottom padding: 0px
  (All padding is handled inside the HTML blocks already)


GALLERY PHOTOS (Section 08):
──────────────────────────────
The gallery section has placeholder spots. To add your real photos:

  1. Go to Systeme.io → Files / Media Library
  2. Upload the WhatsApp photos you received (classroom, students, etc.)
  3. Copy each photo's URL from the media library
  4. Open 08_GALLERY.html in a text editor
  5. Replace each "YOUR_XXXXX_URL_HERE" with the real photo URL
  6. Paste the updated code into Systeme.io


CONTACT FORM (Section 09):
────────────────────────────
Option A (Best): Use Systeme.io's own Form element instead of the
HTML form in Section 09. This connects directly to your contacts.
  - Delete the form box from the HTML
  - Drag Systeme.io's Form block into that area
  - Connect it to your email list in the automation settings

Option B: Keep the HTML form and connect via Webhook:
  - In Systeme.io automations, create a Webhook trigger
  - Copy the webhook URL and add it to the form's action="" attribute


NAVIGATION LINKS:
──────────────────
The nav links use anchor IDs (e.g. #ae-courses, #ae-contact).
Each section HTML already has matching id="" attributes.
If Systeme.io scrolling doesn't work between sections,
use Systeme.io's built-in anchor/link settings on nav buttons instead.


FONTS:
───────
All sections use 'Sora' from Google Fonts. This loads automatically
via the @import in the CSS. No extra setup needed.


COLORS REFERENCE:
──────────────────
  Navy (primary):    #0d1b40
  Orange (accent):   #e85d1a
  Gold (highlight):  #f0a500
  Light gray (bg):   #f8f6f2
  Text mid:          #3d4f7c


CONTACT & SOCIAL:
──────────────────
  Phone 1:    9318543435
  Phone 2:    9459014028
  Landline:   01902-314840
  Instagram:  @adhyayankullu
  Facebook:   @adhyayankullu (search page name)
  Branch 1:   Near Govt College Gate, Kullu, HP 175101
  Branch 2:   Above Bank of Baroda, Gandhi Nagar, Kullu, HP 175101

============================================================
