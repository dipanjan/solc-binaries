Based on solc-select: https://github.com/crytic/solc-select/tree/add3f08609d902bdceb11c6007a8d59a50b49fb5
solc binaries are stored in the .solc-select hidden directory

=> ln -s .solc-select ~/.solc-select
=> export PATH=~/.solc-select:$PATH
=> chmod -R 755 .solc-select
=> solc --versions
=> solc use 0.4.24
=> solc --version
