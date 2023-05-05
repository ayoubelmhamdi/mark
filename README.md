# Mark a file/directory


This tool selects a file/directory and processes it with another tool such as [Paste](https://github.com/ayoubelmhamdi/past) or [Move](https://github.com/ayoubelmhamdi/move).

```shell
$ mark file.txt
```
At this point, we have a string `file.txt` in `tmp/target_content`.

## Example of using the Past tool
```shell
$ past
```
`past` without arguments copies the file/directory content in the file `/tmp/target_content` to this working directory.

## Contribution

- This project requires many `PR`s to handle permission errors, redundancy, and storage limits.
- This project should be refactored in another programming language such as C, Rust, or Go.
