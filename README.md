Hasher Script

The Hasher script calculates hash checksums and provides detailed information about a specified file.
Usage

bash

`hasher <file_path>`

Replace <file_path> with the path to the file you want to analyze.

Example

Let's say you want to analyze the script. You would run the Hasher script as follows:

bash```
hasher script
```
The script would then provide detailed information about the file including metadata and various hash checksums.

```
Wed Aug 16 12:22:43 PM EDT 2023
--------------------------------------------------
  File: script
  Size: 339       	Blocks: 8          IO Block: 4096   regular file
Device: 254,0	Inode: 46817289    Links: 1
Access: (0755/-rwxr-xr-x)  Uid: ( 1000/      user)   Gid: ( 1000/      user)
Access: 2023-08-16 12:06:08.633624175 -0400
Modify: 2023-08-16 12:02:42.066609833 -0400
Change: 2023-08-16 12:02:42.066609833 -0400
 Birth: 2023-08-16 12:02:42.066609833 -0400
--------------------------------------------------
6c729109c8b4c81b129e714ff5993cd3  script
bb3503214d8a89c245ba8858377e8141c8b6e3a4  script
12181033fc09cfde5fc2262de7396e998f310e444264dd2bdd2f15711a86a68e  script
7cb8b9eff14121032652d0e6a71c1d212b44e5e028ab8e659752d817cf658f4528c3a38ffc6a35fedd854f116a8fdc6ef0a1b9e1fadbff57c2a8efa5eb84f552  script
```
