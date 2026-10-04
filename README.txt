LOZO FILES + APKS - starter website

Files:
- index.html : public download page
- admin.html : frontend admin/upload mockup

HOW TO USE
1. Open index.html to test the 3-step flow.
2. Replace the example entries in the `files` array with real storage URLs.
3. Upload index.html and admin.html to your static host.
4. For real uploads, connect a backend/object-storage service and authentication.

IMPORTANT
This starter does not upload files by itself. GitHub Pages is static hosting, so use proper file/object storage for APK/ZIP files.
Ads: replace the clearly labeled ad areas with code from an ad network you are approved to use. Never make ad clicks a condition for downloading.


PER-FILE LINKS & COUNTERS
Each file entry has its own `id` and `url`. The starter tracks a separate download counter for each ID in the browser. For production, counters should be stored server-side so they are shared across all users.

1-MINUTE TIMER
The current design keeps the requested 3 x 15-second gates. If you want each gate to be 60 seconds, change the three `countdown(...,15)` calls to `countdown(...,60)`.
