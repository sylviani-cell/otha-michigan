OTHA WEBSITE — VERSION 7 EDITING GUIDE

OPEN THE CORRECT FOLDER
1. Unzip this download.
2. In VS Code choose File > Close Workspace.
3. Choose File > Open Folder and select only the new “otha website” folder.
4. Open index.html and click Go Live.

NAVIGATION ORDER
Home | About | OTHA Events | Research Symposium | Board | Get Involved | Resources

WHAT CHANGED IN VERSION 5
- Added a separate Research Symposium page and archive for 2025 and 2026.
- Menu label is “Research Symposium”; page title identifies the Transplant Center Research Symposium.
- OTHA's symposium role is accurately described as volunteering, setup, tabling, and student engagement—not co-hosting.
- Reorganized OTHA Events in this order: Gift of Life Michigan Campus Challenge, Speaker Events, Volunteering, Camp Michitanki Fundraising, Education & Member Meetings, and High School Outreach.
- Removed Spookathon for now.
- Added short impact captions to each event section.
- Removed the old partnerships section from About.

REPLACING EVENT PHOTOS
Place your own image in the folder and give it the exact same filename:
- speaker-1.jpg, speaker-2.jpg
- volunteer-1.jpg through volunteer-4.jpg
- camp-michitanki.jpg
- meeting-1.jpg, meeting-2.jpg
- outreach-1.jpg, outreach-2.jpg
The page updates automatically after saving/refreshing.

RESEARCH SYMPOSIUM PHOTOS
Replace:
- symposium-2025-1.jpg through symposium-2025-3.jpg
- symposium-2026-1.jpg through symposium-2026-3.jpg
Open symposium.html to edit each year's title, theme, and recap.

CAMPUS CHALLENGE
campus-challenge-flyer.png is the supplied flyer image. Replace it in future years with a newer graphic using the same filename.

BOARD BIOS & PHOTO CROPS
Open board.html and search for a person's name to edit the biography.
Open style.css and search for .person--archit (or another name) to change object-position and center the face.

HOMEPAGE IMAGE
Replace hero-home.jpg with your own wide photograph using the exact same filename.

CONTACTS AND NEWSLETTER
Open resources.html and join.html to replace email, Instagram, Maize Pages, forms, and newsletter placeholders.


VERSION 6 UPDATES
- OTHA Events now has a dropdown menu linking directly to Campus Awareness, Speaker Events, Volunteering, Camp Michitanki Fundraising, Member Meetings, and Outreach.
- All board members are labeled as seniors.
- Position descriptions now appear inside each biography section rather than as separate subtitles above names.
- Personal biography text remains clearly editable in board.html.


VERSION 7 UPDATES
- Added the 2026 symposium theme: “Innovations in Transplantation: Beginning of a New Era.”
- Kept the 2026 archive description to one concise sentence.
- Symposium years use photo galleries only; no annual flyer requirement was added.
- No attendance or event-statistics section was added.
- Updated the Campus Challenge flyer display so the entire flyer fits without cropping.


INTERNAL PAGE HEADER PHOTOS
---------------------------
The homepage keeps its large hero image. Every other page now has a smaller photo banner.
To replace one, add a wide JPG with the exact filename below to this folder:

About: hero-about.jpg
OTHA Events: hero-events.jpg
Research Symposium: hero-symposium.jpg
Board: hero-board.jpg
Get Involved: hero-join.jpg
Resources: hero-resources.jpg

Recommended image shape: wide landscape, approximately 1800 x 700 pixels.
The dark overlay is added automatically so the white page title remains readable.
To reposition a photo, open style.css and find the matching .page-intro-- class. Add, for example:
background-position: center 35%;


ABOUT US / HOMEPAGE
- about.html is now the main landing page.
- index.html redirects to about.html so Go Live and GitHub Pages open the correct page.
- Replace hero-home.jpg for the large top hero.
- Replace about-mission-placeholder.jpg for the About Us mission photo.


NEWSLETTER FORM
The Get Involved page embeds the Brevo signup form directly. To change it, search join.html for e8beff2a.sibforms.com and replace the full URL inside the iframe src attribute.

INTEREST FORM
The About Us page now contains the interest-form button. Replace href="#" on the “Complete the Interest Form” button with the current interest form URL.


BOARD LEADERSHIP ARCHIVE
------------------------
The current board is labeled "Founding Team" on board.html.

To add a future leadership team:
1. In board.html, copy the full section beginning with:
   <section class="content-section content-section--cream" id="founding-team">
2. Paste the copy below the Founding Team section.
3. Change the copied id to a unique value, such as:
   id="2027-2028-team"
4. Change the heading "Founding Team" to the new team's name or academic year.
5. Replace the names, positions, majors, years, biographies, and photos.
6. In every page's Board dropdown, add:
   <a href="board.html#2027-2028-team"><strong>2027–2028 Team</strong></a>

The Board dropdown is intentionally structured so future leadership teams can be added as an archive.
