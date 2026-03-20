---
layout: post
topic: counting
---

How To Count
Is cron working?
 file search paths in maxima\\
24072023 \\
[Maxima-discuss] more about file search paths,24072023 \\
(%i1) file_search_maxima;\\
(%o1) [/home/toy/.maxima/**/*.mac, /home/toy/.maxima/**/*.wxm, 
/home/toy/src/sourceforge/maxima/share/**/*.mac, 
/home/toy/src/sourceforge/maxima/src/*.mac, 
/home/toy/src/sourceforge/maxima/*.mac]\\
(%i2) file_search_lisp;\\
(%o2) [/home/toy/.maxima/**/*.sse2f, /home/toy/.maxima/**/*.lisp, 
/home/toy/src/sourceforge/maxima/share/**/*.lisp, 
/home/toy/src/sourceforge/maxima/src/*.sse2f, 
/home/toy/src/sourceforge/maxima/src/*.lisp, 
/home/toy/src/sourceforge/maxima/*.sse2f, 
/home/toy/src/sourceforge/maxima/*.lisp]\\
(%i3) file_search_demo;\\
(%o3) [/home/toy/src/sourceforge/maxima/share/**/*.dem, 
                                   /home/toy/src/sourceforge/maxima/demo/*.dem]\\
(%i4) file_search_usage;\\
(%o4) [/home/toy/src/sourceforge/maxima/share/**/*.usg, 
                                    /home/toy/src/sourceforge/maxima/doc/*.usg]\\