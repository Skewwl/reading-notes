# Command Line

### Path
- A path is a means to get to a particular file or directory on the system. Absolute paths specify a location (file or directory) in relation to the root directory. Relative paths specify a location in relation to where we currently are in the system.

### Files
- We use an extensionless system, in other words all of the directories, which make up our hierarchical system, are files that don't have an extension tagged on at the end.
- Spaces in file and directory names are perfectly valid but we need to be a little careful with them. As you would remember, a space on the command line is how we seperate items. They are how we know what is the program name and can identify each command line argument. If we wanted to move into a directory called Holiday Photos for example the following would not work.
- In the above instance we would have to use quotes or the escape character. Quotes would look like this, "Holiday Photos" and the escape character, which is a backslash ( \ ) that nullifies the special meaning of the next character, would look like this, Holiday\ Photos.

### Manual
- The manual pages are a set of pages that explain every command available on your system including what they do. An example, man <command>, or man ls, man pwd, etc.
- Long hand command line options begin with two dashes, like --all, and short hand options begin with a single dash, like -a. They do the same thing.

### Manipulation
- With mkdir we can add a -p, -v and/or -pv. '-p' which tells mkdir to make parent directories as needed, which would be helpful with this command, mkdir -p linuxtutorialwork/foo/bar. And '-v' makes mkdir tell us what it is doing. Here's an example: mkdir -pv linuxtutorialwork/foo/bar -> mkdir: created directory 'linuxtutorialwork/foo' -> mkdir: created directory 'linuxtutorialwork/foo/bar'.
- rmdir linuxtutorialwork/foo/bar would delete bar.
- touch filename creates a file.
- cp filename copiedfile copies a file, filename, and renames it copiedfile.
- mv filename destination/optionalrename, would move a file to a directory, and could potentially be renamed in the process.
- mv foo foo3 will rename the file foo to foo3. because we did not include a destination/ like was done above.
- rm filename will remove a file.
- rm -r directoryname will allow you to remove a non-empty directory.



