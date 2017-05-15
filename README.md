Ansible Role: CUDA
=========

Install [NVIDIA CUDA](https://developer.nvidia.com/cuda-toolkit) on Linux System.

Requirements
------------

None.

Role Variables
--------------

`cuda_version`: The version of CUDA. (default: 8.0)

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: gpu
  become: yes

  roles:
    - { role: cuda, cuda_version: 8.0 }
```

License
-------

BSD

Author Information
------------------

This role was created by [Daniel D](https://github.com/djx339).
