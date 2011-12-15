# LMAX Disruptor

This is just a port and repackaging of the LMAX Disruptor code found on Google Code.

http://code.google.com/p/disruptor/

### Why?

1. All the cool cats use Github.
2. I prefer Gradle over Ant.
3. The source code is in a standard location (src/main|test/java).

### Create Maven artifacts

For easy re-use inside your other projects, you can use the Gradle Maven integration
to locally install Disruptor artifacts. Just type `gradle install` and you'll have
a maven artifact in local repository at `com.lmax.disruptor:disruptor:2.8.SNAPSHOT`.

Disruptor is Apache 2.0 licensed:

http://www.apache.org/licenses/LICENSE-2.0.html