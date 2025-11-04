# lima-extras

Extra configuration and management tools for Lima VMs.

## What's Here

### VM Templates

Templates for creating Lima VMs with desktop environments:

- `debian-trixie-desktop.yaml` - Debian Trixie with desktop
- `debian-trixie-plasma.yaml` - Debian Trixie with KDE Plasma
- `ubuntu-desktop-basic.yaml` - Ubuntu with basic desktop

## Usage

Create a VM from a template:

```bash
limactl create --name=myvm vm/templates/debian-trixie-desktop.yaml
limactl start myvm
```

## Requirements

- [Lima](https://github.com/lima-vm/lima)

## License

MIT
