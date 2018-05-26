##  tools.sh

Make snapshots of the git repositories inside a directory. 
Save / Pull / Clone all of them at once.
Takes effect in the current working directory.

 usage : tools.sh [add|list|pull|clone]
 
### tools.sh add

When using tools.sh add, a .toolsrc file listing all of the git repositories in directory will be generated.

### tools.sh list

List all of the git repositories found in your .toolsrc file.

### tools.sh pull

Pull all of the git repositories in ./* .

### tools.sh clone

Clone all of the git repositories described in your .toolsrc file.
