## xxhash

[![Build Status](https://travis-ci.org/Oefenweb/ansible-xxhash.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-xxhash) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-xxhash-blue.svg)](https://galaxy.ansible.com/Oefenweb/xxhash)

Set up [xxHash](http://www.xxhash.com/) (An extremely fast non-cryptographic hash algorithm, working at speeds close to RAM limits) in Debian-like systems.

#### Requirements

* `git-core` (will be installed)
* `build-essential` (will be installed)

#### Variables

* `xxhash_version` [default: `v0.6.5`]: What version of `xxhash` to check out (set up). This can be the full 40-character SHA-1 hash, the literal string HEAD, a branch name, or a tag name
* `xxhash_install_dir` [default: `/usr/bin`]: Install directory

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - xxhash
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-xxhash/issues)!
