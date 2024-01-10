# Resources

On this page you will find some helpful resources that are discused in class.

## Softwares

### Primary Code Editor

- VSCode
    - Download it from [here](https://code.visualstudio.com/download).
    - Make sure to download the correct version for your operating system.
    - The stable build is recommended for most users.

### FTP Clients

- Option A: FileZila (Windows, Mac, Linux)
    - Download it from [here](https://filezilla-project.org/download.php?type=client).
    - Make sure to download the correct version for your operating system.
    - Install the client version

- Option B: WinSCP (Windows)
    - Download it from [here](https://winscp.net/eng/download.php).
    - This is an SFTP client for Windows. It is simple, clean, and effective.

## Alternative Softwares

The following link includes various alternative softwares that you can use for this course.

#### Editors

- Atom [Download](https://atom.io/)
    - Created by github, relatively new and very impressive editor.
    - Recommended plugin: emmet

- Notepad++ [Download](https://notepad-plus-plus.org)
    - Well established, syntax highlighting editor

- Sublime [Download](https://www.sublimetext.com/3)
    - A very advanced and capable editor.

- WebStorm [Download](https://www.jetbrains.com/webstorm/download)
    - Part of intelij, a very powerful IDE.

## CIS Server

[http://cisweb.ufv.ca](http://cisweb.ufv.ca) is a web server for publishing content. Use SFTP to manage the content and HTTP to view the content.

Use the following information to access your personal server:

```{code-block} text
host: cisweb.ufv.ca
port: 22
protocol: sftp
login: (your student id)
password: (your password)
```

```{warning}
If you have multiple login errors, the server will ban your address for an interval ranging from a few minutes to a few hours, so if you have a password login error, carefully re-enter your correct username and password before retrying. If the server does not respond at all, your address is probably temporarily banned.
```

When you are logged in via sftp to the cisweb.ufv.ca server, your home directory is `/home/cis145/(studentid)`. Any files placed in this directory are accessible to the world using a web browser at `http://cisweb.ufv.ca/~(studentid)`.

```{tip}
If you change from `/home/cis145/(studentid)` to its parent directory (..) your sftp client will not be able to read or write from the current directory. This is intentional, as you are not permitted to list all other home directories on the system. The simplest solution is to just change back to your home directory by changing to `(/home/cis145/(studentid))` or, depending on your sftp client, by clicking on home icon.
```
