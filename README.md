# computer-setup

Resource for setting up laptop for data-science

## Conda

To get things setup to be able to work with data, we will install conda and setup jupyterlab.

1. Install Conda

2. Copy `.condarc` to your user home directory.

    ``` bash
    cp .condarc ~/.condarc`
    ```

3. Reopen terminal and install `jupyterlab`, `nb_conda_kernels`, and `mamba`.

    ``` bash
    conda install jupyterlab nb_conda_kernels mamba
    ```

4. All set!
