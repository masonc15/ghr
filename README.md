# ghr

ghr is a command line tool for creating and pushing git repositories to GitHub. Glorified wrapper for [`gh`](https://github.com/cli/cli) specific to my workflow.

## Usage

```
ghr -p -d "A description of the repo" -f file.txt
```

Options:

- `-p, --public`: Make the repo public
- `-d, --description`: A description of the repo
- `-f, --file`: The file to be uploaded (the repo will be created with the same name as the file)
- `-h, --help`: Show this help message

## Examples

Create a public repo with a description:

```
ghr -p -d "My awesome repo"
```

Create a private repo and populate it with a file:

```
ghr -f myfile.txt
```
