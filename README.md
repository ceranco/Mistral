# Mistal Constraint Solver

Forked from <https://www.cs.utexas.edu/~tdillig/mistral/>.

> :warning: **Only tested on Ubuntu**.

## Dependencies

To compile, you need the following dependencies:

* *CMake*
* *libglademm-2.4-dev*
* *libgtkmm-2.4-dev*

```bash
sudo apt install cmake libglademm-2.4-dev libgtkmm-2.4-dev
```

## Building 

Build using cmake:

```bash
mkdir build
cd build
cmake ../
cmake --build .
```

## Running the GUI

After building, you can run the Mistral GUI by:

```bash
cd ui
../build/ui/mistral_ui
```

After this, you can start the Mistral GUI as:


> :heavy_exclamation_mark: The UI will only start from the /mistral/ui folder

## Using as a library

If you want to use mistral as a library, read the file example/example.cpp 
for how to link Mistral against your project.
