# Supplementaries (fork)

This is a fork of [Supplementaries](https://github.com/MehVahdJukaar/Supplementaries/tree/1.21) 
created by [MehVahdJukaar](https://github.com/MehVahdJukaar) and contributors which modifies the original version 
to revert some changes it makes to vanilla behavior.  The need for this fork was discovered after attempting to build 
and use the [Orbital Strike Cannon mk.6](https://www.youtube.com/watch?v=q78LRgHt_zU) by 
[cubicmetre](https://www.youtube.com/@cubicmetre) and finding that complex redstone machines such as this one did not 
work as expected. The following changes were made to ensure that vanilla behavior is preserved, unless intentionally modified.

## Changes
- Disabled `Relayer`

# Supported Minecraft Version
This fork is based on the 1.21 version of Supplementaries and is compatible with Minecraft 1.21 and 1.21.1. There
are no intentions of supporting other versions of Minecraft. Contributors are welcome to submit pull requests for
adding support for other versions, but this is not a priority for the maintainers of this fork.

# Building
This fork is built using [Gradle](https://gradle.org/) and requires Java 17 to build. The following steps will guide you
through the process of building this fork:
1. Clone the repository to your local machine.
2. Run `gradle fabric:build` in the root directory of the repository. This will build the mod and create a JAR file in the `build/libs` directory.
3. Copy the JAR file to you desired mod's folder.