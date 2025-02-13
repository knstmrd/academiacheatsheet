
# CLI

* `julia -e 'using Pkg; Pkg.generate("MyPKG")'` - generate boilerplate package "MyPKG"
* `python3 -m http.server` - run `localhost:8000` server from directory
* `jupyter lab --no-browser --port=1234` - run jupyter lab for remote access
* `du -sh ./* | sort -h` - display all subdirectories sorted by size
* `find . -name "*.dat" -type f -delete` - delete all `.dat` files in current directory
* `grep --include="*.jl"  -nRHI 'search_string' *` - find `search_string` in all files with given extension (`.jl` in this case)
* `convert input.png -trim output.png` - trim background from png
* `tar czfv name_of_archive.tar.gz name_of_directory_to_compress` - tarball and compress a directory
* `ffmpeg -framerate 3 -start_number 1 -i prefix_%d.png -pix_fmt yuv420p out.mp4` - convert all
    images with names `prefix_1.png`, `prefix_2.png` into a mp4 video with a framerate of 3 fps

# Git

* `git tag -a v1.0.0 -m 'version 1.0.0'` - create git tag
* `git push origin tag v1.0.0` - push tag
* `git branch` - list selected branches
* `git tag -l` - list tags
* `git checkout tags/<tag_name>` - checkout specific tag (add `-b <branch_name>` to checkout to a new branch)

# Matplotlib

* `ax.tick_params(axis='both', labelsize=tick_size)` - set size of tick labels
* `ax.legend(fontsize=legend_size, ncol=2, framealpha=1.0)` - 2-column legend, no transparency
* `ax.set_axisbelow(True)` - set Z-order of ticks and grid below others

# Packages

* `https://github.com/lincolnloop/python-qrcode` - create QR codes from Python

# Websites

* https://www.when2meet.com/ - scheduling meetings
* https://cassi.cas.org/ - journal name abbreviations
* https://beej.us/guide/bggit/html/split/ - Git guide
* https://croppdf.com - crop whitespace from PDFs
* https://smallpdf.com - compress PDFs
