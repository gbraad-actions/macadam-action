macadam action
==============

Action to manage (create, run, ssh) virtual machines using macadam

## Usage
```yaml
  - name: run VM
    uses: gbraad-actions/macadam-action@v1
    with:
      disk_image: ~/DiskImages/dotfedora.qcow2
      image_username: gbraad
      identity_path: ~/.ssh/id_machine
```

## Inputs
| Name            | Description                                                                 | Required | Default          |
|-----------------|-----------------------------------------------------------------------------|----------|------------------|
| `disk_image`    | Path to the disk image to use for the VM                                    | Yes      |                  |
| `image_username`| Username to use for the VM                                                   | No      | core                 |
| `identity_path` | Path to the SSH identity file to use for the VM                             | Yes       |                     |

