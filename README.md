
# gdtxt

Purpose: An attempt to manually create a godot project and see if it will run in godot 4.0

Reason: I made a godot project, added some stuff, then looked at the resulting files in a text editor. They're pretty readable. I bet it could be done manually.

Structure
---

Project.godot

```
; Engine configuration file.
; It's best edited using the editor UI and not directly,
; since the parameters that go here are not all obvious.
;
; lol
;
; Format:
;   [section] ; section goes between []
;   param=value ; assign values to parameters

config_version=5
; What are the differences between config versions?
; I'll keep the 5 since the rest are related to this config version.

[application]

config/name="projectName"
config/features=PackedStringArray("godotVersion", "Mobile")
; In this case, 4.0
; Don't remember what the PC only one is called.

config/icon=:res://icon.svg"

[rendering]
renderer/rendering_method="mobile"
; Seems like other rendering methods can be used.
```
