# GitPython

#### `repo = git.Repo('/path/to/dir')`
repo object
#### `origin = repo.remotes['origin']`
remote object - 'origin' is name of remote
#### `origin.pull()`
pull from remote object

#### `repo.is_dirty()`
are there tracked files with changes present?

#### `repo.index.add(['/path/to/file'])`
add file to index

#### `repo.index.commit("Commit msg")`
commit with commit message

#### `origin.push()`
push to remote

#### `repo.git.checkout('--', '/path/to/file')`
"git checkout -- file" to throw away local changes

#### `repo.head.reset('--hard')`
hard reset to remove all local changes
