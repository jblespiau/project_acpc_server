# Annual Computer Poker Competition (ACPC)

The code is a pristine copy of
http://www.computerpokercompetition.org/downloads/code/competition_server/project_acpc_server_v1.0.42.tar.bz2

with some minor changes:

1) Deletion of:
- protocol.odt
- protocol.pdf

2) We moved the files game.c, net.c and rng.c to be C++ and we add a namespace
to them to prevent collisions.

3) We remove the define of `__STDC_FORMAT_MACROS`, which should be replaced by a
flag.

