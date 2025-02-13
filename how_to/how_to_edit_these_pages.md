## How to edit these pages

Basically just the usual process of committing changes to a branch in github, opening a pull request for that branch, and then merging it to the main branch.

#### Start by cloning the github repository

```
git clone git@github.com:KIPAC/Rubin.git
```

or

```
git clone https://github.com/KIPAC/Rubin.git
```


#### Make a branch for your changes


```
git checkout -b my_nice_changes
```


#### Edit the files you want to add, add any new materials, etc...

Don't forget to `git add` any new files you have added.


#### Commit your changes to the branch and push it back to the origin


```
git commit -m "I made it prettier" the_file_I_edited.md
git push
```

Note that the `git push` might fail with a message telling you to set the remote branch.  If so, just
copy & paste the command it suggests.


#### Navigate to github and open a Pull Request for your changes.

https://github.com/KIPAC/Rubin/pulls


#### Pick a couple of the site managers to review your changes.   Once they are approved you can merge them.  This will automatically update the web pages in a few minutes.



