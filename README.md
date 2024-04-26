# sdf_tools

Builds 2D signed distance fields from images, 3D signed distance fields from pointclouds, 3D signed distance fields from Octomap, provides a lightweight signed distance field library, message types for signed distance fields, and tools to compress signed distance fields for transport.

A simple example/tutorial is provided, see the [Wiki](https://github.com/WPI-ARC/sdf_tools/wiki).

### Compile

```bash
catkin_make install --source src/sdf_tools --build build/sdf_tools
```

Check if has been updated.

```bash
ls -la /opt/ros/noetic/lib/ | grep sdf_tools
```

If not, install manually.

```bash
sudo cp ~/mapping_ws/src/sdf_tools/lib/libsdf_tools.so /opt/ros/noetic/lib/
sudo cp -r ~/mapping_ws/src/sdf_tools/include/sdf_tools /opt/ros/noetic/lib/
```
