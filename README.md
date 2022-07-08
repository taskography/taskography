# Taskography - Evaluating robot task planning over large 3D scene graphs

This is the landing page for *Taskography: Evaluating robot task planning over large 3D scene graphs*, presented at CoRL2021.
For a brief overview of the work, please refer to our [project webpage](https://taskography.github.io/).


### :building_construction:	Taskography-API
**[To API.](https://github.com/taskography/taskography-api)** 
A simple API for sampling symbolic planning tasks in large-scale 3D scene graphs. 
Provides support for the following: (1) hierarchical-symbolic graph construction; (2) task sampling; (3) trajectory sampling; (4) procedurally generated environment wrappers.

### :earth_americas: PDDLGym Environments
**[To Envs.](https://github.com/taskography/pddlgym)**
Official benchmark domains encoded in Planning Domain Definition Language ([PDDL](https://planning.wiki/ref/pddl/domain)). 
PDDLGym enables [gym-style](https://github.com/openai/gym) interfacing for each planning domain and problem pair.

### :rocket: Modern Planners
**[To Planners.](https://github.com/taskography/scenegraph-planners)**
A collection of performant, domain-agnostic learning-based planners, and the SCRUB and SEEK planners specifically designed to exploit 3D scene graph hierarchies.

### :airplane: Classical Planners
**[To Baselines.](https://github.com/agiachris/pddlgym_planners)**
A package interfacing all satisficing and optimal symbolic planners benchmarked in Taskography with Python.
Planners are automatically installed on first use.

### :house: Development Repository
**[To Dev.](https://github.com/taskography/3dscenegraph-dev)**
An in-house repository that contains the [official benchmark results](https://github.com/taskography/3dscenegraph-dev/tree/main/scenegraph/exp-official) in `.json` file format, along with original scripts used to generate all Taskography planning domains.

**Note:** The majority of this code has been repurposed in Taskography-API.

---
## Citation
All Taskography repositories are offered under the MIT License agreement. If you find Taskography useful, please consider citing our work:

```
@inproceedings{agia2022taskography,
  title={Taskography: Evaluating robot task planning over large 3D scene graphs},
  author={Agia, Christopher and Jatavallabhula, {Krishna Murthy} and Khodeir, Mohamed and Miksik, Ondrej and Vineet, Vibhav and Mukadam, Mustafa and Paull, Liam and Shkurti, Florian},
  booktitle={Conference on Robot Learning},
  pages={46--58},
  year={2022},
  organization={PMLR}
}
```
