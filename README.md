# NCPass
NCPass is a Passwordmanager that is developed by the NorgCollective.
It uses `libnccrypt` (`nccrypt`) for Password-encryption.
For compatibility reasons, NCPass always includes the 3 newest Versions of `libnccrypt` in order to provide stability.

In future, there might be a custom 'Compatibility' Version that includes ALL Versions of `libnccrypt` wich should only be used
to update the Password Database from an older version.

NCPass adds an additional security extension to `libnccrypt`, so the Password Database is not decryptable with `libnccrypt`.

Please do not edit `~/.local/share/ncpass/password.json` manually, this could make the database, or parts of it, unusable.
