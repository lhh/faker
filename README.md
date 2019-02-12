# faker
A tool for faking RPM installations.

Sometimes, you get stuck in a dependency loop, even though
you do not require the functionality of a given package.

Faker creates an empty RPM and installs it with the given
name, epoch, version, and release.

# Usage:
./faker name-[epoch:]version-release
