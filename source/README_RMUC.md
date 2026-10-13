# RoboMaster RMUL 2023 Infantry Simulator

Complete Godot 4.7 assignment build. Open `project.godot` and press F5.

Controls: WASD move, Space low hop, mouse gimbal, left mouse fire, R reset, M overview, Esc release cursor.

Implemented: 3D collision, true wedge ramps, synchronized minimap, 05:00 timer, HP/ammo/score/target UI, rotating target, 1500 HP bases, timed supply recovery, victory feedback, and localhost camera/status output at `http://127.0.0.1:8080/`.

Rule-aligned values from the RMUL 2023 V1.2 rulebook: 12m x 8m 3V3 field, five-minute match, 200 infantry HP, 10 damage per 17mm hit on robots, 5 damage per hit on base armor, and 1500 base HP. Jumping is retained only because the course requires it; the hop is limited to approximately 0.6m.

Explicit simplifications: base shield/invulnerability, heat, chassis power and the complete respawn system are outside this single-player demonstration.
