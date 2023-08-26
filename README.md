# ros2_toolbox

## Description

This repository contains a docker image with some tools for ROS2.
## Usage

### Create image:

```bash
./scripts/dockerize.sh
```

### Run tool:

Posible tools:

- rviz2
- rqt
- plot_juggler
- robot_steering

```bash
export ROS_DOMAIN_ID=your_domain_id
docker compose run --rm rviz2
```
