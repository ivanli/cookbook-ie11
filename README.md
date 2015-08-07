ie11 Cookbook
=============
Installs internet explorer via Chocolatey packages.

Requirements
------------
Runs on windows only. Been tested in Win7.

#### packages
- `chocolatey` - ie11 needs chocolatey to install packages.

Attributes
----------
None.

Usage
-----
Just include `ie11` in your node's `run_list`:

```json
{
  "name":"my_node",
  "run_list": [
    "recipe[ie11]"
  ]
}
```

Contributing
------------
1. Fork the repository on Github
2. Create a named feature branch (like `add_component_x`)
3. Write your change
4. Write tests for your change (if applicable)
5. Run the tests, ensuring they all pass
6. Submit a Pull Request using Github

License and Authors
-------------------
Authors: Ivan Li
