<img src="https://github.com/adapta-project/adapta-github-resources/blob/master/images/logo_thumb.png" alt="Logo" align="left"/> Adapta-backgrounds
=========

A wallpaper collection for adapta-project.

| **1. Tri-Fadeno** | **2. Tealized** | **3. Suna** |
|:---:|:---:|:---:|
|<img src="https://github.com/adapta-project/adapta-github-resources/blob/master/images/tri-fadeno-thumbnail.jpg" alt="Tri-Fadeno"/>|<img src="https://github.com/adapta-project/adapta-github-resources/blob/master/images/tealized-thumbnail.jpg" alt="Tealized"/>|<img src="https://github.com/adapta-project/adapta-github-resources/blob/master/images/suna-thumbnail.jpg" alt="Suna"/>|
| Author: Tista<br>Resolution: 3840 x 2160 pixels<br>Image-Type: Drawing | Author: Tista<br>Resolution: 3840 x 2160 pixels<br>Image-Type: Drawing | Author: Tista<br>Resolution: 3840 x 2160 pixels<br>Image-Type: Drawing |

| **4. Poly** | **5. Kahelo** |
|:---:|:---:|
|<img src="https://github.com/adapta-project/adapta-github-resources/blob/master/images/poly-thumbnail.jpg" alt="Poly"/>|<img src="https://github.com/adapta-project/adapta-github-resources/blob/master/images/kahelo-thumbnail.jpg" alt="Kahelo"/>|
| Author: Tista<br>Resolution: 3840 x 2160 pixels<br>Image-Type: Drawing | Author: Tista<br>Resolution: 3840 x 2400 pixels<br>Image-Type: Drawing |

Installation from Package
------------
 * AUR: https://aur.archlinux.org/packages/adapta-backgrounds

 * PPA: https://launchpad.net/~tista/+archive/ubuntu/adapta

Installation from Git Source
------------

1. Check build-requirements:

 ```
 * libglib2.0-dev (glib2)          >= 2.48.0
 * meson                           >= 0.40
 ```

3. Build and install system-wide:

 ```
 meson build --prefix=/usr && cd build
 ninja
 sudo ninja install
 ```

 > **Note:**
 >
 >   * Currently `ninja` command builds nothing.

Work in Progress
----------------

TODO
----
* Hunt some more wallpapers
* Add a dynamic wallpaper

Public License
--------------
 GPLv2

 > **Note:**
 >
 > wallpaper files are licensed under CC BY-SA 4.0
