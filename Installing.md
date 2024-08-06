# Search for a package by keyword.
yum/apt/dnf search keyword

# Install package.
yum/apt/dnf install package

# Display description and summary information about package.
yum/apt/dnf info package

# Install package from local file named package.rpm
rpm -i package.rpm

# Remove/uninstall package.
yum/apt/dnf remove package

# Install software from source code.
tar zxvf sourcecode.tar.gz
cd sourcecode
./configure
make
make install
