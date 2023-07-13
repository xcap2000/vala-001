# vala-001

Using the following command initializes a new gtkmm project using the name of the parent folder, adds a version, cpp,
default options, dependencies and install: true:

```bash
$ meson init -d gtkmm-3.0
```

After a the following command the build directory is created and you can build using the ninja command:

```bash
$ meson build # creates build directory based on meson.build file
$ ninja -C build PROJECT_AND_OR_EXECUTABLE_NAME # build is the directory name
```

TODO - Search for meson compile, I think this is the same as using ninja.

# References

```
https://youtu.be/LDMNWYLpklc?list=PLUtN5L6mwP7LCYEBnyzKpc06TtK75w_UT
```