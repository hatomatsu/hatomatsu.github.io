
# Table of Contents

-   [ABOUT](#org8be1a01)
    -   [Links](#org90521cf)
    -   [Repository Structure](#orgcbff68d)



<a id="org8be1a01"></a>

# ABOUT


<a id="org90521cf"></a>

## Links

-   My homepage URL: <https://hatomatsu.github.io/>
-   X / Twitter: <https://x.com/hatomatzu>
-   YouTube: [はとまつ - YouTube](https://www.youtube.com/channel/UCAPzKjekYs17jkNIqW0eqvw)


<a id="orgcbff68d"></a>

## Repository Structure

      hatomatsu.github.io/
    ├── index.html                 # Created from index.org using org-export
    ├── assets/
    │   ├── css/
    │   └── images/
    │
    ├── pdf/                       # Downloadable files served on the site
    │   ├── example.pdf
    │   └── papers/
    │       └── paper1.pdf
    │
    ├── src/                        # Source files you edit
    │   ├── tex/                    # store .tex files
    │   ├── markdown/               # store .md files
    │   ├── org/                    # Emacs org-mode files
    │   └── cpp/                    # C++ source code
    │       ├── project1/
    │       │   ├── main.cpp
    │       │   ├── include/
    │       │   ├── src/
    │       │   ├── CMakeLists.txt
    │       │   └── README.md
    │       └── examples/
    │           └── hello-world.cpp
    │
    ├── build/                      # Build artifacts (ignored by git)
    │   ├── tex/
    │   ├── org/
    │   └── cpp/
    │       └── project1/
    │           └── project1        # Compiled executable
    │
    ├── scripts/
    │   └── build.sh
    │
    │
    ├── abs/
    │   └── example.html           # abstract page 
    │
    ├── README.md                   # Created from README.org using org-export
    └── .gitignore

