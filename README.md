# Computer Networking: A Top-Down Approach 9<sup>th</sup> Edition

Repo to store notes and solutions to the Wireshark labs found here: [Computer Networking: A Top-Down Approach 9<sup>th</sup> Edition](https://gaia.cs.umass.edu/kurose_ross/wireshark.php)

Ran the following command to create `NOTES.md` files in all directories other than `ch1_getting_started` since I initially manually added the file there.

Did initial validation with:

```shell
find . -type d ! -name "ch1_*" -name "ch*_*"
```

```shell
find . -type d ! -name "ch1_*" -name "ch*_*" -exec touch {}/NOTES.md \;
```

- `.`: Starts search in the current directory.
- `-type d`: Selects only directories.
- `! -name "ch1_*"`: Selects all directories that don't start with `ch1_`.
- `-name "ch*_*"`: Selects all directories output from previous `-name` option that start with `ch*_*`.
- `-exec touch {}/NOTES.md \;`: Creates `NOTES.md` inside each found directory.
