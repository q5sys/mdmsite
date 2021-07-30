# mdmsite
mdmsite
 
Steps to preview:

1) Install Hugo
2) run `git clone https://github.com/q5sys/mdmsite`
3) run `cd mdmsite`
4) run `hugo serve`
5) open http://localhost:1313/

Updated Steps to deploy so even a toddler could deploy this:

1) ssh into whatever www directory has the files for http://minddripmedia.com/ and delete them (leave nginx running).
2) Install Hugo `sudo dnf install hugo -y`
3) run `git clone https://github.com/q5sys/mdmsite`
4) run `cd mdmsite`
5) run `hugo`
6) run `cd public`
7) run `rsync -vz ./ ${yourserver}`
8) sit back and wonder why we've been 30 seconds away from this being done for months.

.
