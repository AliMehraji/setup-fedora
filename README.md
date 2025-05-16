# Fedora Setup

## Description

Setup a fresh fedora linux in new workstation or laptop.

## Features

- setup `dnf.conf` and `proxy` for dnf
- enable `rpmfusion` repos
- install favorite fonts
- install all packages and applications
- remove extra and useless packages for me
- install `ansible`, `mitogen` for ansible and generates `ansible.cfg`
- install `virtualization`
- setup `proxychains-ng`

## Requirements

Install the required packages, for Fedora Linux:

```bash
dnf install -y git make cmake g++ gcc tmux vim
```

## Example usage

```bash
git clone https://github.com/AliMehraji/fedora-setup.git
cd workstation-setup/fedora
make all
```

## Resources

- [dnf configurations](https://dnf.readthedocs.io/en/latest/conf_ref.html)
- [Enabling the RPM Fusion repositories](https://docs.fedoraproject.org/en-US/quick-docs/rpmfusion-setup/)
- [mitogen](https://mitogen.networkgenomics.com/ansible_detailed.html)
- [Virtualization](https://docs.fedoraproject.org/en-US/quick-docs/virtualization-getting-started/)
- [proxychains-ng](https://github.com/rofl0r/proxychains-ng)
- [FiraCode Fonts](https://github.com/tonsky/FiraCode)
- [Ansible Configuration](https://docs.ansible.com/ansible/latest/reference_appendices/config.html)
- [Ansible Lint](https://ansible.readthedocs.io/projects/lint/)
- [K8S Lens Desktop](https://k8slens.dev/)
- [K8S FreeLens](https://github.com/freelensapp/freelens)
- [Kubectx - Kubens](https://github.com/ahmetb/kubectx)
- [Minio Client](https://min.io/docs/minio/linux/reference/minio-mc.html#minio-client)
