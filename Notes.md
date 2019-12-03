 # Shell Commands 
    -; = on a line that has multiple Commands
    ` = list long directory
    ls = list files
        -L = long list
    curl = see webpage source code. = don't forget single quotes
    curl -l = -L meant to follow a redirect
       -o = save source to a file = -o filename.ext
    cat = display entire file = concatenate short for
    less = display a file one page at a time. 
        b = backup
        l = search
    rm = rmove file
        -i = add warning
    rmdir = remove directory
        -r = removes a non-empty directory
    pwd = print working directory




# Git Commands
    status = gets the status of the current directory
    log = logs of commits
        j or ↓ to move down one line at a time
        d to move by half the page screen
        f to move by a whole page screen
        to scroll up, press
        k or ↑ to move _up_ one line at a time
        u to move by half the page screen
        b to move by a whole page screen
        press q to quit out of the log (returns to the regular command prompt)
            --oneline: = short SHA and commit message
            --stat = displays the files that have been modified, number of lines edited, etc.
            --patch or -p = displays changes to a file
            --graph = displays branching
            --all = displays all branches
    diff = check changes of non committed files. 
    tag -a = add a message tag to a specific commit. -a is annotation for author,date,message.
        -d *tag name* = delete tag
    branch = display all branches and the currently selected branch.
        -d = delete branch
        -D = force delete
    branch *new branch* = create a new branch. 
    checkout *branch* = checkout a branch.
        -b = create new branch
    merge = merge branch
            There are two types of merges:
            Fast-forward merge – the branch being merged in must be ahead of the checked out branch.    The checked out branch's pointer will just be moved forward to point to the same         commit as the other branch.
            Regular type of merge
                two divergent branches are combined
                a merge commit is created
    commit = commit staged files
        --amend = change most recent commit message / add new changes to same commit
