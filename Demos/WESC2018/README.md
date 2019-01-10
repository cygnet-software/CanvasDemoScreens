# CanvasDemoScreens

These screens are designed to showcase some of the 9.2 Canvas features. 

They are built on top of the CygNet for Production data model and sample data, so if you want them to run in your environment, you'll need to make some changes.

Step 1) Stage the files. You can run the screens locally or from a BSS. A few of the screens use script hyperlinking to navigate, so you'll need to update the paths in the script to match your environment.

Step 2) Fix image paths. The buttons on the Navigation screen reference vector images. If you store the images in your BSS in a folder called IMAGES, the links should work. If you want to change the path, use Find/Replace on the string "XXXXXX.BSS\IMAGES"

Step 3) Replace site name. Use the Find/Replace feature in Canvas 9.2 to replace the placeholder site name (XXXXXX) with your local site.

Step 4) Change points and time ranges. These screens reference points in the CygNet for Production sample data. Change these UDCs (and their historical time ranges) to values meaningful in your system.

Step 5) Relative facility relationships. There are some examples of relative facilities in these screens. If your data doesn't require relative facility relationships, change these settings. Otherwise, if your data is using the CygNet for Production data model, you can use the provided Global Settings File. The screens each have a reference to their Global Settings File (XXXXXX.BSS\GLOBAL\globalsettings.gsf) which can be changed via Find/Replace. If you have your own data model, you'll need to define it in your global settings, and then reference it accordingly in your version of these sample screens.


