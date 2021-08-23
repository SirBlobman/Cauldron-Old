# Cauldron
A Forge/Bukkit/Spigot Minecraft Server

## Compilation Instructions
I created a modified version of ForgeGradle 1.2-SNAPSHOT that is used to compile this project.
The instructions below should work for most setups. Make sure to compile this with JDK 8.

1) Checkout this project.
2) Init Submodules: `git submodule update --init --recursive`
3) Setup the workspace: `gradlew setupCauldron`
4) Build jars/binaries: `gradlew buildPackages`

Note: all binaries will be in distributions folder

## Profiling
We use YourKit as our Java Profiler.

YourKit is kindly supporting open source projects with its full-featured Java Profiler.
YourKit, LLC is the creator of innovative and intelligent tools for profiling
Java and .NET applications. Take a look at YourKit's leading software products:
* [YourKit Java Profiler](http://www.yourkit.com/java/profiler/index.jsp)
* [YourKit .NET Profiler](http://www.yourkit.com/.net/profiler/index.jsp)

## Contributing
I am not accepting any PRs to this restoration.
The project will remain as-is unless there is a need to repair something.

## Credits
* [MCP](http://mcp.ocean-labs.de) - permission to use data to make Cauldron.
* [Forge](http://www.minecraftforge.net) - mod support.
* [CraftBukkit](http://bukkit.org) - plugin support.
* [Spigot](http://www.spigotmc.org) - performance optimizations.
* [TechCable/Cauldron-Old](/TechCable/Cauldron-Old) - The repository that allowed me to make this restoration.
