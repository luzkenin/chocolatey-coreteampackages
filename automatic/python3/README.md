# <img src="https://cdn.jsdelivr.net/gh/luzkenin/chocolatey-coreteampackages@edba4a5849ff756e767cba86641bea97ff5721fe/icons/python.svg" width="48" height="48"/> [python3](https://chocolatey.org/packages/python3)

Python 3.x is a programming language that lets you work more quickly and integrate your systems more effectively. You can learn to use Python 3.x and see almost immediate gains in productivity and lower maintenance costs.

## Package Parameters

- `/InstallDir` - Installation directory. **NOTE**: If you have pre-existing python3 installation, this parameter is ignored and existing python install location will be used

Example: `choco install python3 --params "/InstallDir:C:\your\install\path"`

## Notes

- Python package manager `pip` is installed by default, but you can also invoke it using command `py -m pip` which will use `pip3` and adequate version of python if you also have python2 installed and/or pip2 on the `PATH`. For more details see [Python on Windows FAQ](https://docs.python.org/3/faq/windows.html).
- For complete list of silent install options see the [Installing Without UI](https://docs.python.org/3/using/windows.html#installing-without-ui) page.
