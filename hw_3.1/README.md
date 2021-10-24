

## задание 12 (пока не забыл)
mkdir /tmp/new_path_dir
export PATH=/tmp/new_path_dir:$PATH
ln -s /usr/bin/bash /tmp/new_path_dir/bash
type -a bash
