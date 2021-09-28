It can be useful to make a few optimizations to your ssh configuration; for example, this ~/.ssh/config contains settings to avoid dropped connections in certain network environments, uses compression (which is helpful with scp over low-bandwidth connections), and multiplex channels to the same server with a local control file

A few other options relevant to ssh are security sensitive and should be enabled with care, e.g. per subnet or host or in trusted networks: StrictHostKeyChecking=no, ForwardAgent=yes
