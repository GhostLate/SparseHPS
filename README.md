# SparseHPS: A Unified Model for Human Pose and Shape across Depth Cameras and LiDARs

**Project page: https://ghostlate.github.io/SparseHPS/**

SparseHPS recovers SMPL-X pose, shape and global translation from a human point cloud of any depth camera or LiDAR
with one set of weights, for single frames and streams alike.

The page contains:

- the abstract and the method, with the architecture figure;
- comparisons with prior methods: Table 2 of the paper (SLOPER4D and FreeMotion LiDAR benchmarks) and Table 3
  (HuMMan-Point, real Azure Kinect);
- a humanoid demo on test sequences of HuMMan, FreeMotion, RELI11D, BEDLAM2 and AMASS. Each clip shows the input
  cloud, the SparseHPS-T estimate and a Unitree G1 driven by kinematic retargeting (GMR); the body and the robot are
  rendered in NVIDIA Isaac Sim. A tag on each clip gives the percentile of its error within its test set.

The paper will be linked from the page once it is public.

## Credits

The datasets, the SMPL-X body model, the robot model and the tools behind the demo are credited in the
[Datasets and acknowledgements](https://ghostlate.github.io/SparseHPS/#credits) section of the page. The demo videos
show data of these datasets; their reuse is subject to the datasets' licenses.
