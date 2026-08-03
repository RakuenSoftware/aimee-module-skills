# Aimee module: skills

This is the independent `skills` source-ownership repository.

It builds `aimee-module-skills` as a separate process for the
server bus. Its generated grant serves exactly the
declared stage event kinds. Its repository-owned handler implements the declared stage contract.

The daemon admits the process only when its installed absolute executable path,
UID, principal class, principal reference, and event-kind grants match the
installed `.grant` file. Copy that generated grant into each declared daemon
policy directory under `modules.d`.


The descriptor-owned production sources, headers, tests, and documentation are
preserved at their canonical paths so their migration history remains auditable.
