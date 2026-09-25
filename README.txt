AMAZON INTERNATIONAL WEBSITE
============================
Open index.html in a browser to view the site. Arabic is the default; the EN button switches to English.
Navigation is the small floating dots on the side of the screen: they highlight the section you are in,
show its name when you point at them, and never cover the page.

THE QUOTE FORM
A visitor fills it in and picks WhatsApp or email. Either way the request is sent complete,
exactly as typed, to the number/address set at the top of the script in index.html:
  var WHATSAPP = "96555776301";
  var EMAIL    = "amazoninternational527@gmail.com";
Change those two lines to send requests somewhere else.

ADDING YOUR IMAGES
Put images in the "images" folder with these exact names (JPG). Each image appears automatically once the file exists.
Until then the site shows a placeholder with the file name it expects.

  images/logo.png              your logo (transparent PNG works best, shown in the header)
  images/hero.jpg              main image at the top (square-ish, e.g. 1400x1500)
  images/about-1.jpg           About section, tall (4:5)
  images/about-2.jpg           About section, small square
  images/services/booths.jpg   Services card images (16:10)
  images/services/interior.jpg
  images/services/3d.jpg
  images/services/stages.jpg
  images/services/fabrication.jpg
  images/services/branding.jpg
  images/booths/booth-01.jpg ... booth-05.jpg      built booth photos
  images/3d/design-01.jpg ... design-04.jpg        3D renders (remove client names/logos first)
  images/interior/interior-01.jpg ... interior-03.jpg

ADDING MORE PROJECTS
Open index.html in a text editor and find "var PROJECTS". Copy a line and change the src, category and captions:
  { src:"images/booths/booth-06.jpg", cat:"booths", en:"English caption", ar:"الوصف بالعربي" },
cat can be: booths, 3d, interior.  Add  wide:true  to make a tile double width.
