# metis 5.1.0 (needed to build the elmer flatpak)

I was having problems building ElmerFEM as a flatpak because at the time when I was building it, the university website hosting the source tarball for the version of metis that was known to work in the flatpak build, seemed to be offline. Just out of laziness to edit the patches to get it compiled with a newer version of metis from elsewhere, I just decided to grab a tarball from some random sourceforge page and make it into this git repo.... of course I at least checked the sha256sum to verify it first. It matched the sum in the flatpak manifest.

edit: i got it from here --> https://sourceforge.net/projects/foam-extend/files/ThirdParty/metis-5.1.0.tar.gz/download
