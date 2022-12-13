# ansible-role-win-notepadplusplus

Ansible Role to install Notepad++

## Table of content

- [Default Variables](#default-variables)
  - [notepadplusplus_already_installed_path](#notepadplusplus_already_installed_path)
  - [notepadplusplus_download_url](#notepadplusplus_download_url)
  - [notepadplusplus_download_validate_certs](#notepadplusplus_download_validate_certs)
  - [notepadplusplus_extract_dir](#notepadplusplus_extract_dir)
  - [notepadplusplus_install_exe](#notepadplusplus_install_exe)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Default Variables

### notepadplusplus_already_installed_path

Path to check if already installed.

#### Default value

```YAML
notepadplusplus_already_installed_path: C:\Program Files\
```

### notepadplusplus_download_url

Download URL of the package.

#### Default value

```YAML
notepadplusplus_download_url: https://github.com/notepad-plus-plus/notepad-plus-plus/releases/download/v8.4.7/npp.8.4.7.Installer.x64.exe
```

### notepadplusplus_download_validate_certs

Validate SSL certs when downloading.

#### Default value

```YAML
notepadplusplus_download_validate_certs: yes
```

### notepadplusplus_extract_dir

Extract directory.

#### Default value

```YAML
notepadplusplus_extract_dir: C:\windows\temp\notepadplusplus
```

### notepadplusplus_install_exe

File name of the installation package.

#### Default value

```YAML
notepadplusplus_install_exe: npp.8.4.7.Installer.x64.exe
```



## Dependencies

None.

## License

license (GPL-2.0-or-later, MIT, etc)

## Author

andif888
