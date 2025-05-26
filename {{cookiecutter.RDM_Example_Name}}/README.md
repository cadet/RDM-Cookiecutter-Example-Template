# {{cookiecutter.README_md_Title}}

This repository contains an example simulation of {{cookiecutter.README_md_Title}}. {{cookiecutter.Example_Description}}

This example reproduces part of the case study from:

* *“Example Title of Reference”*
  Martina Mustermann
  *Journal* (2018); 111:183-198.
  [doi:10.1016/j.compchemeng.2017.12.022.](https://www.sciencedirect.com/science/article/pii/S0098135417304520)

---

## Authors

* {{cookiecutter.Author1}}
* {{cookiecutter.Author2}}
* {{cookiecutter.Author3}}
* {{cookiecutter.Author4}}
---

## Running the Example Simulation

1. Clone this repository.
2. Set up the environment using the `environment.yml` file.
3. Run the simulation:

   ```bash
   python main.py
   ```

The results will be stored in the `src` folder inside the `output` directory.

> **Note**: Running `cadet-rdm` requires [**Git LFS**](https://git-lfs.com/), which needs to be installed separately.
>
> * **Ubuntu/Debian**:
>
>   ```bash
>   sudo apt-get install git-lfs
>   git lfs install
>   ```
>
> * **macOS** (with Homebrew):
>
>   ```bash
>   brew install git-lfs
>   git lfs install
>   ```
>
> * **Windows**:
>   Download and install from [https://git-lfs.com](https://git-lfs.com)

---

## Output Repository

The output data for this case study can be found here:
[{{cookiecutter.Output_Repo_Path}}]({{cookiecutter.Output_Repo_Path}})