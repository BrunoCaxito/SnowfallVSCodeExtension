# Publish

Instructions of how to publish this extension.

* Execute Visual Studio Code as administrator:

```sh
Set-ExecutionPolicy unrestricted
npm install -g vsce
vsce package
```

Go to the marketplace page and drag and drop the .vsix file.
