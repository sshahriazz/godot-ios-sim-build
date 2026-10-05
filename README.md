# Godot iOS simulator template (arm64)

Builds Godot's iOS export template libraries for the **Apple Silicon (arm64) iOS Simulator**. The official templates only ship an x86_64 simulator slice, which iOS 26+ simulators refuse.

Run the "iOS simulator template (arm64)" workflow (Actions tab, or `gh workflow run`). The artifact holds `libgodot.ios.template_debug.arm64.simulator.a` and `libgodot_camera.ios.template_debug.arm64.simulator.a`. Swap them into the `ios-arm64_x86_64-simulator` slices of a copy of the official `ios.zip` and use it as a custom template.

Godot is MIT-licensed; this repo only holds the build workflow.
