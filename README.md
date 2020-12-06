# How i push Large File Using LFS

Download Git-lfs from this link https://git-lfs.github.com/

    git init
    git remote add origin https://github.com/imraviarora/spark2.4.7-targz.git
    git lfs track "spark/*.tgz"
    git add .
    git commit -m "LF file is pushing"
    git push -u origin master

# Ravi Arora
# rarora7878@gmail.com
