PUT YOUR IMAGES IN THIS FOLDER
==============================
Save each photo with the exact file name below and it appears on the site automatically.
Until a file exists, the site shows a grey placeholder naming the file it is waiting for.

logo.png                    your logo (transparent PNG is best)
hero.jpg                    the big image at the top (roughly square, e.g. 1400x1500)
about-1.jpg                 About section, tall photo
about-2.jpg                 About section, small square photo

services/booths.jpg         the six service cards (each roughly 16:10)
services/interior.jpg
services/3d.jpg
services/stages.jpg
services/fabrication.jpg
services/branding.jpg

booths/booth-01.jpg  ...  booth-05.jpg        photos of booths you built
3d/design-01.jpg     ...  design-04.jpg        3D renders (remove client logos first)
interior/interior-01.jpg ... interior-03.jpg   interior decor photos

WALL PANELS (the materials section)
Two images per panel code, both named after the code:
  panels/WAL-20.jpg          the flat swatch on its own, tall, about 1:2.45
  panels/rooms/WAL-20.jpg    the same panel applied in a room
Cut them out of the catalogue page - do NOT use the whole catalogue page as one image,
and leave the logo and the code text out of the image itself; the site prints the code.
Then open index.html, find "var PANELS", and replace that list with your real codes.

TO ADD MORE PROJECTS
Open index.html, find the line "var PROJECTS", copy one line and change it:
  { src:"images/booths/booth-06.jpg", cat:"booths", en:"English caption", ar:"الوصف بالعربي" },
cat can be: booths, 3d, interior.   Add  wide:true  to make a tile double width.
