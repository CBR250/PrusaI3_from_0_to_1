# PrusaI3_from_0_to_1
Collect all tools from internet into the repository.

## git submodule
### git add submodule under Bundle/snipmate-snippets'
Example : <br />
git submodule add \<git-rul> \<folder> <br />
git submodule add https://github.com/spf13/snipmate-snippets.git Bundle/snipmate-snippets <br />
<br />
git commit -ae<br />
git push<br />

### git update submodule
git submodule update --init (clone all submodule)<br />
git submodule foreach git pull origin master (update all submodule)<br />


### remove snipmate from submodule
git rm Bundle/snipmate-snippets<br />
rm ‘Bundle/snipmate-snippets’<br />

### Clean all file which under Bundle/snipmate-snippets
git submodule deinit -f Bundle/snipmate-snippets<br />
Cleared directory ‘Bundle/snipmate-snippets’<br />
