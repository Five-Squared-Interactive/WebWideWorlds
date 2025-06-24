# 📄 VEML – Virtual Environment Markup Language

**VEML** defines a world’s metadata, logic, portals, and behavior in a declarative, human-readable format.

## Sample

```yaml
world:
  name: "Dream Vault"
  tags: ["abstract", "interactive"]
  portals:
    - target: /worlds/forest_gate
      trigger: onTouch
logic:
  - id: open_crate
    trigger: onClick
    target: crate_01
    action: playAnimation
