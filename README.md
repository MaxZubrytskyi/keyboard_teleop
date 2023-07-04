```bash
echo "deb [trusted=yes] https://github.com/MaxZubrytskyi/keyboard_teleop/raw/jammy-humble/ ./" | sudo tee /etc/apt/sources.list.d/MaxZubrytskyi_keyboard_teleop.list
echo "yaml https://github.com/MaxZubrytskyi/keyboard_teleop/raw/jammy-humble/local.yaml humble" | sudo tee /etc/ros/rosdep/sources.list.d/1-MaxZubrytskyi_keyboard_teleop.list
```
