# rotki build dependencies

## Build dependencies requires for packaging rotki

### TCLTK
Required to compile SQLCIpher on Windows, used in [rotki-pysqlcipher3](https://github.com/rotki/pysqlcipher3)

The archive was originally pulled from https://bitbucket.org/tombert/tcltk

### Patched pip wheel
A patched version of [pip](https://github.com/kelsos/pip/commit/78694f772bc2c93cc4ea84790214ec804d198654) used to force pip to install universal wheels.

