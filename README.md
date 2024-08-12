## GLFW Installation
You can install GLFW from [extra repo](https://archlinux.org/packages/extra/x86_64/glfw/), but I built it from source.
- Download source from the [GLFW](https://www.glfw.org/download.html).
- Extract it.
- `cd` into the extracted directory.
- Create a *build* folder and `cd` into *build*.
```bash
mkdir build
cd build
```
Then use `cmake` to build the project.
```bash
cmake -DCMAKE_INSTALL_PREFIX=/usr/local ..
make
sudo make install
```
> I like to separate user installed libraries from system wide libraries. So, i put them in /usr/local

