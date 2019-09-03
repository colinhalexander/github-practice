# Notes

Other Step - Linking:
git init(ialize) the directory as a local git repo
create repo on github.com, get SSH key
link it: git remote add origin /SSH-key/

Stage -> Commit -> Push Cycle
(working, saving) -> 
    (officially save to git; w/message!) -> 
        (publish to remote repo, github)

commands: (git add /file/) -> 
    (git commit -m "message" /file/) -> 
        (git push origin master; working directory implied)

Commands in Terminal:
git - use it first, tells computer that you'll be entering git commands after
(git) init - initialize as a local git repository
(git) status - check status of directory you're in
(git) add file.type - add specified file to git tracking (this is staging)
(git) add . - add all untracked files in current directory
(git) commit -m "message" - commit changes (save), best practice to add '-m' tag with
    descriptive message about what you've changed
(git) remote add origin /SSH key/ - create repo on github, then link via SSH key 
    note: origin is an optional name for remote repo, but typical
(git) push origin master - push committed changes to origin repo master branch
